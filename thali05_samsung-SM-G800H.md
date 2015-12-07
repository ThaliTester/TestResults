#### Test 502422852e23b2c_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
W/ActivityManager(  753): Permission Denial: getCurrentUser() from pid=2632, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
D/MediaScannerReceiver( 1204): action: android.intent.action.BOOT_COMPLETED
D/MediaScannerService( 1204): !@start scanning volume internal: [/system/media]
--------- beginning of /dev/log/main
D/TP/MmsProvider( 1239): Update uri=content://mms, match=0
D/TP/MmsProvider( 1239): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1239): need read changed broadcast:false
I/Mms:transaction( 1723): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 1723): [start]    nonBlockingUpdateMessageIndicator()
I/Mms/ReservationManager( 1723): resetAfterConnected()
D/TP/MmsSmsProvider( 1239): match 7:Elapsed time : 2.274 ms
I/Mms/ReservationManager( 1723): getReservedSendMessageCount(): retMessageCount=0
D/Mms/MessagingNotification( 1723): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1723): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1723): isDefault true
I/SELinux ( 2660): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2660):  
D/TP/MmsSmsProvider( 1239): match 200:Elapsed time : 1.257 ms
D/Mms/TelephonyPermission( 1723): isDefault true
D/Mms/SmsReceiverService( 1723): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 1723): [start]    handleBootCompleted()
I/SELinux ( 2660): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2660):  
I/SELinux ( 2660):  
I/SELinux ( 2660): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2660): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2660): >>>>> Normal User
E/dalvikvm( 2660): >>>>> com.sec.android.app.safetyassurance [ userId:0 | appId:10050 ]
E/SELinux ( 2660): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/BadgeProvider( 1337): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/BadgeProvider( 1337): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1337): sendNotify, [notify] : null
D/BadgeProvider( 1337): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1337): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1337): update, [UpdateCount] : 1
D/TimaKeyStoreProvider( 2660): in addTimaSignatureService
D/Launcher.Model( 1250): reloadBadges entered.
D/TimaKeyStoreProvider( 2660): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2660): Added TimaKesytore provider
D/Mms/MessagingNotification( 1723): setBadgeCount(), count=0
D/TP/MmsSmsProvider( 1239): deleteConversation threadId: 9223372036854775806
D/MessagingNotification( 1723): remove alarm
D/TP/MmsSmsProvider( 1239): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
D/Mms/MessagingNotification( 1723): updateAllHistoryAsRead()
D/Mms/MessagingNotification( 1723): [end]    nonBlockingUpdateMessageIndicator()
D/TP/MmsSmsProvider( 1239): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1239): need read changed broadcast:false
D/Mms/Conversation( 1723): deleteTempConversation(),deleted=0
D/SmsProvider( 1239): Update uri=content://sms/outbox, match=8
D/MediaScanner( 1204): Prescan. DB items number : 156 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/TP/MmsSmsProvider( 1239): need read changed broadcast:false
W/dalvikvm( 2660): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
D/Mms/SmsReceiverService( 1723): sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 1723): [SIM-1]sendFirstQueuedMessage()
D/SafetyAssuranceAppFeatures( 2660): init start
I/SafetyAssuranceAppFeatures( 2660): mLoadBaiduMap:false
I/SafetyAssuranceAppFeatures( 2660): mFeatureEnableMultiSim true
D/SafetyAssuranceAppFeatures( 2660): init end
D/Mms/MessagingNotification( 1723): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1723): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1723): isDefault true
D/SafetyAssuranceReceiver( 2660): onReceive
I/SafetyAssuranceApp( 2660): Acquire WL
D/SafetyAssuranceConfig( 2660): getAppState : 1
D/SafetyAssuranceReceiver( 2660): onReceive - action:android.intent.action.BOOT_COMPLETED, currentAppState:1
D/SafetyAssuranceReceiver( 2660): Init App state
D/TP/MmsSmsProvider( 1239): match 200:Elapsed time : 0.864 ms
D/SafetyAssuranceConfig( 2660): setAppState : 1
W/BackupManagerService(  753): dataChanged but no participant pkg='com.android.providers.settings' uid=10050
D/SafetyAssuranceApp( 2660): topActivity's name is=.BatteryCover
I/SafetyAssuranceApp( 2660): Release WL
D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
I/NetworkStatusReceiver( 1239): action: android.intent.action.BOOT_COMPLETED
D/BadgeProvider( 1337): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
V/MediaScanner( 1204): processDirectory :  /system/media
D/Launcher.Model( 1250): reloadBadges entered.
D/BadgeProvider( 1337): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1337): sendNotify, [notify] : null
D/BadgeProvider( 1337): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1337): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1337): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 1723): setBadgeCount(), count=0
D/MessagingNotification( 1723): remove alarm
D/NearbySettings( 1304): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1304): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1304): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
I/NearbySettings( 1304): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1304): MountReceiver.onReceive - Internal Path
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
D/Mms/MessagingNotification( 1723): updateAllHistoryAsRead()
D/Mms/SmsReceiverService( 1723): [end]    handleBootCompleted()
I/AccessibilityManagerService(  753): setmDNIeNegative (false)
V/MediaScanner( 1204):  prescan time: 233ms (DB items: 156)
V/MediaScanner( 1204):     scan time: 73ms (Caching mode: true), (makeEntry time: 29ms ~39%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1204): postscan time: 1ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1204):    total time: 307ms
V/MediaScanner( 1204): checked files: 149  directories : 5  (I: 0, U: 0)
D/MediaScanner( 1204): checkDefaultSounds
D/MediaScanner( 1204): system alarm_alert  : Vwiurug_etwofi5wgg
D/MediaScanner( 1204): OK. alarm_alert is already exist in setting DB.
D/MediaScanner( 1204): system notification_sound  : K_Oprkltf5wgg
D/MediaScanner( 1204): OK. notification_sound is already exist in setting DB.
D/MediaScanner( 1204): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1204): OK. ringtone is already exist in setting DB.
D/MediaScanner( 1204): system ringtone_2  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1204): OK. ringtone_2 is already exist in setting DB.
,D/MediaScanner( 1204): system notification_sound_2  : K_Oprkltf5wgg
D/MediaScanner( 1204): OK. notification_sound_2 is already exist in setting DB.
D/MediaScannerService( 1204): !@done scanning volume internal
D/MediaScannerService( 1204): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter finished
D/MediaScanner( 1204): Prescan. DB items number : 20 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
V/MediaScanner( 1204): processDirectory :  /storage/emulated/0
D/MediaScanner( 1204): Skipping:
D/MediaScanner( 1204): 7klwibgf7fvntblfd7(75ebcf7
I/iu.UploadsManager( 1639): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
D/MediaScanner( 1204): Skipping:
D/MediaScanner( 1204): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
I/iu.UploadsManager( 1639): End new media; added: 0, uploading: 0, time: 45 ms
V/MediaScanner( 1204): processDirectory :  /storage/extSdCard
W/MediaScanner( 1204): Error opening directory, reason : Permission denied.
W/MediaScanner( 1204): 7klwibgf7fxlKdCbid7
W/Atfwd_Sendcmd(  287): AtCmdFwd service not published, waiting... retryCnt : 3
W/Settings( 1304): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/dalvikvm(  753): GC_EXPLICIT freed 1162K, 17% free 22550K/27152K, paused 6ms+14ms, total 132ms
E/File    ( 1204): fail readDirectory() errno=2
I/SettingSearch/SearchIntentReceiver( 1304): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1304): search setting db init!!
V/MediaScanner( 1204): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@42b7acf0
V/MediaScanner( 1204): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@42b7acf0
I/SettingSearch/SearchIntentReceiver( 1304): BOOT_COMPLETED call InitSerachDBThread thread start!
V/MediaScanner( 1204):  prescan time: 36ms (DB items: 20)
V/MediaScanner( 1204):     scan time: 86ms (Caching mode: true), (makeEntry time: 71ms ~82%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:40 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:60 
V/MediaScanner( 1204): postscan time: 159ms (bulkDeleter : 0), (delete DeadThumbnail time : 14ms)
V/MediaScanner( 1204):    total time: 281ms
V/MediaScanner( 1204): checked files: 3  directories : 17  (I: 0, U: 0)
I/SELinux ( 2698): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2698):  
D/MediaScannerService( 1204): !@done scanning volume external
D/MediaScannerService( 1204): send command to ssrm : REQ_DROP_CACHE
I/SELinux ( 2698): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2698):  
I/SELinux ( 2698):  
I/SELinux ( 2698): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2698): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2698): >>>>> Normal User
E/dalvikvm( 2698): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10160 ]
E/SELinux ( 2698): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/PhoneNumberLocatorBootCompletedReceiver( 1239): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 1239): Phone number locator feature is dsiabled
D/TimaKeyStoreProvider( 2698): in addTimaSignatureService
W/BackupManagerService(  753): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
I/BootupListener( 1239): mPendingNetworkManualSelection : false
D/AndroidRuntime( 2692): 
D/AndroidRuntime( 2692): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ManualSelectionReceiver( 1239): onReceive : Intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.phone/.ManualSelectionReceiver (has extras) }
D/TimaKeyStoreProvider( 2698): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2698): Added TimaKesytore provider
D/AndroidRuntime( 2692): CheckJNI is OFF
D/AndroidRuntime( 2692): setted country_code = Poland
D/AndroidRuntime( 2692): setted countryiso_code = PL
D/AndroidRuntime( 2692): setted sales_code = XEO
D/AndroidRuntime( 2692): readGMSProperty: start
D/AndroidRuntime( 2692): readGMSProperty: already setted!!
D/AndroidRuntime( 2692): readGMSProperty: end
D/AndroidRuntime( 2692): addProductProperty: start
D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
I/SELinux ( 2710): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2710):  
D/dalvikvm( 2692): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2692): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2692): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2692): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2692): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 2710): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2710):  
I/SELinux ( 2710):  
I/SELinux ( 2710): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2710): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2710): >>>>> Normal User
E/dalvikvm( 2710): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
E/SELinux ( 2710): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 2710): in addTimaSignatureService
D/TimaKeyStoreProvider( 2710): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2710): Added TimaKesytore provider
W/ActivityManager(  753): Permission Denial: getCurrentUser() from pid=2698, uid=10160 requires android.permission.INTERACT_ACROSS_USERS
E/memtrack( 2692): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 2692): failed to load memtrack module: -2
D/dalvikvm( 2692): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/DBG_DM  ( 2710): [][Line:95][onCreate] 
E/DBG_DM  ( 2710): BootingfileStream is null
E/DBG_DM  ( 2710): xdmCreateBootingFilestream
D/AndroidRuntime( 2692): Calling main entry com.android.commands.am.Am
I/DBG_DM  ( 2710): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
I/DBG_DM  ( 2710): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
I/DBG_DM  ( 2710): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
I/DBG_DM  ( 2710): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
V/ApplicationPolicy(  753): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/DBG_DM  ( 2710): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
I/DBG_DM  ( 2710): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
D/CustomFrequencyManagerService(  753): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 753  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  753): mDVFSHelper.acquire()
I/DBG_DM  ( 2710): [3.19.140541][Line:36][onCreate] myUserId : 0
I/SurfaceFlinger(  247): id=15 createSurf (1x1),1 flag=404, iello
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
W/ContextImpl(  753): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  753): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.ssrm.u.i:-1 com.android.server.ssrm.ai.run:-1 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 
D/PowerManagerService(  753): [s] UserActivityState : 1 -> 0
I/PowerManagerService(  753): [PWL] On : 0 (39912 ms ago)
I/PowerManagerService(  753): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  753): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1067, ws=null) (elapsedTime=2244)
D/DisplayPowerController(  753): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService(  753): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/lights  (  753): lcd : 2 +
D/RampAnimator(  753): Light Animator Finished currentValue=2
D/lights  (  753): lcd : 2 -
I/WindowManager(  753): Screenshot max retries 4 of Token{4279f878 ActivityRecord{428b7ee0 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{433be478 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
W/WindowManager(  753): Screenshot failure taking screenshot for (720x1280) to layer 21005
D/LockPatternUtils( 1067): isPcwEnable = null
D/AndroidRuntime( 2692): Shutting down VM
D/dalvikvm( 2692): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+1ms, total 3ms
I/DBG_DM  ( 2710): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 0
I/DBG_DM  ( 2710): [3.19.140541][Line:2702][xdmdbsqlGetDownloadPostponeStatus] xdbsqlGetDownloadPostponeStatus : 0
I/SELinux ( 2733): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2733):  
D/SSRMv2:SIOP(  753): SIOP:: AP = 320, Delta = 10
I/DBG_DM  ( 2710): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
I/DBG_DM  ( 2710): [3.19.140541][Line:99][onCreate] DMApplication NOT Start !
I/DBG_DM  ( 2710): [3.19.140541][Line:139][onReceive] android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1067): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1067): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1067): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1067): isSafeMode = false
I/SELinux ( 2733): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2733):  
I/SELinux ( 2733):  
I/SELinux ( 2733): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2733): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2733): >>>>> Normal User
E/dalvikvm( 2733): >>>>> com.example.hello [ userId:0 | appId:10180 ]
E/SELinux ( 2733): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 2733): in addTimaSignatureService
E/Tethering(  753): No numeric data
E/Tethering(  753): No numeric data
D/TimaKeyStoreProvider( 2733): Cannot add TimaSignature Service, License check Failed
E/Tethering(  753): No numeric data
E/Tethering(  753): No numeric data
D/ActivityThread( 2733): Added TimaKesytore provider
E/Tethering(  753): No numeric data
E/Tethering(  753): No numeric data
I/ConnectivityService(  753): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  753): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  753): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  753): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  753): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  753): defaultVal : 1, tetherEnabledInSettings : true
D/Launcher.HomeView( 1250): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1446): [237392/5] Surface widget pause on instance = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1446): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 1446): [KK AccuPhone]>>> SWW:224 [0:0] [SWW] onPause : instance = 1
D/accuweather( 1446): [KK AccuPhone]>>> SWW:239 [0:0] onPause : size = 0
D/accuweather( 1446): [KK AccuPhone]>>> SWW:517 [0:0]  unRegisterTTReceiver !! 
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/LockPatternUtils( 1067): isPcwEnable = null
D/accuweather( 1446): [KK AccuPhone]>>> WR:149 [0:0] onPause
D/accuweather( 1446): [KK AccuPhone]>>> SM:526 [0:0] onPause
D/SurfaceWidgetView( 1250): destroyHardwareResources():1130995960
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/Launcher( 1250): onTrimMemory. Level: 20
W/ActivityManager(  753): Permission Denial: getCurrentUser() from pid=2733, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  753): Permission Denial: getCurrentUser() from pid=2733, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
D/LocationManagerService(  753): getProviders()=[passive]
V/WebViewChromium( 2733): Binding Chromium to the background looper Looper (main, tid 1) {42772538}
I/chromium( 2733): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 2733): Initializing chromium process, renderers=0
W/chromium( 2733): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 2733): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2733): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2733): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2733): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2733): Remote Branch: 
I/Adreno-EGL( 2733): Local Patches: 
I/Adreno-EGL( 2733): Reconstruct Branch: 
D/SensorService(  753):   -0.1 -0.1 9.6
E/Tethering(  753): No numeric data
E/Tethering(  753): No numeric data
E/Tethering(  753): No numeric data
I/ConnectivityService(  753): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  753): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  753): defaultVal : 1, tetherEnabledInSettings : true
E/Tethering(  753): No numeric data
V/NFC     ( 1304): this device does not have NFC support
V/NFC     ( 1304): this device does not have NFC support
V/NFC     ( 1304): this device does not have NFC support
V/NFC     ( 1304): this device does not have NFC support
I/ConnectivityService(  753): defaultVal : 1, tetherEnabledInSettings : true
V/VibratorService(  753): hasVibrator - useVibetonz: false
I/ContactAccountLoggerTas( 2126): canRun() : Opted Out
I/dalvikvm( 2733): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2733): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2733): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2733): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2733): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2733): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2733): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2733): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2733): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2733): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2733): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2733): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2733): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2733): CordovaWebView is running on device made by: samsung
I/HarmonyEASService(  753): Updating for all 1
W/dalvikvm( 2126): method Lcom/google/android/search/core/state/QueryState;.a incorrectly overrides package-private method with same name in Lcfl;
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  247): id=16 createSurf (720x1280),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 2733): EGLImpl-HWUI Protected EGL context created
D/WifiDisplayAdapter(  753): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/OpenGLRenderer( 2733): Enabling debug mode 0
D/WifiDisplayAdapter(  753): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/AwContents( 2733): nativeOnDraw failed; clearing to background color.
I/AudioService(  753): getStreamVolume 3 index 0
I/MediaRouter( 2126): Found default route: MediaRouter.RouteInfo{ uniqueId=android/kb:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/LockPatternUtils( 1067): isPcwEnable = null
I/SurfaceFlinger(  247): id=15 Removed iello (10/13)
D/CustomFrequencyManagerService(  753): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 753  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  753): mDVFSHelper.release()
I/SurfaceFlinger(  247): id=15 Removed iello (-2/13)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  247): id=9 Removed Mauncher (8/12)
I/SurfaceFlinger(  247): id=9 Removed Mauncher (-2/12)
D/CustomFrequencyManagerService(  753): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 753  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1250): destroyHardwareResources():1130995960
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (8/11)
I/SurfaceFlinger(  247): id=14 Removed CatteryCove (-2/11)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/WifiDisplayAdapter(  753): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/Velvet.VelvetFactory( 2126): refreshing search history.
I/SELinux ( 2789): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2789):  
D/dalvikvm(  248): GC_EXPLICIT freed 44K, 49% free 9510K/18460K, paused 2ms+3ms, total 28ms
I/ActivityManager(  753): Waited long enough for: ServiceRecord{43473850 u0 com.google.android.gms/.gcm.GcmService}
I/SELinux ( 2789): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2789):  
I/SELinux ( 2789):  
I/SELinux ( 2789): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2789): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2789): >>>>> Normal User
E/dalvikvm( 2789): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 2789): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 49% free 9510K/18460K, paused 2ms+4ms, total 22ms
D/LockPatternUtils( 1067): isPcwEnable = null
D/TimaKeyStoreProvider( 2789): in addTimaSignatureService
D/TimaKeyStoreProvider( 2789): Cannot add TimaSignature Service, License check Failed
D/dalvikvm(  248): GC_EXPLICIT freed <1K, 49% free 9510K/18460K, paused 2ms+3ms, total 22ms
D/ActivityThread( 2789): Added TimaKesytore provider
W/GAV2    ( 2126): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/LockPatternUtils( 1304): isSmartCardAuthenticationAvailable: false
I/ContactAccountLoggerTas( 2126): canRun() : Opted Out
W/GAV2    ( 2126): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ContactAccountLoggerTas( 2126): canRun() : Opted Out
V/WebViewChromium( 2126): Binding Chromium to the main looper Looper (main, tid 1) {42770648}
I/chromium( 2126): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 2126): Initializing chromium process, renderers=0
I/chromium( 2733): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
W/chromium( 2126): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 2126): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2126): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2126): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2126): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2126): Remote Branch: 
I/Adreno-EGL( 2126): Local Patches: 
I/Adreno-EGL( 2126): Reconstruct Branch: 
I/chromium( 2733): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
E/libGLESv2( 2733): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
E/libGLESv2( 2733): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
D/UserAnalysis.PlaceProvider( 2789): Create SecureDbHelper
E/SMD     (  241): DCD ON
W/ActivityManager(  753): Permission Denial: getCurrentUser() from pid=2789, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
D/UserAnalysis.UserAnalysisBroadcastReceiver( 2789): Create SecureDbHelper
E/AndroidProtocolHandler( 2733): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 2733): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
I/SQLiteSecureOpenHelper( 2789): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2789): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 2789): Open Place.db in secure mode
D/JsMessageQueue( 2733): Set native->JS mode to OnlineEventsBridgeMode
V/VibratorService(  753): hasVibrator - useVibetonz: false
,E/libGLESv2( 2733): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,E/libGLESv2( 2733): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,D/dalvikvm( 2733): Trying to load lib /data/app-lib/com.example.hello-4/libjxcore.so 0x42a991d8
,I/SQLiteSecureOpenHelper( 2789): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2789): ...getDatabaseLocked(b,b,pwd)
,I/SQLiteSecureOpenHelper( 2789): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2789): getDatabaseLocked(b,b,pwd)...
,D/UserAnalysis.CarAnalyzer( 2789): Create SecureDbHelper
,I/SQLiteSecureOpenHelper( 2789): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2789): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2789): Open Place.db in secure mode
,W/NetworkUtils( 2126): OkHttp exception
,I/ContactAccountLoggerTas( 2126): canRun() : Opted Out
,I/LockPatternUtils( 1304): isSmartCardAuthenticationAvailable: false
D/dalvikvm( 2733): Added shared lib /data/app-lib/com.example.hello-4/libjxcore.so 0x42a991d8
D/jxcore_app_log( 2733): JniHelper::setJavaVM(0x41d504f8), pthread_self() = 1945676872
,D/JX-Cordova( 2733): jxcore cordova android initializing
,I/SQLiteSecureOpenHelper( 2789): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2789): ...getDatabaseLocked(b,b,pwd)
,I/SELinux ( 2827): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2827):  
,W/jxcore-log( 2733): Initializing JXcore engine
,W/jxcore-log( 2733): JXcore engine is ready
,I/SELinux ( 2827): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2827):  
I/SELinux ( 2827):  
,I/SELinux ( 2827): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2827): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2827): >>>>> Normal User
,E/dalvikvm( 2827): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 2827): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/jxcore-log( 2733): Starting JXcore engine
,D/TimaKeyStoreProvider( 2827): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2827): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2827): Added TimaKesytore provider
,I/sCloudBackupApp( 2827): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SELinux ( 2840): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2840):  
,I/SettingSearch/SearchIntentReceiver( 1304): InitSerachDBThread thread end!
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:129 <bottom of call stack> 
,D/CustomFrequencyManagerService(  753): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 753  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 2840): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2840):  
I/SELinux ( 2840):  
,I/SELinux ( 2840): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2840): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2840): >>>>> Normal User
,E/dalvikvm( 2840): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 2840): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2840): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2840): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2840): Added TimaKesytore provider
,W/ActivityManager(  753): Permission Denial: getCurrentUser() from pid=2840, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,D/AmoledAdjustTimer(  753): prevTemp = 281, currTemp = 283, prevStep = 4, currStep = 4
,I/SELinux ( 2853): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2853):  
W/jxcore-log( 2733): Platform android
W/jxcore-log( 2733): 
,W/jxcore-log( 2733): Process ARCH arm
W/jxcore-log( 2733): 
,W/BackupManagerService(  753): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/BackupManagerService(  753): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/SELinux ( 2853): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2853):  
I/SELinux ( 2853):  
,I/SELinux ( 2853): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2853): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2853): >>>>> Normal User
,E/dalvikvm( 2853): >>>>> com.wssnps [ userId:0 | appId:1000 ]
,E/SELinux ( 2853): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2853): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2853): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2853): Added TimaKesytore provider
,I/jxcore-log( 2733): JXcore Cordova bridge is ready!
I/jxcore-log( 2733): 
,W/jxcore-log( 2733): JXcore engine is started
,D/NPS_WSSNPS( 2853): [] android.intent.action.BOOT_COMPLETED
,D/NPS_WSSNPS( 2853): [] Service onCreate!!
W/ContextImpl( 2853): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.wssnps.smlNpsReceiver.onReceive:380 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2868): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2868):  
,D/NPS_WSSNPS( 2853): [] NpsServiceTask Start
,I/NPS_WSSNPS( 2853): [44.140541] loadCryptionkeyLibrary
,I/NPS_WSSNPS( 2853): [44.140541] FirstLoad Or Not Exist
,D/dalvikvm( 2853): Trying to load lib /data/data/com.wssnps/files/libCryptionkey.so 0x42a93630
,D/dalvikvm( 2853): Added shared lib /data/data/com.wssnps/files/libCryptionkey.so 0x42a93630
,D/NPS_WSSNPS( 2853): [44.140541] smlDBHelper
,E/jxcore-log( 2733): >> samsung-SM-G800H
E/jxcore-log( 2733): 
,I/jxcore-log( 2733): Total memory 1454641152
I/jxcore-log( 2733): 
,I/jxcore-log( 2733): Free memory 416096256
I/jxcore-log( 2733): 
I/jxcore-log( 2733): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2733): 
,I/jxcore-log( 2733): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2733): 
,I/jxcore-log( 2733): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2733): 
,I/jxcore-log( 2733): Size 720 1280
I/jxcore-log( 2733): 
,I/jxcore-log( 2733): Screen Brightness 134
I/jxcore-log( 2733): 
,E/jxcore-log( 2733): Dummy Error Log.
E/jxcore-log( 2733): 
,I/NPS_WSSNPS( 2853): [44.140541] AsyncBulkFlagCheck
,I/NPS_WSSNPS( 2853): [44.140541] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 2853): [44.140541] IsRemain_Asyncing nothing
,D/NPS_WSSNPS( 2853): [44.140541] Service onDestroy
,I/NPS_WSSNPS( 2853): [44.140541] smlBRConfigurationDelete
,I/NPS_WSSNPS( 2853): [44.140541] smlBRMessageDelete
,I/NPS_WSSNPS( 2853): [44.140541] smlBREmailDelete
,I/SELinux ( 2868): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2868):  
I/SELinux ( 2868):  
,W/ContextImpl( 2853): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 com.wssnps.smlNpsService$1.run:108 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/SELinux ( 2868): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/NPS_WSSNPS( 2853): [44.140541] smlBRNetworkDelete
E/SELinux ( 2868): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2868): >>>>> Normal User
E/dalvikvm( 2868): >>>>> com.samsung.android.app.accesscontrol [ userId:0 | appId:10064 ]
I/NPS_WSSNPS( 2853): [44.140541] smlBRCallLogDelete
I/NPS_WSSNPS( 2853): [44.140541] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 2853): [44.140541] smlBRPenMemoMDelete
I/NPS_WSSNPS( 2853): [44.140541] smlBRSMemoDelete
E/SELinux ( 2868): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/NPS_WSSNPS( 2853): [44.140541] cpuBooster release : false
D/NPS_WSSNPS( 2853): [44.140541] dsServerSocket close
,D/TimaKeyStoreProvider( 2868): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2868): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2868): Added TimaKesytore provider
,I/SELinux ( 2889): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2889):  
,I/SELinux ( 2889): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2889):  
I/SELinux ( 2889):  
,I/SELinux ( 2889): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2889): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2889): >>>>> Normal User
,E/dalvikvm( 2889): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
,E/SELinux ( 2889): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2889): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2889): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2889): Added TimaKesytore provider
,D/FileShare-Server( 2889): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/SELinux ( 2907): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2907):  
,I/SELinux ( 2907): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2907):  
I/SELinux ( 2907):  
,I/SELinux ( 2907): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2907): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2907): >>>>> Normal User
,E/dalvikvm( 2907): >>>>> com.sec.android.nearby.mediaserver [ userId:0 | appId:10070 ]
,E/SELinux ( 2907): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2907): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2907): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2907): Added TimaKesytore provider
,I/jxcore-log( 2733): getBuffer is called!!!!
I/jxcore-log( 2733): 
,I/AllShare(ASF-DMSLIB)( 2907): DMSReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,W/BackupManagerService(  753): dataChanged but no participant pkg='com.android.providers.settings' uid=10070
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/SELinux ( 2922): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2922):  
I/ActivityManager(  753): Killing 1287:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #43
,I/SELinux ( 2922): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2922):  
I/SELinux ( 2922):  
,I/SELinux ( 2922): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2922): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2922): >>>>> Normal User
,E/dalvikvm( 2922): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 2922): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2922): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2922): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2922): Added TimaKesytore provider
,W/ContextImpl( 2922): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:61 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2940): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2940):  
,I/SELinux ( 2940): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2940):  
I/SELinux ( 2940):  
,I/SELinux ( 2940): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2940): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2940): >>>>> Normal User
,E/dalvikvm( 2940): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
,E/SELinux ( 2940): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2940): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2940): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2940): Added TimaKesytore provider
,D/BluetoothBDAdrressReceiver( 2940): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2940): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
W/ContextImpl( 2940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2952): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2952):  
,D/BluetoothBDTestService( 1239): onCreate()
E/BluetoothBDTestService( 1239): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
,E/BluetoothBDTestService( 1239): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1239): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/ActivityManager(  753): Killing 1272:com.android.printspooler/u0a144 (adj 15): empty #43
D/PackageManager(  753): [MSG] MCS_UNBIND
I/PackageManager(  753): calling disconnectService()
D/PackageManager(  753): Trying to unbind to DefaultContainerService
,I/SELinux ( 2952): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2952):  
I/SELinux ( 2952):  
,I/SELinux ( 2952): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2952): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2952): >>>>> Normal User
,E/dalvikvm( 2952): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,I/ActivityManager(  753): Killing 1770:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #43
E/SELinux ( 2952): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 2952): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2952): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2952): Added TimaKesytore provider
,W/ActivityManager(  753): Permission Denial: getCurrentUser() from pid=2952, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 2968): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2968):  
I/ActivityManager(  753): Killing 1783:com.sec.modem.settings/1000 (adj 15): empty #43
,I/SELinux ( 2968): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2968):  
I/SELinux ( 2968):  
,I/SELinux ( 2968): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2968): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2968): >>>>> Normal User
,E/dalvikvm( 2968): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 2968): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2968): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2968): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2968): Added TimaKesytore provider
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2922): Resource data:2131165197
,I/AMMetaDataParserService( 2922): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131165194
,I/AMMetaDataParserService( 2922): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/AMMetaDataParserService( 2922): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
E/PersonaManagerService(  753): returning null in  getPersonasForUser
,I/SELinux ( 2980): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2980):  
I/ActivityManager(  753): Killing 1795:com.sec.tcpdumpservice/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2922): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,D/dalvikvm(  248): GC_EXPLICIT freed 46K, 49% free 9510K/18460K, paused 2ms+3ms, total 30ms
,I/SELinux ( 2980): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2980):  
I/SELinux ( 2980):  
,I/SELinux ( 2980): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2980): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2980): >>>>> Normal User
,E/dalvikvm( 2980): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 49% free 9510K/18460K, paused 2ms+3ms, total 19ms
,E/SELinux ( 2980): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2922): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,D/TimaKeyStoreProvider( 2980): in addTimaSignatureService
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 49% free 9510K/18460K, paused 1ms+2ms, total 19ms
,D/TimaKeyStoreProvider( 2980): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2980): Added TimaKesytore provider
,I/AMMetaDataParserService( 2922): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131165194
I/AMMetaDataParserService( 2922): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/AMMetaDataParserService( 2922): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,V/AlarmManager(  753): waitForAlarm result :4
,V/AlarmManager(  753): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/AMMetaDataParserService( 2922): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,I/AMMetaDataParserService( 2922): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,W/BackupManagerService(  753): dataChanged but no participant pkg='com.android.providers.settings' uid=10084
,I/AMMetaDataParserService( 2922): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,I/AMMetaDataParserService( 2922): Resource data:2131165195
,I/AMMetaDataParserService( 2922): getResourceName:com.sec.android.gallery3d:xml/device_filter
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2922): Resource data:2131165204
,I/AMMetaDataParserService( 2922): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2922): Resource data:2131165204
,I/AMMetaDataParserService( 2922): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2922): Resource data:2131165204
I/AMMetaDataParserService( 2922): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2922): Resource data:2131099676
,I/AMMetaDataParserService( 2922): getResourceName:com.android.mms:xml/spellscroll
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/AMMetaDataParserService( 2922): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131099648
I/AMMetaDataParserService( 2922): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/AMMetaDataParserService( 2922): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 2997): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2997):  
,I/AMMetaDataParserService( 2922): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
I/ActivityManager(  753): Killing 1826:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/SensorService(  753):   -0.1 -0.1 9.6
,I/AMMetaDataParserService( 2922): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/SELinux ( 2997): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2997):  
I/SELinux ( 2997):  
,I/SELinux ( 2997): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2997): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2997): >>>>> Normal User
,E/dalvikvm( 2997): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
,E/SELinux ( 2997): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2922): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/TimaKeyStoreProvider( 2997): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2997): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2997): Added TimaKesytore provider
,I/AMMetaDataParserService( 2922): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2922): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131099648
I/AMMetaDataParserService( 2922): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/SELinux ( 3010): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3010):  
,I/AMMetaDataParserService( 2922): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
I/ActivityManager(  753): Killing 1743:com.sec.android.app.mt/1000 (adj 15): empty #43
,D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,I/AMMetaDataParserService( 2922): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/ActivityManager(  753): Waited long enough for: ServiceRecord{43490888 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/SELinux ( 3010): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3010):  
I/SELinux ( 3010):  
,I/SELinux ( 3010): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3010): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 3010): >>>>> Normal User
,E/dalvikvm( 3010): >>>>> com.dropbox.android [ userId:0 | appId:10091 ]
,E/SELinux ( 3010): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/AMMetaDataParserService( 2922): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/TimaKeyStoreProvider( 3010): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3010): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3010): Added TimaKesytore provider
,I/AMMetaDataParserService( 2922): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2922): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2922): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131099648
I/AMMetaDataParserService( 2922): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,E/SMD     (  241): DCD ON
,I/AMMetaDataParserService( 2922): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2922): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3010): Setting receiver enabled: false
,I/AMMetaDataParserService( 2922): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/com.dropbox.sync.android.a( 3010): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/AMMetaDataParserService( 2922): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
I/com.dropbox.sync.android.aa( 3010): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800H armeabi-v7a; en_US))
,I/AMMetaDataParserService( 2922): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,W/ActivityManager(  753): Permission Denial: getCurrentUser() from pid=3010, uid=10091 requires android.permission.INTERACT_ACROSS_USERS
,I/AMMetaDataParserService( 2922): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131099648
I/AMMetaDataParserService( 2922): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/SELinux ( 3037): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3037):  
I/ActivityManager(  753): Killing 1894:com.sec.phone/1001 (adj 15): empty #43
,I/AMMetaDataParserService( 2922): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2922): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 3037): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3037):  
I/SELinux ( 3037):  
,I/SELinux ( 3037): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3037): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3037): >>>>> Normal User
,E/dalvikvm( 3037): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 3037): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3037): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3037): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3037): Added TimaKesytore provider
,I/AMMetaDataParserService( 2922): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/AMMetaDataParserService( 2922): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2922): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/elm:14132( 3037): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 3037): ELMEngine.ELMEngine( context ).
,W/ActivityManager(  753): Permission Denial: getCurrentUser() from pid=3037, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 3037): MDMBridge.setEnterpriseBridge()
D/elm:14132( 3037): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 3037): ElmAgentService : onCreate()
D/elm:14132( 3037): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14132( 3037): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:14132( 3037): BootCompletedState : startBootCompleted() call
,I/AMMetaDataParserService( 2922): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/SELinux ( 3052): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3052):  
,D/elm:14132( 3037): ModuleBase.resetCalllogAPIAlarm()
,D/elm:14132( 3037): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:14132( 3037): Get License : 0
,D/elm:14132( 3037): ElmAgentService : onDestroy().
I/ActivityManager(  753): Killing 1989:com.google.android.configupdater/u0a3 (adj 15): empty #43
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131099648
I/AMMetaDataParserService( 2922): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/AMMetaDataParserService( 2922): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
I/SELinux ( 3052): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3052):  
I/SELinux ( 3052):  
,I/SELinux ( 3052): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3052): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3052): >>>>> Normal User
,E/dalvikvm( 3052): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,E/SELinux ( 3052): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3052): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3052): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3052): Added TimaKesytore provider
,I/AMMetaDataParserService( 2922): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2922): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/System.out( 3010): Thread-257(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 3010): Thread-257(ApacheHTTPLog):isShipBuild true
,I/System.out( 3010): Thread-257(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/AMMetaDataParserService( 2922): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/System.out( 3010): pool-4-thread-1 calls detatch()
,I/AMMetaDataParserService( 2922): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2922): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131099648
,I/AMMetaDataParserService( 2922): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,D/dalvikvm(  753): GC_EXPLICIT freed 1634K, 17% free 22670K/27152K, paused 5ms+11ms, total 123ms
,I/AMMetaDataParserService( 2922): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2922): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 3068): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3068):  
,I/AMMetaDataParserService( 2922): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
I/ActivityManager(  753): Killing 2088:com.sec.dsm.system/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2922): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 3068): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3068):  
I/SELinux ( 3068):  
,I/SELinux ( 3068): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3068): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3068): >>>>> Normal User
,E/dalvikvm( 3068): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,E/SELinux ( 3068): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2922): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/TimaKeyStoreProvider( 3068): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3068): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3068): Added TimaKesytore provider
,I/AMMetaDataParserService( 2922): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2922): Resource data:2131099671
I/AMMetaDataParserService( 2922): getResourceName:com.android.mms:xml/searchable
I/AMMetaDataParserService( 2922): getResourceTypeNamexml
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/CameraApp( 3068): CameraApp.onCreate()... mFeature : null
I/testFeature( 3068): Feature.Feature(context)
I/testFeature( 3068): Feature.readInternalDefaultXml()
I/testFeature( 3068): ResetFeatureValue
I/CameraFirmware_broadcast( 3068): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3068): CameraApp.getAppFeature()...
,I/SELinux ( 3083): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3083):  
I/ActivityManager(  753): Killing 2157:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
,I/SELinux ( 3083): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3083):  
I/SELinux ( 3083):  
,I/SELinux ( 3083): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3083): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3083): >>>>> Normal User
,E/dalvikvm( 3083): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 3083): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3083): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3083): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3083): Added TimaKesytore provider
,D/dalvikvm( 2922): GC_CONCURRENT freed 4984K, 32% free 12706K/18460K, paused 3ms+3ms, total 40ms
,D/dalvikvm( 2922): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131165216
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/AMMetaDataParserService( 2922): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,D/PackageIntentReceiver( 3083): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3083): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager(  753): Killing 2177:com.sec.kidsplat.installer/u0a158 (adj 15): empty #43
,I/AMMetaDataParserService( 2922): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.TimDataConnectionDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429159
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2922): Resource data:2131296695
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/SELinux ( 3098): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3098):  
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429159
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429144
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429144
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429144
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
,I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2922): Resource data:2131297114
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ApnSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ApnSettingsTabActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429146
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429146
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429168
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/mirror_link_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429159
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2922): Resource data:2131296695
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429159
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2922): Resource data:2131296695
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429144
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2922): Resource data:2131297114
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429159
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2922): Resource data:2131296695
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429159
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2922): Resource data:2131296695
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429159
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2922): Resource data:2131296695
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429159
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2922): Resource data:2131296695
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429159
I/SELinux ( 3098): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3098):  
I/SELinux ( 3098):  
,I/SELinux ( 3098): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131296695
,E/SELinux ( 3098): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3098): >>>>> Normal User
E/dalvikvm( 3098): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429219
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429191
E/SELinux ( 3098): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429191
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429191
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429191
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429191
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429191
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131298419
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429191
D/TimaKeyStoreProvider( 3098): in addTimaSignatureService
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131298419
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429191
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/TimaKeyStoreProvider( 3098): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131298419
D/ActivityThread( 3098): Added TimaKesytore provider
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429176
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SoundSettings
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429176
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429173
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429173
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429172
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429172
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429182
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429173
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429186
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429186
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429173
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/display_settings
,I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2922): Resource data:2131297804
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429173
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/display_settings
,I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429228
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.users.UserOptions
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429128
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
,I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2922): Resource data:2131429128
,I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.RunningServices
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429128
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429127
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429127
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429128
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429128
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/PowerManagerService(  753): [PWL] On : 0 (44912 ms ago)
I/PowerManagerService(  753): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService(  753): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1067, ws=null) (elapsedTime=7244)
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429127
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429127
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429128
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429153
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429224
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.CarrierMatchSetting
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserServ,ice( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429224
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131296750
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429224
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429123
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/privacy_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429224
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131296750
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429224
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:21312,96750
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429187
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429187
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131298587
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429187
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131298587
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429191
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429180
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/driving_mode
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429223
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429225
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429159
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131296695
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429165
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429225
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429223
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131297938
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429223
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131297938
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429161
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429163
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429167
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131296695
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429221
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429221
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429119
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429217
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429224
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429224
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429159
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429173
W/ContextImpl(  753): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429208
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429286
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429224
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429201
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429185
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429185
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131299843
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/power_saving_mode_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,W/ActivityManager(  753): Permission Denial: getCurrentUser() from pid=3098, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
I/AMMetaDataParserService( 2922): Resource data:2131429185
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429185
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429222
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/power_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429186
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 2922): Resource data:1
W/ResourceType( 2922): No package identifier when getting name for resource number 0x00000001
W/System.err( 2922): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 2922): 	at android.content.res.Resources.getResourceName(Resources.java:3017)
W/System.err( 2922): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.construc,tDBdata(AMMetaDataParserService.java:159)
W/System.err( 2922): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 2922): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 2922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2922): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 2922): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429199
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131301070
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429173
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131297804
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429203
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429193
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.sett,ings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429194
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429206
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131300118
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429196
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429260
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429197
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429291
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429228
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429199
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429199
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429199
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429199
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.NetworkManagement
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.MultiSimCardManagerPreference
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.NetworkManagementSetting
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.DualHelpActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.DualSoundRingtoneSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.RingtoneSettingTabActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.IccLockTabSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429173
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429285
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429172
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131301505
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429203
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429203
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131302910
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429179
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2130838248
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2922): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429216
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429209
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429209
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAlertDialogActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429177
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429212
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429213
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429153
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131302078
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429153
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131302078
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429153
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131302107
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429159
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429159
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429117
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/Babel   ( 3098): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3098): MmsConfig.loadMmsSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/Babel   ( 3098): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
I/Babel   ( 3098): MmsConfig.loadFromDatabase
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429122
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429195
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131297804
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429151
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429204
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429204
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429195
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2130838300
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2922): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2130838300
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2922): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429202
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429202
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2922): Resource data:2131165381
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:xml/searchable
I/AMMetaDataParserService( 2922): getResourceTypeNamexml
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429124
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429187
E/Babel   ( 3098): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3098): MmsConfig.loadFromResources
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2922): Resource data:2131298587
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2922): getResourceTypeNamestring
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
E/Babel   ( 3098): canonicalizeMccMnc: invalid mccmnc nullnull
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429198
I/Babel   ( 3098): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429258
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429220
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429220
W/Settings( 3098): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429276
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429276
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429148
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429242
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.KnoxSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429211
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2130838248
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2922): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2922): Resource data:2131429192
I/AMMetaDataParserService( 2922): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 2922): getResourceTypeNameid
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintOnehandGrip
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
D/dalvikvm( 3098): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 3098): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3098): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3098): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3098): VFY: unable to resolve instance field 46
D/dalvikvm( 3098): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3098): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3098): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3098): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3098): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 3098): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
D/dalvikvm( 3098): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bca388
D/dalvikvm( 3098): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bca388
D/dalvikvm( 3098): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bca388, skipping init
V/Babel   ( 3098): babel boot account: thalitester@gmail.com
V/Babel   ( 3098): babel boot account: SMS
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2922): Resource data:2131034120
D/dalvikvm( 3098): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bca388
D/dalvikvm( 3098): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bca388
V/JNIHelp ( 3098): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/AMMetaDataParserService( 2922): getResourceName:com.android.contacts:xml/searchable
I/AMMetaDataParserService( 2922): getResourceTypeNamexml
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
I/AMMetaDataParserService( 2922): Resource data:2131034113
I/AMMetaDataParserService( 2922): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 2922): getResourceTypeNamexml
I/SELinux ( 3129): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3129):  
I/ActivityManager(  753): Killing 2202:com.sec.factory/1000 (adj 15): empty #43
I/AMMetaDataParserService( 2922): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/AMMetaDataParserService( 2922): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
I/SELinux ( 3129): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3129):  
I/SELinux ( 3129):  
,I/SELinux ( 3129): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3129): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3129): >>>>> Normal User
,E/dalvikvm( 3129): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 3129): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 3098): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bca388
,D/dalvikvm( 3098): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42bca388
D/dalvikvm( 3098): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bca388
,D/dalvikvm( 3098): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42bca388
,D/TimaKeyStoreProvider( 3129): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3129): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3129): Added TimaKesytore provider
,I/AMMetaDataParserService( 2922): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/AMMetaDataParserService( 2922): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131034113
I/AMMetaDataParserService( 2922): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/ProviderInstaller( 3098): Installed default security provider GmsCore_OpenSSL
,I/AMMetaDataParserService( 2922): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
V/AlarmManager(  753): waitForAlarm result :4
V/AlarmManager(  753): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 3145): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3145):  
,I/AMMetaDataParserService( 2922): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
I/ActivityManager(  753): Killing 2228:com.sec.android.diagmonagent/1000 (adj 15): empty #43
V/AlarmManager(  753): waitForAlarm result :4
V/AlarmManager(  753): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/AMMetaDataParserService( 2922): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/SELinux ( 3145): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3145):  
I/SELinux ( 3145):  
,I/SELinux ( 3145): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3145): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3145): >>>>> Normal User
,E/dalvikvm( 3145): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
,I/AMMetaDataParserService( 2922): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,E/SELinux ( 3145): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2922): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 2922): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 2922): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131034112
I/AMMetaDataParserService( 2922): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 3145): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3145): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3145): Added TimaKesytore provider
,I/AMMetaDataParserService( 2922): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
,I/AMMetaDataParserService( 2922): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
,W/ContextImpl( 3145): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
,I/AMMetaDataParserService( 2922): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
,I/knox    ( 3145): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3145): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
,I/knox    ( 3145): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3145): KNOXAgentService : onCreate()
,D/knox    ( 3145): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3145): KNOXAgentService. startJobThread() start
,D/knox    ( 3145): KNOXAgentService. JobThread()
D/knox    ( 3145): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3145): KNOXAgentService. startJobThread() wait
,I/AMMetaDataParserService( 2922): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
,I/SELinux ( 3160): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3160):  
,D/knox    ( 3145): mKnoxAgentEngine.ELMEngine( context , reStart:true).
D/knox    ( 3145): KNOXAgentService : onDestroy().
,D/knox    ( 3145): ModuleBase.cancelAllAlarmManageModule()
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserSer,vice( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
I/AMMetaDataParserService( 2922): Resource data:2131034113
,I/AMMetaDataParserService( 2922): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/AMMetaDataParserService( 2922): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/AMMetaDataParserService( 2922): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/SELinux ( 3160): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3160):  
I/SELinux ( 3160):  
I/SELinux ( 3160): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3160): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3160): >>>>> Normal User
,E/dalvikvm( 3160): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
,E/SELinux ( 3160): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3160): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3160): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3160): Added TimaKesytore provider
,D/dalvikvm( 2922): GC_CONCURRENT freed 2314K, 33% free 12377K/18460K, paused 3ms+2ms, total 39ms
,I/AMMetaDataParserService( 2922): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,E/KnoxSetupWizardClient( 3160): isShipMode : 1
,I/KnoxSetupWizardClient( 3160): onReceive : android.intent.action.BOOT_COMPLETED
,W/System.err( 3160): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3160): 	at android.os.Parcel.readException(Parcel.java:1469)
,W/System.err( 3160): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 3160): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
,W/System.err( 3160): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 3160): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
,W/System.err( 3160): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/System.err( 3160): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
W/System.err( 3160): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 3160): 	at android.os.Parcel.readException(Parcel.java:1419)
,W/System.err( 3160): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3160): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 3160): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
I/AMMetaDataParserService( 2922): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,W/System.err( 3160): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
W/System.err( 3160): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/ShortcutReceiver( 3160):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/yash    ( 3160): setDisableWidget>size:0
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2922): Resource data:2131034116
I/AMMetaDataParserService( 2922): getResourceName:com.android.contacts:xml/findo_searchable
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2922): Resource data:2131099668
,I/SELinux ( 3173): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3173):  
I/ActivityManager(  753): Killing 1696:com.fmm.dm/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2922): getResourceName:com.sec.android.app.sbrowser:xml/searchable
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
I/ActivityManager(  753): Waited long enough for: ServiceRecord{435e16b0 u0 com.samsung.android.providers.context/.ContextService}
,I/AMMetaDataParserService( 2922): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 2922): Resource data:2131099650
I/AMMetaDataParserService( 2922): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,D/dalvikvm(  248): GC_EXPLICIT freed 47K, 49% free 9510K/18460K, paused 5ms+3ms, total 31ms
,I/AMMetaDataParserService( 2922): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,I/SELinux ( 3173): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3173):  
I/SELinux ( 3173):  
,I/SELinux ( 3173): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3173): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3173): >>>>> Normal User
,E/dalvikvm( 3173): >>>>> com.LocalFota [ userId:0 | appId:10110 ]
,E/SELinux ( 3173): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 49% free 9510K/18460K, paused 2ms+3ms, total 20ms
,I/GAV2    ( 2126): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 3173): in addTimaSignatureService
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 49% free 9510K/18460K, paused 2ms+3ms, total 21ms
,D/TimaKeyStoreProvider( 3173): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3173): Added TimaKesytore provider
,I/AMMetaDataParserService( 2922): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
,I/GAv4-SVC( 1639): Google Analytics 8.3.01 is starting up.
,I/AMMetaDataParserService( 2922): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
,D/dalvikvm( 2126): GC_CONCURRENT freed 6332K, 40% free 11243K/18460K, paused 4ms+2ms, total 40ms
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 2922): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAutoDiscover
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserSe,rvice( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131099667
,I/AMMetaDataParserService( 2922): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,W/ActivityManager(  753): Permission Denial: getCurrentUser() from pid=3173, uid=10110 requires android.permission.INTERACT_ACROSS_USERS
I/DBG_WSS_LF( 3173): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
I/DBG_WSS_LF( 3173): [20.0040.140326][Line:27][<init>] First call
,I/AMMetaDataParserService( 2922): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559
,I/AMMetaDataParserService( 2922): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558
,I/DBG_WSS_LF( 3173): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_WSS_LF( 3173): [20.0040.140326][Line:31][onReceive] *** boot complete ***
,I/DBG_WSS_LF( 3173): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
,I/DBG_WSS_LF( 3173): [20.0040.140326][Line:41][onReceive] nStatus : -1
,I/AMMetaDataParserService( 2922): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
,I/SELinux ( 3193): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3193):  
I/ActivityManager(  753): Killing 2242:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
,I/AMMetaDataParserService( 2922): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
,I/SELinux ( 3193): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3193):  
I/SELinux ( 3193):  
,I/SELinux ( 3193): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/AMMetaDataParserService( 2922): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
E/SELinux ( 3193): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3193): >>>>> Normal User
,E/dalvikvm( 3193): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
,E/SELinux ( 3193): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3193): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3193): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3193): Added TimaKesytore provider
,I/AMMetaDataParserService( 2922): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2922): Resource data:2131099689
,I/AMMetaDataParserService( 2922): getResourceName:com.android.email:xml/spellscroll
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2922): Resource data:2131099685
,I/AMMetaDataParserService( 2922): getResourceName:com.android.email:xml/searchable
I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/AMMetaDataParserService( 2922): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 2922): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2922): getResourcePackageName:com.android.keyguard.layout
,I/AMMetaDataParserService( 2922): Resource data:2130903052
,I/AMMetaDataParserService( 2922): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
I/AMMetaDataParserService( 2922): getResourceTypeNamelayout
I/AMMetaDataParserService( 2922): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2922): Resource data:2131034112
,I/AMMetaDataParserService( 2922): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 2922): getResourceTypeNamexml
,I/AMMetaDataParserService( 2922): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,D/StatusChecker( 3193): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 2922): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
,I/SELinux ( 3210): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3210):  
I/ActivityManager(  753): Killing 2254:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #43
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 2922): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
I/ActivityManager(  753): Killing 2281:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,I/SELinux ( 3210): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3210):  
I/SELinux ( 3210):  
,I/SELinux ( 3210): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3210): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3210): >>>>> Normal User
,E/dalvikvm( 3210): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10133 ]
,E/SELinux ( 3210): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3210): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3210): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3210): Added TimaKesytore provider
,D/QuickConnect( 3210): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,W/BackupManagerService(  753): dataChanged but no participant pkg='com.android.providers.settings' uid=10133
D/QuickConnect( 3210): Utils.setQCRunningSetting - set : 0
I/QuickConnect( 3210): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
V/QuickConnect( 3210): SconnectManager.getInstance - () return existing instance null
W/ContextImpl( 3210): Implicit intents with startService are not safe: Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } android.content.ContextWrapper.startServiceAsUser:517 android.content.ContextWrapper.startServiceAsUser:517 com.samsung.android.sconnect.periph.PeriphStartReceiver.onReceive:30 
I/QuickConnect( 3210): PeriphService.onCreate - [START]
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,I/SELinux ( 3223): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3223):  
,I/QuickConnect( 3210): PeriphService.onCreate - [START] USER_OWNER
,D/QuickConnect( 3210): PeriphService.setProcessForeground - Build.VERSION.SDK_INT = 19
,I/QuickConnect( 3210): PeriphService.setProcessForeground - true of JB_MR2 complete 
I/QuickConnect( 3210): PeriphService.setState - 0 >> 1
,V/QuickConnect( 3210): PeriphService.runService - 
,I/QuickConnect[1.1][2] ( 3210): SconnectManager.SconnectManager - initiate from com.samsung.android.sconnect.periph.PeriphService@42a9b558
,I/QuickConnect[1.1][2] ( 3210): SconnectManager.SconnectManager - set getApplicationContext android.app.Application@42a93420
,D/QuickConnect[1.1][2] ( 3210): SconnectManager.registerBroadcast - --
,D/QuickConnect[1.1][2] ( 3210): SconnectManager.SconnectManager - REQUEST_ID :  1
,D/QuickConnect[1.1][2] ( 3210): ScanThread.ScanThread - created!
,V/QuickConnect[1.1][2] ( 3210): BluetoothHelper.BluetoothHelper - 
,D/QuickConnect[1.1][2] ( 3210): BluetoothHelper.registerBluetoothAdapterReceiver - mIsBluetoothAdapterReceiver = false
,V/QuickConnect[1.1][2] ( 3210): BleHelper.BleHelper - Constructor
I/SELinux ( 3223): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3223):  
I/SELinux ( 3223):  
,I/SELinux ( 3223): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3223): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3223): >>>>> Normal User
,E/dalvikvm( 3223): >>>>> com.sec.android.service.bezel [ userId:0 | appId:1000 ]
,E/SELinux ( 3223): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3223): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3223): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3223): Added TimaKesytore provider
,E/QuickConnect[1.1][2] ( 3210): BleHelper.startScan - not isGattServiceReady. Try to BLE On calling addLeRadioReference()
D/BluetoothRadioManager( 3210): addLeRadioReference: Add CB  com.samsung.android.sconnect.common.net.BleHelper$GattServiceStateChangeCallback@42aae908
D/BluetoothRadioManager( 3210):  addRadioReference enabled = false
,D/BluetoothRadioManager( 3210):  BLE Radio count is : 1
D/BluetoothManagerService(  753): foregroundUser: 0
D/BluetoothRadioManager( 3210): addLeRadioReference: isRadioEnabled() =  false
,V/QuickConnect[1.1][2] ( 3210): BleHelper.mSearchWearable - true
,V/QuickConnect[1.1][2] ( 3210): UpnpHelper.UpnpHelper - 
,V/QuickConnect[1.1][2] ( 3210): JmdnsHelper.JmdnsHelper - Constructor
,V/QuickConnect[1.1][2] ( 3210): P2pHelper.P2pHelper - EXEC
,D/QuickConnect[1.1][2] ( 3210): p2pHelperWorkThread.p2pHelperWorkThread - created!
,E/BluetoothManagerService(  753): Package is exist.
,D/QuickConnect[1.1][2] ( 3210): WifiHelper.WifiHelper -  -- 
,I/SELinux ( 3238): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3238):  
,I/QuickConnect[1.1][2] ( 3210): CentralActionManager.CentralActionManager - EXEC
,V/QuickConnect[1.1][2] ( 3210): BluetoothOppActionHelper.BluetoothOppActionHelper - 
,V/QuickConnect[1.1][2] ( 3210): GroupVoiceTalkActionHelper.GroupVoiceTalkActionHelper -  --
,V/QuickConnect[1.1][2] ( 3210): SmartHomeActionHelper.SmartHomeActionHelper - --
,D/WifiDisplayAdapter(  753): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
V/QuickConnect[1.1][2] ( 3210): ScreenMirrorActionHelper.ScreenMirrorActionHelper - 
D/BezelQuickConnect( 3223): BezelBroadcastReceiver - onReceive : android.intent.action.BOOT_COMPLETED
D/BezelQuickConnect( 3223): BezelBroadcastReceiver - StartBezelInteractionService
V/QuickConnect[1.1][2] ( 3210): BluetoothActionHelper.BluetoothActionHelper - 
D/BezelQuickConnect( 3223): BezelManagerService - setProcessForeground, Build.VERSION.SDK_INT = 19
D/BluetoothAdapter( 3210): 1118481304: getState() :  mService = null. Returning STATE_OFF
I/BezelQuickConnect( 3223): BezelManagerService - setProcessForeground, true of JB_MR2 complete 
,D/BezelQuickConnect( 3223): BezelBroadcastReceiver - onReceive : Send to quickpanel - service.ENABLED
,V/PhoneStatusBar( 1067): onReceive: Intent { act=com.sec.android.sconnect.service.ENABLED flg=0x10 }mQconnectEnable = true
W/ContextImpl( 3223): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.android.service.bezel.BezelBroadcastReceiver.onReceive:40 android.app.ActivityThread.handleReceiver:2698 
,E/NetworkSettingsReceiver( 1757): onReceive: android.intent.action.BOOT_COMPLETED
D/STATUSBAR-PhoneStatusBar( 1067): showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
,E/BluetoothHeadset( 3210): BTStateChangeCB is registed
,E/BluetoothHeadset( 3210): BluetoothHeadset service is binded
,W/BroadcastQueue(  753): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.android.calendar/.magazine.CalendarUpdateRelatedDataReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/SELinux ( 3238): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3238):  
I/SELinux ( 3238):  
,I/SELinux ( 3238): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3238): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3238): >>>>> Normal User
,E/dalvikvm( 3238): >>>>> com.android.bluetooth [ userId:0 | appId:1002 ]
,E/SELinux ( 3238): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3238): in addTimaSignatureService
,I/SELinux ( 3252): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3252):  
,D/TimaKeyStoreProvider( 3238): Cannot add TimaSignature Service, License check Failed
I/QuickConnect[1.1][2] ( 3210): SconnectManager.getInstance - make new instance com.samsung.android.sconnect.SconnectManager@42a9d150
,V/QuickConnect[1.1][2] ( 3210): SconnectManager.getInstance - return existing instance com.samsung.android.sconnect.SconnectManager@42a9d150
V/QuickConnect[1.1][2] ( 3210): PreDiscoveryHelper.PreDiscoveryHelper -  -- 
,D/QuickConnect[1.1][2] ( 3210): PreDiscoveryHelper.setVisibilityFromSystemDb - --
,D/ActivityThread( 3238): Added TimaKesytore provider
,D/QuickConnect[1.1][2] ( 3210): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,D/QuickConnect[1.1][2] ( 3210): Utils.getFromDb -  Key[quick_connect_contact_only], isEnabled [1] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 3210): PreDiscoveryHelper.setVisibilityFromSystemDb - isAllowToConnect : false, isContactOnly : true, visibilitySetting : 2
,D/QuickConnect[1.1][2] ( 3210): PreDiscoveryHelper.changeResponseSetting - changed: 2
V/QuickConnect[1.1][2] ( 3210): PreDiscoveryHelper.updateAdvData - 
,V/QuickConnect[1.1][2] ( 3210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a9d150
,V/QuickConnect[1.1][2] ( 3210): PreDiscoveryHelper.updateRespTarget - 
,D/QuickConnect[1.1][2] ( 3210): PreDiscoveryHelper.initializeAdvData - 
,V/QuickConnect[1.1][2] ( 3210): PreDiscoveryHelper.initializeAdvData - name: Galaxy S5-2(11)
D/QuickConnect[1.1][2] ( 3210): PreDiscoveryHelper.initializeAdvData - name selected: Galaxy S5-2(11)
,V/QuickConnect[1.1][2] ( 3210): CONTACT_Info.getMyMobileNumber - 
,I/SELinux ( 3252): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3252):  
I/SELinux ( 3252):  
,I/SELinux ( 3252): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3252): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3252): >>>>> Normal User
,E/dalvikvm( 3252): >>>>> com.sec.android.app.camera [ userId:0 | appId:10147 ]
,D/QuickConnect[1.1][2] ( 3210): CONTACT_Info.getAccountNumber - ($)
E/SELinux ( 3252): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/QuickConnect[1.1][2] ( 3210): CONTACT_Info.getMyMobileNumber - null 
,D/QuickConnect[1.1][2] ( 3210): NetUtil.getP2pMacFromWifiMac - ($)
,V/QuickConnect[1.1][2] ( 3210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a9d150
,W/QuickConnect[1.1][2] ( 3210): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.emeeting.b2c.hancom
,D/QuickConnect[1.1][2] ( 3210): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.emeeting
,D/TimaKeyStoreProvider( 3252): in addTimaSignatureService
,D/QuickConnect[1.1][2] ( 3210): AppPackageUtil.isStubApk - but Stub version[2.7.025] of com.samsung.groupcast
W/QuickConnect[1.1][2] ( 3210): AppPackageUtil.isAppInstalled - this is Stub - com.samsung.groupcast
,D/QuickConnect[1.1][2] ( 3210): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.samsung.groupcast
W/QuickConnect[1.1][2] ( 3210): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3210): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3210): PeriphService.registerUserReceiver - mIsUserReceiver == false
,D/TimaKeyStoreProvider( 3252): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3252): Added TimaKesytore provider
I/QuickConnect[1.1][2] ( 3210): PeriphService.onStartCommand - USER_OWNER
I/QuickConnect[1.1][2] ( 3210): PeriphService.onStartCommand - Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } flags[0] startId[1]
,I/QuickConnect[1.1][2] ( 3210): PeriphService.onStartCommand - Action: com.samsung.android.sconnect.periph.START_SERVICE
,D/BtSettings.ProfileConfig( 3238): Adding GattService
,D/BtSettings.ProfileConfig( 3238): Adding HeadsetService
D/BtSettings.ProfileConfig( 3238): Adding A2dpService
D/BtSettings.ProfileConfig( 3238): Adding HidService
,D/BtSettings.ProfileConfig( 3238): Adding HealthService
D/BtSettings.ProfileConfig( 3238): Adding PanService
,D/BtSettings.ProfileConfig( 3238): Adding BluetoothMapService
,W/dalvikvm( 3252): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,D/BluetoothAdapterService( 3238): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterState( 3238): make
I/bluedroid( 3238): init
,I/BluetoothAdapterState( 3238): Entering OffState
,I/bte_conf( 3238): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/SELinux ( 3268): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3268):  
,I/bluedroid( 3238): get_profile_interface socket
,D/BluetoothAdapterService( 3238):  checkAddrForIOP: Loading from conf
,I/GKI_LINUX( 3238): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
I/ActivityManager(  753): Killing 2297:com.sec.android.app.mss/u0a21 (adj 15): empty #43
,E/BluetoothServiceJni( 3238): populateRssiValuesNative
I/bluedroid( 3238): getModelRssiValues
,E/BluetoothServiceJni( 3238): model_rssi_values_callback: low = -70, mid = -60, high = 127
,I/SELinux ( 3268): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3268):  
I/SELinux ( 3268):  
,I/SELinux ( 3268): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3268): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3268): >>>>> Normal User
,E/dalvikvm( 3268): >>>>> com.sec.android.inputmethod [ userId:0 | appId:1000 ]
,I/bluedroid( 3238): config_hci_snoop_log
,E/SELinux ( 3268): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BluetoothManagerService(  753): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/TimaKeyStoreProvider( 3268): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3268): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3268): Added TimaKesytore provider
,D/BluetoothRadioManager( 3210): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42b05dd8
,D/BluetoothRadioManager( 3210): onBluetoothServiceUp()  registerRadioClient mUUID = 80ecab0d-a6f6-40a9-8ef2-cabc3be61801
,I/bluedroid( 3238): update_radio_count
,D/BluetoothAdapterState( 3238): CURRENT_STATE=OFF, MSG = USER_TURN_ON_RADIO
I/BluetoothAdapterState( 3238): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=false
D/BluetoothAdapterState( 3238): CURRENT_STATE=PENDING, MSG = BEGIN_ENABLE_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
,I/bluedroid( 3238): enable
,I/bt_hci_bdroid( 3238): init
,I/bt_vendor( 3238): bt-vendor : init
I/bt_vendor( 3238): bt-vendor : get_bt_soc_type
E/bt_vendor( 3238): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 3238): init: Local BD Address : dc:06:b5:96:94:38
D/bt_userial_mct( 3238): userial_init
I/bt_vendor( 3238): bt-vendor : BT_VND_OP_POWER_CTRL: Off
,I/bt_hci_bdroid( 3238): bt_hc_worker_thread started
I/bt_vendor( 3238): Starting hciattach daemon
,I/bt_vendor( 3238): try to set false
,I/bt_vendor( 3238): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 3238): Starting hciattach daemon
,I/bt_vendor( 3238): try to set true
,I/qcom-bluetooth( 3283): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/SELinux ( 3289): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3289):  
I/ActivityManager(  753): Killing 2311:com.sec.android.app.msa/u0a23 (adj 15): empty #43
,I/qcom-bluetooth( 3293): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 3294): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/SELinux ( 3289): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3289):  
I/SELinux ( 3289):  
,I/SELinux ( 3289): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3289): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3289): >>>>> Normal User
,E/dalvikvm( 3289): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 3289): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/qcom-bluetooth( 3296): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/TimaKeyStoreProvider( 3289): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3289): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3289): Added TimaKesytore provider
,I/qcom-bluetooth( 3305): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3306): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3307): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,E/BluetoothManagerService(  753): Bluetooth is already disabled. DO NOT disable again.
,D/SensorService(  753):   -0.1 -0.1 9.6
,I/WifiManager( 2733): packageName : com.example.hello
I/WifiManager( 2733): setWifiEnabled : false
,I/WifiService(  753): setWifiEnabled: false pid=2733, uid=10180
,E/SMD     (  241): DCD ON
,I/jxcore-log( 2733): ****TEST TOOK:  5062  ms ****
I/jxcore-log( 2733): 
,I/jxcore-log( 2733): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2733): 
,D/RCPManagerService(  753): exchangeData() failure , invalid userId
,D/RCPManagerService(  753): exchangeData() failure , invalid userId
,D/RCPManagerService(  753): exchangeData() failure , invalid userId
,D/RCPManagerService(  753): exchangeData() failure , invalid userId
,D/BadgeProvider( 1337): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 1337): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1337): sendNotify, [notify] : null
D/BadgeProvider( 1337): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1337): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1337): update, [UpdateCount] : 1
,D/Launcher.Model( 1250): reloadBadges entered.
,W/ActivityManager(  753): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 3325): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3325):  
I/ActivityManager(  753): Killing 1188:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
,I/SELinux ( 3325): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3325):  
I/SELinux ( 3325):  
,I/SELinux ( 3325): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3325): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 3325): >>>>> Normal User
,E/dalvikvm( 3325): >>>>> com.android.exchange [ userId:0 | appId:10156 ]
,W/ActivityManager(  753): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
E/SELinux ( 3325): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/Process ( 3289): Sending signal. PID: 3289 SIG: 9
,D/TimaKeyStoreProvider( 3325): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3325): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3325): Added TimaKesytore provider
,I/ActivityManager(  753): Process com.android.email (pid 3289) (adj 9) has died.
,D/AndroidRuntime( 3311): 
D/AndroidRuntime( 3311): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/SELinux ( 3343): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3343):  
,D/AndroidRuntime( 3311): CheckJNI is OFF
,D/AndroidRuntime( 3311): setted country_code = Poland
,D/AndroidRuntime( 3311): setted countryiso_code = PL
D/AndroidRuntime( 3311): setted sales_code = XEO
D/AndroidRuntime( 3311): readGMSProperty: start
,D/AndroidRuntime( 3311): readGMSProperty: already setted!!
D/AndroidRuntime( 3311): readGMSProperty: end
,D/AndroidRuntime( 3311): addProductProperty: start
,I/SELinux ( 3349): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3349):  
,D/dalvikvm( 3311): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3311): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3311): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3311): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3311): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,I/SELinux ( 3343): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3343):  
I/SELinux ( 3343):  
,I/SELinux ( 3343): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3343): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3343): >>>>> Normal User
,E/dalvikvm( 3343): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 3343): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3343): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3343): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3343): Added TimaKesytore provider
,I/SELinux ( 3349): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3349):  
I/SELinux ( 3349):  
I/SELinux ( 3349): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3349): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 3349): >>>>> Normal User
,E/dalvikvm( 3349): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 3349): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3349): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3349): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3349): Added TimaKesytore provider
,E/memtrack( 3311): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3311): failed to load memtrack module: -2
,D/dalvikvm( 3311): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/dalvikvm(  753): GC_EXPLICIT freed 1374K, 17% free 22764K/27152K, paused 4ms+10ms, total 118ms
I/ActivityManager(  753): Killing 2331:com.sec.pcw.device/1000 (adj 15): empty #43
,I/SELinux ( 3378): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3378):  
,I/ActivityManager(  753): Killing 2362:com.vlingo.midas/u0a33 (adj 15): empty #43
D/AndroidRuntime( 3311): Calling main entry com.android.commands.pm.Pm
,D/dalvikvm(  248): GC_EXPLICIT freed 47K, 49% free 9510K/18460K, paused 1ms+3ms, total 27ms
,D/PackageManagerService(  753): deletePackageAsUser- pkg:com.example.hello, userId:0
D/PersonaManagerService(  753): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  753): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  753): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager(  753): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  753): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManagerService(  753): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  753): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  753): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  753): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService(  753): deletePackageX- pkg:com.example.hello, userId:0
D/PackageManager(  753): START PACKAGE DELETE: observer{1129729584}
D/PackageManager(  753): pkg{<packageName>}
D/PackageManager(  753): user{0}
D/PackageManager(  753): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  753): [MSG] DELETE_PACKAGE_AS_USER
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 49% free 9510K/18460K, paused 1ms+2ms, total 20ms
I/SELinux ( 3378): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3378):  
I/SELinux ( 3378):  
,I/SELinux ( 3378): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3378): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3378): >>>>> Normal User
,E/dalvikvm( 3378): >>>>> com.sec.modem.settings [ userId:0 | appId:1000 ]
,E/SELinux ( 3378): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/RCPManagerService(  753): exchangeData() failure , invalid userId
,D/dalvikvm(  248): GC_EXPLICIT freed <1K, 49% free 9510K/18460K, paused 2ms+2ms, total 20ms
,D/TimaKeyStoreProvider( 3378): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3378): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3378): Added TimaKesytore provider
,D/RCPManagerService(  753): exchangeData() failure , invalid userId
,D/RCPManagerService(  753): exchangeData() failure , invalid userId
,D/LockPatternUtils( 1067): isPcwEnable = null
D/PackageManager(  753): !@killApplicatoin: 10180, uninstall pkg
I/ActivityManager(  753): Killing 2733:com.example.hello/u0a180 (adj 0): stop com.example.hello
W/ActivityManager(  753): Force removing ActivityRecord{4351f128 u0 com.example.hello/.MainActivity t3}: app died, no saved state
I/SQLiteSecureOpenHelper( 2040): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2040): getDatabaseLocked(b,b,pwd)...
D/CustomFrequencyManagerService(  753): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 753  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  753): mDVFSHelper.acquire()
,I/SurfaceFlinger(  247): id=16 Removed NainActivit (7/10)
,I/SurfaceFlinger(  247): id=16 Removed NainActivit (-2/10)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,I/WindowState(  753): WIN DEATH: Window{4345f1c8 u0 com.example.hello/com.example.hello.MainActivity}
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  247): id=16 Removed NainActivit (-2/10)
,W/PackageSettings(  753): Skipping PackageSetting{42ccea38 com.test.thalitest/10179} due to missing metadata
,D/PackageManager(  753): setPackageStoppedState - Execution time: 120 ms
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/PackageManager(  753): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10180, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetView( 1250): destroyHardwareResources():1130995960
,D/BadgeProvider( 1337): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1250): onRestart, Launcher: 1119061960
D/Launcher( 1250): onStart, Launcher: 1119061960
,D/Launcher.HomeView( 1250): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1446): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1446): [237392/5] SurfaceWidget drawing first frame
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/RCPManagerService(  753): exchangeData() failure , invalid userId
,I/SurfaceFlinger(  247): id=17 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/PackageManager(  753): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10180, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,W/ActivityManager(  753): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/SurfaceFlinger(  247): id=18 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/BadgeProvider( 1337): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1337): sendNotify, [notify] : null
D/BadgeProvider( 1337): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1337): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1337): update, [UpdateCount] : 1
,I/FPMS_FingerprintManagerService( 1086): onReceive: android.intent.action.PACKAGE_REMOVED
,D/AdaptiveEventManager( 1067): action=android.intent.action.PACKAGE_REMOVED
,D/QuickConnect[1.1][2] ( 3210): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.example.hello
,D/dalvikvm( 1413): GC_EXPLICIT freed 4144K, 46% free 9988K/18460K, paused 3ms+6ms, total 56ms
,I/PackageManager(  753):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  753):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  753):   Scheme: "sms"
I/PackageManager(  753): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/Launcher.Model( 1250): reloadBadges entered.
,I/PackageManager(  753):   Action: "android.intent.action.SENDTO"
I/PackageManager(  753):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  753):   Scheme: "smsto"
,I/InputReader(  753): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1218): Ignoring removeGeofence because network location is disabled.
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/PackageManager(  753): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 3406): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3406):  
I/ActivityManager(  753): Killing 2465:com.sec.android.app.shealth/u0a35 (adj 15): empty #43
I/PackageManager(  753):   Action: "android.intent.action.SENDTO"
I/PackageManager(  753):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  753):   Scheme: "mms"
,I/Process ( 3325): Sending signal. PID: 3325 SIG: 9
D/CustomFrequencyManagerService(  753): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 753  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  753): mDVFSHelper.release()
I/PackageManager(  753): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/CustomFrequencyManagerService(  753): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 753  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/PackageManager(  753):   Action: "android.intent.action.SENDTO"
I/PackageManager(  753):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  753):   Scheme: "mmsto"
I/PackageManager(  753): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3406): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3406):  
I/SELinux ( 3406):  
,I/SELinux ( 3406): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3406): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3406): >>>>> Normal User
,E/dalvikvm( 3406): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 3406): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3406): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3406): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3406): Added TimaKesytore provider
,I/ActivityManager(  753): Process com.android.exchange (pid 3325) (adj 11) has died.
D/RCPManagerService(  753): PackageReceiver onReceive()
,I/HarmonyEASService(  753): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PackageManager(  753):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  753):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  753):   Scheme: "sms"
I/PackageManager(  753): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  753):   Action: "android.intent.action.SENDTO"
I/PackageManager(  753):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  753):   Scheme: "smsto"
,I/PackageManager(  753): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  753): Package has changed for user 0
D/EnterpriseDeviceManagerService(  753): Admin package name: com.google.android.gms
,D/dalvikvm(  753): GC_EXPLICIT freed 1776K, 17% free 22806K/27152K, paused 7ms+16ms, total 288ms
I/PackageManager(  753):   Action: "android.intent.action.SENDTO"
I/PackageManager(  753):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  753):   Scheme: "mms"
D/PackageManager(  753): delete sourFile : 
I/PackageManager(  753): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/PackageManager(  753): delete native library directory: 
,D/PackageManager(  753): return delete result to caller: 1129729584
,D/AndroidRuntime( 3311): Shutting down VM
,D/dalvikvm( 3311): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
D/PackageManager(  753): returnCode: 1
,I/PackageManager(  753):   Action: "android.intent.action.SENDTO"
I/PackageManager(  753):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  753):   Scheme: "mmsto"
I/PackageManager(  753): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager(  753):   Action: "android.intent.action.SENDTO"
I/PackageManager(  753):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  753):   Scheme: "sms"
I/PackageManager(  753): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  753): Permission Denial: getCurrentUser() from pid=3406, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  753):   Action: "android.intent.action.SENDTO"
I/PackageManager(  753):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  753):   Scheme: "smsto"
I/PackageManager(  753): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  753):   Action: "android.intent.action.SENDTO"
I/PackageManager(  753):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  753):   Scheme: "mms"
I/PackageManager(  753): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager(  753):   Action: "android.intent.action.SENDTO"
I/PackageManager(  753):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  753):   Scheme: "mmsto"
I/PackageManager(  753): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/BackupManagerService(  753): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/BackupManagerService(  753): removePackageParticipantsLocked: uid=10180 #1
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/qcom-bluetooth( 3421): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 38:94:96:b5:06:dc 
,I/qcom-bluetooth( 3422): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/bt_vendor( 3238): bluetooth satus is on
D/bt_userial_mct( 3238): userial_open(port:0)
I/bt_vendor( 3238): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/GKI_LINUX( 3238): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/bt_vendor( 3238): Done intiailizing UART
I/bt_vendor( 3238): Done intiailizing UART
,I/bt_userial_mct( 3238): CMD=61, EVT=61, ACL_Out=62, ACL_In=62
I/bt_vendor( 3238): Bluetooth Firmware and transport layer are initialized
,D/bt_userial_mct( 3238): Entering userial_read_thread()
,D/GKI_LINUX( 3238): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
I/        ( 3238): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3238): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3238): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3238): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3238): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3238): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3238): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3238): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3238): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3238): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3238): BTE_InitTraceLevels -- TRC_SAP
I/        ( 3238): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3238): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3238): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3238): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3238): BTE_InitTraceLevels -- TRC_BTIF
,I/        ( 3238): BTE_InitTraceLevels -- TRC_PROTOCOL
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NotiRemoteService( 3406): action com.peel.widget.notification.SETUP_SERVICE_CONNECTION
,D/NotiRemoteService( 3406): connectToPeelService 0
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  753): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ContextImpl( 3406): Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:529 tv.peel.samsung.widget.a.c.<init>:-1 tv.peel.samsung.widget.NotiRemoteService.a:-1 
,E/SQLiteDatabase( 3406): Failed to open database '/data/data/tv.peel.smartremote/databases/peel'.
E/SQLiteDatabase( 3406): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3406): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3406): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3406): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3406): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3406): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3406): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3406): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3406): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3406): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3406): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3406): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3406): 	at com.peel.c.s.a(Unknown Source)
E/SQLiteDatabase( 3406): 	at com.peel.data.v.a(Unknown Source)
E/SQLiteDatabase( 3406): 	at com.peel.control.ba.run(Unknown Source)
E/SQLiteDatabase( 3406): 	at com.peel.util.l.run(Unknown Source)
E/SQLiteDatabase( 3406): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 3406): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3406): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3406): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 3433): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3433):  
,I/CrashAnrDetector(  753): onPackageRemoved : com.example.hello
D/NotiRemoteService( 3406): onServiceOn() mServiceState = 1
,D/NotiRemoteService( 3406): Send action to self com.peel.widget.notification.SERVICE_BINDED
,D/NotiRemoteService( 3406): action com.peel.widget.notification.SERVICE_BINDED
D/NotiRemoteService( 3406): feature is Off. Stop service
,D/NotiRemoteService( 3406): Send action to self com.peel.widget.notification.STOP_PROCESS
,D/UsbSettingsManager(  753): clearDefaults: com.example.hello
D/NotiRemoteService( 3406): action com.peel.widget.notification.STOP_PROCESS
E/bt-btm  ( 3238): BTM_SecRegister:p_cb_info->p_le_callback == 0x77e87ca1 
E/bt-btm  ( 3238): BTM_SecRegister: btm_cb.api.p_le_callback = 0x77e87ca1 
D/NotiRemoteService( 3406): onDestroy()
W/AtomicFile(  753): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,D/NotiRemoteService( 3406): mOrientationChangeReceier was not registered
W/AppWidgetServiceImpl(  753): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/bt-btif ( 3238): btif_storage_get_adapter_property service_mask:0x0
E/BluetoothServiceJni( 3238): populateRssiValuesNative
I/bluedroid( 3238): getModelRssiValues
,E/BluetoothServiceJni( 3238): model_rssi_values_callback: low = -70, mid = -60, high = 127
,E/BluetoothAdapterProperties( 3238): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3238): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3238): 	at dalvik.system.NativeStart.run(Native Method)
,E/BluetoothAdapterProperties( 3238): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3238): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3238): 	at dalvik.system.NativeStart.run(Native Method)
,E/BluetoothAdapterProperties( 3238): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3238): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 3238): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3238): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 3238): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3238): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 3238): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3238): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 3238): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 3238): java.lang.NullPointerException
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3238): java.lang.NullPointerException
E/BluetoothServiceJni( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3238): java.lang.NullPointerException
E/BluetoothServiceJni( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3238): java.lang.NullPointerException
E/BluetoothServiceJni( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3238): java.lang.NullPointerException
E/BluetoothServiceJni( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3238): java.lang.NullPointerException
E/BluetoothServiceJni( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3238): java.lang.NullPointerException
E/BluetoothServiceJni( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 3238): java.lang.NullPointerException
E/BluetoothServiceJni( 3238): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 3238): 	at dalvik.system.NativeStart.run(Native Method)
E/bt-btif ( 3238): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 3238): btif_sock_init, radio_req:1, rfc_init:0, vhci_init:0
E/bt-btif ( 3238): btif_sock_init: !vhci_init
D/BluetoothAdapterState( 3238): CURRENT_STATE=PENDING, MSG = ENABLED_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
D/BluetoothAdapterService(1118470144)( 3238): startQuietModeServices:bStart =true QModeRCnt=1
D/BluetoothBondStateMachine( 3238): make
W/BluetoothAdapterService( 3238): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(1118470144)( 3238): startQuietModeServices:Starting  com.android.bluetooth.gatt.GattService
D/BluetoothSecureManager( 3238): getInstant: null
E/bt_mct  ( 3238): hci lib postload completed
D/BluetoothSecureManager( 3238): calling getMethod for getService
D/BluetoothSecureManager( 3238): calling getService
D/BluetoothSecureManager( 3238): getService return binder: android.os.BinderProxy@42ae3e00
I/BluetoothBondStateMachine( 3238): StableState(): Entering Off State
I/SELinux ( 3433): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3433):  
I/SELinux ( 3433):  
I/SELinux ( 3433): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/BluetoothSecureManagerService(  753): isSecureModeEnabled
D/BluetoothSecureManagerService(  753): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 3238): isSecureModeOn:false
D/BluetoothAdapterService( 3238): setProfileState(): setting profile com.android.bluetooth.gatt.GattService to state = 10
W/BluetoothAdapterService( 3238): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 3238): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3238): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
I/BtGatt.JNI( 3238): classInitNative(L703): classInitNative: Success!
W/BluetoothAdapterService( 3238): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 3238): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 3238): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
I/BluetoothAdapterState( 3238): Bluetooth adapter radio state changed: 14
D/BluetoothAdapterService( 3238): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3238): updateAdapterState state is 14
D/BluetoothAdapterService( 3238): Broadcasting updateAdapterState() to 1 receivers.
D/BtGatt.GattService( 3238): BluetoothAdapter state is = 10
D/BluetoothManagerService(  753): Broadcasting Radio() to 1 Radio Mgr receivers.
D/BluetoothAdapterService( 3238): Autoconnection is available 
D/BluetoothAdapterService( 3238): updateAdapterState prevState = 10newState = 14
I/BluetoothAdapterState( 3238): Entering OffState
D/BtGatt.DebugUtils( 3238): handleDebugAction() action=null
D/BluetoothRadioManager( 3210): onBTRadioStateChange:  up = true
D/BtGatt.GattService( 3238): Received start request. Starting profile...
D/BtGatt.GattService( 3238): start()
,I/bluedroid( 3238): get_profile_interface gatt
I/BluetoothManagerService(  753): enableGatt, doBind called
D/BluetoothManagerService(  753): Broadcasting onBluetoothServiceUp() to 1 receivers.
D/BluetoothRadioManager( 3210): onGattServiceStateChange: up = truemBleCount = 1
E/QuickConnect[1.1][2] ( 3210): BleHelper.onGattServiceStateChange - up = true, BluetoothGatt is android.bluetooth.IBluetoothGatt$Stub$Proxy@42b07498
E/QuickConnect[1.1][2] ( 3210): BleHelper.onGattServiceStateChange - Radio turned on
,V/AlarmManager(  753): waitForAlarm result :4
,V/AlarmManager(  753): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  753): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  753): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  753): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  753): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  753): mCoverManager.getCoverState() : true
,D/InputReader(  753): Processing first event
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/qdoverlay(  247): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  247): MdpCtrl failed to setOverlay
E/qdoverlay(  247): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  247): src msmfb_img w=1312 h=1280 format=15 MDP_RGBX_8888
E/qdoverlay(  247): Ctrl commit failed set overlay
E/qdhwcomposer(  247): configureNonSplit: commit failed for low res panel
E/qdoverlay(  247): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  247): MdpCtrl failed to setOverlay
E/qdoverlay(  247): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  247): src msmfb_img w=736 h=1280 format=13 MDP_RGBA_8888
E/qdoverlay(  247): Ctrl commit failed set overlay
E/qdhwcomposer(  247): configure: configMdp failed for dpy 0
E/qdoverlay(  247): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  247): MdpCtrl failed to setOverlay
E/qdoverlay(  247): == Bad OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  247): src msmfb_img w=736 h=1280 format=13 MDP_RGBA_8888
E/qdoverlay(  247): Ctrl commit failed set overlay
E/qdhwcomposer(  247): configure: configMdp failed for dpy 0
E/qdoverlay(  247): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  247): MdpCtrl failed to setOverlay
E/qdoverlay(  247): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  247): src msmfb_img w=736 h=1280 format=13 MDP_RGBA_8888
E/qdoverlay(  247): Ctrl commit failed set overlay
E/qdhwcomposer(  247): configure: configMdp failed for dpy 0
E/qdoverlay(  247): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  247): MdpCtrl close error in unset
E/qdoverlay(  247): GenericPipe failed to close ctrl
E/qdoverlay(  247): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  247): MdpCtrl close error in unset
E/qdoverlay(  247): GenericPipe failed to close ctrl
E/qdoverlay(  247): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  247): MdpCtrl close error in unset
,E/qdoverlay(  247): GenericPipe failed to close ctrl
E/qdhwcomposer(  247): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  247): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=4
E/qdoverlay(  247): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  247): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&, bool): commit failed
E/qdhwcomposer(  247): hwc_set_primary: display commit fail for 0 dpy!
E/qdhwcomposer(  247): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : No such device
,E/SurfaceFlinger(  247): eventControl(0, 1) failed No such device
D/STATUSBAR-IconMerger( 1067): checkOverflow(384), More:false, Req:false Child:2
,E/qdoverlay(  247): Cant open device /dev/graphics/fb0 err=1
E/qdoverlay(  247): Ctrl failed to init fbnum=0
E/qdoverlay(  247): Ctrl failed to init dpy=0
E/qdoverlay(  247): GenericPipe failed to init ctrl
E/qdoverlay(  247): Cant open device /dev/graphics/fb0 err=1
E/qdoverlay(  247): Ctrl failed to init fbnum=0
E/qdoverlay(  247): Ctrl failed to init dpy=0
E/qdoverlay(  247): GenericPipe failed to init ctrl
E/qdoverlay(  247): Cant open device /dev/graphics/fb0 err=1
E/qdoverlay(  247): Ctrl failed to init fbnum=0
E/qdoverlay(  247): Ctrl failed to init dpy=0
E/qdoverlay(  247): GenericPipe failed to init ctrl
E/qdoverlay(  247): Failed to call ioctl MSMFB_OVERLAY_SET err=Bad file number
E/qdoverlay(  247): MdpCtrl failed to setOverlay
E/qdoverlay(  247): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=-1
E/qdoverlay(  247): src msmfb_img w=1312 h=1280 format=15 MDP_RGBX_8888
E/qdoverlay(  247): Ctrl commit failed set overlay
E/qdhwcomposer(  247): configureNonSplit: commit failed for low res panel
E/qdoverlay(  247): Failed to call ioctl MSMFB_OVERLAY_SET err=Bad file number
E/qdoverlay(  247): MdpCtrl failed to setOverlay
E/qdoverlay(  247): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=-1
E/qdoverlay(  247): src msmfb_img w=736 h=1280 format=13 MDP_RGBA_8888
E/qdoverlay(  247): Ctrl commit failed set overlay
E/qdhwcomposer(  247): configure: configMdp failed for dpy 0
E/qdoverlay(  247): Failed to call ioctl MSMFB_OVERLAY_SET err=Bad file number
E/qdoverlay(  247): MdpCtrl failed to setOverlay
E/qdoverlay(  247): == Bad OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x20000 id=-1
E/qdoverlay(  247): src msmfb_img w=736 h=1280 format=13 MDP_RGBA_8888
E/qdoverlay(  247): Ctrl commit failed set overlay
E/qdhwcomposer(  247): configure: configMdp failed for dpy 0
E/qdoverlay(  247): Failed to call ioctl MSMFB_OVERLAY_SET err=Bad file number
E/qdoverlay(  247): MdpCtrl failed to setOverlay
E/qdoverlay(  247): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=-1
E/qdoverlay(  247): src msmfb_img w=736 h=1280 format=13 MDP_RGBA_8888
E/qdoverlay(  247): Ctrl commit failed set overlay
,E/qdhwcomposer(  247): configure: configMdp failed for dpy 0
E/qdhwcomposer(  247): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  247): hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=4
E/qdoverlay(  247): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  247): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&, bool): commit failed
,E/qdhwcomposer(  247): hwc_set_primary: display commit fail for 0 dpy!
,I/QuickConnect[1.1][2] ( 3210): BleAdvertiser.BleAdvertiser - Constructor
,D/BluetoothGattServer( 3210): registerCallback()
,D/BluetoothGattServer( 3210): registerCallback() - UUID=197f0a58-a107-47a2-b6c1-34769dcad6f9
,W/ApplicationsProvider( 1413): Could not fetch usage stats
W/ApplicationsProvider( 1413): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1413): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1413): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1413): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1413): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1413): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1413): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1413): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/BtGatt.GattService( 3238): registerServer() - UUID=197f0a58-a107-47a2-b6c1-34769dcad6f9
,D/BtGatt.btif( 3238): btif_gatts_register_app
D/BtGatt.btif( 3238): btgatts_handle_event: Event 2000
E/bt-btif ( 3238): register application first_unuse rcb_idx = 0
D/BtGatt.btif( 3238): btapp_gatts_handle_cback: Event 0
,D/BtGatt.GattService( 3238): onServerRegistered() - UUID=197f0a58-a107-47a2-b6c1-34769dcad6f9, serverIf=4
,D/BluetoothGattServer( 3210): onServerRegistered() - status=0 serverIf=4
V/QuickConnect[1.1][2] ( 3210): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 3210): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 3210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a9d150
V/QuickConnect[1.1][2] ( 3210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a9d150
V/QuickConnect[1.1][2] ( 3210): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 3210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a9d150
,V/QuickConnect[1.1][2] ( 3210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a9d150
V/QuickConnect[1.1][2] ( 3210): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42a9d150
D/QuickConnect[1.1][2] ( 3210): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 3210): BleHelper.startScan - bluetoothActionState = 0
,D/QuickConnect[1.1][2] ( 3210): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 3210): BleHelper.startScan - shouldScanBleFg = false

```
