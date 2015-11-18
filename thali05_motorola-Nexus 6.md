#### Test 50388019f4ce509_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GmsCoreStatsServiceLauncher( 1825): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 1759): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 1825): Restart initialization of location
D/GCM     ( 1463): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1463): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 1825): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 1759): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
--------- beginning of system
I/ActivityManager(  822): Start proc 2132:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
D/LocationInitializer( 1825): Restart initialization of location
,D/AndroidRuntime( 2152): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 2152): CheckJNI is OFF
I/ServiceManager(  376): Waiting for service AtCmdFwd...
I/GCoreUlr( 1759): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.android.location.internal.server.ACTION_RESTARTED}]
I/GCoreUlr( 1759): DispatchingService.onCreate()
D/AndroidRuntime( 2152): Calling main entry com.android.commands.am.Am
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{168b8b0e token=Token{3b495d09 ActivityRecord{12519e10 u0 com.example.hello/.MainActivity t20}}} to stack=1 task=20 at 0
D/AndroidRuntime( 2152): Shutting down VM
I/HotwordDetector( 1530): Closing mic
I/MicrophoneInputStream( 1530): mic_close com.google.android.apps.gsa.speech.audio.u@2bfbe914
I/art     ( 1825): Explicit concurrent mark sweep GC freed 58079(3MB) AllocSpace objects, 31(496KB) LOS objects, 37% free, 27MB/43MB, paused 685us total 43.989ms
I/ActivityManager(  822): Start proc 2174:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
I/ActivityManager(  822): Start proc 2191:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
V/ActivityManager(  822): Display changed displayId=0
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1530): Stopping hotword detection.
I/HotwordRecognitionRnr( 1530): Hotword detection finished
W/ResourcesManager( 2191): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/WebViewFactory( 2174): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@389ca92f}
I/LibraryLoader( 2174): Time to load native libraries: 1 ms (timestamps 417-418)
I/LibraryLoader( 2174): Expected native library version number "",actual native library version number ""
I/GoogleURLConnFactory( 1759): Using platform SSLCertificateSocketFactory
W/GoogleHttpClient( 1759): Ignoring unsupported parameter: http.conn-manager.max-per-route
I/GCoreUlr( 1759): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.android.location.internal.server.ACTION_RESTARTED
D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@39d4a94b}
W/System.err( 1759): java.net.UnknownHostException: Unable to resolve host "www.google.com": No address associated with hostname
W/System.err( 1759): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
W/System.err( 1759): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
W/System.err( 1759): 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
W/System.err( 1759): 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
W/System.err( 1759): 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
W/System.err( 1759): 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
W/System.err( 1759): 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
W/System.err( 1759): 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
W/System.err( 1759): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:382)
W/System.err( 1759): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:106)
W/System.err( 1759): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:217)
W/System.err( 1759): 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
W/System.err( 1759): 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
W/System.err( 1759): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:933)
W/System.err( 1759): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:775)
W/System.err( 1759): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:676)
W/System.err( 1759): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:660)
W/System.err( 1759): 	at com.google.t.a.b.a.b.g(SourceFile:126)
W/System.err( 1759): 	at com.google.t.a.b.a.b.c(SourceFile:172)
W/System.err( 1759): 	at com.google.aa.a.d.run(SourceFile:435)
W/System.err( 1759): 	at com.google.aa.a.c.c(SourceFile:232)
W/System.err( 1759): 	at com.google.aa.a.c.run(SourceFile:206)
W/System.err( 1759): 	at com.google.t.a.c.b.run(SourceFile:96)
W/System.err( 1759): Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
W/System.err( 1759): 	at libcore.io.Posix.android_getaddrinfo(Native Method)
W/System.err( 1759): 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
W/System.err( 1759): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:438)
W/System.err( 1759): 	... 22 more
D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@39d4a94b}
D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@389ca92f}
V/WebViewChromiumFactoryProvider( 2174): Binding Chromium to main looper Looper (main, tid 1) {12aecbb3}
I/LibraryLoader( 2174): Expected native library version number "",actual native library version number ""
I/chromium( 2174): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2174): Initializing chromium process, singleProcess=true
W/art     ( 2174): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2174): ApplicationContext is null in ApplicationStatus
W/chromium( 2174): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659213075
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ConfigService( 1463): onDestroy
W/chromium( 2174): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2174): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2174): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 2174): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
I/GCoreUlr( 1759): WorldUpdater:com.google.android.location.internal.server.ACTION_RESTARTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1759): Unbound from all location providers
D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d50ab40:true
D/BluetoothAdapter( 2174): 355559034: getState() :  mService = null. Returning STATE_OFF
W/art     ( 2174): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2174): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2174): CordovaWebView is running on device made by: motorola
I/art     ( 1463): Explicit concurrent mark sweep GC freed 17707(829KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 851us total 41.889ms
W/art     ( 2174): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2174): Attempt to remove local handle scope entry from IRT, ignoring
I/GCoreUlr( 1759): DispatchingService.onDestroy()
I/GCoreUlr( 1759): Unbound from all location providers
D/OpenGLRenderer( 2174): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 2174): Validating map...
V/WindowManager(  822): Adding window Window{16856470 u0 com.example.hello/com.example.hello.MainActivity} at 3 of 8 (after Window{30cb9fce u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
W/chromium( 2174): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 2174): Initialized EGL, version 1.4
D/OpenGLRenderer( 2174): Enabling debug mode 0
I/Keyboard.Facilitator( 1229): onFinishInput()
I/ActivityManager(  822): Displayed com.example.hello/.MainActivity: +438ms (total +7s805ms)
W/BindingManager( 2174): Cannot call determinedVisibility() - never saw a connection for the pid: 2174
I/chromium( 2174): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 2174): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 2174): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/jxcore_app_log( 2174): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576502912
D/JX-Cordova( 2174): jxcore cordova android initializing
I/art     (  822): Explicit concurrent mark sweep GC freed 13287(702KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 32MB/48MB, paused 1.230ms total 49.680ms
I/Babel_SMS( 2191): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 2191): MmsConfig.loadMmsSettings
I/Babel_SMS( 2191): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 2191): MmsConfig.loadFromDatabase
E/Babel_SMS( 2191): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 2191): MmsConfig.loadFromResources
E/Babel_SMS( 2191): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 2191): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
W/jxcore-log( 2174): Initializing JXcore engine
W/jxcore-log( 2174): JXcore engine is ready
W/jxcore-log( 2174): Starting JXcore engine
W/Settings( 2191): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/m.example.hello( 2174): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12591]" dev="sockfs" ino=12591 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 2174): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 2174): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10697]" dev="sockfs" ino=10697 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 2174): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[16967]" dev="sockfs" ino=16967 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/Babel_Crash( 2191): startup - clean
I/Babel   ( 2191): deleted: false for 0
W/jxcore-log( 2174): Platform android
W/jxcore-log( 2174): 
W/jxcore-log( 2174): Process ARCH arm
W/jxcore-log( 2174): 
I/ServiceManager(  376): Waiting for service AtCmdFwd...
I/jxcore-log( 2174): JXcore Cordova bridge is ready!
I/jxcore-log( 2174): 
W/jxcore-log( 2174): JXcore engine is started
I/Babel_telephony( 2191): TeleModule.launchCompleted
E/jxcore-log( 2174): >> motorola-Nexus 6
E/jxcore-log( 2174): 
I/jxcore-log( 2174): Total memory 3113791488
I/jxcore-log( 2174): 
I/jxcore-log( 2174): Free memory 1238437888
I/jxcore-log( 2174): 
I/jxcore-log( 2174): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2174): 
I/jxcore-log( 2174): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2174): 
W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
I/jxcore-log( 2174): userPath [ 'www' ]
I/jxcore-log( 2174): 
I/Babel_telephony( 2191): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 2191): BAM#gBA: invalid account id: -1
W/Babel   ( 2191): BAM#gBA: invalid account id: -1
I/jxcore-log( 2174): Size 1440 2392
I/jxcore-log( 2174): 
I/Babel_telephony( 2191): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
I/jxcore-log( 2174): Screen Brightness 82
I/jxcore-log( 2174): 
E/jxcore-log( 2174): Dummy Error Log.
E/jxcore-log( 2174): 
W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
W/VideoCapabilities( 2191): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  822): Start proc 2257:com.motorola.android.buacontactadapter/u0a88 for broadcast com.motorola.android.buacontactadapter/.BuaReceiver
I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 10.129ms
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 16.528ms
I/VideoCapabilities( 2191): Unsupported profile 4 for video/mp4v-es
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 8.379ms
W/VideoCapabilities( 2191): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2191): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2191): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2191): Unrecognized profile 2130706433 for video/avc
D/BuaReceiver( 2257): ====== got intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/vclib   ( 2191): onServiceConnected
W/Babel   ( 2191): Attempted to change video mute state without an active call.
I/ActivityManager(  822): Start proc 2279:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
D/PackageBroadcastService( 1825): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraCfgMgr( 1825): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1825): Module APK com.google.android.play.games already loaded
--------- beginning of crash
F/libc    (  327): Fatal signal 11 (SIGSEGV), code 1, fault addr 0x0 in tid 330 (BootAnimation)
I/ConfigService( 1463): onCreate
I/ConfigFetchService( 1825): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1825): launchTask
D/ChimeraCfgMgr( 1825): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1825): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1825): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1825): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1825): Failed to find package metadata for com.example.hello
D/Vision  ( 1825): No vision deps
I/ConfigFetchService( 1825): service connected
E/DEBUG   (  356): unexpected waitpid response: n=330, status=00000000
E/DEBUG   (  356): tid exited before attach completed: tid 330
D/ConfigFetchService( 1825): ConfigApi connection successful.
I/PeopleContactsSync( 1825): CP2 sync disabled
V/ConfigFetchTask( 1825): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UYZzqx1MqTqioqXWMEAtKrQZF51s2w1Z0J6f4MOUN2ucve2SWGTCpGlOBLtQAdObGbMTNtmMMnWMAYXaO36sYgBHga_vq8hmqVcqIQSCylIlThPVLGilWA68oP1zmmnf_tr7AJqrPKEahP5HVvGZ77pjti0W2SDGdstSOta-kt6scjoU1kCrGbbTqBAqfXxzgZvhmF_lgyLk4fgAKGB-y_s6aVbzaOr2PHtKdEFKrSvXcbK60
I/ActivityManager(  822): Start proc 2311:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/GoogleURLConnFactory( 1825): Using platform SSLCertificateSocketFactory
I/UpdateIcingCorporaServi( 1530): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
W/ConfigFetchTask( 1825): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1825): fetch service done; releasing wakelock
I/ConfigFetchService( 1825): stopping self
W/BaseAppContext( 1825): Using Auth Proxy for data requests.
I/SystemServiceManager(  822): Starting phase 1000
I/GLSUser ( 1825): [ChannelManager] Attempting to channel bind connection HttpClient.
I/GLSUser ( 1825): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
W/BaseAppContext( 1825): Using Auth Proxy for data requests.
I/UpdateIcingCorporaServi( 1530): UpdateCorporaTask done [took 156 ms] updated apps [took 156 ms] 
W/BaseAppContext( 1825): Using Auth Proxy for data requests.
W/BaseAppContext( 1825): Using Auth Proxy for data requests.
W/BaseAppContext( 1825): Using Auth Proxy for data requests.
I/jxcore-log( 2174): getBuffer is called!!!!
I/jxcore-log( 2174): 
W/BaseAppContext( 1825): Using Auth Proxy for data requests.
,I/ServiceManager(  376): Waiting for service AtCmdFwd...
,I/GAv4    ( 2311): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2311):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2311):   adb logcat -s GAv4
,W/GAv4    ( 2311): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2311): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2311): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 2311): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,W/ResourcesManager( 2311): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2311): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  822): Start proc 2355:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,V/JNIHelp ( 2311): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 2311): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1463): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1825): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,D/Icing   ( 1825): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1825): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,D/Finsky  ( 2355): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ServiceManager(  376): Waiting for service AtCmdFwd...
,D/Finsky  ( 2355): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  822): Start proc 2392:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 2355): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 2392): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2392): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/Settings( 2355): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/MultiDex( 2392): VM with version 2.1.0 has multidex support
I/MultiDex( 2392): install
,I/MultiDex( 2392): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 2392): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  822): Start proc 2412:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/Finsky  ( 2355): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2355): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 2355): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 2355): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ProviderInstaller( 2392): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 2412): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/Finsky  ( 2355): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/ActivityManager(  822): Start proc 2448:com.android.keychain/1000 for service com.android.keychain/.KeyChainService
,I/RecoverySystem(  822): No recovery log file
,I/ActivityManager(  822): Start proc 2470:com.google.android.dialer/u0a13 for broadcast com.google.android.dialer/com.android.dialer.calllog.CallLogReceiver
,I/BootReceiver(  822): Copying /sys/fs/pstore/console-ramoops to DropBox (SYSTEM_LAST_KMSG)
,I/ActivityManager(  822): Killing 1490:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,W/ResourcesManager( 2470): Asset path '/system/framework/com.google.android.dialer.support.jar' does not exist or contains no resources.
,I/BootReceiver(  822): Copying audit failures to DropBox
,I/BootReceiver(  822): Copied 220 worth of audits to DropBox
,I/BootReceiver(  822): Checking for fsck errors
,I/ServiceManager(  376): Waiting for service AtCmdFwd...
,I/ActivityManager(  822): Killing 1910:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,D/WIFI    (  822): Registering NetworkFactory
D/WIFI_UT (  822): Registering NetworkFactory
D/ConnectivityService(  822): Got NetworkFactory Messenger for WIFI
D/ConnectivityService(  822): Got NetworkFactory Messenger for WIFI_UT
,D/WIFI    (  822): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
,D/WIFI_UT (  822): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
,I/ActivityManager(  822): Start proc 2494:com.motorola.motocit/u0a2 for broadcast com.motorola.motocit/.CQATestBootReceiver
,D/Finsky  ( 2355): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1463): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1463): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1463): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GLSUser ( 1463): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1463): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1463): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1463): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1463): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 23640(1307KB) AllocSpace objects, 21(1474KB) LOS objects, 32% free, 32MB/48MB, paused 993us total 63.359ms
,I/ActivityManager(  822): Start proc 2512:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarReceiver
,W/Finsky  ( 2355): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1463): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 2512): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/GLSUser ( 1463): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1463): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1463): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1463): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1463): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1463): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1463): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1463): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1463): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1463): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1463): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2355): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/CalendarProvider2( 2512): Created com.android.providers.calendar.CalendarAlarmManager@2ec65522(com.android.providers.calendar.CalendarProvider2@12aecbb3)
,I/ActivityManager(  822): Start proc 2534:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.BootCompletedReceiver
,I/ActivityManager(  822): Killing 2037:com.android.cellbroadcastreceiver/u0a4 (adj 15): empty #17
,V/GLSActivity( 1463): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 15047(808KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 2.205ms total 67.240ms
,I/GLSUser ( 1463): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1463): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1463): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1463): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1463): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2355): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 2355): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 2355): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,W/Atfwd_Sendcmd(  376): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Finsky  ( 2355): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,I/ActivityManager(  822): Killing 2019:com.verizon.omadm/u0a93 (adj 15): empty #17
,D/DeviceConnectionService( 1759): client connected with version: 7571000
,I/ActivityManager(  822): Killing 2002:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #18
,I/ActivityManager(  822): Killing 1335:com.android.printspooler/u0a81 (adj 15): empty #17
,I/CalendarProvider2( 2512): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 2512): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  822): Start proc 2563:com.google.android.onetimeinitializer/u0a15 for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
,I/ActivityManager(  822): Killing 2103:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 347us total 37.266ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 346us total 14.912ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 351us total 25.241ms
,I/ActivityManager(  822): Killing 2132:com.google.android.keep/u0a79 (adj 15): empty #17
,V/OneTimeInitializerReceiver( 2563): OneTimeInitializerReceiver.onReceive
,V/OneTimeService( 2563): OneTimeService.onHandleIntent
,I/ActivityManager(  822): Start proc 2587:com.android.managedprovisioning/u0a17 for broadcast com.android.managedprovisioning/.BootReminder
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  822): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  822): Message: 2
,D/WifiService(  822): New client listening to asynchronous messages
,D/WifiService(  822): setWifiEnabled: false pid=2174, uid=10272
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2174): ****TEST TOOK:  5035  ms ****
I/jxcore-log( 2174): 
I/jxcore-log( 2174): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2174): 
,I/RlzPingService( 1577): Setting next ping for 1448439173636
,I/ActivityManager(  822): Killing 2191:com.google.android.talk/u0a61 (adj 15): empty #17
,I/ActivityManager(  822): Killing 2279:com.android.musicfx/u0a18 (adj 15): empty #17
,D/AndroidRuntime( 2606): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 2606): CheckJNI is OFF
,I/ConfigService( 1463): onDestroy
,E/SQLiteLog( 1084): (283) recovered 147 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,I/ActivityManager(  822): Start proc 2621:com.android.settings/1000 for broadcast com.android.settings/.sim.SimBootReceiver
,D/MtpService( 1084): updating state; isCurrentUser=true, mMtpLocked=false
,D/AndroidRuntime( 2606): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  822): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
,I/ActivityManager(  822): Killing 2174:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/MediaScanner( 1084): Error opening directory '/oem/media/', skipping: Permission denied.
,W/PackageSettings(  822): Skipping PackageSetting{362c863e com.test.thalitest/10265} due to missing metadata
,I/WindowState(  822): WIN DEATH: Window{16856470 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  822): Client connection lost with reason: 4
,W/ActivityManager(  822): Force removing ActivityRecord{12519e10 u0 com.example.hello/.MainActivity t20}: app died, no saved state
,I/ActivityManager(  822): Force stopping com.example.hello appid=10272 user=0: pkg removed
,W/ActivityManager(  822): Spurious death for ProcessRecord{2406388b 2174:com.example.hello/u0a272}, curProc for 2174: null
,I/Keyboard.Facilitator( 1229): resetDictionaries() : en_US
,D/TaskPersister(  822): removeObsoleteFile: deleting file=20_task.xml
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1063): Explicit concurrent mark sweep GC freed 34151(1395KB) AllocSpace objects, 0(0B) LOS objects, 18% free, 70MB/86MB, paused 723us total 38.223ms
,I/Keyboard.Facilitator.DecoderInitializer( 1229): run()
,I/Decoder ( 1229): createOrResetDecoder
,I/ConfigService( 1463): onCreate
,I/art     ( 1530): Explicit concurrent mark sweep GC freed 65586(8MB) AllocSpace objects, 6(721KB) LOS objects, 37% free, 26MB/42MB, paused 1.126ms total 84.504ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1229): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1229): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1229): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1229): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1229): run()
I/StatsUtilsManager( 1229): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1229): shouldRecordStats() = Too Soon
,I/ActivityManager(  822): Start proc 2648:org.simalliance.openmobileapi.service/u0a23 for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver
,W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 2174 uid 10272
,I/Keyboard.Facilitator( 1229): onFinishInput()
D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/art     (  822): Explicit concurrent mark sweep GC freed 17334(1085KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 32MB/48MB, paused 1.993ms total 128.999ms
,I/art     (  822): WaitForGcToComplete blocked for 18.888ms for cause Explicit
,I/art     ( 2606): System.exit called, status: 0
I/AndroidRuntime( 2606): VM exiting with result code 0.
,I/art     (  822): Explicit concurrent mark sweep GC freed 2741(136KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 32MB/48MB, paused 1.146ms total 44.427ms
,W/LocationOracleImpl( 1530): Best location was null
,W/ErrorReporter( 1530): reportError [type: 29, code: 917507]: null
,W/ResourcesManager( 2648): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,I/iu.UploadsManager( 1825): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,W/GCoreFlp( 1759): No location to return for getLastLocation()
,I/HotwordRecognitionRnr( 1530): Starting hotword detection.
I/MicrophoneInputStream( 1530): mic_starting com.google.android.apps.gsa.speech.audio.u@9a8cda0
,I/AudioFlinger(  359): AudioFlinger's thread 0xb4068000 ready to run
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1530): mic_started com.google.android.apps.gsa.speech.audio.u@9a8cda0
,D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
,I/iu.UploadsManager( 1825): End new media; added: 0, uploading: 0, time: 50 ms
,W/GCoreFlp( 1759): No location to return for getLastLocation()
,D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
,V/SmartcardService( 2648): main Received broadcast
,V/SmartcardService( 2648): Starting smartcard service after boot completed
,I/ActivityManager(  822): Start proc 2680:org.simalliance.openmobileapi.service:remote/u0a23 for service org.simalliance.openmobileapi.service/.SmartcardService
W/GCoreFlp( 1759): No location to return for getLastLocation()
,I/ActivityManager(  822): Start proc 2697:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/HotwordWorker( 1530): onReady
,W/ResourcesManager( 2680): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,W/GCoreFlp( 1759): No location to return for getLastLocation()
,V/MediaScanner( 1084): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@2bcf40cc
,V/MediaScanner( 1084): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@2bcf40cc
,D/Launcher.Workspace( 1309): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1309): 11683562 - stripEmptyScreens()
,E/SQLiteDatabase( 1309): Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/cache/widgetpreviews.db'.
E/SQLiteDatabase( 1309): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1309): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1309): 	at com.android.launcher3.fu$2.b(WidgetPreviewLoader.java:403)
E/SQLiteDatabase( 1309): 	at com.android.launcher3.fu$2.doInBackground(WidgetPreviewLoader.java:401)
E/SQLiteDatabase( 1309): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 1309): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1309): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1309): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1309): 	at java.lang.Thread.run(Thread.java:818)
,V/SmartcardService( 2680): main smartcard service onCreate
,I/ActivityManager(  822): Start proc 2717:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,E/AndroidRuntime( 1309): FATAL EXCEPTION: AsyncTask #3
E/AndroidRuntime( 1309): Process: com.google.android.googlequicksearchbox, PID: 1309
E/AndroidRuntime( 1309): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 1309): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/AndroidRuntime( 1309): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 1309): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 1309): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 1309): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1309): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1309): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 1309): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 1309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 1309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 1309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 1309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 1309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 1309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 1309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 1309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 1309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 1309): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 1309): 	at com.android.launcher3.fu$2.b(WidgetPreviewLoader.java:403)
E/AndroidRuntime( 1309): 	at com.android.launcher3.fu$2.doInBackground(WidgetPreviewLoader.java:401)
E/AndroidRuntime( 1309): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AndroidRuntime( 1309): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 1309): 	... 3 more
,W/ActivityManager(  822):   Force finishing activity 1 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop87.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
I/SmartcardService( 2680): Initializing Access Control
I/SmartcardService( 2680): OnPostExecute()
V/SmartcardService( 2680): register SIM_STATE_CHANGED event
I/HotwordDetector( 1530): Closing mic
I/MicrophoneInputStream( 1530): mic_close com.google.android.apps.gsa.speech.audio.u@9a8cda0
,D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  822): Validating map...
,V/SmartcardService( 2680): register ADAPTER_STATE_CHANGED event
,I/ActivityManager(  822): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,V/WindowManager(  822): addAppToken: AppWindowToken{b09aedf token=Token{2bf7597e ActivityRecord{34429f39 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t21}}} to stack=0 task=21 at 0
,V/SmartcardService( 2680): register MEDIA_MOUNTED event
,W/Launcher( 1309): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1531667a new=com.google.android.velvet.VelvetApplication@1531667a
,D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1530): Hotword detection finished
,I/HotwordRecognitionRnr( 1530): Stopping hotword detection.
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/OpenGLRenderer(  822): Initialized EGL, version 1.4
,D/OpenGLRenderer(  822): Enabling debug mode 0
,I/GEL     ( 1309): handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,E/SQLiteLog( 1463): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ClearcutLoggerIntentService( 1463): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1463): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1463): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1463): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1463): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1463): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/ClearcutLoggerIntentService( 1463): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1463): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1463): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1463): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1463): 	at java.lang.Thread.run(Thread.java:818)
,V/WindowManager(  822): Adding window Window{1c191948 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} at 3 of 9 (after Window{31e09b6b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,E/SQLiteLog( 1463): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ClearcutLoggerIntentService( 1463): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1463): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1463): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1463): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1463): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1463): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/ClearcutLoggerIntentService( 1463): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1463): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1463): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1463): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1463): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 2697): Failed to open database '/data/data/com.google.android.calendar/databases/timelydata.db'.
E/SQLiteDatabase( 2697): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2697): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2697): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2697): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2697): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2697): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2697): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2697): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 2697): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 2697): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 2697): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 2697): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 2697): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2697): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2697): 	at com.google.android.syncadapters.calendar.timely.TimelyStore.<init>(TimelyStore.java:167)
E/SQLiteDatabase( 2697): 	at com.google.android.syncadapters.calendar.timely.TimelyStore.acquire(TimelyStore.java:157)
E/SQLiteDatabase( 2697): 	at com.google.android.syncadapters.calendar.timely.TimelyProvider.onCreate(TimelyProvider.java:56)
E/SQLiteDatabase( 2697): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1696)
E/SQLiteDatabase( 2697): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1671)
E/SQLiteDatabase( 2697): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4999)
E/SQLiteDatabase( 2697): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4594)
E/SQLiteDatabase( 2697): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4534)
E/SQLiteDatabase( 2697): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
E/SQLiteDatabase( 2697): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
E/SQLiteDatabase( 2697): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2697): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 2697): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 2697): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 2697): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 2697): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 2697): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 2697): Shutting down VM
E/AndroidRuntime( 2697): FATAL EXCEPTION: main
E/AndroidRuntime( 2697): Process: com.google.android.calendar, PID: 2697
E/AndroidRuntime( 2697): java.lang.RuntimeException: Unable to get provider com.google.android.syncadapters.calendar.timely.TimelyProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2697): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5002)
E/AndroidRuntime( 2697): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4594)
E/AndroidRuntime( 2697): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4534)
E/AndroidRuntime( 2697): 	at android.app.Acti,vityThread.access$1500(ActivityThread.java:151)
E/AndroidRuntime( 2697): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
E/AndroidRuntime( 2697): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2697): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2697): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 2697): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 2697): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 2697): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 2697): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 2697): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2697): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2697): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 2697): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 2697): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2697): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 2697): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 2697): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 2697): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 2697): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 2697): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 2697): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 2697): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 2697): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 2697): 	at com.google.android.syncadapters.calendar.timely.TimelyStore.<init>(TimelyStore.java:167)
E/AndroidRuntime( 2697): 	at com.google.android.syncadapters.calendar.timely.TimelyStore.acquire(TimelyStore.java:157)
E/AndroidRuntime( 2697): 	at com.google.android.syncadapters.calendar.timely.TimelyProvider.onCreate(TimelyProvider.java:56)
E/AndroidRuntime( 2697): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1696)
E/AndroidRuntime( 2697): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1671)
E/AndroidRuntime( 2697): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4999)
E/AndroidRuntime( 2697): 	... 11 more
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop91.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
I/ActivityManager(  822): Killing 2311:com.google.android.apps.docs/u0a46 (adj 15): empty #17
D/GFEEDBACK_SendErrorReportOperation( 1825): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 1825): Error saving report: java.io.IOException: failed to create reports directory
,W/OpenGLRenderer( 1309): Incorrectly called buildLayer on View: ew, destroying layer...
D/Launcher( 1309): 11683562 - bindAddScreens()
D/Launcher( 1309): 11683562 -   orderedScreenIds: 0
D/Launcher.Workspace( 1309): 11683562 - insertNewWorkspaceScreen(): 0 at index: 0
,I/ActivityManager(  822): Killing 2412:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,W/ResourcesManager( 1309): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1309): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  822): Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +477ms
,E/SQLiteLog( 1463): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ClearcutLoggerIntentService( 1463): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1463): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1463): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1463): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1463): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1463): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ClearcutLoggerIntentService( 1463): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1463): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1463): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1463): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1463): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1463): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1463): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  822): Killing 2448:com.android.keychain/1000 (adj 15): empty #17
,E/qdoverlay(  257): Bad ov dump:  mdp_overlay z=1 fg=0 alpha=255 mask=-1 flags=0x60200 id=8
E/qdoverlay(  257): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  257): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  257): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  257): Bad ov dump:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  257): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  257): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  257): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  257): Bad ov dump:  mdp_overlay z=1 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  257): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  257): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  257): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  257): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  257): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
,E/qdoverlay(  257): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  257): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  257): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  257): MdpCtrl close error in unset
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
E/qdoverlay(  257): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  257): MdpCtrl close error in unset
E/qdoverlay(  257): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  257): MdpCtrl close error in unset
E/qdoverlay(  257): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  257): MdpCtrl close error in unset
E/qdoverlay(  257): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  257): MdpCtrl close error in unset
```
