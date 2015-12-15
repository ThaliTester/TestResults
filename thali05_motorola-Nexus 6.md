#### Test 5038801913f4183_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
W/ResourcesManager( 3193): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3193): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  820): Start proc 3237:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  820): Killing 2794:com.google.android.talk/u0a61 (adj 15): empty #17
--------- beginning of main
I/GAV2    ( 2931): Thread[GAThread,5,main]: No campaign data found.
I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
W/ResourcesManager( 3237): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 3193): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
V/GmsNetworkLocationProvi( 1797): DISABLE
I/ProviderInstaller( 3193): Installed default security provider GmsCore_OpenSSL
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  820): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  820): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/GmsNetworkLocationProvi( 1797): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
V/GLSActivity( 1415): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  820): Explicit concurrent mark sweep GC freed 15077(738KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.290ms total 48.743ms
V/BackupManagerService(  820): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  820): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2016d4f1
V/GmsNetworkLocationProvi( 1797): ENABLE
V/GmsNetworkLocationProvi( 1797): SET-REQUEST
V/GmsNetworkLocationProvi( 1797): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
V/BackupManagerService(  820): Scheduling immediate backup pass
V/BackupManagerService(  820): Running a backup pass
V/BackupManagerService(  820): clearing pending backups
V/PerformBackupTask(  820): Beginning backup of 14 targets
D/PerformBackupTask(  820): invokeAgentForBackup on @pm@
V/BackupServiceBinder(  820): doBackup() invoked
I/PMBA    (  820): Previous metadata 1570415 mismatch vs 1743759 - rewriting
I/BackupRestoreController(  820): Getting widget state for user: 0
W/GmsBackupTransport( 1797): Unknown package in backup request: @pm@
V/GmsBackupTransport( 1797): starting performBackup for @pm@
V/GmsBackupTransport( 1797): performBackup done for @pm@
W/ContextImpl( 3031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
V/GLSActivity( 1415): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f09dc6b:true
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/GLSUser ( 1415): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1415): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1415): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1415): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/BluetoothAdapter( 2157): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 3031): Adding local A2DP profile
D/AuthorizationBluetoothService( 1415): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  820): Message: 30
V/GLSActivity( 1415): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 2157): getBluetoothService() called with no BluetoothManagerCallback
I/BtOppRfcommListener( 2157): Accept thread started.
D/LocalBluetoothProfileManager( 3031): Adding local HEADSET profile
D/BluetoothManagerService(  820): Message: 30
D/BluetoothManagerService(  820): Message: 30
D/BluetoothManagerService(  820): Message: 30
W/GLSActivity( 1415): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1415): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1415): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1415): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1415): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1415): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1415): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1797): Error sending final backup to server: 
W/GmsBackupTransport( 1797): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1797): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1797): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1797): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1797): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1797): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1797): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1797): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1797): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1797): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1797): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1797): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1797): 	... 1 more
D/BackupManagerService(  820): Now staging backup of com.google.android.talk
V/MusicLeanback( 3051): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/LocalBluetoothProfileManager( 3031): Adding local MAP profile
D/BluetoothMap( 3031): Create BluetoothMap proxy object
D/BluetoothManagerService(  820): Message: 30
D/BluetoothManagerService(  820): Message: 30
D/LocalBluetoothProfileManager( 3031): LocalBluetoothProfileManager construction complete
D/BackupManagerService(  820): Now staging backup of com.google.android.dialer
D/BackupManagerService(  820): Now staging backup of com.android.providers.settings
D/BackupManagerService(  820): Now staging backup of com.android.sharedstoragebackup
D/BackupManagerService(  820): Now staging backup of com.google.android.gm
D/BackupManagerService(  820): Now staging backup of com.android.providers.userdictionary
D/BackupManagerService(  820): Now staging backup of com.google.android.apps.genie.geniewidget
I/ActivityManager(  820): Start proc 3281:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
D/BackupManagerService(  820): Now staging backup of com.android.nfc
D/DockEventReceiver( 3031): finishStartingService: stopping service
D/BluetoothA2dp( 3031): Proxy object connected
D/BackupManagerService(  820): Now staging backup of com.google.android.marvin.talkback
D/BackupManagerService(  820): Now staging backup of com.android.vending
D/A2dpProfile( 3031): Bluetooth service connected
D/BluetoothInputDevice( 3031): Proxy object connected
I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 616us total 9.805ms
D/BackupManagerService(  820): Now staging backup of com.google.android.calendar
D/HidProfile( 3031): Bluetooth service connected
D/BackupManagerService(  820): Now staging backup of com.google.android.inputmethod.latin
D/BluetoothPan( 3031): BluetoothPAN Proxy object connected
D/PanProfile( 3031): Bluetooth service connected
D/BluetoothMap( 3031): Proxy object connected
D/MapProfile( 3031): Bluetooth service connected
D/BluetoothMap( 3031): getConnectedDevices()
D/BackupManagerService(  820): Now staging backup of android
D/BluetoothPbap( 3031): Proxy object connected
D/PbapServerProfile( 3031): Bluetooth service connected
D/BackupManagerService(  820): Now staging backup of com.google.android.googlequicksearchbox
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 9.184ms
I/GmsBackupTransport( 1797): Next backup will happen in 43199946 millis.
I/BackupManagerService(  820): Backup pass finished.
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 8.379ms
D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset( 3031): Proxy object connected
D/HeadsetProfile( 3031): Bluetooth service connected
I/ActivityManager(  820): Start proc 3308:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  820): Killing 2847:com.google.android.deskclock/u0a44 (adj 15): empty #17
D/SprintDMReceiver( 3308): Received intent: android.net.conn.CONNECTIVITY_CHANGE
D/SprintDMHelper( 3308): simOperator:  IMSI: null
D/SprintDMReceiver( 3308): Not Sprint UICC, don't do anything.
,I/ActivityManager(  820): Killing 2910:com.google.android.gms:car/u0a11 (adj 15): empty #17
I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1771): onCreate
D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1771): active receiver: enabled
I/SystemUpdateService( 1771): showing system update notification
I/ValidateNoPeople(  820): skipping global notification
V/SystemUpdateService( 1771): retry (wakeup: false) in 3599980 ms
D/SystemUpdateService( 1771): onDestroy
I/iu.SyncManager( 1771): SYNC; picasa accounts
I/MediaStoreImporter( 3051): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  820): Killing 2931:com.google.android.gm/u0a78 (adj 15): empty #17
D/NetworkLogImpl( 1771): Loaded NetworkSpeedPredictor
I/iu.Environment( 1771): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1771): num queued entries: 0
I/iu.UploadsManager( 1771): num updated entries: 0
I/iu.SyncManager( 1771): NEXT; no task
D/AndroidRuntime( 3325): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3325): CheckJNI is OFF
D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/AndroidRuntime( 3325): Calling main entry com.android.commands.am.Am
I/ActivityManager(  820): Start proc 3348:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{2766f035 token=Token{22e2126c ActivityRecord{3e9e0f1f u0 com.example.hello/.MainActivity t26}}} to stack=1 task=26 at 0
V/WindowManager(  820): Adding window Window{1d15bb96 u0 Starting com.example.hello} at 2 of 7 (after Window{1fa5637b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3325): Shutting down VM
I/HotwordDetector( 1514): Closing mic
I/MicrophoneInputStream( 1514): mic_close com.google.android.apps.gsa.speech.audio.u@37103538
D/GCM     ( 1415): Connected
I/ActivityManager(  820): Start proc 3367:com.example.hello/u0a273 for activity com.example.hello/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1514): Hotword detection finished
I/HotwordRecognitionRnr( 1514): Stopping hotword detection.
D/GCM     ( 1415): Message class com.google.f.a.a.p
W/ResourcesManager( 3348): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/GLSUser ( 1415): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1415): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1415): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1415): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1415): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Kids    ( 1771): [AccountUtils] Account not ready
W/Kids    ( 1771): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1771): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1771): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1771): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1771): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1771): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1771): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1771): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1771): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager(  820): Killing 2965:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
I/WebViewFactory( 3367): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659528467
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/LibraryLoader( 3367): Time to load native libraries: 1 ms (timestamps 6698-6699)
I/LibraryLoader( 3367): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3367): Binding Chromium to main looper Looper (main, tid 1) {3e3d32b1}
I/LibraryLoader( 3367): Expected native library version number "",actual native library version number ""
I/chromium( 3367): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3367): Initializing chromium process, singleProcess=true
W/art     ( 3367): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3367): ApplicationContext is null in ApplicationStatus
W/chromium( 3367): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3367): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3367): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3367): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
I/art     ( 1415): Explicit concurrent mark sweep GC freed 12411(671KB) AllocSpace objects, 5(362KB) LOS objects, 37% free, 26MB/42MB, paused 713us total 21.874ms
I/Babel_SMS( 3348): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3348): MmsConfig.loadMmsSettings
I/Babel_SMS( 3348): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 3348): MmsConfig.loadFromDatabase
D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@179188ff:true
E/Babel_SMS( 3348): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3348): MmsConfig.loadFromResources
E/Babel_SMS( 3348): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 3348): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
W/art     ( 3367): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3367): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3367): CordovaWebView is running on device made by: motorola
W/art     ( 3367): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3367): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  820): Explicit concurrent mark sweep GC freed 16387(905KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.122ms total 54.470ms
D/OpenGLRenderer( 3367): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3367): Validating map...
V/WindowManager(  820): Adding window Window{2ab65c0b u0 com.example.hello/com.example.hello.MainActivity} at 2 of 8 (before Window{1d15bb96 u0 Starting com.example.hello})
W/chromium( 3367): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/Settings( 3348): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 3348): startup - clean
I/OpenGLRenderer( 3367): Initialized EGL, version 1.4
D/OpenGLRenderer( 3367): Enabling debug mode 0
I/Keyboard.Facilitator( 1214): onFinishInput()
I/Babel   ( 3348): deleted: false for 0
I/ActivityManager(  820): Displayed com.example.hello/.MainActivity: +540ms
I/Babel_telephony( 3348): TeleModule.launchCompleted
W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
I/Babel_telephony( 3348): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 3348): BAM#gBA: invalid account id: -1
W/Babel   ( 3348): BAM#gBA: invalid account id: -1
I/Babel_telephony( 3348): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
W/BindingManager( 3367): Cannot call determinedVisibility() - never saw a connection for the pid: 3367
I/chromium( 3367): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager(  820): Start proc 3433:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
W/VideoCapabilities( 3348): Unrecognized profile 2130706433 for video/avc
D/JsMessageQueue( 3367): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3367): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/VideoCapabilities( 3348): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 3348): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3348): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3348): Unrecognized profile 2130706433 for video/avc
I/GAv4    ( 3433): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3433):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3433):   adb logcat -s GAv4
W/GAv4    ( 3433): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/VideoCapabilities( 3348): Unrecognized profile 2130706433 for video/avc
W/GAv4    ( 3433): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/vclib   ( 3348): onServiceConnected
W/Babel   ( 3348): Attempted to change video mute state without an active call.
W/GAv4    ( 3433): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/jxcore_app_log( 3367): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576526208
D/JX-Cordova( 3367): jxcore cordova android initializing
W/jxcore-log( 3367): Initializing JXcore engine
W/jxcore-log( 3367): JXcore engine is ready
W/jxcore-log( 3367): Starting JXcore engine
W/m.example.hello( 3367): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9690]" dev="sockfs" ino=9690 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3367): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3367): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10725]" dev="sockfs" ino=10725 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3367): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21252]" dev="sockfs" ino=21252 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/Babel   ( 3348): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  820): Killing 2828:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
I/WebViewFactory( 3433): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3433): Time to load native libraries: 1 ms (timestamps 7373-7374)
I/LibraryLoader( 3433): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3433): Binding Chromium to main looper Looper (main, tid 1) {3c709b8a}
I/LibraryLoader( 3433): Expected native library version number "",actual native library version number ""
I/chromium( 3433): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/jxcore-log( 3367): Platform android
W/jxcore-log( 3367): 
W/jxcore-log( 3367): Process ARCH arm
W/jxcore-log( 3367): 
I/BrowserStartupController( 3433): Initializing chromium process, singleProcess=true
W/art     ( 3433): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3433): ApplicationContext is null in ApplicationStatus
W/chromium( 3433): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3433): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3433): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3433): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
I/jxcore-log( 3367): JXcore Cordova bridge is ready!
I/jxcore-log( 3367): 
W/jxcore-log( 3367): JXcore engine is started
E/jxcore-log( 3367): >> motorola-Nexus 6
E/jxcore-log( 3367): 
I/jxcore-log( 3367): Total memory 3113791488
I/jxcore-log( 3367): 
I/jxcore-log( 3367): Free memory 1015341056
I/jxcore-log( 3367): 
I/jxcore-log( 3367): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3367): 
I/jxcore-log( 3367): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3367): 
W/AudioManagerAndroid( 3433): Requires BLUETOOTH permission
I/jxcore-log( 3367): userPath [ 'www' ]
I/jxcore-log( 3367): 
I/jxcore-log( 3367): Size 1440 2392
I/jxcore-log( 3367): 
I/jxcore-log( 3367): Screen Brightness 82
I/jxcore-log( 3367): 
E/jxcore-log( 3367): Dummy Error Log.
E/jxcore-log( 3367): 
I/NSApplication( 3433): Starting up...
I/ActivityManager(  820): Start proc 3494:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  820): Killing 2090:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/ActivityManager(  820): Waited long enough for: ServiceRecord{1960a45 u0 org.simalliance.openmobileapi.service/.SmartcardService}
,I/jxcore-log( 3367): getBuffer is called!!!!
I/jxcore-log( 3367): 
,I/ActivityManager(  820): Start proc 3515:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  820): Killing 2998:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/ActivityManager(  820): Waited long enough for: ServiceRecord{37a3db81 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,I/ActivityManager(  820): Killing 3126:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 3534:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  820): Waited long enough for: ServiceRecord{229a031a u0 com.qualcomm.atfwd/.AtFwdService}
,I/ActivityManager(  820): Start proc 3556:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/ConfigService( 1415): onDestroy
,I/ActivityManager(  820): Killing 3146:com.android.musicfx/u0a18 (adj 15): empty #17
,D/TimeService( 3556): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450199024311
D/        ( 3556): TimeServiceNative: User Time to be set is 1450199024312
,D/QC-time-services( 3556): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3556): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3556): Lib:time_genoff_operation: pargs->ts_val = 1450199024312
D/QC-time-services(  374): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3556): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  374): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450199024312
,D/QC-time-services(  374): Daemon:genoff_opr: Base = 2, val = 1450199024312, operation = 0
D/QC-time-services(  374): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/2/70 13:16:34
,D/QC-time-services(  374): Daemon:Value read from RTC seconds = 10502194000
,D/QC-time-services(  374): Daemon:new time 1450199024312 
D/QC-time-services(  374): Daemon: delta 1439696830312 genoff 1439696830312 
,D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696830312 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  374): Updating the TOD offset
,D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696830312 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  374): Daemon:Update to modem bit set,
D/QC-time-services(  374): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  374): Daemon: Base = 2, Value being sent to MODEM = 1134234224312
,E/QC-time-services( 3556): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  374): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  374): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  820): Killing 3166:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 3576:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/art     ( 1771): Explicit concurrent mark sweep GC freed 33172(2MB) AllocSpace objects, 17(295KB) LOS objects, 35% free, 29MB/45MB, paused 1.844ms total 56.718ms
,I/GAv4    ( 3576): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3576):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3576):   adb logcat -s GAv4
,W/GAv4    ( 3576): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3576): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3576): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Killing 3193:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/Atfwd_Daemon(  376): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  376): ATFWD --> QMI Port : rmnet_usb0
,V/Herrevad( 1771): NQAS connected
,I/Atfwd_Daemon(  376): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  376): Trying to register 8 commands:
I/Atfwd_Daemon(  376): cmd0: +CKPD
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd1: +CTSA
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0,
I/Atfwd_Daemon(  376): cmd2: +CFUN
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0,
I/Atfwd_Daemon(  376): cmd3: +CMAR
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0,
I/Atfwd_Daemon(  376): cmd4: +CDIS
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd5: +CRSL
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd6: +CSS
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd7: $QCPWRDN
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): Registered AT Commands event handler
,D/GCM     ( 1415): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  820): Start proc 3610:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/GLSUser ( 1415): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1415): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1415): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1415): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1415): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1771): [AccountUtils] Account not ready
W/Kids    ( 1771): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1771): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1771): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1771): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1771): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1771): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1771): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1771): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1771): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 3610): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3610): Created com.android.providers.calendar.CalendarAlarmManager@280e2158(com.android.providers.calendar.CalendarProvider2@3e3d32b1)
,D/GCM     ( 1415): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/SQLiteLog( 3610): (284) automatic index on view_events(_id)
,D/AuthorizationBluetoothService( 1415): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1771): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  820): Start proc 3631:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,I/art     (  820): Explicit concurrent mark sweep GC freed 14891(709KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 1.365ms total 47.472ms
,D/LocationInitializer( 1771): Restart initialization of location
,I/art     (  369): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 325us total 27.616ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 316us total 13.383ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 319us total 13.032ms
,I/ActivityManager(  820): Start proc 3651:com.google.android.gm/u0a78 for broadcast com.google.android.gm/.widget.GmailWidgetProvider
,W/ResourcesManager( 3631): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3631): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3631): VM with version 2.1.0 has multidex support
I/MultiDex( 3631): install
I/MultiDex( 3631): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3631): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3631): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 3631): callingUid 10011, callindPid: 3631
,D/ActivityThread( 3651): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/Gmail   ( 3651): getAccountsCursor
,E/MDM     ( 1797): [157] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/GLSActivity( 1415): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  820): Start proc 3675:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,W/ActivityManager(  820): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 3651): Observing account changes for notifications
,I/Exchange( 3675): EasService.onCreate
,I/Exchange( 3675): RestartPingTask
W/GAV2    ( 3651): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 3651): getAccountsCursor
,V/GLSActivity( 1415): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 3675): RestartPingsTask did not start any pings.
I/Exchange( 3675): PSS stopIfIdle
I/Exchange( 3675): PSS has no active accounts; stopping service.
,I/Exchange( 3675): onDestroy
,D/GCM     ( 1415): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1415): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1771): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1797): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1771): Restart initialization of location
,E/SQLiteLog( 3651): (283) recovered 52 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/PackageBroadcastService( 1771): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1771): Null package name or gms related package.  Ignoreing.
,I/art     ( 1415): Explicit concurrent mark sweep GC freed 16352(775KB) AllocSpace objects, 5(551KB) LOS objects, 37% free, 26MB/42MB, paused 1.492ms total 25.543ms
I/UpdateIcingCorporaServi( 1514): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/ResourcesManager( 3348): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3348): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 1771): updateResources: need to parse f{com.google.android.gms}
,W/Launcher( 1284): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@36f3c370 new=com.google.android.velvet.VelvetApplication@36f3c370
,I/UpdateIcingCorporaServi( 1514): UpdateCorporaTask done [took 56 ms] updated apps [took 56 ms] 
,V/JNIHelp ( 3348): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/Gmail   ( 3651): notifyAccountChanged
,I/Gmail   ( 3651): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3651): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ProviderInstaller( 3348): Installed default security provider GmsCore_OpenSSL
,I/Gmail   ( 3651): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3651): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Babel_telephony( 3348): TeleIncomingWifiCallController.getRegistrationState, wifi calling not enabled
,W/VideoCapabilities( 3348): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3348): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3348): Unrecognized profile 2130706433 for video/avc
,V/GLSActivity( 1415): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3651): getAccountsCursor
,I/ActivityManager(  820): Delay finish: com.google.android.apps.photos/.actionqueue.InternalReceiver
,I/NotifUtils( 3651): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/Gmail   ( 3651): getAccountsCursor
,V/GLSActivity( 1415): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  820): Resuming delayed broadcast
,I/ActivityManager(  820): Delay finish: com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal
I/NotifUtils( 3651): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,I/ActivityManager(  820): Resuming delayed broadcast
,I/MusicLeanback( 3051): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3051): Stop autocaching.
,E/GmsUtils( 3051): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3051): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/GCM     ( 1415): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1415): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1771): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1797): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1771): Restart initialization of location
,I/ActivityManager(  820): Killing 3031:com.android.settings/1000 (adj 15): empty #17
,I/CalendarProvider2( 3610): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3610): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  820): Killing 2537:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/GLSUser ( 1415): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1415): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1415): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1415): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1415): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 3348): UserRecoverableAuthException.
E/Babel   ( 3348): eei: BadAuthentication
E/Babel   ( 3348): 	at eeg.a(Unknown Source)
E/Babel   ( 3348): 	at eeg.a(Unknown Source)
E/Babel   ( 3348): 	at eeg.a(Unknown Source)
E/Babel   ( 3348): 	at g.a(Unknown Source)
E/Babel   ( 3348): 	at cae.a(SourceFile:3089)
E/Babel   ( 3348): 	at cae.a(SourceFile:1131)
E/Babel   ( 3348): 	at cws.a(SourceFile:4333)
E/Babel   ( 3348): 	at cws.a(SourceFile:1419)
E/Babel   ( 3348): 	at crl.a(SourceFile:492)
E/Babel   ( 3348): 	at crl.a(SourceFile:1468)
E/Babel   ( 3348): 	at cqu.a(SourceFile:4416)
E/Babel   ( 3348): 	at cas.b(SourceFile:106)
E/Babel   ( 3348): 	at cap.d(SourceFile:335)
E/Babel   ( 3348): 	at caq.run(SourceFile:81)
,E/Babel   ( 3348): Error getting auth token
E/Babel   ( 3348): dvm
E/Babel   ( 3348): 	at g.a(Unknown Source)
E/Babel   ( 3348): 	at cae.a(SourceFile:3089)
E/Babel   ( 3348): 	at cae.a(SourceFile:1131)
E/Babel   ( 3348): 	at cws.a(SourceFile:4333)
E/Babel   ( 3348): 	at cws.a(SourceFile:1419)
E/Babel   ( 3348): 	at crl.a(SourceFile:492)
E/Babel   ( 3348): 	at crl.a(SourceFile:1468)
E/Babel   ( 3348): 	at cqu.a(SourceFile:4416)
E/Babel   ( 3348): 	at cas.b(SourceFile:106)
E/Babel   ( 3348): 	at cap.d(SourceFile:335)
E/Babel   ( 3348): 	at caq.run(SourceFile:81)
,E/Babel   ( 3348): Account registration failed 1-Redacted-21
,E/Babel   ( 3348): cyp: null -- null
E/Babel   ( 3348): 	at cae.a(SourceFile:3121)
E/Babel   ( 3348): 	at cae.a(SourceFile:1131)
,E/Babel   ( 3348): 	at cws.a(SourceFile:4333)
E/Babel   ( 3348): 	at cws.a(SourceFile:1419)
E/Babel   ( 3348): 	at crl.a(SourceFile:492)
E/Babel   ( 3348): 	at crl.a(SourceFile:1468)
E/Babel   ( 3348): 	at cqu.a(SourceFile:4416)
E/Babel   ( 3348): 	at cas.b(SourceFile:106)
E/Babel   ( 3348): 	at cap.d(SourceFile:335)
E/Babel   ( 3348): 	at caq.run(SourceFile:81)
,I/art     ( 3348): Note: end time exceeds epoch: 
,I/GLSUser ( 1415): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1415): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1415): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1415): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1415): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 15553(793KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.365ms total 69.831ms
,W/ResourcesManager( 1415): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/Babel   ( 3348): Unexpected exception while authenticating.
,E/Babel   ( 3348): eej: User intervention required. Notification has been pushed.
E/Babel   ( 3348): 	at eeg.b(Unknown Source)
E/Babel   ( 3348): 	at eeg.b(Unknown Source)
E/Babel   ( 3348): 	at g.a(Unknown Source)
E/Babel   ( 3348): 	at cae.b(SourceFile:1146)
E/Babel   ( 3348): 	at dcg.run(SourceFile:5617)
E/Babel   ( 3348): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 3348): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 3348): 	at java.lang.Thread.run(Thread.java:818)
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  820): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@b3effd4 mBinding = false
,D/BluetoothManagerService(  820): Message: 2
,D/BluetoothManagerService(  820): Sending off request.
,D/BluetoothAdapterState( 2157): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2157): Setting state to 13
I/BluetoothAdapterState( 2157): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2157): onBluetoothDisable()
D/BluetoothManagerService(  820): Message: 60
I/BluetoothAdapterState( 2157): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 12 -> 13
,D/WifiService(  820): New client listening to asynchronous messages
D/WifiService(  820): setWifiEnabled: false pid=3367, uid=10273
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothMapService( 2157): onReceive
D/BluetoothMapService( 2157): STATE_TURNING_OFF
D/BluetoothMapService( 2157): MAP Service closeService in
,D/BluetoothMapMasInstance( 2157): MAP Service shutdown
V/BluetoothMapMasInstance( 2157): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2157): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2157): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2157): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2157): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2157): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2157): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2157): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,I/BtOppRfcommListener( 2157): stopping Accept Thread
E/BtOppRfcommListener( 2157): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 2157): BluetoothSocket listen thread finished
,I/jxcore-log( 3367): ****TEST TOOK:  5110  ms ****
I/jxcore-log( 3367): 
I/jxcore-log( 3367): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3367): 
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1415): Read error: ssl=0xb4b9d400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1415): SSL shutdown failed: ssl=0xb4b9d400: I/O error during system call, Broken pipe
,I/ActivityManager(  820): Start proc 3766:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/BluetoothAdapterProperties( 2157): Scan Mode:20
D/BluetoothAdapterState( 2157): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/btif_config_util( 2157): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-btif ( 2157): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2157): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2157): L2CAP - PSM: 0x0017 not found for deregistration
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  820): scanCount==0 - aborting,
,D/WifiScanningService(  820): SCAN_AVAILABLE : 1,
,D/RttService(  820): SCAN_AVAILABLE : 1
D/WifiScanningService(  820): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState
D/RttService(  820): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost,
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
E/WifiStateMachine(  820): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/ContextImpl( 3766): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  820): MasterInitialState.processMessage what=3
D/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8f2b8c3:true
,I/ActivityManager(  820): Start proc 3791:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,E/GpsLocationProvider(  820): No APN found to select.
,I/wpa_supplicant( 1228): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,D/BluetoothManagerService(  820): Message: 30
,D/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1261): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/wpa_supplicant( 1228): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/GpsLocationProvider(  820): No APN found to select.
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3766): Adding local MAP profile
,D/BluetoothMap( 3766): Create BluetoothMap proxy object
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3766): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3766): finishStartingService: stopping service
,D/BluetoothInputDevice( 3766): Proxy object connected
,D/HidProfile( 3766): Bluetooth service connected
,D/BluetoothPan( 3766): BluetoothPAN Proxy object connected
D/PanProfile( 3766): Bluetooth service connected
D/BluetoothMap( 3766): Proxy object connected
D/MapProfile( 3766): Bluetooth service connected
D/BluetoothMap( 3766): getConnectedDevices()
,D/BluetoothMap( 3766): Bluetooth is Not enabled
,I/ActivityManager(  820): Killing 3308:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,D/AndroidRuntime( 3786): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3786): CheckJNI is OFF
,D/bt_userial( 2157): RX termination
W/bt_userial( 2157): select_read return size <=0:-1, exiting userial_read_thread
,D/bt_userial( 2157): Leaving userial_read_thread()
,D/bt_userial( 2157): userial_close_reader Joined userial reader thread: 0,
D/bt_hwcfg( 2157): hw_epilog_process,
I/bt_userial_vendor( 2157): device fd = 53 close,
W/bt-btif ( 2157): ag scb idx 1 not allocated
E/bt-btif ( 2157): BTA AG is already disabled, ignoring ...
,W/bt-l2cap( 2157): L2CAP - PSM: 0x0019 not found for deregistration,
W/bt-l2cap( 2157): L2CAP - PSM: 0x0017 not found for deregistration,
,W/bt-l2cap( 2157): L2CAP - PSM: 0x0019 not found for deregistration,
W/bt-l2cap( 2157): L2CAP - PSM: 0x0017 not found for deregistration,
W/bt-l2cap( 2157): L2CAP - PSM: 0x0019 not found for deregistration,
,W/bt-l2cap( 2157): L2CAP - PSM: 0x0017 not found for deregistration
,D/AndroidRuntime( 3786): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  820): Force stopping com.example.hello appid=10273 user=-1: uninstall pkg
,I/ActivityManager(  820): Killing 3367:com.example.hello/u0a273 (adj 0): stop com.example.hello
,I/GKI_LINUX( 2157): gki_task task_id=0 [BTU] terminating
,W/PackageSettings(  820): Skipping PackageSetting{1e5fda54 com.test.thalitest/10265} due to missing metadata
,I/wpa_supplicant( 1228): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  820): InitialState.processMessage what=4
E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/GKI_LINUX( 2157): GKI_exit_task 0 done
I/GKI_LINUX( 2157): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2157): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,I/WindowState(  820): WIN DEATH: Window{2ab65c0b u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  820): Client connection lost with reason: 4
,W/ActivityManager(  820): Force removing ActivityRecord{3e9e0f1f u0 com.example.hello/.MainActivity t26}: app died, no saved state
,I/ActivityManager(  820): Force stopping com.example.hello appid=10273 user=0: pkg removed
,D/Tethering(  820): sendTetherStateChangedBroadcast 0, 0, 0
W/ActivityManager(  820): Spurious death for ProcessRecord{3db0cd0f 3367:com.example.hello/u0a273}, curProc for 3367: null
,D/TaskPersister(  820): removeObsoleteFile: deleting file=26_task.xml
,D/HeadsetService( 2157): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 2157): Exit Disconnected: -1,
,D/BluetoothHeadset(  820): Proxy object disconnected
,D/BluetoothHeadset( 1064): Proxy object disconnected
,D/BluetoothHeadset( 1261): Proxy object disconnected
,D/BluetoothHeadset(  820): Proxy object disconnected
D/BluetoothHeadset(  820): Proxy object disconnected
D/A2dpService( 2157): Received stop request...Stopping profile...
D/A2dpStateMachine( 2157): Exit Disconnected: -1
,I/Keyboard.Facilitator( 1214): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1214): run()
,I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
W/Settings( 3348): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1064): Explicit concurrent mark sweep GC freed 44012(1843KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 929us total 70ms
,I/Decoder ( 1214): createOrResetDecoder
D/HeadsetStateMachine( 2157): Unbinding service...
,D/BluetoothA2dp( 1064): Proxy object disconnected
W/BluetoothHeadsetServiceJni( 2157): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2157): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterState( 2157): Stopping profile services that were post enabled
W/Settings( 1797): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HidService( 2157): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 1064): Proxy object disconnected,
,D/HealthService( 2157): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 3766): Proxy object disconnected
D/HidProfile( 3766): Bluetooth service disconnected
D/PanService( 2157): Received stop request...Stopping profile...
,I/GKI_LINUX( 2157): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2157): GKI_exit_task 2 done
I/GKI_LINUX( 2157): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothPan( 1064): BluetoothPAN Proxy object disconnected
D/BtGatt.DebugUtils( 2157): handleDebugAction() action=null
D/BtGatt.GattService( 2157): Received stop request...Stopping profile...
D/BtGatt.GattService( 2157): stop()
D/BtGatt.AdvertiseManager( 2157): advertise clients cleared
D/BluetoothPan( 3766): BluetoothPAN Proxy object disconnected
D/PanProfile( 3766): Bluetooth service disconnected
D/BluetoothMapService( 2157): Received stop request...Stopping profile...
D/BluetoothMapService( 2157): stop()
,D/BluetoothMapEmailAppObserver( 2157): deinitObservers()
D/BluetoothMapEmailAppObserver( 2157): removeReceiver()
,D/BluetoothMap( 1064): Proxy object disconnected
,W/BluetoothHidServiceJni( 2157): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2157): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2157): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2157): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2157): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2157): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2157): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 2157): MAP Service closeService in
D/BluetoothAdapterState( 2157): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 2157): cleanup()
D/BluetoothAdapterProperties( 2157): Setting state to 10
D/BluetoothMapService( 2157): MAP Service closeService in
I/BluetoothAdapterState( 2157): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  820): Broadcasting onBluetoothStateChange(false) to 17 receivers.
,D/BluetoothA2dp( 1064): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 2157): Entering OffState
D/BluetoothMap( 3766): Proxy object disconnected
D/MapProfile( 3766): Bluetooth service disconnected
,D/BluetoothA2dpSink( 1064): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1064): 
E/BluetoothA2dpSink( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@bfd433c
E/BluetoothA2dpSink( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1064): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 1064): onBluetoothStateChange: up=false
,D/BluetoothHeadsetClient( 1064): onBluetoothStateChange: up=false
,E/BluetoothHeadsetClient( 1064): 
E/BluetoothHeadsetClient( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@1ba18c5
E/BluetoothHeadsetClient( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1064): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothA2dp(  820): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1261): onBluetoothStateChange: up=false
,D/StrictMode( 3791): StrictMode policy violation; ~duration=529 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3791): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3791): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3791): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3791): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3791): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3791): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3791): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3791): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3791): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3791): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3791): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3791): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3791): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
D/StrictMode( 3791): StrictMode policy violation; ~duration=528 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3791): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3791): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3791): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3791): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3791): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3791): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3791): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3791): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3791): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3791): StrictMode policy violation; ~duration=527 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3791): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3791): 	at libcore.io.BlockGuardOs.open(BlockG,uardOs.java:182)
D/StrictMode( 3791): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3791): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3791): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3791): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3791): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3791): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3791): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3791): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3791): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3791): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3791): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3791): StrictMode policy violation; ~duration=522 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3791): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3791): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3791): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3791): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3791): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3791): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3791): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3791): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3791): StrictMode policy violation; ~duration=517 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3791): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3791): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3791): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3791): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3791): 	at d,alvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3791): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3791): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3791): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3791): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3791): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3791): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/BluetoothAvrcpController( 1064): onBluetoothStateChange: up=false
D/StrictMode( 3791): StrictMode policy violation; ~duration=418 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3791): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3791): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3791): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3791): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3791): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3791): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3791): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3791): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3791): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3791): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3791): # via Binder call with stack:
D/StrictMode( 3791): android.os.StrictMode$LogStackTrace
D/StrictMode( 3791): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3791): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3791): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3791): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3791): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3791): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3791): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3791): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3791): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3791): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3791): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3791): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3791): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3791): StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3791): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3791): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3791): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3791): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3791): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3791): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3791): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3791): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3791): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3791): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3791): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3791): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3791): StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3791): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3791): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3791): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3791): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3791): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3791): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3791): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3791): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3791): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3791): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3791): StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3791): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3791): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3791): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3791): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3791): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3791): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3791): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3791): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3791): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3791): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3791): StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3791): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3791): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3791): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3791): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3791): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3791): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3791): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3791): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3791): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3791): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3791): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3791): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3791): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3791): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3791): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3791): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3791): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3791): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/BluetoothAvrcpController( 1064): 
E/BluetoothAvrcpController( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@1d26c21a
E/BluetoothAvrcpController( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1064): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
D/BluetoothMap( 1064): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1064): onBluetoothStateChange: up=false
D/BluetoothMap( 3766): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 3766): onBluetoothStateChange: up=false
D/BluetoothPbap( 3766): onBluetoothStateChange: up=false
D/BluetoothManagerService(  820): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  820): Broadcasting onBluetoothServiceDown() to 7 receivers.
D/BluetoothManagerService(  820): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@b3effd4 mBinding = false
D/BluetoothManagerService(  820): Sending unbind request.
I/ConfigService( 1415): onCreate
W/com.google.a.a.a.b.a( 3791): Application name is not set. Call Builder#setApplicationName.
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapter( 1064): 462603752: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1064): 462603752: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1064): 462603752: getState() :  mService = null. Returning STATE_OFF
I/GKI_LINUX( 2157): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2157): GKI_exit_task 1 done
I/GKI_LINUX( 2157): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2157): cleanupNative: return from cleanup
I/art     ( 2157): System.exit called, status: 0
I/AndroidRuntime( 2157): VM exiting with result code 0, cleanup skipped.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1214): run()
D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11552dde:true
W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3367 uid 10273
D/AuthorizationBluetoothService( 1415): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/Keyboard.Facilitator( 1214): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1214): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = contacts
V/MusicLeanback( 3051): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1214): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1214): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1214): run()
I/StatsUtilsManager( 1214): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1214): shouldRecordStats() = Too Soon
,I/ActivityManager(  820): Start proc 3839:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  820): Process com.android.bluetooth (pid 2157) has died
,I/art     (  820): Explicit concurrent mark sweep GC freed 24574(1549KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.772ms total 216.499ms
,W/LocationOracleImpl( 1514): Best location was null
,I/HotwordRecognitionRnr( 1514): Starting hotword detection.
,I/MicrophoneInputStream( 1514): mic_starting com.google.android.apps.gsa.speech.audio.u@1634ff3d
,I/AudioFlinger(  358): AudioFlinger's thread 0xb4075000 ready to run
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1514): mic_started com.google.android.apps.gsa.speech.audio.u@1634ff3d
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
,E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,D/Launcher.Workspace( 1284): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1284): 11683562 - stripEmptyScreens()
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,D/SprintDMReceiver( 3839): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3839): simOperator:  IMSI: null
,D/SprintDMReceiver( 3839): Not Sprint UICC, don't do anything.
,I/ActivityManager(  820): Killing 3433:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/art     ( 3786): System.exit called, status: 0
I/AndroidRuntime( 3786): VM exiting with result code 0.
,I/HotwordWorker( 1514): onReady
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/iu.Environment( 1771): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1771): num queued entries: 0
I/iu.UploadsManager( 1771): num updated entries: 0
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.SyncManager( 1771): NEXT; no task
,I/SystemUpdateService( 1771): showing system update notification
,I/Babel   ( 3348): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  820): skipping global notification
V/SystemUpdateService( 1771): retry (wakeup: false) in 3599955 ms
,I/ActivityManager(  820): Start proc 3875:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1771): onDestroy
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659528467
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/GAv4    ( 3875): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3875):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3875):   adb logcat -s GAv4
,W/GAv4    ( 3875): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 3875): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3875): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 3875): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 3875): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 3875): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 3875): Failed to open database '/data/data/com.google.android.apps.magazines/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3875): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3875): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3875): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzj$zza.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzj.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzj.zzb(Unknown Source)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzj.zzie(Unknown Source)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzj.isEmpty(Unknown Source)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzl.zzis(Unknown Source)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzl$3.run(Unknown Source)
E/SQLiteDatabase( 3875): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3875): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3875): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3875): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3875): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.measurement.MeasurementService$zzc.run(Unknown Source)
E/GAv4    ( 3875): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 3875): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 3875): Failed to open database '/data/data/com.google.android.apps.magazines/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3875): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3875): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3875): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3875): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzj$zza.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzj.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzj.zzb(Unknown Source)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzj.zzie(Unknown Source)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzj.isEmpty(Unknown Source)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzl.zzis(Unknown Source)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.analytics.internal.zzl$3.run(Unknown Source)
E/SQLiteDatabase( 3875): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3875): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3875): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3875): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3875): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3875): 	at com.google.android.gms.measurement.MeasurementService$zzc.run(Unknown Source)
,E/GAv4    ( 3875): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/GAv4    ( 3875): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3875): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 3875): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3875): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3875): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3875): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3875): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3875): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 3875): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/OpenGLRenderer( 1284): Incorrectly called buildLayer on View: ew, destroying layer...
,E/NSDepend( 3875): Could not load library: pdflib.dex.jar
E/NSDepend( 3875): java.io.FileNotFoundException: /data/data/com.google.android.apps.magazines/app_dex/pdflib.dex.jar: open failed: EROFS (Read-only file system)
E/NSDepend( 3875): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/NSDepend( 3875): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/NSDepend( 3875): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:202)
E/NSDepend( 3875): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:190)
E/NSDepend( 3875): 	at com.google.common.io.ByteSink.writeFrom(ByteSink.java:138)
E/NSDepend( 3875): 	at com.google.apps.dots.android.newsstand.NSDepend.dynamicallyLoadLibrary(NSDepend.java:1368)
E/NSDepend( 3875): 	at com.google.apps.dots.android.newsstand.NSDepend.getClassLoaderForJar(NSDepend.java:1315)
E/NSDepend( 3875): 	at com.google.apps.dots.android.newsstand.NSDepend$3.doInBackground(NSDepend.java:1348)
E/NSDepend( 3875): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:56)
E/NSDepend( 3875): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:52)
E/NSDepend( 3875): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/NSDepend( 3875): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/NSDepend( 3875): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/NSDepend( 3875): 	at com.google.android.libraries.bind.async.Queue$3$1.run(Queue.java:103)
E/NSDepend( 3875): 	at java.lang.Thread.run(Thread.java:818)
E/NSDepend( 3875): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/NSDepend( 3875): 	at libcore.io.Posix.open(Native Method)
E/NSDepend( 3875): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/NSDepend( 3875): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/NSDepend( 3875): 	... 14 more
,I/WebViewFactory( 3875): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3875): Time to load native libraries: 1 ms (timestamps 3971-3972)
I/LibraryLoader( 3875): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3875): Binding Chromium to main looper Looper (main, tid 1) {864c32c}
,I/LibraryLoader( 3875): Expected native library version number "",actual native library version number ""
,I/chromium( 3875): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3875): Initializing chromium process, singleProcess=true
W/art     ( 3875): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3875): ApplicationContext is null in ApplicationStatus
,W/chromium( 3875): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3875): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3875): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3875): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3875): Requires BLUETOOTH permission
,I/NSApplication( 3875): Starting up...
,E/SQLiteLog( 3237): (3850) statement aborts at 61: [UPDATE media_record SET upload_state=? WHERE upload_account_id != -1 AND upload_state = 200] disk I/O error
,V/MusicLeanback( 3051): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  820): Killing 3556:com.qualcomm.timeservice/1000 (adj 15): empty #17
,D/SprintDMReceiver( 3839): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3839): simOperator:  IMSI: null
D/SprintDMReceiver( 3839): Not Sprint UICC, don't do anything.
E/EsApplication( 3237): Uncaught exception in background thread Thread[iu-sync-manager,5,main]
E/EsApplication( 3237): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/EsApplication( 3237): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/EsApplication( 3237): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/EsApplication( 3237): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/EsApplication( 3237): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/EsApplication( 3237): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
E/EsApplication( 3237): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
E/EsApplication( 3237): 	at ger.a(PG:321)
E/EsApplication( 3237): 	at gdz.a(PG:307)
E/EsApplication( 3237): 	at gdz.a(PG:4414)
E/EsApplication( 3237): 	at geb.handleMessage(PG:1230)
E/EsApplication( 3237): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/EsApplication( 3237): 	at android.os.Looper.loop(Looper.java:135)
E/EsApplication( 3237): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
--------- beginning of crash
E/AndroidRuntime( 3237): FATAL EXCEPTION: iu-sync-manager
E/AndroidRuntime( 3237): Process: com.google.android.apps.plus, PID: 3237
E/AndroidRuntime( 3237): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3237): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3237): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 3237): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3237): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3237): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
E/AndroidRuntime( 3237): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
E/AndroidRuntime( 3237): 	at ger.a(PG:321)
E/AndroidRuntime( 3237): 	at gdz.a(PG:307)
E/AndroidRuntime( 3237): 	at gdz.a(PG:4414)
E/AndroidRuntime( 3237): 	at geb.handleMessage(PG:1230)
E/AndroidRuntime( 3237): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3237): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3237): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteDatabase( 1415): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1415): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 1415): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1415): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1415): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1415): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1415): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1415): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1415): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1415): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1415): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1415): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1415): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1415): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1415): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1415): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1415): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1415): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1415): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
,E/SQLiteDatabase( 1415): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1415): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1415): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1415): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1415): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1415): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteOpenHelper( 1415): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1415): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1415): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1415): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1415): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1415): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1415): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1415): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1415): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1415): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1415): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1415): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1415): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1415): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1415): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1415): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1415): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
,E/SQLiteOpenHelper( 1415): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1415): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1415): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1415): 	at java.lang.Thread.run(Thread.java:818)
I/SystemUpdateService( 1771): active receiver: enabled
I/SystemUpdateService( 1771): showing system update notification
,W/ResourcesManager(  820): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/SQLiteOpenHelper( 1415): Opened phenotype.db in read-only mode
E/SQLiteLog( 1415): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1415): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1415): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1415): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1415): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1415): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1415): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1415): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1415): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1415): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1415): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1415): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1415): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1415): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1415): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1415): 	at java.lang.Thread.run(Thread.java:818)
,E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
,D/OpenGLRenderer(  820): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  820): Validating map...
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599956 ms
,D/SystemUpdateService( 1771): onDestroy
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/OpenGLRenderer(  820): Initialized EGL, version 1.4
,D/OpenGLRenderer(  820): Enabling debug mode 0
,E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/HotwordDetector( 1514): Closing mic
I/MicrophoneInputStream( 1514): mic_close com.google.android.apps.gsa.speech.audio.u@1634ff3d
,E/Search.SharedPreferencesProto( 1514): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1514): Hotword detection finished
,I/HotwordRecognitionRnr( 1514): Stopping hotword detection.
,I/CheckinService( 1771): Done disabling old GoogleServicesFramework version
,E/SQLiteLog( 3610): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DatabaseUtils( 3610): Writing exception to parcel
E/DatabaseUtils( 3610): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 3610): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 3610): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DatabaseUtils( 3610): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 3610): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 3610): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DatabaseUtils( 3610): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DatabaseUtils( 3610): 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1351)
E/DatabaseUtils( 3610): 	,at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1109)
E/DatabaseUtils( 3610): 	at com.android.providers.calendar.CalendarProvider2.queryInternal(CalendarProvider2.java:938)
E/DatabaseUtils( 3610): 	at com.android.providers.calendar.CalendarProvider2.query(CalendarProvider2.java:839)
E/DatabaseUtils( 3610): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 3610): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 3610): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 3610): 	,at android.os.Binder.execTransact(Binder.java:446)
E/AndroidRuntime( 2411): FATAL EXCEPTION: AlertService
E/AndroidRuntime( 2411): Process: com.google.android.calendar, PID: 2411
E/AndroidRuntime( 2411): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2411): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 2411): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
,E/AndroidRuntime( 2411): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
E/AndroidRuntime( 2411): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/AndroidRuntime( 2411): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/AndroidRuntime( 2411): 	at com.android.calendar.alerts.AlarmScheduler.queryUpcomingEvents(AlarmScheduler.java:158)
E/AndroidRuntime( 2411): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:115)
E/AndroidRuntime( 2411): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:106)
E/AndroidRuntime( 2411): 	at com.android.calendar.alerts.AlertService.processMessage(AlertService.java:244)
E/AndroidRuntime( 2411): 	,at com.android.calendar.alerts.AlertService$ServiceHandler.handleMessage(AlertService.java:897)
E/AndroidRuntime( 2411): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2411): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2411): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
,I/GAV2    ( 3651): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  820): Killing 3576:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3675:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/ActivityManager(  820): Waited long enough for: ServiceRecord{365c63df u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/ConfigService( 1415): onDestroy
,E/QMI_FW  (  820): xport_send: Sendto failed for port 4352
,E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659528467
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/kickstart(  871): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
E/kickstart(  871): ERROR: function: sahara_main:1143 Sahara protocol error
E/kickstart(  871): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,E/ThermalEngine(  366): modem_clnt_error_cb: with -2 called for clnt 0x5
,E/ThermalEngine(  366): qmi_clnt_error_cb: with error -2 called for clnt FUSION
D/        (  358): csd_client_error_cb: error -2 cb_data 0xb547e060
,D/        (  358): csd_client_error_cb: MDM reset
E/        (  358): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
E/        (  358): csd_service_deinit: Error -1 deiniting CSD
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb0
,I/Atfwd_Daemon(  376): Modem Out Of Service --> Release ATCOP service client handles, if any
I/Atfwd_Daemon(  376): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb6
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb3
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb4
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb5
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb1
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb7
I/Atfwd_Daemon(  376): Received sys_event: 2 from QMI devId: rmnet_usb2
I/ThermalEngine(  366): qmi: Instance id 157 for fusion TS
,E/        (  358): csd_service_deinit: notifier handle release rc:0
,E/ThermalEngine(  366): qmi_clnt_error_cb: with error -2 called for clnt MODEM
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0

```
