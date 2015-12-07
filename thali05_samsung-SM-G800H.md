#### Test 50242285e707819_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=2638, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,D/MediaScannerReceiver( 1205): action: android.intent.action.BOOT_COMPLETED
--------- beginning of /dev/log/main
I/ServiceManager(  289): Waiting for service AtCmdFwd...
E/SMD     (  240): DCD ON
D/MediaScannerService( 1205): !@start scanning volume internal: [/system/media]
D/TP/MmsProvider( 1238): Update uri=content://mms, match=0
D/TP/MmsProvider( 1238): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1238): need read changed broadcast:false
I/Mms:transaction( 1721): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 1721): [start]    nonBlockingUpdateMessageIndicator()
I/Mms/ReservationManager( 1721): resetAfterConnected()
D/TP/MmsSmsProvider( 1238): match 7:Elapsed time : 2.237 ms
D/Mms/MessagingNotification( 1721): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1721): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1721): isDefault true
I/Mms/ReservationManager( 1721): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1238): match 200:Elapsed time : 1.282 ms
I/SELinux ( 2672): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2672):  
D/Mms/TelephonyPermission( 1721): isDefault true
D/Mms/SmsReceiverService( 1721): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 1721): [start]    handleBootCompleted()
D/MediaScanner( 1205): Prescan. DB items number : 156 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/TP/MmsSmsProvider( 1238): deleteConversation threadId: 9223372036854775806
I/SELinux ( 2672): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2672):  
I/SELinux ( 2672):  
I/SELinux ( 2672): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2672): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2672): >>>>> Normal User
E/dalvikvm( 2672): >>>>> com.sec.android.app.safetyassurance [ userId:0 | appId:10050 ]
E/SELinux ( 2672): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TP/MmsSmsProvider( 1238): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
D/BadgeProvider( 1345): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/TimaKeyStoreProvider( 2672): in addTimaSignatureService
D/TP/MmsSmsProvider( 1238): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1238): need read changed broadcast:false
D/TimaKeyStoreProvider( 2672): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2672): Added TimaKesytore provider
D/Mms/Conversation( 1721): deleteTempConversation(),deleted=0
D/SmsProvider( 1238): Update uri=content://sms/outbox, match=8
D/BadgeProvider( 1345): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1345): sendNotify, [notify] : null
D/BadgeProvider( 1345): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1345): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1345): update, [UpdateCount] : 1
D/Launcher.Model( 1250): reloadBadges entered.
D/Mms/MessagingNotification( 1721): setBadgeCount(), count=0
D/MessagingNotification( 1721): remove alarm
D/TP/MmsSmsProvider( 1238): need read changed broadcast:false
D/Mms/SmsReceiverService( 1721): sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 1721): [SIM-1]sendFirstQueuedMessage()
D/Mms/MessagingNotification( 1721): [end]    nonBlockingUpdateMessageIndicator()
D/Mms/MessagingNotification( 1721): updateAllHistoryAsRead()
W/dalvikvm( 2672): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
D/Mms/MessagingNotification( 1721): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1721): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1721): isDefault true
D/SafetyAssuranceAppFeatures( 2672): init start
I/SafetyAssuranceAppFeatures( 2672): mLoadBaiduMap:false
I/SafetyAssuranceAppFeatures( 2672): mFeatureEnableMultiSim true
D/SafetyAssuranceAppFeatures( 2672): init end
D/SafetyAssuranceReceiver( 2672): onReceive
I/SafetyAssuranceApp( 2672): Acquire WL
D/SafetyAssuranceConfig( 2672): getAppState : 1
D/SafetyAssuranceReceiver( 2672): onReceive - action:android.intent.action.BOOT_COMPLETED, currentAppState:1
D/SafetyAssuranceReceiver( 2672): Init App state
D/TP/MmsSmsProvider( 1238): match 200:Elapsed time : 3.912 ms
V/MediaScanner( 1205): processDirectory :  /system/media
D/SafetyAssuranceConfig( 2672): setAppState : 1
D/SafetyAssuranceApp( 2672): topActivity's name is=.BatteryCover
I/SafetyAssuranceApp( 2672): Release WL
W/BackupManagerService(  739): dataChanged but no participant pkg='com.android.providers.settings' uid=10050
D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
D/AndroidRuntime( 2667): 
D/AndroidRuntime( 2667): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2667): CheckJNI is OFF
D/AndroidRuntime( 2667): setted country_code = Poland
I/NetworkStatusReceiver( 1238): action: android.intent.action.BOOT_COMPLETED
D/AndroidRuntime( 2667): setted countryiso_code = PL
D/AndroidRuntime( 2667): setted sales_code = XEO
D/AndroidRuntime( 2667): readGMSProperty: start
D/AndroidRuntime( 2667): readGMSProperty: already setted!!
D/AndroidRuntime( 2667): readGMSProperty: end
D/AndroidRuntime( 2667): addProductProperty: start
D/dalvikvm( 2667): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2667): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2667): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2667): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2667): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/NearbySettings( 1304): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1304): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1304): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
I/NearbySettings( 1304): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1304): MountReceiver.onReceive - Internal Path
I/AccessibilityManagerService(  739): setmDNIeNegative (false)
D/BadgeProvider( 1345): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/BadgeProvider( 1345): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1345): sendNotify, [notify] : null
D/Launcher.Model( 1250): reloadBadges entered.
D/BadgeProvider( 1345): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1345): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1345): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 1721): setBadgeCount(), count=0
D/MessagingNotification( 1721): remove alarm
D/Mms/MessagingNotification( 1721): updateAllHistoryAsRead()
D/Mms/SmsReceiverService( 1721): [end]    handleBootCompleted()
V/MediaScanner( 1205):  prescan time: 239ms (DB items: 156)
V/MediaScanner( 1205):     scan time: 130ms (Caching mode: true), (makeEntry time: 63ms ~48%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1205): postscan time: 1ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1205):    total time: 370ms
V/MediaScanner( 1205): checked files: 149  directories : 5  (I: 0, U: 0)
D/MediaScanner( 1205): checkDefaultSounds
D/MediaScanner( 1205): system alarm_alert  : Vwiurug_etwofi5wgg
D/MediaScanner( 1205): OK. alarm_alert is already exist in setting DB.
D/MediaScanner( 1205): system notification_sound  : K_Oprkltf5wgg
D/MediaScanner( 1205): OK. notification_sound is already exist in setting DB.
D/MediaScanner( 1205): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1205): OK. ringtone is already exist in setting DB.
D/MediaScanner( 1205): system ringtone_2  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1205): OK. ringtone_2 is already exist in setting DB.
D/MediaScanner( 1205): system notification_sound_2  : K_Oprkltf5wgg
D/MediaScanner( 1205): OK. notification_sound_2 is already exist in setting DB.
D/MediaScannerService( 1205): !@done scanning volume internal
D/MediaScannerService( 1205): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
D/MediaProvider( 1205): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1205): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/MediaProvider( 1205): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/MediaProvider( 1205): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1205): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1205): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1205): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1205): savePlaylistTableInBulkDeleter finished
D/MediaScanner( 1205): Prescan. DB items number : 20 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
E/memtrack( 2667): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 2667): failed to load memtrack module: -2
D/dalvikvm( 2667): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/iu.UploadsManager( 1638): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
V/MediaScanner( 1205): processDirectory :  /storage/emulated/0
D/MediaScanner( 1205): Skipping:
D/MediaScanner( 1205): 7klwibgf7fvntblfd7(75ebcf7
D/MediaScanner( 1205): Skipping:
D/MediaScanner( 1205): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
V/MediaScanner( 1205): processDirectory :  /storage/extSdCard
W/MediaScanner( 1205): Error opening directory, reason : Permission denied.
W/MediaScanner( 1205): 7klwibgf7fxlKdCbid7
E/File    ( 1205): fail readDirectory() errno=2
V/MediaScanner( 1205): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@42625108
V/MediaScanner( 1205): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@42625108
V/MediaScanner( 1205):  prescan time: 49ms (DB items: 20)
V/MediaScanner( 1205):     scan time: 40ms (Caching mode: true), (makeEntry time: 29ms ~72%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1205): postscan time: 10ms (bulkDeleter : 0), (delete DeadThumbnail time : 5ms)
V/MediaScanner( 1205):    total time: 99ms
V/MediaScanner( 1205): checked files: 3  directories : 17  (I: 0, U: 0)
D/AndroidRuntime( 2667): Calling main entry com.android.commands.am.Am
D/MediaScannerService( 1205): !@done scanning volume external
V/ApplicationPolicy(  739): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/Settings( 1304): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/CustomFrequencyManagerService(  739): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 739  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  739): mDVFSHelper.acquire()
D/MediaScannerService( 1205): send command to ssrm : REQ_DROP_CACHE
I/SurfaceFlinger(  246): id=14 createSurf (1x1),1 flag=404, iello
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/dalvikvm(  739): GC_EXPLICIT freed 2717K, 18% free 22588K/27396K, paused 6ms+11ms, total 147ms
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
W/Atfwd_Sendcmd(  289): AtCmdFwd service not published, waiting... retryCnt : 3
I/WindowManager(  739): Screenshot max retries 4 of Token{42d359d8 ActivityRecord{42265848 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42df6470 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
W/WindowManager(  739): Screenshot failure taking screenshot for (720x1280) to layer 21005
D/LockPatternUtils( 1066): isPcwEnable = null
D/AndroidRuntime( 2667): Shutting down VM
D/dalvikvm( 2667): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.ssrm.u.i:-1 com.android.server.ssrm.ai.run:-1 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 
D/PowerManagerService(  739): [s] UserActivityState : 1 -> 0
I/PowerManagerService(  739): [PWL] On : 0 (39025 ms ago)
I/PowerManagerService(  739): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  739): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1066, ws=null) (elapsedTime=1520)
I/SELinux ( 2708): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2708):  
D/DisplayPowerController(  739): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  (  739): lcd : 6 +
I/iu.UploadsManager( 1638): End new media; added: 0, uploading: 0, time: 505 ms
D/PowerManagerService(  739): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/lights  (  739): lcd : 6 -
D/lights  (  739): lcd : 2 +
D/RampAnimator(  739): Light Animator Finished currentValue=2
D/lights  (  739): lcd : 2 -
I/SettingSearch/SearchIntentReceiver( 1304): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1304): search setting db init!!
I/SettingSearch/SearchIntentReceiver( 1304): BOOT_COMPLETED call InitSerachDBThread thread start!
I/SELinux ( 2708): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2708):  
I/SELinux ( 2708):  
I/SELinux ( 2708): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2708): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2708): >>>>> Normal User
E/dalvikvm( 2708): >>>>> com.example.hello [ userId:0 | appId:10180 ]
E/SELinux ( 2708): [DEBUG] seapp_context_lookup: seinfoCategory = default
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:40 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:60 
D/TimaKeyStoreProvider( 2708): in addTimaSignatureService
D/SSRMv2:SIOP(  739): SIOP:: AP = 320, Delta = 10
D/TimaKeyStoreProvider( 2708): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2708): Added TimaKesytore provider
I/SELinux ( 2722): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2722):  
D/PhoneNumberLocatorBootCompletedReceiver( 1238): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 1238): Phone number locator feature is dsiabled
D/Launcher.HomeView( 1250): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1476): [237392/5] Surface widget pause on instance = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1476): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 1476): [KK AccuPhone]>>> SWW:224 [0:0] [SWW] onPause : instance = 1
D/accuweather( 1476): [KK AccuPhone]>>> SWW:239 [0:0] onPause : size = 0
D/accuweather( 1476): [KK AccuPhone]>>> SWW:517 [0:0]  unRegisterTTReceiver !! 
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/LockPatternUtils( 1066): isPcwEnable = null
W/BackupManagerService(  739): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
I/SELinux ( 2722): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2722):  
I/SELinux ( 2722):  
I/SELinux ( 2722): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2722): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2722): >>>>> Normal User
,E/dalvikvm( 2722): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10160 ]
D/accuweather( 1476): [KK AccuPhone]>>> WR:149 [0:0] onPause
D/accuweather( 1476): [KK AccuPhone]>>> SM:526 [0:0] onPause
E/SELinux ( 2722): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
D/SurfaceWidgetView( 1250): destroyHardwareResources():1125418360
I/BootupListener( 1238): mPendingNetworkManualSelection : false
I/ManualSelectionReceiver( 1238): onReceive : Intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.phone/.ManualSelectionReceiver (has extras) }
D/TimaKeyStoreProvider( 2722): in addTimaSignatureService
D/TimaKeyStoreProvider( 2722): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2722): Added TimaKesytore provider
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=2708, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 2735): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2735):  
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/Launcher( 1250): onTrimMemory. Level: 20
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=2708, uid=10180 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 2708): Binding Chromium to the background looper Looper (main, tid 1) {4221e300}
I/chromium( 2708): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/SELinux ( 2735): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2735):  
I/SELinux ( 2735):  
I/SELinux ( 2735): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2735): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2735): >>>>> Normal User
E/dalvikvm( 2735): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
I/BrowserProcessMain( 2708): Initializing chromium process, renderers=0
E/SELinux ( 2735): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/chromium( 2708): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/TimaKeyStoreProvider( 2735): in addTimaSignatureService
I/Adreno-EGL( 2708): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2708): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2708): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2708): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2708): Remote Branch: 
I/Adreno-EGL( 2708): Local Patches: 
I/Adreno-EGL( 2708): Reconstruct Branch: 
D/TimaKeyStoreProvider( 2735): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2735): Added TimaKesytore provider
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=2722, uid=10160 requires android.permission.INTERACT_ACROSS_USERS
I/DBG_DM  ( 2735): [][Line:95][onCreate] 
I/dalvikvm( 2708): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2708): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2708): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2708): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2708): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2708): VFY: replacing opcode 0x6e at 0x0008
E/DBG_DM  ( 2735): BootingfileStream is null
E/DBG_DM  ( 2735): xdmCreateBootingFilestream
W/dalvikvm( 2708): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2708): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2708): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2708): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2708): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2708): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2708): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2708): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2708): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2708): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2708): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2708): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2708): CordovaWebView is running on device made by: samsung
I/DBG_DM  ( 2735): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
I/DBG_DM  ( 2735): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
I/DBG_DM  ( 2735): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
I/DBG_DM  ( 2735): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
I/DBG_DM  ( 2735): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
I/DBG_DM  ( 2735): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
I/DBG_DM  ( 2735): [3.19.140541][Line:36][onCreate] myUserId : 0
I/DBG_DM  ( 2735): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 0
I/DBG_DM  ( 2735): [3.19.140541][Line:2702][xdmdbsqlGetDownloadPostponeStatus] xdbsqlGetDownloadPostponeStatus : 0
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  246): id=15 createSurf (720x1280),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 2708): EGLImpl-HWUI Protected EGL context created
I/DBG_DM  ( 2735): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
I/DBG_DM  ( 2735): [3.19.140541][Line:99][onCreate] DMApplication NOT Start !
I/DBG_DM  ( 2735): [3.19.140541][Line:139][onReceive] android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1066): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1066): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1066): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1066): isSafeMode = false
D/OpenGLRenderer( 2708): Enabling debug mode 0
W/AwContents( 2708): nativeOnDraw failed; clearing to background color.
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  246): id=13 Removed CatteryCove (8/13)
D/CustomFrequencyManagerService(  739): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 739  tag : ACTIVITY_RESUME_BOOSTER@5
I/SurfaceFlinger(  246): id=13 Removed CatteryCove (-2/13)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  246): id=14 Removed iello (9/12)
I/SurfaceFlinger(  246): id=14 Removed iello (-2/12)
W/ActivityManager(  739): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  246): id=7 Removed Mauncher (7/11)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1250): destroyHardwareResources():1125418360
D/CustomFrequencyManagerService(  739): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 739  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
E/Tethering(  739): No numeric data
E/Tethering(  739): No numeric data
E/Tethering(  739): No numeric data
E/Tethering(  739): No numeric data
E/Tethering(  739): No numeric data
E/Tethering(  739): No numeric data
I/ConnectivityService(  739): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  739): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  739): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  739): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  739): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  739): defaultVal : 1, tetherEnabledInSettings : true
D/LocationManagerService(  739): getProviders()=[passive]
E/Tethering(  739): No numeric data
E/Tethering(  739): No numeric data
E/Tethering(  739): No numeric data
E/Tethering(  739): No numeric data
V/NFC     ( 1304): this device does not have NFC support
V/NFC     ( 1304): this device does not have NFC support
V/NFC     ( 1304): this device does not have NFC support
I/ConnectivityService(  739): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  739): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  739): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  739): defaultVal : 1, tetherEnabledInSettings : true
V/NFC     ( 1304): this device does not have NFC support
I/ContactAccountLoggerTas( 2109): canRun() : Opted Out
I/Velvet.VelvetFactory( 2109): checking for language pack updates
V/VibratorService(  739): hasVibrator - useVibetonz: false
D/SensorService(  739):   -0.0 -0.1 9.5
I/chromium( 2708): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 2708): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 2708): Set native->JS mode to OnlineEventsBridgeMode
I/Search.RefreshSearchDomainAndCookiesTask( 2109): refreshing search domain
W/GAV2    ( 2109): Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/WebViewChromium( 2109): Binding Chromium to the main looper Looper (main, tid 1) {4221d978}
W/dalvikvm( 2109): method Lcom/google/android/search/core/state/QueryState;.a incorrectly overrides package-private method with same name in Lcfl;
W/GAV2    ( 2109): Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/Search.GservicesUpdateTask( 2109): Updating Gservices keys
I/HarmonyEASService(  739): Updating for all 1
I/chromium( 2708): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/ContactAccountLoggerTas( 2109): canRun() : Opted Out
I/LockPatternUtils( 1304): isSmartCardAuthenticationAvailable: false
D/dalvikvm( 2708): Trying to load lib /data/app-lib/com.example.hello-5/libjxcore.so 0x42544fa0
D/WifiDisplayAdapter(  739): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter(  739): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/AudioService(  739): getStreamVolume 3 index 0
I/MediaRouter( 2109): Found default route: MediaRouter.RouteInfo{ uniqueId=android/kb:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
I/ActivityManager(  739): Waited long enough for: ServiceRecord{42f1c550 u0 com.google.android.gms/.gcm.GcmService}
I/chromium( 2708): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
E/libGLESv2( 2708): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
E/libGLESv2( 2708): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
D/LockPatternUtils( 1066): isPcwEnable = null
I/ContactAccountLoggerTas( 2109): canRun() : Opted Out
I/ContactAccountLoggerTas( 2109): canRun() : Opted Out
D/dalvikvm( 2708): Added shared lib /data/app-lib/com.example.hello-5/libjxcore.so 0x42544fa0
D/jxcore_app_log( 2708): JniHelper::setJavaVM(0x41703528), pthread_self() = 2028177904
D/JX-Cordova( 2708): jxcore cordova android initializing
I/chromium( 2109): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/ContactAccountLoggerTas( 2109): canRun() : Opted Out
I/SELinux ( 2801): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2801):  
I/ContactAccountLoggerTas( 2109): canRun() : Opted Out
D/dalvikvm(  249): GC_EXPLICIT freed 44K, 49% free 9509K/18456K, paused 2ms+2ms, total 31ms
E/libGLESv2( 2708): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
E/libGLESv2( 2708): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
I/SELinux ( 2801): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2801):  
I/SELinux ( 2801):  
I/SELinux ( 2801): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/BrowserProcessMain( 2109): Initializing chromium process, renderers=0
E/SELinux ( 2801): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2801): >>>>> Normal User
E/dalvikvm( 2801): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 2801): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9509K/18456K, paused 1ms+3ms, total 24ms
D/TimaKeyStoreProvider( 2801): in addTimaSignatureService
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9509K/18456K, paused 2ms+4ms, total 24ms
D/TimaKeyStoreProvider( 2801): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2801): Added TimaKesytore provider
W/chromium( 2109): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 2109): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2109): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2109): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2109): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2109): Remote Branch: 
I/Adreno-EGL( 2109): Local Patches: 
I/Adreno-EGL( 2109): Reconstruct Branch: 
I/dalvikvm( 1311): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.n.a
W/dalvikvm( 1311): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/dalvikvm( 1311): VFY: replacing opcode 0x6e at 0x001c
V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WifiDisplayAdapter(  739): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
V/VibratorService(  739): hasVibrator - useVibetonz: false
W/jxcore-log( 2708): Initializing JXcore engine
W/jxcore-log( 2708): JXcore engine is ready
W/jxcore-log( 2708): Starting JXcore engine
D/UserAnalysis.PlaceProvider( 2801): Create SecureDbHelper
W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=2801, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
D/UserAnalysis.UserAnalysisBroadcastReceiver( 2801): Create SecureDbHelper
I/dalvikvm( 1311): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.o.a
W/dalvikvm( 1311): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
D/dalvikvm( 1311): VFY: replacing opcode 0x6e at 0x001f
D/dalvikvm( 1311): GC_CONCURRENT freed 2000K, 43% free 10702K/18456K, paused 6ms+8ms, total 44ms
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1311): Using platform SSLCertificateSocketFactory
I/dalvikvm( 1311): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.r.a
W/dalvikvm( 1311): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 1311): VFY: replacing opcode 0x6e at 0x0041
,I/SQLiteSecureOpenHelper( 2801): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2801): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2801): Open Place.db in secure mode
,E/dalvikvm( 1311): Could not find class 'android.net.Network', referenced from method com.google.android.gms.auth.be.k.a
W/dalvikvm( 1311): VFY: unable to resolve check-cast 195 (Landroid/net/Network;) in Lcom/google/android/gms/auth/be/k;
,D/dalvikvm( 1311): VFY: replacing opcode 0x1f at 0x0149
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GoogleURLConnFactory( 1311): Using platform SSLCertificateSocketFactory
I/dalvikvm( 1311): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1311): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1311): VFY: replacing opcode 0x6e at 0x0033
,D/CustomFrequencyManagerService(  739): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 739  tag : ACTIVITY_RESUME_BOOSTER@9
,I/System.out( 1311): Thread-53(HTTPLog):isShipBuild true
I/System.out( 1311): Thread-53(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/LockPatternUtils( 1304): isSmartCardAuthenticationAvailable: false
I/GLSUser ( 1311): [GLSUser] IOException in getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> exception: Unable to resolve host "android.clients.google.com": No address associated with hostname)
I/GLSUser ( 1311): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> status: NETWORK_ERROR)
D/AmoledAdjustTimer(  739): prevTemp = 283, currTemp = 285, prevStep = 4, currStep = 4
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1311): gms.StatusHelper Status from wire: NetworkError status: NETWORK_ERROR
,D/dalvikvm( 2109): GC_CONCURRENT freed 6346K, 40% free 11220K/18456K, paused 6ms+34ms, total 117ms
,W/Search.LoginHelper( 2109): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SQLiteSecureOpenHelper( 2801): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2801): ...getDatabaseLocked(b,b,pwd)
,I/SQLiteSecureOpenHelper( 2801): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2801): getDatabaseLocked(b,b,pwd)...
,D/UserAnalysis.CarAnalyzer( 2801): Create SecureDbHelper
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/SQLiteSecureOpenHelper( 2801): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2801): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2801): Open Place.db in secure mode
,W/NetworkUtils( 2109): OkHttp exception
W/Search.RefreshSearchDomainAndCookiesTask( 2109): Search parameters fetch failed: dhq: Error code: 262146
,W/Search.RefreshSearchDomainAndCookiesTask( 2109): Search parameters fetch failed
,I/ContactAccountLoggerTas( 2109): canRun() : Opted Out
,I/GLSUser ( 1311): [GLSUser] IOException in getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> exception: Unable to resolve host "android.clients.google.com": No address associated with hostname)
I/GLSUser ( 1311): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> status: NETWORK_ERROR)
,I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1311): gms.StatusHelper Status from wire: NetworkError status: NETWORK_ERROR
,W/Search.LoginHelper( 2109): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 2708): Platform android
W/jxcore-log( 2708): 
,W/jxcore-log( 2708): Process ARCH arm
W/jxcore-log( 2708): 
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1311): [GLSUser] IOException in getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> exception: Unable to resolve host "android.clients.google.com": No address associated with hostname)
I/GLSUser ( 1311): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> status: NETWORK_ERROR)
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1311): gms.StatusHelper Status from wire: NetworkError status: NETWORK_ERROR
,W/Search.LoginHelper( 2109): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/jxcore-log( 2708): JXcore Cordova bridge is ready!
I/jxcore-log( 2708): 
,W/jxcore-log( 2708): JXcore engine is started
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  240): DCD ON
,I/SQLiteSecureOpenHelper( 2801): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2801): ...getDatabaseLocked(b,b,pwd)
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1311): [GLSUser] IOException in getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> exception: Unable to resolve host "android.clients.google.com": No address associated with hostname)
,I/GLSUser ( 1311): [GLSUser] getAuthtoken(<ELLIDED:1197869880>, oauth2:https://www.googleapis.com/auth/googlenow) -> status: NETWORK_ERROR)
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1311): gms.StatusHelper Status from wire: NetworkError status: NETWORK_ERROR
,I/SELinux ( 2833): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2833):  
,E/jxcore-log( 2708): >> samsung-SM-G800H
E/jxcore-log( 2708): 
,I/jxcore-log( 2708): Total memory 1454641152
I/jxcore-log( 2708): 
I/jxcore-log( 2708): Free memory 428449792
I/jxcore-log( 2708): 
I/jxcore-log( 2708): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2708): 
,I/jxcore-log( 2708): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2708): 
,W/Search.LoginHelper( 2109): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2109): canRun() : Opted Out
,I/jxcore-log( 2708): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2708): 
,I/jxcore-log( 2708): Size 720 1280
I/jxcore-log( 2708): 
,I/jxcore-log( 2708): Screen Brightness 134
I/jxcore-log( 2708): 
,E/jxcore-log( 2708): Dummy Error Log.
E/jxcore-log( 2708): 
,I/SELinux ( 2833): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2833):  
I/SELinux ( 2833):  
,I/SELinux ( 2833): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2833): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2833): >>>>> Normal User
,E/dalvikvm( 2833): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 2833): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2833): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2833): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2833): Added TimaKesytore provider
,I/sCloudBackupApp( 2833): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SettingSearch/SearchIntentReceiver( 1304): InitSerachDBThread thread end!
W/ContextImpl( 1304): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:129 <bottom of call stack> 
,I/SELinux ( 2848): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2848):  
,I/SELinux ( 2848): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2848):  
I/SELinux ( 2848):  
,I/SELinux ( 2848): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2848): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2848): >>>>> Normal User
,E/dalvikvm( 2848): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 2848): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2848): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2848): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2848): Added TimaKesytore provider
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=2848, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 2864): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2864):  
,W/BackupManagerService(  739): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/BackupManagerService(  739): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
,D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
I/SELinux ( 2864): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2864):  
I/SELinux ( 2864):  
,I/SELinux ( 2864): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2864): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2864): >>>>> Normal User
,E/dalvikvm( 2864): >>>>> com.wssnps [ userId:0 | appId:1000 ]
,E/SELinux ( 2864): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2864): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2864): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2864): Added TimaKesytore provider
,D/NPS_WSSNPS( 2864): [] android.intent.action.BOOT_COMPLETED
,I/jxcore-log( 2708): getBuffer is called!!!!
I/jxcore-log( 2708): 
W/ContextImpl( 2864): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.wssnps.smlNpsReceiver.onReceive:380 android.app.ActivityThread.handleReceiver:2698 
,D/NPS_WSSNPS( 2864): [] Service onCreate!!
,I/SELinux ( 2880): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2880):  
,D/NPS_WSSNPS( 2864): [] NpsServiceTask Start
,I/NPS_WSSNPS( 2864): [44.140541] loadCryptionkeyLibrary
,I/NPS_WSSNPS( 2864): [44.140541] FirstLoad Or Not Exist
,D/dalvikvm( 2864): Trying to load lib /data/data/com.wssnps/files/libCryptionkey.so 0x425417b8
,D/dalvikvm( 2864): Added shared lib /data/data/com.wssnps/files/libCryptionkey.so 0x425417b8
,D/NPS_WSSNPS( 2864): [44.140541] smlDBHelper
,I/SELinux ( 2880): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2880):  
I/SELinux ( 2880):  
,I/SELinux ( 2880): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2880): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2880): >>>>> Normal User
E/dalvikvm( 2880): >>>>> com.samsung.android.app.accesscontrol [ userId:0 | appId:10064 ]
,E/SELinux ( 2880): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2880): in addTimaSignatureService
,I/NPS_WSSNPS( 2864): [44.140541] AsyncBulkFlagCheck
,I/NPS_WSSNPS( 2864): [44.140541] IsRemain_AsyncBulkCheck
,D/TimaKeyStoreProvider( 2880): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2880): Added TimaKesytore provider
,I/NPS_WSSNPS( 2864): [44.140541] IsRemain_Asyncing nothing
,W/ContextImpl( 2864): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 com.wssnps.smlNpsService$1.run:108 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
D/NPS_WSSNPS( 2864): [44.140541] Service onDestroy
I/NPS_WSSNPS( 2864): [44.140541] smlBRConfigurationDelete
I/NPS_WSSNPS( 2864): [44.140541] smlBRMessageDelete
I/NPS_WSSNPS( 2864): [44.140541] smlBREmailDelete
I/NPS_WSSNPS( 2864): [44.140541] smlBRNetworkDelete
I/NPS_WSSNPS( 2864): [44.140541] smlBRCallLogDelete
I/NPS_WSSNPS( 2864): [44.140541] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 2864): [44.140541] smlBRPenMemoMDelete
I/NPS_WSSNPS( 2864): [44.140541] smlBRSMemoDelete
I/NPS_WSSNPS( 2864): [44.140541] cpuBooster release : false
D/NPS_WSSNPS( 2864): [44.140541] dsServerSocket close
,I/SELinux ( 2904): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2904):  
,I/SELinux ( 2904): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2904):  
I/SELinux ( 2904):  
,I/SELinux ( 2904): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2904): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2904): >>>>> Normal User
,E/dalvikvm( 2904): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
,E/SELinux ( 2904): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2904): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2904): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2904): Added TimaKesytore provider
,D/FileShare-Server( 2904): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/SELinux ( 2919): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2919):  
,I/SELinux ( 2919): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2919):  
I/SELinux ( 2919):  
,I/SELinux ( 2919): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2919): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2919): >>>>> Normal User
,E/dalvikvm( 2919): >>>>> com.sec.android.nearby.mediaserver [ userId:0 | appId:10070 ]
,E/SELinux ( 2919): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2919): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2919): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2919): Added TimaKesytore provider
,I/AllShare(ASF-DMSLIB)( 2919): DMSReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,W/BackupManagerService(  739): dataChanged but no participant pkg='com.android.providers.settings' uid=10070
,I/SELinux ( 2934): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2934):  
,D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
I/ActivityManager(  739): Killing 1288:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #43
,I/SELinux ( 2934): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2934):  
I/SELinux ( 2934):  
,I/SELinux ( 2934): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2934): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2934): >>>>> Normal User
,E/dalvikvm( 2934): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 2934): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2934): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2934): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2934): Added TimaKesytore provider
,W/ContextImpl( 2934): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:61 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2947): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2947):  
,I/SELinux ( 2947): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2947):  
I/SELinux ( 2947):  
,I/SELinux ( 2947): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2947): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 2947): >>>>> Normal User
,E/dalvikvm( 2947): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
,E/SELinux ( 2947): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/PackageManager(  739): [MSG] MCS_UNBIND
I/PackageManager(  739): calling disconnectService()
,D/PackageManager(  739): Trying to unbind to DefaultContainerService
,I/ActivityManager(  739): Killing 1263:com.android.printspooler/u0a144 (adj 15): empty #43
D/TimaKeyStoreProvider( 2947): in addTimaSignatureService
D/TimaKeyStoreProvider( 2947): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2947): Added TimaKesytore provider
,D/BluetoothBDAdrressReceiver( 2947): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2947): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
W/ContextImpl( 2947): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2959): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2959):  
D/BluetoothBDTestService( 1238): onCreate()
E/BluetoothBDTestService( 1238): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
,E/BluetoothBDTestService( 1238): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1238): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/ActivityManager(  739): Killing 1769:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #43
,I/SELinux ( 2959): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2959):  
I/SELinux ( 2959):  
,I/SELinux ( 2959): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2959): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2959): >>>>> Normal User
,E/dalvikvm( 2959): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 2959): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 2959): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2959): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2959): Added TimaKesytore provider
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=2959, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 2971): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2971):  
I/ActivityManager(  739): Killing 1782:com.sec.modem.settings/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2934): Resource data:2131165197
I/SELinux ( 2971): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2971):  
I/SELinux ( 2971):  
,I/SELinux ( 2971): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2971): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2971): >>>>> Normal User
,E/dalvikvm( 2971): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 2971): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2934): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131165194
,I/AMMetaDataParserService( 2934): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 2971): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2971): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2971): Added TimaKesytore provider
,I/AMMetaDataParserService( 2934): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,E/PersonaManagerService(  739): returning null in  getPersonasForUser
,I/AMMetaDataParserService( 2934): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,I/SELinux ( 2983): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2983):  
I/ActivityManager(  739): Killing 1794:com.sec.tcpdumpservice/1000 (adj 15): empty #43
,D/dalvikvm(  249): GC_EXPLICIT freed 46K, 49% free 9509K/18456K, paused 6ms+2ms, total 31ms
,I/SELinux ( 2983): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2983):  
I/SELinux ( 2983):  
,I/SELinux ( 2983): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2983): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2983): >>>>> Normal User
,E/dalvikvm( 2983): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 2983): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9509K/18456K, paused 3ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 2983): in addTimaSignatureService
V/AlarmManager(  739): waitForAlarm result :4
V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/TimaKeyStoreProvider( 2983): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2983): Added TimaKesytore provider
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9509K/18456K, paused 1ms+3ms, total 20ms
,I/AMMetaDataParserService( 2934): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,I/AMMetaDataParserService( 2934): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
I/ActivityManager(  739): Waited long enough for: ServiceRecord{42eeec58 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131165194
I/AMMetaDataParserService( 2934): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/AMMetaDataParserService( 2934): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,I/AMMetaDataParserService( 2934): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,W/BackupManagerService(  739): dataChanged but no participant pkg='com.android.providers.settings' uid=10084
,I/AMMetaDataParserService( 2934): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
,I/AMMetaDataParserService( 2934): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,I/AMMetaDataParserService( 2934): Resource data:2131165195
I/AMMetaDataParserService( 2934): getResourceName:com.sec.android.gallery3d:xml/device_filter
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2934): Resource data:2131165204
I/AMMetaDataParserService( 2934): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 2934): getResourceTypeNamexml
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2934): Resource data:2131165204
I/AMMetaDataParserService( 2934): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2934): Resource data:2131165204
I/AMMetaDataParserService( 2934): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2934): Resource data:2131099676
,I/AMMetaDataParserService( 2934): getResourceName:com.android.mms:xml/spellscroll
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
I/AMMetaDataParserService( 2934): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131099648
,I/AMMetaDataParserService( 2934): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/AMMetaDataParserService( 2934): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2934): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2934): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/AMMetaDataParserService( 2934): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/dalvikvm(  739): GC_EXPLICIT freed 1793K, 18% free 22698K/27396K, paused 5ms+9ms, total 126ms
,I/AMMetaDataParserService( 2934): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/SensorService(  739):   -0.0 -0.1 9.5
,I/SELinux ( 3005): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3005):  
,I/ActivityManager(  739): Killing 1833:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
I/AMMetaDataParserService( 2934): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131099648
I/AMMetaDataParserService( 2934): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/AMMetaDataParserService( 2934): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 3005): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3005):  
I/SELinux ( 3005):  
,I/SELinux ( 3005): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3005): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3005): >>>>> Normal User
,E/dalvikvm( 3005): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
E/SELinux ( 3005): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2934): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
D/TimaKeyStoreProvider( 3005): in addTimaSignatureService
D/TimaKeyStoreProvider( 3005): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3005): Added TimaKesytore provider
,I/AMMetaDataParserService( 2934): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/AMMetaDataParserService( 2934): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 3017): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3017):  
I/ActivityManager(  739): Killing 1742:com.sec.android.app.mt/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2934): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2934): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/SELinux ( 3017): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3017):  
I/SELinux ( 3017):  
,I/SELinux ( 3017): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
,E/SELinux ( 3017): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
E/dalvikvm( 3017): >>>>> Normal User
E/dalvikvm( 3017): >>>>> com.dropbox.android [ userId:0 | appId:10091 ]
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131099648
,I/AMMetaDataParserService( 2934): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,E/SELinux ( 3017): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 3017): in addTimaSignatureService
,I/AMMetaDataParserService( 2934): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/TimaKeyStoreProvider( 3017): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3017): Added TimaKesytore provider
,I/AMMetaDataParserService( 2934): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2934): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,I/AMMetaDataParserService( 2934): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2934): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2934): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131099648
,I/AMMetaDataParserService( 2934): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3017): Setting receiver enabled: false
,I/AMMetaDataParserService( 2934): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/com.dropbox.sync.android.a( 3017): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/AMMetaDataParserService( 2934): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/com.dropbox.sync.android.aa( 3017): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800H armeabi-v7a; en_US))
,I/AMMetaDataParserService( 2934): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/AMMetaDataParserService( 2934): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=3017, uid=10091 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 3039): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3039):  
I/ActivityManager(  739): Killing 1884:com.sec.phone/1001 (adj 15): empty #43
,I/AMMetaDataParserService( 2934): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/SELinux ( 3039): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3039):  
I/SELinux ( 3039):  
,I/SELinux ( 3039): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3039): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3039): >>>>> Normal User
E/dalvikvm( 3039): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 3039): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2934): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131099648
,I/AMMetaDataParserService( 2934): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 3039): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3039): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3039): Added TimaKesytore provider
,I/AMMetaDataParserService( 2934): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2934): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=3039, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 3039): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 3039): ELMEngine.ELMEngine( context ).
,D/elm:14132( 3039): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 3039): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/AMMetaDataParserService( 2934): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/elm:14132( 3039): ElmAgentService : onCreate()
,D/elm:14132( 3039): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 3039): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:14132( 3039): BootCompletedState : startBootCompleted() call
,I/SELinux ( 3057): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3057):  
,D/elm:14132( 3039): ModuleBase.resetCalllogAPIAlarm()
,D/elm:14132( 3039): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:14132( 3039): Get License : 0
,D/elm:14132( 3039): ElmAgentService : onDestroy().
I/ActivityManager(  739): Killing 1985:com.google.android.configupdater/u0a3 (adj 15): empty #43
,I/AMMetaDataParserService( 2934): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,E/SMD     (  240): DCD ON
W/ContextImpl(  739): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  739): [PWL] On : 0 (44025 ms ago)
I/PowerManagerService(  739): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService(  739): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1066, ws=null) (elapsedTime=6519)
,I/SELinux ( 3057): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3057):  
I/SELinux ( 3057):  
,I/SELinux ( 3057): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3057): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3057): >>>>> Normal User
,E/dalvikvm( 3057): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,E/SELinux ( 3057): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2934): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/TimaKeyStoreProvider( 3057): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3057): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3057): Added TimaKesytore provider
,I/AMMetaDataParserService( 2934): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131099648
,I/AMMetaDataParserService( 2934): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/AMMetaDataParserService( 2934): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/System.out( 3017): Thread-258(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 3017): Thread-258(ApacheHTTPLog):isShipBuild true
,I/System.out( 3017): Thread-258(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 3017): pool-4-thread-1 calls detatch()
,I/SELinux ( 3074): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3074):  
I/ActivityManager(  739): Killing 2093:com.sec.dsm.system/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2934): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 2934): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/SELinux ( 3074): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3074):  
I/SELinux ( 3074):  
,I/SELinux ( 3074): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3074): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3074): >>>>> Normal User
,E/dalvikvm( 3074): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,E/SELinux ( 3074): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2934): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/TimaKeyStoreProvider( 3074): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3074): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3074): Added TimaKesytore provider
,I/AMMetaDataParserService( 2934): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2934): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/CameraApp( 3074): CameraApp.onCreate()... mFeature : null
I/testFeature( 3074): Feature.Feature(context)
I/testFeature( 3074): Feature.readInternalDefaultXml()
,I/testFeature( 3074): ResetFeatureValue
I/CameraFirmware_broadcast( 3074): CameraFirmwareBroadCastReceiver...
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
I/CameraApp( 3074): CameraApp.getAppFeature()...
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
I/AMMetaDataParserService( 2934): Resource data:Loop for running a,ctivitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2934): Resource data:2131099671
I/AMMetaDataParserService( 2934): getResourceName:com.android.mms:xml/searchable
I/AMMetaDataParserService( 2934): getResourceTypeNamexml
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
,I/SELinux ( 3086): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3086):  
I/ActivityManager(  739): Killing 2132:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
,I/SELinux ( 3086): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3086):  
I/SELinux ( 3086):  
,I/SELinux ( 3086): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3086): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 3086): >>>>> Normal User
,E/dalvikvm( 3086): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 3086): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3086): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3086): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3086): Added TimaKesytore provider
,D/dalvikvm( 2934): GC_CONCURRENT freed 4984K, 32% free 12705K/18456K, paused 2ms+3ms, total 32ms
,D/dalvikvm( 2934): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131165216
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/AMMetaDataParserService( 2934): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,D/PackageIntentReceiver( 3086): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3086): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager(  739): Killing 2152:com.sec.kidsplat.installer/u0a158 (adj 15): empty #43
,I/AMMetaDataParserService( 2934): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.TimDataConnectionDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429159
,I/SELinux ( 3101): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3101):  
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131296695
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429159
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429144
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429144
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429144
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131297114
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ApnSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ApnSettingsTabActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429146
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429146
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429168
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/mirror_link_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429159
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131296695
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.TetherSettings
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429159
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131296695
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429144
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131297114
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429159
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131296695
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429159
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131296695
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429159
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131296695
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429159
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131296695
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429159
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131296695
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429219
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429191
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429191
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429191
I/SELinux ( 3101): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3101):  
I/SELinux ( 3101):  
I/SELinux ( 3101): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
E/SELinux ( 3101): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
E/dalvikvm( 3101): >>>>> Normal User
E/dalvikvm( 3101): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429191
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
E/SELinux ( 3101): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/AMMetaDataParserService( 2934): Resource data:2131429191
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429191
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131298419
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429191
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131298419
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429191
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
D/TimaKeyStoreProvider( 3101): in addTimaSignatureService
,I/AMMetaDataParserService( 2934): Resource data:2131298419
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429176
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429176
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429173
D/TimaKeyStoreProvider( 3101): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429173
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429172
D/ActivityThread( 3101): Added TimaKesytore provider
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429172
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429182
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429173
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429186
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429186
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429173
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131297804
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/display_settings
,I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429173
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/display_settings
,I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429228
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.users.UserOptions
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429128
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429128
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ManageApplications
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429128
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429127
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429127
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429128
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429128
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429127
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/home_settings
,I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429127
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429128
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429153
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/location_settings
,I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429224
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.CarrierMatchSetting
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429224
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131296750
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429224
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429123
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/privacy_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429224
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131296750
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429224
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131296750
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429187
,I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429187
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131298587
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/accessibility_settings
,I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429187
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2934): Resource data:2131298587
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429191
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429180
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/driving_mode
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429223
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429225
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429159
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131296695
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429165
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429225
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429223
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131297938
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429223
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131297938
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429161
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/nfc_setting
,I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429163
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429167
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131296695
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429221
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429221
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429119
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429217
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429224
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429224
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429159
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429173
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429208
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2934): Resource data:2131429286
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429224
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429201
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429185
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429185
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131299843
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/power_saving_mode_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429185
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429185
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429222
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/power_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429186
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 2934): Resource data:1
W/ResourceType( 2934): No package identifier when getting name for resource number 0x00000001
W/System.err( 2934): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 2934): 	at android.content.res.Resources.getResourceName(Resources.java:3017)
W/System.err( 2934): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 2934): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 2934): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 2934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2934): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 2934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429199
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131301070
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429173
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131297804
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429203
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429193
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429194
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429206
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131300118
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429196
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429260
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429197
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429291
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429228
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429199
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429199
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429199
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429199
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.NetworkManagement
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.MultiSimCardManagerPreference
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.NetworkManagementSetting
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.DualHelpActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.DualSoundRingtoneSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.RingtoneSettingTabActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.IccLockTabSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429173
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429285
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429172
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131301505
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429203
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429203
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131302910
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429179
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2130838248
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2934): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429216
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429209
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429209
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAlertDialogActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429177
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429212
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429213
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429153
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131302078
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429153
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131302078
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429153
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131302107
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429159
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429159
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429117
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429122
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429195
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131297804
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429151
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429204
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429204
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429195
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2130838300
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2934): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2130838300
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2934): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429202
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429202
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2934): Resource data:2131165381
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:xml/searchable
I/AMMetaDataParserService( 2934): getResourceTypeNamexml
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429124
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429187
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2934): Resource data:2131298587
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2934): getResourceTypeNamestring
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429198
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=3101, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429258
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429220
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429220
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429276
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429276
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePacka,geName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429148
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429242
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.KnoxSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2131429211
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2934): Resource data:2130838248
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2934): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 29,34): Resource data:2131429192
I/AMMetaDataParserService( 2934): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 2934): getResourceTypeNameid
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintOnehandGrip
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2934): Resource data:2131034120
I/AMMetaDataParserService( 2934): getResourceName:com.android.contacts:xml/searchable
I/AMMetaDataParserService( 2934): getResourceTypeNamexml
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
I/AMMetaDataParserService( 2934): Resource data:2131034113
I/AMMetaDataParserService( 2934): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/AMMetaDataParserService( 2934): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/Babel   ( 3101): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3101): MmsConfig.loadMmsSettings
I/Babel   ( 3101): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,I/Babel   ( 3101): MmsConfig.loadFromDatabase
D/dalvikvm( 3101): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3101): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3101): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3101): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3101): VFY: unable to resolve instance field 46
,D/dalvikvm( 3101): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3101): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3101): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3101): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3101): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3101): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
E/Babel   ( 3101): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3101): MmsConfig.loadFromResources
,E/Babel   ( 3101): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3101): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,D/dalvikvm( 3101): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4263a970
,I/AMMetaDataParserService( 2934): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/dalvikvm( 3101): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4263a970
,D/dalvikvm( 3101): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4263a970, skipping init
,D/dalvikvm( 3101): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4263a970
,D/dalvikvm( 3101): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4263a970
V/JNIHelp ( 3101): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/Settings( 3101): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/AMMetaDataParserService( 2934): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,V/Babel   ( 3101): babel boot account: thalitester@gmail.com
,V/Babel   ( 3101): babel boot account: SMS
,I/AMMetaDataParserService( 2934): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131034113
I/AMMetaDataParserService( 2934): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,D/dalvikvm( 3101): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4263a970
,D/dalvikvm( 3101): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4263a970
D/dalvikvm( 3101): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4263a970
,D/dalvikvm( 3101): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4263a970
,I/AMMetaDataParserService( 2934): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/SELinux ( 3126): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3126):  
I/ActivityManager(  739): Killing 2165:com.sec.factory/1000 (adj 15): empty #43
,I/ActivityManager(  739): Waited long enough for: ServiceRecord{43066be0 u0 com.samsung.android.providers.context/.ContextService}
I/AMMetaDataParserService( 2934): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/SELinux ( 3126): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3126):  
I/SELinux ( 3126):  
,I/SELinux ( 3126): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/AMMetaDataParserService( 2934): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
E/SELinux ( 3126): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3126): >>>>> Normal User
,E/dalvikvm( 3126): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 3126): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3126): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3126): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3126): Added TimaKesytore provider
,I/AMMetaDataParserService( 2934): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 2934): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 2934): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 2934): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131034112
I/AMMetaDataParserService( 2934): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/ProviderInstaller( 3101): Installed default security provider GmsCore_OpenSSL
,I/AMMetaDataParserService( 2934): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
V/AlarmManager(  739): waitForAlarm result :4
V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager(  739): waitForAlarm result :4
V/AlarmManager(  739): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/AMMetaDataParserService( 2934): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
,I/SELinux ( 3142): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3142):  
,I/AMMetaDataParserService( 2934): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
I/ActivityManager(  739): Killing 2217:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2934): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sams,ung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
I/AMMetaDataParserService( 2934): Resource data:2131034113
I/AMMetaDataParserService( 2934): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 2934): getResourceTypeNamexml
I/SELinux ( 3142): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3142):  
I/SELinux ( 3142):  
I/SELinux ( 3142): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3142): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3142): >>>>> Normal User
E/dalvikvm( 3142): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
E/SELinux ( 3142): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2934): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
D/TimaKeyStoreProvider( 3142): in addTimaSignatureService
D/TimaKeyStoreProvider( 3142): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3142): Added TimaKesytore provider
I/GAV2    ( 2109): Thread[GAThread,5,main]: No campaign data found.
I/AMMetaDataParserService( 2934): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
I/GAv4-SVC( 1638): Google Analytics 8.3.01 is starting up.
,D/dalvikvm( 2934): GC_CONCURRENT freed 2271K, 33% free 12383K/18456K, paused 2ms+2ms, total 33ms
,I/AMMetaDataParserService( 2934): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,W/ContextImpl( 3142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
,I/AMMetaDataParserService( 2934): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/knox    ( 3142): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
,I/knox    ( 3142): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3142): KNOXAgentService : onCreate()
,D/knox    ( 3142): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 3142): KNOXAgentService. startJobThread() start
D/knox    ( 3142): KNOXAgentService. JobThread()
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2934): Resource data:2131034116
I/AMMetaDataParserService( 2934): getResourceName:com.android.contacts:xml/findo_searchable
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
D/knox    ( 3142): KNOXAgentService. JobThread. notifyAll().
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
,D/knox    ( 3142): KNOXAgentService. startJobThread() wait
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2934): Resource data:2131099668
,I/AMMetaDataParserService( 2934): getResourceName:com.sec.android.app.sbrowser:xml/searchable
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/AMMetaDataParserService( 2934): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 2934): Resource data:2131099650
I/AMMetaDataParserService( 2934): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/SELinux ( 3160): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3160):  
,D/knox    ( 3142): mKnoxAgentEngine.ELMEngine( context , reStart:true).
D/knox    ( 3142): KNOXAgentService : onDestroy().
,D/knox    ( 3142): ModuleBase.cancelAllAlarmManageModule()
,I/AMMetaDataParserService( 2934): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,I/AMMetaDataParserService( 2934): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
,I/SELinux ( 3160): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3160):  
I/SELinux ( 3160):  
,I/SELinux ( 3160): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3160): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3160): >>>>> Normal User
,E/dalvikvm( 3160): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
,E/SELinux ( 3160): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2934): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 2934): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
,D/TimaKeyStoreProvider( 3160): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3160): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3160): Added TimaKesytore provider
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAutoDiscover
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activity,com.android.email.activity.Debug
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131099667
,I/AMMetaDataParserService( 2934): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/AMMetaDataParserService( 2934): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559
,E/KnoxSetupWizardClient( 3160): isShipMode : 1
,I/KnoxSetupWizardClient( 3160): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 2934): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558
,W/System.err( 3160): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3160): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 3160): 	at android.os.Parcel.readException(Parcel.java:1419)
,W/System.err( 3160): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3160): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 3160): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
,W/System.err( 3160): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/System.err( 3160): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
W/System.err( 3160): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 3160): 	at android.os.Parcel.readException(Parcel.java:1419)
,W/System.err( 3160): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3160): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
D/ShortcutReceiver( 3160):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,W/System.err( 3160): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
W/System.err( 3160): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
I/yash    ( 3160): setDisableWidget>size:0
,W/System.err( 3160): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/AMMetaDataParserService( 2934): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
,I/SELinux ( 3174): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3174):  
I/ActivityManager(  739): Killing 1693:com.fmm.dm/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2934): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
,D/dalvikvm(  249): GC_EXPLICIT freed 47K, 49% free 9509K/18456K, paused 2ms+3ms, total 28ms
,I/AMMetaDataParserService( 2934): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9509K/18456K, paused 2ms+2ms, total 19ms
I/SELinux ( 3174): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3174):  
I/SELinux ( 3174):  
,I/SELinux ( 3174): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3174): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3174): >>>>> Normal User
,E/dalvikvm( 3174): >>>>> com.LocalFota [ userId:0 | appId:10110 ]
,E/SELinux ( 3174): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9509K/18456K, paused 3ms+2ms, total 21ms
,D/TimaKeyStoreProvider( 3174): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3174): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 2934): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
,D/ActivityThread( 3174): Added TimaKesytore provider
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2934): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2934): Resource data:2131099689
I/AMMetaDataParserService( 2934): getResourceName:com.android.email:xml/spellscroll
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2934): Resource data:2131099685
,I/AMMetaDataParserService( 2934): getResourceName:com.android.email:xml/searchable
I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,I/AMMetaDataParserService( 2934): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 2934): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2934): getResourcePackageName:com.android.keyguard.layout
,I/AMMetaDataParserService( 2934): Resource data:2130903052
,I/AMMetaDataParserService( 2934): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
I/AMMetaDataParserService( 2934): getResourceTypeNamelayout
I/AMMetaDataParserService( 2934): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2934): Resource data:2131034112
,I/AMMetaDataParserService( 2934): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 2934): getResourceTypeNamexml
,W/ActivityManager(  739): Permission Denial: getCurrentUser() from pid=3174, uid=10110 requires android.permission.INTERACT_ACROSS_USERS
I/DBG_WSS_LF( 3174): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
I/DBG_WSS_LF( 3174): [20.0040.140326][Line:27][<init>] First call
,I/AMMetaDataParserService( 2934): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,I/AMMetaDataParserService( 2934): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
,I/DBG_WSS_LF( 3174): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_WSS_LF( 3174): [20.0040.140326][Line:31][onReceive] *** boot complete ***
,I/DBG_WSS_LF( 3174): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
,I/DBG_WSS_LF( 3174): [20.0040.140326][Line:41][onReceive] nStatus : -1
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 2934): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,I/SELinux ( 3189): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3189):  
I/ActivityManager(  739): Killing 2234:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
I/ActivityManager(  739): Killing 2256:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #43
,I/SELinux ( 3189): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3189):  
I/SELinux ( 3189):  
,I/SELinux ( 3189): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3189): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3189): >>>>> Normal User
,E/dalvikvm( 3189): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
,E/SELinux ( 3189): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3189): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3189): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3189): Added TimaKesytore provider
,D/StatusChecker( 3189): onReceive : android.intent.action.BOOT_COMPLETED
,I/SELinux ( 3203): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3203):  
I/ActivityManager(  739): Killing 2281:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,I/SELinux ( 3203): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3203):  
I/SELinux ( 3203):  
,I/SELinux ( 3203): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3203): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3203): >>>>> Normal User
,E/dalvikvm( 3203): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10133 ]
,E/SELinux ( 3203): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3203): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3203): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3203): Added TimaKesytore provider
,D/QuickConnect( 3203): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 3203): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 3203): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,W/BackupManagerService(  739): dataChanged but no participant pkg='com.android.providers.settings' uid=10133
V/QuickConnect( 3203): SconnectManager.getInstance - () return existing instance null
W/ContextImpl( 3203): Implicit intents with startService are not safe: Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } android.content.ContextWrapper.startServiceAsUser:517 android.content.ContextWrapper.startServiceAsUser:517 com.samsung.android.sconnect.periph.PeriphStartReceiver.onReceive:30 
I/QuickConnect( 3203): PeriphService.onCreate - [START]
,D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
,I/SELinux ( 3222): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3222):  
,I/QuickConnect( 3203): PeriphService.onCreate - [START] USER_OWNER
,D/QuickConnect( 3203): PeriphService.setProcessForeground - Build.VERSION.SDK_INT = 19
,I/QuickConnect( 3203): PeriphService.setProcessForeground - true of JB_MR2 complete 
I/QuickConnect( 3203): PeriphService.setState - 0 >> 1
V/QuickConnect( 3203): PeriphService.runService - 
I/QuickConnect[1.1][2] ( 3203): SconnectManager.SconnectManager - initiate from com.samsung.android.sconnect.periph.PeriphService@42549440
I/QuickConnect[1.1][2] ( 3203): SconnectManager.SconnectManager - set getApplicationContext android.app.Application@425413c8
D/QuickConnect[1.1][2] ( 3203): SconnectManager.registerBroadcast - --
D/QuickConnect[1.1][2] ( 3203): SconnectManager.SconnectManager - REQUEST_ID :  1
D/QuickConnect[1.1][2] ( 3203): ScanThread.ScanThread - created!
,V/QuickConnect[1.1][2] ( 3203): BluetoothHelper.BluetoothHelper - 
,D/QuickConnect[1.1][2] ( 3203): BluetoothHelper.registerBluetoothAdapterReceiver - mIsBluetoothAdapterReceiver = false
,V/QuickConnect[1.1][2] ( 3203): BleHelper.BleHelper - Constructor
I/SELinux ( 3222): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3222):  
I/SELinux ( 3222):  
,I/SELinux ( 3222): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3222): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3222): >>>>> Normal User
,E/dalvikvm( 3222): >>>>> com.sec.android.service.bezel [ userId:0 | appId:1000 ]
,E/SELinux ( 3222): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3222): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3222): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3222): Added TimaKesytore provider
,E/QuickConnect[1.1][2] ( 3203): BleHelper.startScan - not isGattServiceReady. Try to BLE On calling addLeRadioReference()
,D/BluetoothRadioManager( 3203): addLeRadioReference: Add CB  com.samsung.android.sconnect.common.net.BleHelper$GattServiceStateChangeCallback@4255c7f0
D/BluetoothRadioManager( 3203):  addRadioReference enabled = false
,D/BluetoothRadioManager( 3203):  BLE Radio count is : 1
D/BluetoothManagerService(  739): foregroundUser: 0
D/BluetoothRadioManager( 3203): addLeRadioReference: isRadioEnabled() =  false
,V/QuickConnect[1.1][2] ( 3203): BleHelper.mSearchWearable - true
,V/QuickConnect[1.1][2] ( 3203): UpnpHelper.UpnpHelper - 
,V/QuickConnect[1.1][2] ( 3203): JmdnsHelper.JmdnsHelper - Constructor
,V/QuickConnect[1.1][2] ( 3203): P2pHelper.P2pHelper - EXEC
,D/QuickConnect[1.1][2] ( 3203): p2pHelperWorkThread.p2pHelperWorkThread - created!
,E/BluetoothManagerService(  739): Package is exist.
,I/SELinux ( 3240): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3240):  
,D/QuickConnect[1.1][2] ( 3203): WifiHelper.WifiHelper -  -- 
,D/BezelQuickConnect( 3222): BezelBroadcastReceiver - onReceive : android.intent.action.BOOT_COMPLETED
,D/BezelQuickConnect( 3222): BezelBroadcastReceiver - StartBezelInteractionService
,D/BezelQuickConnect( 3222): BezelManagerService - setProcessForeground, Build.VERSION.SDK_INT = 19
,I/BezelQuickConnect( 3222): BezelManagerService - setProcessForeground, true of JB_MR2 complete 
D/BezelQuickConnect( 3222): BezelBroadcastReceiver - onReceive : Send to quickpanel - service.ENABLED
,I/QuickConnect[1.1][2] ( 3203): CentralActionManager.CentralActionManager - EXEC
,V/QuickConnect[1.1][2] ( 3203): BluetoothOppActionHelper.BluetoothOppActionHelper - 
V/QuickConnect[1.1][2] ( 3203): GroupVoiceTalkActionHelper.GroupVoiceTalkActionHelper -  --
,V/QuickConnect[1.1][2] ( 3203): SmartHomeActionHelper.SmartHomeActionHelper - --
,V/QuickConnect[1.1][2] ( 3203): ScreenMirrorActionHelper.ScreenMirrorActionHelper - 
V/QuickConnect[1.1][2] ( 3203): BluetoothActionHelper.BluetoothActionHelper - 
,D/BluetoothAdapter( 3203): 1112902272: getState() :  mService = null. Returning STATE_OFF
,V/PhoneStatusBar( 1066): onReceive: Intent { act=com.sec.android.sconnect.service.ENABLED flg=0x10 }mQconnectEnable = true
D/WifiDisplayAdapter(  739): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/ContextImpl( 3222): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.android.service.bezel.BezelBroadcastReceiver.onReceive:40 android.app.ActivityThread.handleReceiver:2698 
,E/NetworkSettingsReceiver( 1756): onReceive: android.intent.action.BOOT_COMPLETED
,E/BluetoothHeadset( 3203): BTStateChangeCB is registed
,D/STATUSBAR-PhoneStatusBar( 1066): showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
E/BluetoothHeadset( 3203): BluetoothHeadset service is binded
,I/QuickConnect[1.1][2] ( 3203): SconnectManager.getInstance - make new instance com.samsung.android.sconnect.SconnectManager@4254b038
,V/QuickConnect[1.1][2] ( 3203): SconnectManager.getInstance - return existing instance com.samsung.android.sconnect.SconnectManager@4254b038
,V/QuickConnect[1.1][2] ( 3203): PreDiscoveryHelper.PreDiscoveryHelper -  -- 
,D/QuickConnect[1.1][2] ( 3203): PreDiscoveryHelper.setVisibilityFromSystemDb - --
,D/QuickConnect[1.1][2] ( 3203): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,D/QuickConnect[1.1][2] ( 3203): Utils.getFromDb -  Key[quick_connect_contact_only], isEnabled [1] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 3203): PreDiscoveryHelper.setVisibilityFromSystemDb - isAllowToConnect : false, isContactOnly : true, visibilitySetting : 2
D/QuickConnect[1.1][2] ( 3203): PreDiscoveryHelper.changeResponseSetting - changed: 2
V/QuickConnect[1.1][2] ( 3203): PreDiscoveryHelper.updateAdvData - 
,V/QuickConnect[1.1][2] ( 3203): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4254b038
,V/QuickConnect[1.1][2] ( 3203): PreDiscoveryHelper.updateRespTarget - 
,W/BroadcastQueue(  739): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.android.calendar/.magazine.CalendarUpdateRelatedDataReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
I/SELinux ( 3240): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3240):  
I/SELinux ( 3240):  
I/SELinux ( 3240): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3240): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3240): >>>>> Normal User
E/dalvikvm( 3240): >>>>> com.android.bluetooth [ userId:0 | appId:1002 ]
E/SELinux ( 3240): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 3256): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3256):  
,D/QuickConnect[1.1][2] ( 3203): PreDiscoveryHelper.initializeAdvData - 
,D/TimaKeyStoreProvider( 3240): in addTimaSignatureService
V/QuickConnect[1.1][2] ( 3203): PreDiscoveryHelper.initializeAdvData - name: Galaxy S5-2(11)
D/QuickConnect[1.1][2] ( 3203): PreDiscoveryHelper.initializeAdvData - name selected: Galaxy S5-2(11)
,V/QuickConnect[1.1][2] ( 3203): CONTACT_Info.getMyMobileNumber - 
,D/TimaKeyStoreProvider( 3240): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3240): Added TimaKesytore provider
,D/QuickConnect[1.1][2] ( 3203): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3203): CONTACT_Info.getMyMobileNumber - null 
,D/QuickConnect[1.1][2] ( 3203): NetUtil.getP2pMacFromWifiMac - ($)
,V/QuickConnect[1.1][2] ( 3203): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4254b038
W/QuickConnect[1.1][2] ( 3203): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.emeeting.b2c.hancom
,D/QuickConnect[1.1][2] ( 3203): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.emeeting
D/QuickConnect[1.1][2] ( 3203): AppPackageUtil.isStubApk - but Stub version[2.7.025] of com.samsung.groupcast
W/QuickConnect[1.1][2] ( 3203): AppPackageUtil.isAppInstalled - this is Stub - com.samsung.groupcast
,D/QuickConnect[1.1][2] ( 3203): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.samsung.groupcast
W/QuickConnect[1.1][2] ( 3203): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3203): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3203): PeriphService.registerUserReceiver - mIsUserReceiver == false
I/SELinux ( 3256): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3256):  
I/SELinux ( 3256):  
,I/SELinux ( 3256): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3256): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3256): >>>>> Normal User
,E/dalvikvm( 3256): >>>>> com.sec.android.app.camera [ userId:0 | appId:10147 ]
,E/SELinux ( 3256): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/QuickConnect[1.1][2] ( 3203): PeriphService.onStartCommand - USER_OWNER
I/QuickConnect[1.1][2] ( 3203): PeriphService.onStartCommand - Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } flags[0] startId[1]
,I/QuickConnect[1.1][2] ( 3203): PeriphService.onStartCommand - Action: com.samsung.android.sconnect.periph.START_SERVICE
,E/BluetoothManagerService(  739): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 2708): packageName : com.example.hello
,I/WifiManager( 2708): setWifiEnabled : false
I/WifiService(  739): setWifiEnabled: false pid=2708, uid=10180
,D/TimaKeyStoreProvider( 3256): in addTimaSignatureService
,I/jxcore-log( 2708): ****TEST TOOK:  5074  ms ****
I/jxcore-log( 2708): 
,D/TimaKeyStoreProvider( 3256): Cannot add TimaSignature Service, License check Failed
I/jxcore-log( 2708): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2708): 
,D/ActivityThread( 3256): Added TimaKesytore provider
,W/dalvikvm( 3256): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,D/BtSettings.ProfileConfig( 3240): Adding GattService
,D/BtSettings.ProfileConfig( 3240): Adding HeadsetService
D/BtSettings.ProfileConfig( 3240): Adding A2dpService
,D/BtSettings.ProfileConfig( 3240): Adding HidService
D/BtSettings.ProfileConfig( 3240): Adding HealthService
,D/BtSettings.ProfileConfig( 3240): Adding PanService
,D/BtSettings.ProfileConfig( 3240): Adding BluetoothMapService
,D/BluetoothAdapterService( 3240): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterState( 3240): make
I/bluedroid( 3240): init
,I/BluetoothAdapterState( 3240): Entering OffState
,I/SELinux ( 3280): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3280):  
,I/ActivityManager(  739): Killing 2297:com.sec.android.app.mss/u0a21 (adj 15): empty #43
I/bte_conf( 3240): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bluedroid( 3240): get_profile_interface socket
I/GKI_LINUX( 3240): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterService( 3240):  checkAddrForIOP: Loading from conf
E/BluetoothServiceJni( 3240): populateRssiValuesNative
I/bluedroid( 3240): getModelRssiValues
E/BluetoothServiceJni( 3240): model_rssi_values_callback: low = -70, mid = -60, high = 127
,I/SELinux ( 3280): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3280):  
I/SELinux ( 3280):  
,I/SELinux ( 3280): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3280): >>>>> Normal User
,E/dalvikvm( 3280): >>>>> com.sec.android.inputmethod [ userId:0 | appId:1000 ]
,E/SELinux ( 3280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/bluedroid( 3240): config_hci_snoop_log
,D/BluetoothManagerService(  739): Broadcasting onBluetoothServiceUp() to 11 receivers.
,D/TimaKeyStoreProvider( 3280): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3280): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3280): Added TimaKesytore provider
,D/BluetoothRadioManager( 3203): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@425b3d80
,D/BluetoothRadioManager( 3203): onBluetoothServiceUp()  registerRadioClient mUUID = 0df2adf8-b201-46f0-91e8-594a9bf7c35f
,I/bluedroid( 3240): update_radio_count
D/BluetoothAdapterState( 3240): CURRENT_STATE=OFF, MSG = USER_TURN_ON_RADIO
I/BluetoothAdapterState( 3240): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=false
D/BluetoothAdapterState( 3240): CURRENT_STATE=PENDING, MSG = BEGIN_ENABLE_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
,I/bluedroid( 3240): enable
,I/bt_hci_bdroid( 3240): init
I/bt_vendor( 3240): bt-vendor : init
I/bt_vendor( 3240): bt-vendor : get_bt_soc_type
E/bt_vendor( 3240): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 3240): init: Local BD Address : dc:06:b5:96:94:38
D/bt_userial_mct( 3240): userial_init
I/bt_vendor( 3240): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3240): Starting hciattach daemon
I/bt_vendor( 3240): try to set false
,I/bt_hci_bdroid( 3240): bt_hc_worker_thread started
I/bt_vendor( 3240): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 3240): Starting hciattach daemon
,I/bt_vendor( 3240): try to set true
,I/qcom-bluetooth( 3297): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/SELinux ( 3301): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3301):  
I/ActivityManager(  739): Killing 2311:com.sec.android.app.msa/u0a23 (adj 15): empty #43
,I/qcom-bluetooth( 3307): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/SELinux ( 3301): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3301):  
I/SELinux ( 3301):  
,I/SELinux ( 3301): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3301): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3301): >>>>> Normal User
,E/dalvikvm( 3301): >>>>> com.android.email [ userId:0 | appId:10155 ]
,I/qcom-bluetooth( 3308): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,E/SELinux ( 3301): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3301): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3301): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3301): Added TimaKesytore provider
,I/qcom-bluetooth( 3318): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3319): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3320): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3322): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/SensorService(  739):   -0.0 -0.1 9.6
,D/RCPManagerService(  739): exchangeData() failure , invalid userId
,D/AndroidRuntime( 3277): 
D/AndroidRuntime( 3277): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3277): CheckJNI is OFF
,D/RCPManagerService(  739): exchangeData() failure , invalid userId
,D/AndroidRuntime( 3277): setted country_code = Poland
,D/AndroidRuntime( 3277): setted countryiso_code = PL
,D/RCPManagerService(  739): exchangeData() failure , invalid userId
D/AndroidRuntime( 3277): setted sales_code = XEO
D/AndroidRuntime( 3277): readGMSProperty: start
,D/AndroidRuntime( 3277): readGMSProperty: already setted!!
D/AndroidRuntime( 3277): readGMSProperty: end
,D/AndroidRuntime( 3277): addProductProperty: start
,D/dalvikvm( 3277): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3277): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3277): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3277): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3277): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/RCPManagerService(  739): exchangeData() failure , invalid userId
,E/memtrack( 3277): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3277): failed to load memtrack module: -2
,D/dalvikvm(  739): GC_EXPLICIT freed 1326K, 17% free 22777K/27396K, paused 4ms+12ms, total 122ms
,D/BadgeProvider( 1345): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
W/ActivityManager(  739): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/Launcher.Model( 1250): reloadBadges entered.
D/BadgeProvider( 1345): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1345): sendNotify, [notify] : null
D/BadgeProvider( 1345): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1345): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1345): update, [UpdateCount] : 1
,D/dalvikvm( 3277): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,I/SELinux ( 3344): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3344):  
I/ActivityManager(  739): Killing 1183:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
,D/AndroidRuntime( 3277): Calling main entry com.android.commands.pm.Pm
I/SELinux ( 3344): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3344):  
I/SELinux ( 3344):  
,I/SELinux ( 3344): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3344): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3344): >>>>> Normal User
,E/dalvikvm( 3344): >>>>> com.android.exchange [ userId:0 | appId:10156 ]
,E/SELinux ( 3344): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/ActivityManager(  739): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 3344): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3344): Cannot add TimaSignature Service, License check Failed
,D/PackageManagerService(  739): deletePackageAsUser- pkg:com.example.hello, userId:0
D/ActivityThread( 3344): Added TimaKesytore provider
D/PersonaManagerService(  739): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService(  739): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  739): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  739): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  739): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManagerService(  739): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManager(  739): START PACKAGE DELETE: observer{1122722448}
D/PackageManager(  739): pkg{<packageName>}
D/PackageManager(  739): user{0}
D/PackageManager(  739): deletePackageAsUser : uid = 2000 userId = 0
,D/PackageManager(  739): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  739): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  739): getApplicationUninstallationEnabled
D/ApplicationPolicy(  739): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  739): deletePackageX- pkg:com.example.hello, userId:0
,I/Process ( 3301): Sending signal. PID: 3301 SIG: 9
,I/ActivityManager(  739): Process com.android.email (pid 3301) (adj 9) has died.
,D/PackageManager(  739): !@killApplicatoin: 10180, uninstall pkg
,I/ActivityManager(  739): Killing 2708:com.example.hello/u0a180 (adj 0): stop com.example.hello
,E/SMD     (  240): DCD ON
,I/SurfaceFlinger(  246): id=15 Removed NainActivit (7/10)
,I/SurfaceFlinger(  246): id=15 Removed NainActivit (-2/10)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  246): id=15 Removed NainActivit (-2/10)
I/WindowState(  739): WIN DEATH: Window{422aaee8 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  739): Skipping PackageSetting{425a99d0 com.test.thalitest/10179} due to missing metadata
,D/PackageManager(  739): queryIntentReceivers - Execution time: 110 ms
D/LockPatternUtils( 1066): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2047): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2047): getDatabaseLocked(b,b,pwd)...
W/ActivityManager(  739): Force removing ActivityRecord{430c8600 u0 com.example.hello/.MainActivity t3}: app died, no saved state
D/PackageManager(  739): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10180, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/CustomFrequencyManagerService(  739): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 739  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  739): mDVFSHelper.acquire()
,D/LockPatternUtils( 1066): isPcwEnable = null
,D/SurfaceWidgetView( 1250): destroyHardwareResources():1125418360
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/Launcher( 1250): onRestart, Launcher: 1113483976
D/Launcher( 1250): onStart, Launcher: 1113483976
,D/Launcher.HomeView( 1250): onStart
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1476): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1476): [237392/5] SurfaceWidget drawing first frame
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/PackageManager(  739): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10180, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/SurfaceFlinger(  246): id=16 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  246): id=17 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/FPMS_FingerprintManagerService( 1085): onReceive: android.intent.action.PACKAGE_REMOVED
,D/AdaptiveEventManager( 1066): action=android.intent.action.PACKAGE_REMOVED
,D/QuickConnect[1.1][2] ( 3203): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.example.hello
,I/InputReader(  739): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 1408): GC_EXPLICIT freed 4144K, 46% free 9988K/18456K, paused 3ms+7ms, total 56ms
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  739):   Scheme: "sms"
,W/GeofencerStateMachine( 1209): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "smsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mms"
D/CustomFrequencyManagerService(  739): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 739  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  739): mDVFSHelper.release()
D/CustomFrequencyManagerService(  739): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 739  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService(  739): PackageReceiver onReceive()
,I/HarmonyEASService(  739): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mmsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3363): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3363):  
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "sms"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3367): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3367):  
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/SELinux ( 3363): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3363):  
I/SELinux ( 3363):  
,I/SELinux ( 3363): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3363): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3363): >>>>> Normal User
,E/dalvikvm( 3363): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 3363): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "smsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 3363): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3363): Cannot add TimaSignature Service, License check Failed
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mms"
,D/ActivityThread( 3363): Added TimaKesytore provider
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3367): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3367):  
I/SELinux ( 3367):  
,I/SELinux ( 3367): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3367): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3367): >>>>> Normal User
,E/dalvikvm( 3367): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 3367): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mmsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 3367): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3367): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3367): Added TimaKesytore provider
,I/ActivityManager(  739): Killing 2327:com.sec.pcw.device/1000 (adj 15): empty #43
,D/EnterpriseDeviceManagerService(  739): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  739): Admin package name: com.google.android.gms
,D/dalvikvm(  739): GC_EXPLICIT freed 1896K, 17% free 22866K/27396K, paused 6ms+18ms, total 311ms
D/PackageManager(  739): delete sourFile : 
,D/PackageManager(  739): delete native library directory: 
,D/PackageManager(  739): return delete result to caller: 1122722448
,D/AndroidRuntime( 3277): Shutting down VM
,D/PackageManager(  739): returnCode: 1
D/dalvikvm( 3277): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
,D/BackupManagerService(  739): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  739): removePackageParticipantsLocked: uid=10180 #1
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "sms"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3390): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3390):  
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager(  739): Killing 2353:com.vlingo.midas/u0a33 (adj 15): empty #43
,D/dalvikvm(  249): GC_EXPLICIT freed 46K, 49% free 9509K/18456K, paused 2ms+3ms, total 29ms
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "smsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3390): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3390):  
I/SELinux ( 3390):  
,I/SELinux ( 3390): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3390): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3390): >>>>> Normal User
,E/dalvikvm( 3390): >>>>> com.sec.modem.settings [ userId:0 | appId:1000 ]
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9509K/18456K, paused 2ms+3ms, total 20ms
,E/SELinux ( 3390): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mms"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService(  739): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 3390): in addTimaSignatureService
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 49% free 9509K/18456K, paused 2ms+2ms, total 21ms
D/TimaKeyStoreProvider( 3390): Cannot add TimaSignature Service, License check Failed
,D/RCPManagerService(  739): exchangeData() failure , invalid userId
,D/ActivityThread( 3390): Added TimaKesytore provider
,D/RCPManagerService(  739): exchangeData() failure , invalid userId
I/PackageManager(  739):   Action: "android.intent.action.SENDTO"
I/PackageManager(  739):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  739):   Scheme: "mmsto"
I/PackageManager(  739): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Process ( 3344): Sending signal. PID: 3344 SIG: 9
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 3406): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3406):  
,D/BadgeProvider( 1345): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/ActivityManager(  739): Killing 2466:com.sec.android.app.shealth/u0a35 (adj 15): empty #43
,D/BadgeProvider( 1345): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1345): sendNotify, [notify] : null
,D/BadgeProvider( 1345): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1345): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1345): update, [UpdateCount] : 1
,I/ActivityManager(  739): Process com.android.exchange (pid 3344) (adj 9) has died.
D/Launcher.Model( 1250): reloadBadges entered.
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 3406): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3406):  
I/SELinux ( 3406):  
,I/SELinux ( 3406): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3406): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3406): >>>>> Normal User
,E/dalvikvm( 3406): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 3406): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/RCPManagerService(  739): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 3406): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3406): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3406): Added TimaKesytore provider
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager(  739): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  739): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector(  739): onPackageRemoved : com.example.hello
D/UsbSettingsManager(  739): clearDefaults: com.example.hello
,I/qcom-bluetooth( 3422): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 38:94:96:b5:06:dc 
,I/qcom-bluetooth( 3423): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/InputReader(  739): Processing first event
,I/EventHub(  739): Removing device sec_touchscreen due to epoll hang-up event.
,I/EventHub(  739): Removed device: path=/dev/input/event1 name=sec_touchscreen id=6 fd=216 classes=0x94
,W/ApplicationsProvider( 1408): Could not fetch usage stats
W/ApplicationsProvider( 1408): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1408): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1408): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1408): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1408): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1408): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1408): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1408): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1408): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1408): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1408): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/CustomFrequencyManagerService(  739): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 739  tag : ACTIVITY_RESUME_BOOSTER@9

```
