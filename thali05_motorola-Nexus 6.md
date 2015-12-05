#### Test 50388019f33194e_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
W/ResourcesManager( 2952): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
--------- beginning of main
I/LibraryLoader( 1519): Time to load native libraries: 4 ms (timestamps 2887-2891)
I/LibraryLoader( 1519): Expected native library version number "",actual native library version number ""
W/art     ( 1519): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1519): Attempt to remove local handle scope entry from IRT, ignoring
I/Babel_SMS( 2952): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 2952): MmsConfig.loadMmsSettings
I/Babel_SMS( 2952): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 2952): MmsConfig.loadFromDatabase
E/Babel_SMS( 2952): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 2952): MmsConfig.loadFromResources
E/Babel_SMS( 2952): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 2952): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
W/Settings( 2952): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 2952): startup - clean
I/Babel   ( 2952): deleted: false for 0
I/Babel_telephony( 2952): TeleModule.launchCompleted
W/Telecom (  821): TelecomServiceImpl: null is not visible for the calling user
I/Babel_telephony( 2952): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 2952): BAM#gBA: invalid account id: -1
W/Babel   ( 2952): BAM#gBA: invalid account id: -1
I/Babel_telephony( 2952): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
W/Telecom (  821): TelecomServiceImpl: null is not visible for the calling user
W/VideoCapabilities( 2952): Unrecognized profile 2130706433 for video/avc
I/VideoCapabilities( 2952): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 2952): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2952): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2952): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2952): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 2952): onServiceConnected
W/Babel   ( 2952): Attempted to change video mute state without an active call.
I/ActivityManager(  821): Start proc 2999:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.FitnessBootReceiver
I/ActivityManager(  821): Killing 2486:com.motorola.motocit/u0a2 (adj 15): empty #17
I/FitnessApp( 2999): Initializers took 0 milliseconds
I/ActivityManager(  821): Start proc 3019:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
I/ActivityManager(  821): Killing 2526:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
I/GAV2    ( 2658): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4    ( 3019): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3019):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3019):   adb logcat -s GAv4
W/GAv4    ( 3019): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3019): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/AndroidRuntime( 3037): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3037): CheckJNI is OFF
W/GAv4    ( 3019): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  821): Start proc 3054:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver
I/ActivityManager(  821): Killing 1886:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
D/AndroidRuntime( 3037): Calling main entry com.android.commands.am.Am
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{314bc980 token=Token{1ed6a603 ActivityRecord{33b6e6b2 u0 com.example.hello/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3037): Shutting down VM
I/HotwordDetector( 1519): Closing mic
I/MicrophoneInputStream( 1519): mic_close com.google.android.apps.gsa.speech.audio.u@31e9c2c6
V/WindowManager(  821): Adding window Window{16e59a75 u0 Starting com.example.hello} at 3 of 8 (after Window{364fad01 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/ActivityManager(  821): Start proc 3073:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1519): Hotword detection finished
I/HotwordRecognitionRnr( 1519): Stopping hotword detection.
I/ActivityManager(  821): Killing 2558:com.google.android.onetimeinitializer/u0a15 (adj 15): empty #17
I/WebViewFactory( 3073): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660396819
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/LibraryLoader( 3073): Time to load native libraries: 5 ms (timestamps 4416-4421)
I/LibraryLoader( 3073): Expected native library version number "",actual native library version number ""
V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WebViewChromiumFactoryProvider( 3073): Binding Chromium to main looper Looper (main, tid 1) {3f2ee17d}
I/LibraryLoader( 3073): Expected native library version number "",actual native library version number ""
I/chromium( 3073): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/GLSUser ( 1543): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.chrome, service: oauth2:https://www.googleapis.com/auth/chromesync
I/GLSUser ( 1543): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chromesync without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1543): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1543): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/BrowserStartupController( 3073): Initializing chromium process, singleProcess=true
V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/art     ( 3073): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3073): ApplicationContext is null in ApplicationStatus
D/Finsky  ( 3054): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/chromium( 3073): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3073): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3073): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3073): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3073): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
W/GLSActivity( 1543): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1543): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1543): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1543): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1543): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1543): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1543): 	at android.os.Binder.execTransact(Binder.java:446)
W/AccountManagerHelper( 1238): Auth token - authenticator exception
W/AccountManagerHelper( 1238): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/AccountManagerHelper( 1238): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/AccountManagerHelper( 1238): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/AccountManagerHelper( 1238): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/AccountManagerHelper( 1238): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/AccountManagerHelper( 1238): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28d761e3:true
D/BluetoothAdapter( 3073): 156047481: getState() :  mService = null. Returning STATE_OFF
D/Finsky  ( 3054): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/art     ( 3073): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3073): onDetachedFromWindow called when already detached. Ignoring
I/ActivityManager(  821): Start proc 3132:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
D/SystemWebViewEngine( 3073): CordovaWebView is running on device made by: motorola
W/Settings( 3054): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3054): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/art     ( 3073): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3073): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3073): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Volley  ( 3054): [301] DiskBasedCache.clear: Cache cleared.
W/ResourcesManager( 3132): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3132): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Atlas   ( 3073): Validating map...
V/WindowManager(  821): Adding window Window{19b27d1a u0 com.example.hello/com.example.hello.MainActivity} at 3 of 9 (before Window{16e59a75 u0 Starting com.example.hello})
D/Volley  ( 3054): [308] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  821): Start proc 3156:com.google.android.gm/u0a78 for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver
I/ActivityManager(  821): Killing 2582:com.android.managedprovisioning/u0a17 (adj 15): empty #17
I/MultiDex( 3132): VM with version 2.1.0 has multidex support
I/MultiDex( 3132): install
I/MultiDex( 3132): VM has multidex support, MultiDex support library is disabled.
W/chromium( 3073): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/Finsky  ( 3054): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3054): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 3054): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/JNIHelp ( 3132): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 3054): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/art     (  821): Explicit concurrent mark sweep GC freed 10888(505KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.178ms total 54.689ms
I/OpenGLRenderer( 3073): Initialized EGL, version 1.4
D/OpenGLRenderer( 3073): Enabling debug mode 0
I/ProviderInstaller( 3132): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  821): Displayed com.example.hello/.MainActivity: +734ms (total +21s913ms)
W/BindingManager( 3073): Cannot call determinedVisibility() - never saw a connection for the pid: 3073
I/Keyboard.Facilitator( 1222): onFinishInput()
I/chromium( 3073): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3073): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3073): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ActivityManager(  821): Killing 1636:com.google.android.partnersetup/u0a16 (adj 15): empty #17
V/Finsky  ( 3054): [1] GearheadStateMonitor.onReady: sIsProjecting:false
D/jxcore_app_log( 3073): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576512640
D/JX-Cordova( 3073): jxcore cordova android initializing
I/Gmail   ( 3156): getAccountsCursor
V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityThread( 3156): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/jxcore-log( 3073): Initializing JXcore engine
W/jxcore-log( 3073): JXcore engine is ready
W/jxcore-log( 3073): Starting JXcore engine
V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1543): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.chrome, service: oauth2:https://www.googleapis.com/auth/userinfo.email https://www.googleapis.com/auth/userinfo.profile
I/GLSUser ( 1543): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userinfo.email https://www.googleapis.com/auth/userinfo.profile without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1543): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1543): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/m.example.hello( 3073): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12527]" dev="sockfs" ino=12527 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3073): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3073): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11819]" dev="sockfs" ino=11819 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3073): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19835]" dev="sockfs" ino=19835 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/GLSActivity( 1543): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1543): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1543): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1543): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1543): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1543): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1543): 	at android.os.Binder.execTransact(Binder.java:446)
W/AccountManagerHelper( 1238): Auth token - authenticator exception
W/AccountManagerHelper( 1238): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/AccountManagerHelper( 1238): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/AccountManagerHelper( 1238): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/AccountManagerHelper( 1238): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/AccountManagerHelper( 1238): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/AccountManagerHelper( 1238): 	at android.os.Binder.execTransact(Binder.java:446)
I/ActivityManager(  821): Start proc 3197:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
W/jxcore-log( 3073): Platform android
W/jxcore-log( 3073): 
W/jxcore-log( 3073): Process ARCH arm
W/jxcore-log( 3073): 
I/jxcore-log( 3073): JXcore Cordova bridge is ready!
I/jxcore-log( 3073): 
W/jxcore-log( 3073): JXcore engine is started
I/art     ( 1543): Explicit concurrent mark sweep GC freed 12156(684KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 627us total 23.241ms
E/jxcore-log( 3073): >> motorola-Nexus 6
E/jxcore-log( 3073): 
I/jxcore-log( 3073): Total memory 3113791488
I/jxcore-log( 3073): 
I/jxcore-log( 3073): Free memory 1028755456
I/jxcore-log( 3073): 
I/jxcore-log( 3073): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3073): 
I/jxcore-log( 3073): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3073): 
I/jxcore-log( 3073): userPath [ 'www' ]
I/jxcore-log( 3073): 
I/jxcore-log( 3073): Size 1440 2392
I/jxcore-log( 3073): 
I/jxcore-log( 3073): Screen Brightness 82
I/jxcore-log( 3073): 
E/jxcore-log( 3073): Dummy Error Log.
E/jxcore-log( 3073): 
W/GAV2    ( 3156): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Gmail   ( 3156): getAccountsCursor
W/ActivityManager(  821): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SystemBroadcastReceiver( 1222): Boot has been completed
I/SystemBroadcastReceiver( 1222): toggleAppIcon() : FLAG_SYSTEM = true
I/Gmail   ( 3156): Observing account changes for notifications
V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  821): Start proc 3229:com.google.android.apps.messaging/u0a75 for broadcast com.google.android.apps.messaging/.receiver.BootAndPackageReplacedReceiver
E/ActivityThread( 3156): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@26c19f2a that was originally bound here
E/ActivityThread( 3156): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@26c19f2a that was originally bound here
E/ActivityThread( 3156): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
E/ActivityThread( 3156): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
E/ActivityThread( 3156): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
E/ActivityThread( 3156): 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
E/ActivityThread( 3156): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
E/ActivityThread( 3156): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 3156): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 3156): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 3156): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 3156): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 3156): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 3156): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 3156): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3156): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3156): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3156): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Exchange( 3197): EasService.onCreate
E/SQLiteLog( 3156): (283) recovered 44 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/Exchange( 3197): RestartPingTask
I/Exchange( 3197): RestartPingsTask did not start any pings.
I/Exchange( 3197): PSS stopIfIdle
I/Exchange( 3197): PSS has no active accounts; stopping service.
I/Exchange( 3197): onDestroy
I/ActivityManager(  821): Killing 2603:com.android.settings/1000 (adj 15): empty #17
I/Gmail   ( 3156): notifyAccountChanged
I/Gmail   ( 3156): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 3156): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 3156): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3156): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3156): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
,I/Gmail   ( 3156): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,I/Gmail   ( 3156): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
,I/ActivityManager(  821): Killing 2624:org.simalliance.openmobileapi.service/u0a23 (adj 15): empty #17
,I/jxcore-log( 3073): getBuffer is called!!!!
I/jxcore-log( 3073): 
,V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3156): getAccountsCursor
,V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3156): getAccountsCursor
,V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 3229): Note: end time exceeds epoch: 
,W/VideoCapabilities( 3229): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 3229): Unsupported profile 4 for video/mp4v-es
,W/Bugle   ( 3229): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3229): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3229): PhoneUtils.getForLMR1(): invalid subId = -1
,D/GCM     ( 1543): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ResourcesManager( 3229): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/AuthorizationBluetoothService( 1543): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ResourcesManager( 3229): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GmsCoreStatsServiceLauncher( 1850): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/Bugle   ( 3229): PhoneUtils.getForLMR1(): invalid subId = -1
,I/Bugle   ( 3229): ApnsOta: OTA version -1
,W/Bugle   ( 3229): PhoneUtils.getForLMR1(): invalid subId = -1
,I/ActivityManager(  821): Start proc 3265:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,W/Bugle   ( 3229): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3229): PhoneUtils.getForLMR1(): invalid subId = -1
,D/LocationInitializer( 1850): Restart initialization of location
,V/UserPresentBroadcastReceiver( 1775): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,W/ResourcesManager( 3265): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3265): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/BugleUsageStatistics( 3229): PlayLogger.onLoggerConnected
,I/MultiDex( 3265): VM with version 2.1.0 has multidex support
I/MultiDex( 3265): install
I/MultiDex( 3265): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3265): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  821): Start proc 3291:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ProviderInstaller( 3265): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 3265): callingUid 10011, callindPid: 3265
I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 212us total 12.659ms
I/BugleDataModel( 3229): Fixup: Send failed - 0 Download failed - 0
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 358us total 12.228ms
,E/MDM     ( 1775): [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 10.134ms
,W/Bugle   ( 3229): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3229): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3229): PhoneUtils.getForLMR1(): invalid subId = -1
,W/Bugle   ( 3229): PhoneUtils.getSelfRawNumber: subInfo is null for -1
,W/Bugle   ( 3229): PhoneUtils.getForLMR1(): invalid subId = -1
,I/art     (  821): Explicit concurrent mark sweep GC freed 11232(538KB) AllocSpace objects, 2(124KB) LOS objects, 32% free, 33MB/49MB, paused 4.694ms total 56.168ms
,W/Bugle   ( 3229): PhoneUtils.getForLMR1(): invalid subId = -1
,I/BugleDataModel( 3229): SyncMessagesAction: Starting batch for messages from 1449220314079 to 1449275256998 (message update limit = 80, message scan limit = 4000)
,I/BugleDataModel( 3229): SyncMessagesAction: All messages now in sync
,I/ActivityManager(  821): Killing 2504:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/MusicStore( 3291): Database version: 120
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{12ddb18a u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,W/ResourcesManager( 3291): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3291): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3291): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3291): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3291): GMSCore installation verified
,I/ConfigStore( 3291): Config Database version: 1
,I/MediaRouter( 3291): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 3291): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3291): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  821): Start proc 3331:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,W/ResourcesManager( 3331): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3331): Created com.android.providers.calendar.CalendarAlarmManager@1c495bd4(com.android.providers.calendar.CalendarProvider2@3f2ee17d)
,E/SQLiteLog( 3331): (284) automatic index on view_events(_id)
,I/art     ( 1850): Explicit concurrent mark sweep GC freed 18290(1243KB) AllocSpace objects, 19(304KB) LOS objects, 36% free, 27MB/43MB, paused 1.326ms total 44.235ms
,I/iu.UploadsManager( 1850): End new media; added: 0, uploading: 0, time: 167 ms
,I/MediaStoreImporter( 3291): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  821): Killing 2684:com.google.android.configupdater/u0a42 (adj 15): empty #17
,D/GCM     ( 1543): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 1850): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1850): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1850): [KidAccountFixer] No network connection
,D/GCM     ( 1543): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1543): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1850): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 1775): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 1850): Restart initialization of location
,D/GCM     ( 1543): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1543): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1850): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1775): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1850): Restart initialization of location
,I/NotifUtils( 3156): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/ActivityManager(  821): Delay finish: com.google.android.gm/.widget.GmailWidgetProvider
,I/ActivityManager(  821): Resuming delayed broadcast
,W/ResourcesManager( 2952): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2952): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotifUtils( 3156): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,V/JNIHelp ( 2952): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 2952): Installed default security provider GmsCore_OpenSSL
,I/Babel_telephony( 2952): TeleIncomingWifiCallController.getRegistrationState, wifi calling not enabled
,W/VideoCapabilities( 2952): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2952): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2952): Unrecognized profile 2130706433 for video/avc
,I/Babel   ( 2952): connection state changed from UNKNOWN to DISCONNECTED
,I/CalendarProvider2( 3331): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3331): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Atfwd_Daemon(  376): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
I/Atfwd_Daemon(  376): ATFWD --> QMI Port : rmnet_usb0
,I/Atfwd_Daemon(  376): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 486606848
I/Atfwd_Daemon(  376): Trying to register 8 commands:
I/Atfwd_Daemon(  376): cmd0: +CKPD
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd1: +CTSA
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd2: +CFUN
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd3: +CMAR
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd4: +CDIS
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): disable(): mBluetooth = null mBinding = false
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  376): cmd5: +CRSL
,D/BluetoothManagerService(  821): Message: 2,
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0,
I/Atfwd_Daemon(  376): cmd6: +CSS
D/WifiService(  821): New client listening to asynchronous messages,
D/WifiService(  821): setWifiEnabled: false pid=3073, uid=10272
,E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3073): ****TEST TOOK:  5035  ms ****
I/jxcore-log( 3073): ,
I/jxcore-log( 3073): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3073): 
,I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): cmd7: $QCPWRDN
I/Atfwd_Daemon(  376): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  376): Registered AT Commands event handler
,I/GAV2    ( 3156): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 1543): Explicit concurrent mark sweep GC freed 25563(1164KB) AllocSpace objects, 5(551KB) LOS objects, 38% free, 25MB/41MB, paused 2.206ms total 61.526ms
,V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1543): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1543): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1543): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1543): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1543): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AndroidRuntime( 3390): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3390): CheckJNI is OFF
,I/art     (  821): Explicit concurrent mark sweep GC freed 15020(773KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 1.159ms total 77.847ms
,D/Finsky  ( 3054): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3054): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3054): [1] 5.onFinished: Scheduling replication attempt 1.
,D/AndroidRuntime( 3390): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3073:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/PackageSettings(  821): Skipping PackageSetting{2f0e7190 com.test.thalitest/10265} due to missing metadata
,D/WifiService(  821): Client connection lost with reason: 4
,I/WindowState(  821): WIN DEATH: Window{19b27d1a u0 com.example.hello/com.example.hello.MainActivity}
,W/ActivityManager(  821): Force removing ActivityRecord{33b6e6b2 u0 com.example.hello/.MainActivity t24}: app died, no saved state
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=0: pkg removed
,W/ActivityManager(  821): Spurious death for ProcessRecord{292afff1 3073:com.example.hello/u0a272}, curProc for 3073: null
,D/TaskPersister(  821): removeObsoleteFile: deleting file=24_task.xml
,I/Keyboard.Facilitator( 1222): resetDictionaries() : en_US
,I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,D/BuaReceiver( 2241): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/Keyboard.Facilitator.DecoderInitializer( 1222): run()
,I/Decoder ( 1222): createOrResetDecoder
,D/VoicemailCleanupService( 1403): Cleaning up data for package: com.example.hello
,I/art     ( 1073): Explicit concurrent mark sweep GC freed 39780(1677KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 1.017ms total 79.911ms
,I/ActivityManager(  821): Start proc 3409:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1222): run()
,D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3073 uid 10272
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1222): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator( 1222): onFinishInput()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1222): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1222): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1222): run()
I/StatsUtilsManager( 1222): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1222): shouldRecordStats() = Too Soon
,I/ActivityManager(  821): Start proc 3429:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,W/LocationOracleImpl( 1519): Best location was null
,W/ErrorReporter( 1519): reportError [type: 29, code: 917507]: null
,D/Launcher.Workspace( 1336): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1336): 11683562 - stripEmptyScreens()
,I/HotwordRecognitionRnr( 1519): Starting hotword detection.
,I/MicrophoneInputStream( 1519): mic_starting com.google.android.apps.gsa.speech.audio.u@25f5401b
,I/AudioFlinger(  359): AudioFlinger's thread 0xb4046000 ready to run
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
W/GCoreFlp( 1775): No location to return for getLastLocation()
,I/MicrophoneInputStream( 1519): mic_started com.google.android.apps.gsa.speech.audio.u@25f5401b
,I/art     (  821): Explicit concurrent mark sweep GC freed 12512(913KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 2.760ms total 224.781ms
,D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
,W/ContextImpl( 3429): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1543): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1543): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/art     ( 3390): System.exit called, status: 0
I/AndroidRuntime( 3390): VM exiting with result code 0.
,I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,I/HotwordWorker( 1519): onReady
,W/GCoreFlp( 1775): No location to return for getLastLocation()
,W/GCoreFlp( 1775): No location to return for getLastLocation()
,I/ActivityManager(  821): Killing 1976:com.android.defcontainer/u0a7 (adj 15): empty #17
,D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  821): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  821): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,E/SQLiteLog( 3331): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DatabaseUtils( 3331): Writing exception to parcel
E/DatabaseUtils( 3331): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 3331): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 3331): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DatabaseUtils( 3331): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 3331): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 3331): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DatabaseUtils( 3331): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DatabaseUtils( 3331): 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1351)
E/DatabaseUtils( 3331): 	at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1109)
E/DatabaseUtils( 3331): 	at com.android.providers.calendar.CalendarProvider2.queryInternal(CalendarProvider2.java:938)
E/DatabaseUtils( 3331): 	at com.android.providers.calendar.CalendarProvider2.query(CalendarProvider2.java:839)
E/DatabaseUtils( 3331): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 3331): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 3331): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 3331): 	at android.os.Binder.execTransact(Binder.java:446)
,--------- beginning of crash
E/AndroidRuntime( 2658): FATAL EXCEPTION: AlertService
E/AndroidRuntime( 2658): Process: com.google.android.calendar, PID: 2658
E/AndroidRuntime( 2658): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2658): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 2658): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 2658): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
E/AndroidRuntime( 2658): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/AndroidRuntime( 2658): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/AndroidRuntime( 2658): 	at com.android.calendar.alerts.AlarmScheduler.queryUpcomingEvents(AlarmScheduler.java:158)
E/AndroidRuntime( 2658): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:115)
E/AndroidRuntime( 2658): 	at com.android.calendar.alerts.AlarmScheduler.scheduleNextAlarm(AlarmScheduler.java:106)
E/AndroidRuntime( 2658): 	at com.android.calendar.alerts.AlertService.processMessage(AlertService.java:244)
E/AndroidRuntime( 2658): 	at com.android.calendar.alerts.AlertService$ServiceHandler.handleMessage(AlertService.java:897)
E/AndroidRuntime( 2658): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2658): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2658): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop88.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
,I/art     ( 1775): Explicit concurrent mark sweep GC freed 15042(858KB) AllocSpace objects, 5(80KB) LOS objects, 37% free, 26MB/42MB, paused 2.354ms total 30.398ms
,D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  821): Validating map...
E/DataBuffer( 1775): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@26c1c551)
,V/BackupManagerService(  821): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  821): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@ea26c9e
,D/ChimeraCfgMgr( 1850): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1850): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1850): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1850): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1850): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1850): Module APK com.google.android.play.games already loaded
,W/GCoreFlp( 1775): No location to return for getLastLocation()
,E/SQLiteLog( 1850): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/UpdateIcingCorporaServi( 1519): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/OpenGLRenderer(  821): Initialized EGL, version 1.4
,W/Launcher( 1336): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@b94516c new=com.google.android.velvet.VelvetApplication@b94516c
,E/AndroidRuntime( 1850): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1850): Process: com.google.android.gms, PID: 1850
E/AndroidRuntime( 1850): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1850): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1850): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1850): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1850): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1850): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1850): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1850): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1850): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1850): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1850): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1850): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1850): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1850): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1850): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1850): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1850): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1850): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1850): 	at java.lang.Thread.run(Thread.java:818)
,D/OpenGLRenderer(  821): Enabling debug mode 0
E/SharedPreferencesImpl( 1775): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.backupScheduler.xml to backup file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.backupScheduler.xml.bak
E/SharedPreferencesImpl( 1775): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.restoreScheduler.xml to backup file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.restoreScheduler.xml.bak
I/LocationSettingsChecker( 1850): Removing dialog suppression flag for package com.example.hello
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop90.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
E/SQLiteLog( 1336): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
V/GmsNetworkLocationProvi( 1775): DISABLE
,E/SQLiteDatabase( 1850): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1850): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1850): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1850): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1850): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1850): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1850): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1850): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1850): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1850): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1850): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1850): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1850): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1850): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1850): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1850): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1850): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1850): 	at com.google.android.g,ms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1850): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1850): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1850): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1850): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1850): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1850): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1850): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1850): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1850): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/ActivityManager(  821): Start proc 3485:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
E/SQLiteLog( 1850): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1850): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1850): Sending signal. PID: 1850 SIG: 9
E/SQLiteLog( 1519): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
V/GmsNetworkLocationProvi( 1775): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
E/SQLiteLog( 1336): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
E/QMI_FW  (  821): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  821): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660396819
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  821): Start proc 3505:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/lowmemorykiller(  256): Error writing /proc/1850/oom_score_adj; errno=22
E/SharedPreferencesImpl( 1519): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 1519): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1519): Process: com.google.android.googlequicksearchbox:search, PID: 1519
E/AndroidRuntime( 1519): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1519): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1519): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1519): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1519): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1519): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1519): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1519): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1519): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1519): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1519): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1519): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1519): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1519): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1519): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1519): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1519): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1519): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1519): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1519): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1519): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  821): Failure sending service ComponentInfo{com.google.android.gms/com.google.android.location.util.PreferenceService} to connection android.os.BinderProxy@41f5a6f (in com.google.android.gms)
W/ActivityManager(  821): android.os.TransactionTooLargeException
W/ActivityManager(  821): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  821): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  821): 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
W/ActivityManager(  821): 	at com.android.server.am.ActiveServices.publishServiceLocked(ActiveServices.java:885)
W/ActivityManager(  821): 	at com.android.server.am.ActivityManagerService.publishService(ActivityManagerService.java:15342)
W/ActivityManager(  821): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:978)
W/ActivityManager(  821): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  821): 	at android.os.Binder.execTransact(Binder.java:446)
,V/GmsNetworkLocationProvi( 1775): ENABLE
,V/GmsNetworkLocationProvi( 1775): SET-REQUEST
V/GmsNetworkLocationProvi( 1775): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,E/JavaBinder( 1775): !!! FAILED BINDER TRANSACTION !!!
W/GmsClient( 1775): Remote exception occurred
W/GmsClient( 1775): android.os.TransactionTooLargeException
W/GmsClient( 1775): 	at android.os.BinderProxy.transactNative(Native Method)
W/GmsClient( 1775): 	at android.os.BinderProxy.transact(Binder.java:496)
W/GmsClient( 1775): 	at com.google.android.gms.common.internal.bu.b(SourceFile:1948)
W/GmsClient( 1775): 	at com.google.android.gms.common.internal.aq.a(SourceFile:1297)
W/GmsClient( 1775): 	at com.google.android.gms.common.api.ar.a(SourceFile:906)
W/GmsClient( 1775): 	at com.google.android.gms.common.api.au.run(SourceFile:799)
W/GmsClient( 1775): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/GmsClient( 1775): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/GmsClient( 1775): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/GmsClient( 1775): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/GmsClient( 1775): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  821): Process com.google.android.gms (pid 1850) has died
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 21000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.config.ConfigFetchService in 21000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.ads.identifier.service.AdvertisingIdService in 21000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.usagereporting.service.UsageReportingService in 31000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 41000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 41000ms
,W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 41000ms
,W/OpenGLRenderer( 1336): Incorrectly called buildLayer on View: ew, destroying layer...
,I/HotwordDetector( 1519): Closing mic
,I/MicrophoneInputStream( 1519): mic_close com.google.android.apps.gsa.speech.audio.u@25f5401b
,I/ActivityManager(  821): Start proc 3526:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1519): Hotword detection finished
I/HotwordRecognitionRnr( 1519): Stopping hotword detection.
,W/ResourcesManager( 3526): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3526): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/QMI_FW  (  821): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  821): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660396819
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/MultiDex( 3526): VM with version 2.1.0 has multidex support
I/MultiDex( 3526): install
I/MultiDex( 3526): VM has multidex support, MultiDex support library is disabled.
,E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  259): MdpData failed to play
E/qdoverlay(  259): == Dump MdpData start ==
E/qdoverlay(  259): == Dump OvFD fd=26 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  259): mOvData msmfb_overlay_data id=8
E/qdoverlay(  259): data msmfb_data offset=0 memid=50 id=0 flags=0x0 priv=0
E/qdoverlay(  259): == Dump MdpData end ==
E/qdhwcomposer(  259): draw: queue failed for left of dpy = 0
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  259): MdpData failed to play
E/qdoverlay(  259): == Dump MdpData start ==
E/qdoverlay(  259): == Dump OvFD fd=31 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  259): mOvData msmfb_overlay_data id=16
E/qdoverlay(  259): data msmfb_data offset=0 memid=50 id=0 flags=0x0 priv=0
E/qdoverlay(  259): == Dump MdpData end ==
E/qdhwcomposer(  259): draw: queue failed for right of dpy = 0
E/qdhwcomposer(  259): hwc_set_primary: FBUpdate draw failed
E/qdoverlay(  259): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  259): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  259): hwc_set_primary: display commit fail for 0 dpy!
E/qdhwcomposer(  259): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
E/SurfaceFlinger(  259): eventControl(0, 1) failed Operation not permitted
,E/qdoverlay(  259): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  259): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  259): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset
,E/SQLiteDatabase( 3526): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 3526): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3526): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3526): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3526): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 3526): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 3526): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 3526): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 3526): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3526): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3526): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3526): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 3526): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3526): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3526): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3526): 	at android.database.sqlite.SQLiteOpenHelper.getWr,itableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3526): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 3526): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 3526): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 3526): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 3526): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3526): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3526): 	at java.lang.Thread.run(Thread.java:818)
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset

```
