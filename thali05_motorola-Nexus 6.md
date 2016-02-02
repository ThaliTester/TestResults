#### Test 57972094912017a_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  824): Waited long enough for: ServiceRecord{220d14c1 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,--------- beginning of main
D/AndroidRuntime( 3731): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3731): CheckJNI is OFF
I/ActivityManager(  824): Killing 2570:com.google.android.apps.maps/u0a65 (adj 15): empty #17
D/AndroidRuntime( 3731): Calling main entry com.android.commands.am.Am
I/ActivityManager(  824): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  824): addAppToken: AppWindowToken{213e0dd2 token=Token{964e05d ActivityRecord{246e8a34 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3731): Shutting down VM
I/MicrophoneInputStream( 1510): mic_close com.google.android.apps.gsa.speech.audio.u@15872738
I/HotwordDetector( 1510): Closing mic
V/WindowManager(  824): Adding window Window{2468f1ff u0 Starting com.test.thalitest} at 2 of 7 (after Window{1cf4357d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  824): Start proc 3745:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1510): Stopping hotword detection.
I/HotwordRecognitionRnr( 1510): Hotword detection finished
I/ActivityManager(  824): Killing 3505:com.google.android.partnersetup/u0a16 (adj 15): empty #17
I/ActivityManager(  824): Killing 3442:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/WebViewFactory( 3745): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3745): Time to load native libraries: 4 ms (timestamps 5331-5335)
I/LibraryLoader( 3745): Expected native library version number "",actual native library version number ""
,E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1721218323
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,V/WebViewChromiumFactoryProvider( 3745): Binding Chromium to main looper Looper (main, tid 1) {24cb4bb3}
I/LibraryLoader( 3745): Expected native library version number "",actual native library version number ""
I/chromium( 3745): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3745): Initializing chromium process, singleProcess=true
,W/art     ( 3745): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3745): ApplicationContext is null in ApplicationStatus
,W/chromium( 3745): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3745): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 3745): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
,I/Adreno  ( 3745): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31fc16c9:true
,W/art     ( 3745): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3745): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3745): CordovaWebView is running on device made by: motorola
,W/art     ( 3745): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3745): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3745): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3745): Validating map...
,V/WindowManager(  824): Adding window Window{3bb4439 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2468f1ff u0 Starting com.test.thalitest})
,W/chromium( 3745): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,I/OpenGLRenderer( 3745): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3745): Enabling debug mode 0
,I/ActivityManager(  824): Displayed com.test.thalitest/.MainActivity: +1s42ms
,I/Keyboard.Facilitator( 1235): onFinishInput()
,W/BindingManager( 3745): Cannot call determinedVisibility() - never saw a connection for the pid: 3745
,D/JsMessageQueue( 3745): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3745): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576401152
,I/chromium( 3745): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3745): Initializing JXcore engine
W/jxcore-log( 3745): JXcore engine is ready
,W/Thread-416( 3797): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9580]" dev="sockfs" ino=9580 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-416( 3797): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-416( 3797): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9743]" dev="sockfs" ino=9743 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-416( 3797): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23664]" dev="sockfs" ino=23664 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3745): Starting JXcore engine
,W/jxcore-log( 3745): Platform android
W/jxcore-log( 3745): 
W/jxcore-log( 3745): Process ARCH arm
W/jxcore-log( 3745): 
,I/jxcore-log( 3745): JXcore Cordova bridge is ready!
I/jxcore-log( 3745): 
,W/jxcore-log( 3745): JXcore engine is started
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3745): Toggling radios to true
I/jxcore-log( 3745): 
,D/BluetoothAdapter( 3745): enable(): BT is already enabled..!
,D/WifiService(  824): setWifiEnabled: true pid=3745, uid=10265,
,E/WifiService(  824): Invoking mWifiStateMachine.setWifiEnabled,
,D/WifiService(  824): New client listening to asynchronous messages,
,I/jxcore-log( 3745): Radios toggled
I/jxcore-log( 3745): 
I/jxcore-log( 3745): My device name is: motorola-Nexus 6
I/jxcore-log( 3745): 
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 1130): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  824): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1256): Read error: ssl=0xb4887c00: I/O error during system call, Connection timed out
V/NativeCrypto( 1256): SSL shutdown failed: ssl=0xb4887c00: I/O error during system call, Broken pipe
,D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  824): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  824): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  824): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): ValidatedState{ when=-5ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): DefaultState{ when=-5ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Forcing reevaluation
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/Finsky  ( 3605): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3605): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3605): [1] 5.onFinished: Scheduling replication attempt 1.
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  824): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  824): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  824): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  824): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Disconnected - quitting
D/CSLegacyTypeTracker(  824): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  824): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  824): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  824): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering(  824): MasterInitialState.processMessage what=3
,D/Tethering(  824): MasterInitialState.processMessage what=3
,E/WifiConfigStore(  824): Setting BSSID for "NG7005g"WPA_PSK to any
V/MusicLeanback( 3055): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/WifiConfigStore(  824): will read network variables netId=0
,D/PhoneInterfaceManager( 1362): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1362): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  824): getDataEnabled: retVal=false
,E/WifiStateMachine(  824): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  824): will read network variables netId=0
,I/ActivityManager(  824): Start proc 3807:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/GpsLocationProvider(  824): No APN found to select.
,D/PhoneInterfaceManager( 1362): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1362): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  824): getDataEnabled: retVal=false
,E/GpsLocationProvider(  824): No APN found to select.
,D/SprintDMReceiver( 3807): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3807): simOperator:  IMSI: null
D/SprintDMReceiver( 3807): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1774): num queued entries: 0
I/iu.UploadsManager( 1774): num updated entries: 0
,I/iu.SyncManager( 1774): NEXT; no task
,I/ValidateNoPeople(  824): skipping global notification
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599983 ms
,I/Babel   ( 2789): connection state changed from CONNECTED to DISCONNECTED
,D/SystemUpdateService( 1774): onDestroy
,I/art     ( 1256): Explicit concurrent mark sweep GC freed 26519(1341KB) AllocSpace objects, 6(661KB) LOS objects, 38% free, 25MB/41MB, paused 937us total 21.433ms
,I/ActivityManager(  824): Start proc 3829:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,V/GoogleAuthProtoRequest( 3091): [305] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GAv4    ( 3829): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3829):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3829):   adb logcat -s GAv4
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 3829): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ExperimentUpdateService( 3091): [305] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3091): [305] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3091): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3091): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3091): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  824): Killing 3532:com.android.musicfx/u0a18 (adj 15): empty #17
,W/GAv4    ( 3829): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3829): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3829): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3829): Time to load native libraries: 1 ms (timestamps 8697-8698)
,I/LibraryLoader( 3829): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3829): Binding Chromium to main looper Looper (main, tid 1) {30472856}
,I/LibraryLoader( 3829): Expected native library version number "",actual native library version number ""
I/chromium( 3829): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3829): Initializing chromium process, singleProcess=true
,W/art     ( 3829): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3829): ApplicationContext is null in ApplicationStatus
,W/chromium( 3829): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3829): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3829): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3829): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3829): Requires BLUETOOTH permission
,I/NSApplication( 3829): Starting up...
,I/ActivityManager(  824): Start proc 3885:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  824): Killing 3566:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/art     (  824): Explicit concurrent mark sweep GC freed 31263(1481KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 1.450ms total 73.359ms
,I/ActivityManager(  824): Killing 3248:android.process.acore/u0a5 (adj 15): empty #17
,V/MusicLeanback( 3055): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3807): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3807): simOperator:  IMSI: null,
D/SprintDMReceiver( 3807): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  824): skipping global notification
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599946 ms
,D/SystemUpdateService( 1774): onDestroy
,I/wpa_supplicant( 1130): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 1130): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1130): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1130): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=],
,D/ConnectivityService(  824): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  824): Start Dhcp Watchdog 2
,E/WifiStateMachine(  824):  WifiLinkLayerStats: 
E/WifiStateMachine(  824):  my bss beacon rx: 217
E/WifiStateMachine(  824):  RSSI mgmt: -51
E/WifiStateMachine(  824):  BE :  rx=157 tx=136 lost=0 retries=0
E/WifiStateMachine(  824):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  on_time : 9656 tx_time=152 rx_time=365 scan_time=0
,D/ConnectivityService(  824): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  824): do suspend false
,E/WifiStateMachine(  824): scanCount==0 - aborting
,I/dhcpcd  ( 3918): version 5.5.6 starting
,I/dhcpcd  ( 3918): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3918): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3918): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3745): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3745): 
,D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  824): Adding iface wlan0 to network 101
,E/WifiStateMachine(  824): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  824): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  824): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  824): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  824): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  824): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  824): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  824): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  824): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  824):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  824): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  824): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  824): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  824): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  824): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  824): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  824): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  824): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3055): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1362): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1362): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  824): getDataEnabled: retVal=false
,V/MusicLeanback( 3055): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  824): No APN found to select.
,I/ActivityManager(  824): Start proc 3953:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,D/SprintDMReceiver( 3807): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3807): simOperator:  IMSI: null
D/SprintDMReceiver( 3807): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  824): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 13:46:16 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454420776978], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454420776958]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  824): Validated
,D/ConnectivityService(  824): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  824): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  824): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  824): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  824): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/SystemUpdateService( 1774): onCreate
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.94 rxSuccessRate=10.19 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/ValidateNoPeople(  824): skipping global notification
,V/GoogleAuthProtoRequest( 3091): [306] a.<init>: mAccountName set to: thalitester@gmail.com
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1774): num queued entries: 0
,I/iu.UploadsManager( 1774): num updated entries: 0
,I/iu.SyncManager( 1774): NEXT; no task
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599990 ms
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/SystemUpdateService( 1774): onDestroy
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3223): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3223): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3223): 	at jdm.a(PG:82)
E/HttpOperation( 3223): 	at jcs.o(PG:406)
E/HttpOperation( 3223): 	at jcn.a(PG:1379)
E/HttpOperation( 3223): 	at jcs.i(PG:143)
E/HttpOperation( 3223): 	at blb.a(PG:3937)
E/HttpOperation( 3223): 	at czp.a(PG:18188)
E/HttpOperation( 3223): 	at czp.a(PG:9081)
E/HttpOperation( 3223): 	at czq.run(PG:1686)
E/HttpOperation( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3223): 	at jdj.a(PG:4091)
E/HttpOperation( 3223): 	at jdj.a(PG:1125)
E/HttpOperation( 3223): 	at jdm.a(PG:77)
E/HttpOperation( 3223): 	... 12 more
E/HttpOperation( 3223): Caused by: faj: BadAuthentication
E/HttpOperation( 3223): 	at fal.a(PG:38)
E/HttpOperation( 3223): 	at jdj.a(PG:4089)
E/HttpOperation( 3223): 	... 14 more
,I/Babel   ( 2789): connection state changed from DISCONNECTED to CONNECTED
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1774): NQAS connected
,W/ExperimentUpdateService( 3091): [306] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3091): [306] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3091): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3091): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3091): 	at com.a.a.k.run(SourceFile:110)
,W/Kids    ( 1774): [AccountUtils] Account not ready
W/Kids    ( 1774): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1774): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1774): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1774): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1774): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1774): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1774): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1774): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1774): 	at java.lang.Thread.run(Thread.java:818)
,E/HttpOperation( 3223): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3223): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3223): 	at jdm.a(PG:82)
E/HttpOperation( 3223): 	at jcs.o(PG:406)
E/HttpOperation( 3223): 	at jcn.a(PG:1379)
E/HttpOperation( 3223): 	at jcs.i(PG:143)
E/HttpOperation( 3223): 	at hec.a(PG:42)
E/HttpOperation( 3223): 	at hee.a(PG:102)
E/HttpOperation( 3223): 	at czr.a(PG:65)
E/HttpOperation( 3223): 	at kka.a(PG:108)
E/HttpOperation( 3223): 	at czp.a(PG:19176)
E/HttpOperation( 3223): 	at czp.a(PG:9081)
E/HttpOperation( 3223): 	at czq.run(PG:1686)
E/HttpOperation( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3223): 	at jdj.a(PG:4091)
E/HttpOperation( 3223): 	at jdj.a(PG:1125)
E/HttpOperation( 3223): 	at jdm.a(PG:77)
E/HttpOperation( 3223): 	... 15 more
E/HttpOperation( 3223): Caused by: faj: BadAuthentication
E/HttpOperation( 3223): 	at fal.a(PG:38)
E/HttpOperation( 3223): 	at jdj.a(PG:4089)
E/HttpOperation( 3223): 	... 17 more
E/ExperimentLoader( 3223): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3223): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3223): 	at jdm.a(PG:82)
E/ExperimentLoader( 3223): 	at jcs.o(PG:406)
E/ExperimentLoader( 3223): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3223): 	at jcs.i(PG:143)
E/ExperimentLoader( 3223): 	at hec.a(PG:42)
E/ExperimentLoader( 3223): 	at hee.a(PG:102)
E/ExperimentLoader( 3223): 	at czr.a(PG:65)
E/ExperimentLoader( 3223): 	at kka.a(PG:108)
E/ExperimentLoader( 3223): 	at czp.a(PG:19176)
E/ExperimentLoader( 3223): 	at czp.a(PG:9081)
E/ExperimentLoader( 3223): 	at czq.run(PG:1686)
E/ExperimentLoader( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3223): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3223): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3223): 	at jdm.a(PG:77)
E/ExperimentLoader( 3223): 	... 15 more
E/ExperimentLoader( 3223): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3223): 	at fal.a(PG:38)
E/ExperimentLoader( 3223): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3223): 	... 17 more
,D/GCM     ( 1256): Connected
,D/GCM     ( 1256): Message class com.google.f.a.a.p
,V/KeepSync( 3953): Connecting to GoogleApiClient
D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 74783, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  824): Start proc 3994:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3953): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1256): Explicit concurrent mark sweep GC freed 20794(1152KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 805us total 21.316ms
,I/jxcore-log( 3745): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3745): 
W/GAV2    ( 3994): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3994): Created application version: 3.6.8 (30608)
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,E/KeepSync( 3953): IOException
E/KeepSync( 3953): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3953): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3953): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3953): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3953): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3953): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3953): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3953): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3953): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3953): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3953): 	... 10 more
W/KeepSync( 3953): Sync result 2
,I/jxcore-log( 3745): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3745): 
I/jxcore-log( 3745): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3745): 
,I/art     (  824): Explicit concurrent mark sweep GC freed 40952(1940KB) AllocSpace objects, 6(96KB) LOS objects, 31% free, 34MB/50MB, paused 1.478ms total 50.860ms
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 74824, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430)
I/jxcore-log( 3745): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3745): 
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/jxcore-log( 3745): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3745): 
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3994): Soft error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3994): Sync error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3994): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 76720, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  824): Killing 3417:com.google.android.gm/u0a78 (adj 15): empty #17
,D/ConnectivityService(  824): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  824): Killing 3645:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/GAV2    ( 3994): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3745): Test app app.js loaded
I/jxcore-log( 3745): ,
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@371bd42b added. We now have 1 listener(s)
,I/jxcore-log( 3745): BLE advertisement is supported
I/jxcore-log( 3745): 
,I/chromium( 3745): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.73 rxSuccessRate=11.30 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,D/Finsky  ( 3605): [384] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3605): [384] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3605): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3605): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3605): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.90 rxSuccessRate=2.35 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3605): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3605): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3605): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.66 rxSuccessRate=2.77 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  824): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,V/KeepSync( 3953): Connecting to GoogleApiClient
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3223): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3223): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3223): 	at jdm.a(PG:82)
E/HttpOperation( 3223): 	at jcs.o(PG:406)
E/HttpOperation( 3223): 	at jcn.a(PG:1379)
E/HttpOperation( 3223): 	at jcs.i(PG:143)
E/HttpOperation( 3223): 	at blb.a(PG:3937)
E/HttpOperation( 3223): 	at czp.a(PG:18188)
E/HttpOperation( 3223): 	at czp.a(PG:9081)
E/HttpOperation( 3223): 	at czq.run(PG:1686)
E/HttpOperation( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3223): 	at jdj.a(PG:4091)
E/HttpOperation( 3223): 	at jdj.a(PG:1125)
E/HttpOperation( 3223): 	at jdm.a(PG:77)
E/HttpOperation( 3223): 	... 12 more
E/HttpOperation( 3223): Caused by: faj: BadAuthentication
E/HttpOperation( 3223): 	at fal.a(PG:38)
E/HttpOperation( 3223): 	at jdj.a(PG:4089)
E/HttpOperation( 3223): 	... 14 more
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3953): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3223): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3223): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3223): 	at jdm.a(PG:82)
E/HttpOperation( 3223): 	at jcs.o(PG:406)
E/HttpOperation( 3223): 	at jcn.a(PG:1379)
E/HttpOperation( 3223): 	at jcs.i(PG:143)
E/HttpOperation( 3223): 	at hec.a(PG:42)
E/HttpOperation( 3223): 	at hee.a(PG:102)
E/HttpOperation( 3223): 	at czr.a(PG:65)
E/HttpOperation( 3223): 	at kka.a(PG:108)
E/HttpOperation( 3223): 	at czp.a(PG:19176)
E/HttpOperation( 3223): 	at czp.a(PG:9081)
E/HttpOperation( 3223): 	at czq.run(PG:1686)
E/HttpOperation( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3223): 	at jdj.a(PG:4091)
E/HttpOperation( 3223): 	at jdj.a(PG:1125)
E/HttpOperation( 3223): 	at jdm.a(PG:77)
E/HttpOperation( 3223): 	... 15 more
E/HttpOperation( 3223): Caused by: faj: BadAuthentication
E/HttpOperation( 3223): 	at fal.a(PG:38)
E/HttpOperation( 3223): 	at jdj.a(PG:4089)
E/HttpOperation( 3223): 	... 17 more
,E/ExperimentLoader( 3223): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3223): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3223): 	at jdm.a(PG:82)
E/ExperimentLoader( 3223): 	at jcs.o(PG:406)
E/ExperimentLoader( 3223): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3223): 	at jcs.i(PG:143)
E/ExperimentLoader( 3223): 	at hec.a(PG:42)
E/ExperimentLoader( 3223): 	at hee.a(PG:102)
E/ExperimentLoader( 3223): 	at czr.a(PG:65)
E/ExperimentLoader( 3223): 	at kka.a(PG:108)
E/ExperimentLoader( 3223): 	at czp.a(PG:19176)
E/ExperimentLoader( 3223): 	at czp.a(PG:9081)
E/ExperimentLoader( 3223): 	at czq.run(PG:1686)
E/ExperimentLoader( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3223): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3223): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3223): 	at jdm.a(PG:77)
E/ExperimentLoader( 3223): 	... 15 more
E/ExperimentLoader( 3223): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3223): 	at fal.a(PG:38)
E/ExperimentLoader( 3223): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3223): 	... 17 more
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3953): IOException
E/KeepSync( 3953): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3953): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3953): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3953): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3953): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3953): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3953): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3953): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3953): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3953): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3953): 	... 10 more
W/KeepSync( 3953): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 115378, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 113206, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  824): Explicit concurrent mark sweep GC freed 46483(2MB) AllocSpace objects, 15(334KB) LOS objects, 31% free, 34MB/50MB, paused 1.538ms total 91.897ms
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3994): Soft error
,E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3994): Sync error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3994): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 115448, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1235): run()
I/Keyboard.Facilitator( 1235): flushDynamicLanguageModels()
,I/ConfigService( 1256): onCreate
,I/art     ( 1256): Explicit concurrent mark sweep GC freed 30815(1927KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 2.246ms total 42.217ms
,V/GoogleAuthProtoRequest( 3091): [307] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3091): [307] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3091): [307] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3091): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3091): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3091): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1256): Using platform SSLCertificateSocketFactory
,W/Uploader( 1256): No account for auth token provided
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3605): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3605): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3605): [1] 5.onFinished: Scheduling replication attempt 4.
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1256): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1256): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,E/Uploader( 1256): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
,E/Uploader( 1256): ,	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:235),
,E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
,E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
,E/Uploader( 1256): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1256): No account for auth token provided
,W/Uploader( 1256): No account for auth token provided
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1256): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1256): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
E/Uploader( 1256): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1256): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1256): No account for auth token provided
,W/Uploader( 1256): No account for auth token provided
,W/Uploader( 1256): No account for auth token provided
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1256): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1256): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1256): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1256): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1256): No account for auth token provided
,W/Uploader( 1256): No account for auth token provided,
,W/Uploader( 1256): No account for auth token provided
,W/Uploader( 1256): No account for auth token provided
,I/ConfigService( 1256): onDestroy
,W/Uploader( 1256):  no longer exists, so no auth token.
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1256): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1256): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1256): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1256): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1256): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1256): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1256): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1256): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1256): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1256): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=11.53 rxSuccessRate=8.56 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  824): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.47 rxSuccessRate=2.09 targetRoamBSSID=any RSSI=-51
,I/PowerManagerService(  824): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  824): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (205 us)
,I/DisplayManagerService(  824): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  279): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  824): Display changed displayId=0
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  279): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  824): Excessive delay in setPowerMode(): 275ms
,I/DreamManagerService(  824): Entering dreamland.
,I/PowerManagerService(  824): Dozing...
,I/DreamController(  824): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  824): cancelDelayedScan -> 12
,E/native  (  824): do suspend false
,I/Keyboard.Facilitator( 1235): onFinishInput()
,E/WifiStateMachine(  824): cancelDelayedScan -> 14
,E/native  (  824): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3605): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3605): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 3605): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  872): STATUS: Received file 'm9kefs1'
I/kickstart(  872): STATUS: 950272 bytes transferred in 0.994192 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,V/GoogleAuthProtoRequest( 3091): [308] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3091): [308] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3091): [308] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3091): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3091): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3091): 	at com.a.a.k.run(SourceFile:110)
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3605): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3605): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3605): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0,
,I/art     (  824): Explicit concurrent mark sweep GC freed 43981(2MB) AllocSpace objects, 12(474KB) LOS objects, 31% free, 34MB/50MB, paused 2.324ms total 94.550ms
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3223): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3223): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3223): 	at jdm.a(PG:82)
E/HttpOperation( 3223): 	at jcs.o(PG:406)
E/HttpOperation( 3223): 	at jcn.a(PG:1379)
E/HttpOperation( 3223): 	at jcs.i(PG:143)
E/HttpOperation( 3223): 	at blb.a(PG:3937)
E/HttpOperation( 3223): 	at czp.a(PG:18188)
E/HttpOperation( 3223): 	at czp.a(PG:9081)
E/HttpOperation( 3223): 	at czq.run(PG:1686)
E/HttpOperation( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3223): 	at jdj.a(PG:4091)
E/HttpOperation( 3223): 	at jdj.a(PG:1125)
E/HttpOperation( 3223): 	at jdm.a(PG:77)
E/HttpOperation( 3223): 	... 12 more
E/HttpOperation( 3223): Caused by: faj: BadAuthentication
E/HttpOperation( 3223): 	at fal.a(PG:38)
E/HttpOperation( 3223): 	at jdj.a(PG:4089)
E/HttpOperation( 3223): 	... 14 more
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3223): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3223): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3223): 	at jdm.a(PG:82)
E/HttpOperation( 3223): 	at jcs.o(PG:406)
E/HttpOperation( 3223): 	at jcn.a(PG:1379)
E/HttpOperation( 3223): 	at jcs.i(PG:143)
E/HttpOperation( 3223): 	at hec.a(PG:42)
E/HttpOperation( 3223): 	at hee.a(PG:102)
E/HttpOperation( 3223): 	at czr.a(PG:65)
E/HttpOperation( 3223): 	at kka.a(PG:108)
E/HttpOperation( 3223): 	at czp.a(PG:19176)
E/HttpOperation( 3223): 	at czp.a(PG:9081)
E/HttpOperation( 3223): 	at czq.run(PG:1686)
E/HttpOperation( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3223): 	at jdj.a(PG:4091)
E/HttpOperation( 3223): 	at jdj.a(PG:1125)
E/HttpOperation( 3223): 	at jdm.a(PG:77)
E/HttpOperation( 3223): 	... 15 more
E/HttpOperation( 3223): Caused by: faj: BadAuthentication
E/HttpOperation( 3223): 	at fal.a(PG:38)
E/HttpOperation( 3223): 	at jdj.a(PG:4089)
E/HttpOperation( 3223): 	... 17 more
,E/ExperimentLoader( 3223): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3223): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3223): 	at jdm.a(PG:82)
E/ExperimentLoader( 3223): 	at jcs.o(PG:406)
E/ExperimentLoader( 3223): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3223): 	at jcs.i(PG:143)
E/ExperimentLoader( 3223): 	at hec.a(PG:42)
E/ExperimentLoader( 3223): 	at hee.a(PG:102)
E/ExperimentLoader( 3223): 	at czr.a(PG:65)
E/ExperimentLoader( 3223): 	at kka.a(PG:108)
E/ExperimentLoader( 3223): 	at czp.a(PG:19176)
E/ExperimentLoader( 3223): 	at czp.a(PG:9081)
E/ExperimentLoader( 3223): 	at czq.run(PG:1686)
E/ExperimentLoader( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3223): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3223): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3223): 	at jdm.a(PG:77)
E/ExperimentLoader( 3223): 	... 15 more
E/ExperimentLoader( 3223): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3223): 	at fal.a(PG:38)
E/ExperimentLoader( 3223): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3223): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 193882, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1235): run()
I/Keyboard.Facilitator( 1235): flushDynamicLanguageModels()
,I/ConfigService( 1256): onCreate
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3953): Connecting to GoogleApiClient
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3953): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1256): Explicit concurrent mark sweep GC freed 62461(3MB) AllocSpace objects, 11(1127KB) LOS objects, 36% free, 27MB/43MB, paused 1.253ms total 28.819ms
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3994): Soft error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3994): Sync error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3994): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 197890, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3953): IOException
E/KeepSync( 3953): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3953): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3953): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3953): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3953): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3953): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3953): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3953): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3953): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3953): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3953): 	... 10 more
,W/KeepSync( 3953): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 197695, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1256): onDestroy
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3091): [309] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3091): [309] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3091): [309] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3091): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3091): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3091): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3091): [310] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3091): [310] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3091): [310] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3091): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3091): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3091): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3745): TAP version 13
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # multiplex can send data
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 1 String should be length:200
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # enqueue and run in order
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 2 firstPromise setTimeout
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 3 firstPromise result
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 4 firstPromise testValue
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 5 secondPromise setTimeout
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 6 secondPromise result
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 7 secondPromise testValue
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 8 thirdPromise in promise
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 9 thirdPromise result
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 10 thirdPromise testValue
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # basic
,I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 11 sane
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # another
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 12 sane
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 13 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 14 null
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 15 (unnamed assert)
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 16 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 17 should not throw
I/jxcore-log( 3745): 
I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 18 (unnamed assert)
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 19 (unnamed assert)
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 20 should not throw
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 21 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 22 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 23 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # failed to get mobile documents path
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 24 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 25 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 26 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 27 should be equal
I/jxcore-log( 3745): 
I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #init should register the networkChanged event
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 28 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #startBroadcasting should throw on null device name
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 29 should throw
,I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #startBroadcasting should throw on empty string device name,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 30 should throw,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3745): ,
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 31 should throw
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 32 should throw
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #startBroadcasting should throw on negative port
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): ,
,I/jxcore-log( 3745): ok 33 should throw,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #startBroadcasting should throw on too large port,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 34 should throw,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #startBroadcasting should call Mobile("StartBroadcasting") without an error,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 35 should be equal,
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 36 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 37 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 38 should be equal
I/jxcore-log( 3745): 
I/jxcore-log( 3745): ok 39 should be equal
I/jxcore-log( 3745): 
I/jxcore-log( 3745): ok 40 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 41 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 42 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 43 should be equal
I/jxcore-log( 3745): 
I/jxcore-log( 3745): ok 44 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 45 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 46 should be equal
I/jxcore-log( 3745): 
I/jxcore-log( 3745): ok 47 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 48 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 49 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
,I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 50 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 51 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
,I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 52 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): ok 53 should be equal
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # setup
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3745): 
,I/jxcore-log( 3745): # teardown
I/jxcore-log( 3745): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): load: ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): 	,Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c0a088 added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): setDiscoveryMode: BLE_AND_WIFI -> WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454420991287.3745
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): bind: Binding a new listener
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3745): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991287.3745","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): start: OK
I/io.jxcore.node.ConnectionHelper( 3745): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3745): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454420991287.3745, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3745): bind: Binding a new listener
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,W/BluetoothAdapter( 3745): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3745): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3745): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991287.3745","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991287.3745","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3745): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991287.3745","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onIsWifiPeerDiscoveryStartedChanged: true,
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: OK
I/io.jxcore.node.ConnectionHelper( 3745): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454420991287.3745, mode: WIFI
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3745): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3745): 
I/io.jxcore.node.ConnectionHelper( 3745): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3745): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3745): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: OK,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3745): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3745): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3745): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3745): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): setState: STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3745): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3745): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3745): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3745): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 3745): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): ,	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@173f175d added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3745): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/wpa_supplicant( 1130): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): P2P device discovery stopped successfully
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3745): Service requests cleared successfully
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454420991397.3745
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): bind: Binding a new listener
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3745): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991397.3745","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3745): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): start: OK
I/io.jxcore.node.ConnectionHelper( 3745): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3745): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454420991397.3745, mode: BLE_AND_WIFI,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3745): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3745): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3745): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3745): createAdvertiseData: From: 1454420991397.3745 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2157): registerClient() - UUID=b7b9ad91-a544-4279-87ee-47aa3a649ec5
,D/BtGatt.GattService( 2157): onClientRegistered() - UUID=b7b9ad91-a544-4279-87ee-47aa3a649ec5, clientIf=5
D/BluetoothLeScanner( 3745): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2157): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3745): setState: State changed from NOT_STARTED to STARTING
D/BtGatt.ScanManager( 2157): handling starting scan
D/BluetoothAdapterService( 2157): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b11f570
,D/BtGatt.GattService( 2157): registerClient() - UUID=9ef6314b-26d5-4458-b463-9d3546029cb7
D/BtGatt.GattService( 2157): onClientRegistered() - UUID=9ef6314b-26d5-4458-b463-9d3546029cb7, clientIf=6
,D/BluetoothLeAdvertiser( 3745): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2157): message : 0,
D/BtGatt.GattService( 2157): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2157): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2157): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2157): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2157): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2157): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/BtGatt.AdvertiseManager( 2157): starting multi advertising
,D/BtGatt.GattService( 2157): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2157): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3745): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991397.3745","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991397.3745","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3745): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991397.3745","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: OK,
,I/io.jxcore.node.ConnectionHelper( 3745): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454420991397.3745, mode: BLE_AND_WIFI
I/wpa_supplicant( 1130): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3745): createAdvertiseData: From: 1454420991397.3745 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/jxcore-log( 3745): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 3745): 
,D/BtGatt.AdvertiseManager( 2157): message : 1
,D/BtGatt.AdvertiseManager( 2157): stop advertise for client 6
I/io.jxcore.node.ConnectionHelper( 3745): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3745): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3745): Exiting thread
,D/BtGatt.GattService( 2157): onAdvertiseInstanceDisabled() - clientIf=6, status=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): onServerStopped
D/BtGatt.GattService( 2157): Client app is not null!
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): setState: NOT_STARTED
D/BtGatt.GattService( 2157): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2157): registerClient() - UUID=b0d172a3-e2be-4565-a0f4-4869af1eb50f
D/BtGatt.GattService( 2157): onClientRegistered() - UUID=b0d172a3-e2be-4565-a0f4-4869af1eb50f, clientIf=6
,D/BluetoothLeAdvertiser( 3745): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2157): message : 0
,D/BtGatt.AdvertiseManager( 2157): starting multi advertising
,D/BtGatt.GattService( 2157): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2157): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3745): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): start: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): start: Already running, call stopListening() first to restart,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): onStartSuccess
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3745): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3745): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): stop,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3745): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): setState: STARTED
I/wpa_supplicant( 1130): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 2157): message : 1
D/BtGatt.AdvertiseManager( 2157): stop advertise for client 6
D/BtGatt.GattService( 2157): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2157): Client app is not null!
D/BtGatt.GattService( 2157): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onIsBlePeerDiscovererStateChanged: [SCANNING]
,D/BtGatt.GattService( 2157): stopScan() - queue size =1
,D/BtGatt.GattService( 2157): unregisterClient() - clientIf=5,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3745): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3745): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): updateState(): State changed from [SCANNING] to [NOT_STARTED]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onIsBlePeerDiscovererStateChanged: [NOT_STARTED]
I/io.jxcore.node.ConnectionHelper( 3745): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): onIsAdvertiserStartedChanged: true,
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): updateState(): State changed from [NOT_STARTED] to [ADVERTISING_SELF]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): stop: Stopping P2P device discovery...
D/BtGatt.GattService( 2157): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2157): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2157): stop scan
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3745): Local services cleared successfully
,D/BtGatt.ScanManager( 2157): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2157): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2157): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3745): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3745): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3745): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3745): onDiscoveryManagerStateChanged: NOT_STARTED,
I/jxcore-log( 3745): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 3745): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): 	Connection timeout in milliseconds: 15000, ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): ,	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cbcfecc added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454420991541.3745
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): bind: Binding a new listener
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3745): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991541.3745","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): start: OK
I/io.jxcore.node.ConnectionHelper( 3745): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3745): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3745): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454420991541.3745, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3745): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3745): Waiting for incoming connections...
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3745): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991541.3745","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991541.3745","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3745): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991541.3745","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: OK
I/io.jxcore.node.ConnectionHelper( 3745): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454420991541.3745, mode: WIFI
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3745): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 3745): 
,I/io.jxcore.node.ConnectionHelper( 3745): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3745): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3745): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): setState: NOT_STARTED,
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3745): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): restart: Restarting...
I/wpa_supplicant( 1130): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3745): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3745): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3745): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): P2P device discovery started successfully
I/wpa_supplicant( 1130): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3745): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3745): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3745): clear,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3745): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3745): Service requests cleared successfully
,I/jxcore-log( 3745): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 3745): ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): load: 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): 	,Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3745): 	Maximum number of connection attempt retries: 0,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): load: 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Automate Bluetooth MAC address resolution: true, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): ,	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Peer expiration time in milliseconds: 60000, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Advertise TX power level: 1, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12213bb8 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3745): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454420991585.3745
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): bind: Binding a new listener
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3745): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991585.3745","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3745): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): start: OK
I/io.jxcore.node.ConnectionHelper( 3745): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3745): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454420991585.3745, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3745): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3745): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3745): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3745): createAdvertiseData: From: 1454420991585.3745 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,D/BtGatt.GattService( 2157): registerClient() - UUID=60b640e1-5bd3-464c-8049-3aa5b8ca9894
D/BtGatt.GattService( 2157): onClientRegistered() - UUID=60b640e1-5bd3-464c-8049-3aa5b8ca9894, clientIf=5
,D/BluetoothLeScanner( 3745): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2157): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3745): setState: State changed from NOT_STARTED to STARTING
,D/BtGatt.ScanManager( 2157): handling starting scan
,D/BtGatt.GattService( 2157): registerClient() - UUID=5e973ee6-265e-4d07-9f72-e9679c73007a
,D/BtGatt.GattService( 2157): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2157): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2157): onClientRegistered() - UUID=5e973ee6-265e-4d07-9f72-e9679c73007a, clientIf=6
D/BluetoothLeAdvertiser( 3745): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2157): message : 0
D/BtGatt.GattService( 2157): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2157): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2157): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2157): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648,
D/BtGatt.AdvertiseManager( 2157): starting multi advertising,
,D/BtGatt.GattService( 2157): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2157): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3745): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991585.3745","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991585.3745","ra":"F8:CF:C5:D9:E5:61"},
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3745): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454420991585.3745","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): setState: INITIALIZED,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3745): start: Starting P2P device discovery...,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): start: Already running, call stopListening() first to restart,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: OK
I/io.jxcore.node.ConnectionHelper( 3745): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454420991585.3745, mode: BLE_AND_WIFI,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3745): createAdvertiseData: From: 1454420991585.3745 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/jxcore-log( 3745): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 3745): ,
I/wpa_supplicant( 1130): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/io.jxcore.node.ConnectionHelper( 3745): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3745): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3745): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3745): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3745): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3745): setState: NOT_STARTED,
D/BtGatt.AdvertiseManager( 2157): message : 1
D/BtGatt.AdvertiseManager( 2157): stop advertise for client 6
D/BtGatt.GattService( 2157): onAdvertiseInstanceDisabled() - clientIf=6, status=0,
D/BtGatt.GattService( 2157): Client app is not null!
D/BtGatt.GattService( 2157): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2157): registerClient() - UUID=ae26294e-6e63-4af6-8dc0-2a85deec4646
,D/BtGatt.GattService( 2157): onClientRegistered() - UUID=ae26294e-6e63-4af6-8dc0-2a85deec4646, clientIf=6
D/BluetoothLeAdvertiser( 3745): onClientRegistered() - status=0 clientIf=6,
D/BtGatt.AdvertiseManager( 2157): message : 0
,D/BtGatt.AdvertiseManager( 2157): starting multi advertising
,D/BtGatt.GattService( 2157): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2157): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3745): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3745): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3745): stopForRestart
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3745): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): stop
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3745): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3745): onIsAdvertiserStartedChanged: true
,D/btif_config_util( 2157): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3223): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3223): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3223): 	at jdm.a(PG:82)
E/HttpOperation( 3223): 	at jcs.o(PG:406)
E/HttpOperation( 3223): 	at jcn.a(PG:1379)
E/HttpOperation( 3223): 	at jcs.i(PG:143)
E/HttpOperation( 3223): 	at blb.a(PG:3937)
E/HttpOperation( 3223): 	at czp.a(PG:18188)
E/HttpOperation( 3223): 	at czp.a(PG:9081)
E/HttpOperation( 3223): 	at czq.run(PG:1686)
E/HttpOperation( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3223): 	at jdj.a(PG:4091)
E/HttpOperation( 3223): 	at jdj.a(PG:1125)
E/HttpOperation( 3223): 	at jdm.a(PG:77)
E/HttpOperation( 3223): 	... 12 more
E/HttpOperation( 3223): Caused by: faj: BadAuthentication
E/HttpOperation( 3223): 	at fal.a(PG:38)
E/HttpOperation( 3223): 	at jdj.a(PG:4089)
E/HttpOperation( 3223): 	... 14 more
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3223): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3223): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3223): 	at jdm.a(PG:82)
E/HttpOperation( 3223): 	at jcs.o(PG:406)
E/HttpOperation( 3223): 	at jcn.a(PG:1379)
E/HttpOperation( 3223): 	at jcs.i(PG:143)
E/HttpOperation( 3223): 	at hec.a(PG:42)
E/HttpOperation( 3223): 	at hee.a(PG:102)
E/HttpOperation( 3223): 	at czr.a(PG:65)
E/HttpOperation( 3223): 	at kka.a(PG:108)
E/HttpOperation( 3223): 	at czp.a(PG:19176)
E/HttpOperation( 3223): 	at czp.a(PG:9081)
E/HttpOperation( 3223): 	at czq.run(PG:1686)
E/HttpOperation( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3223): 	at jdj.a(PG:4091)
E/HttpOperation( 3223): 	at jdj.a(PG:1125)
E/HttpOperation( 3223): 	at jdm.a(PG:77)
E/HttpOperation( 3223): 	... 15 more
E/HttpOperation( 3223): Caused by: faj: BadAuthentication
E/HttpOperation( 3223): 	at fal.a(PG:38)
E/HttpOperation( 3223): 	at jdj.a(PG:4089)
E/HttpOperation( 3223): 	... 17 more
,E/ExperimentLoader( 3223): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3223): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3223): 	at jdm.a(PG:82)
E/ExperimentLoader( 3223): 	at jcs.o(PG:406)
E/ExperimentLoader( 3223): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3223): 	at jcs.i(PG:143)
E/ExperimentLoader( 3223): 	at hec.a(PG:42)
E/ExperimentLoader( 3223): 	at hee.a(PG:102)
E/ExperimentLoader( 3223): 	at czr.a(PG:65)
E/ExperimentLoader( 3223): 	at kka.a(PG:108)
E/ExperimentLoader( 3223): 	at czp.a(PG:19176)
E/ExperimentLoader( 3223): 	at czp.a(PG:9081)
E/ExperimentLoader( 3223): 	at czq.run(PG:1686),
E/ExperimentLoader( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3223): ,	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3223): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3223): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3223): 	at jdm.a(PG:77)
E/ExperimentLoader( 3223): 	... 15 more
E/ExperimentLoader( 3223): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3223): 	at fal.a(PG:38)
E/ExperimentLoader( 3223): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3223): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 315907, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  824): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1e706803}
E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,D/WifiService(  824): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1e706803}
,I/art     (  824): Explicit concurrent mark sweep GC freed 38007(1763KB) AllocSpace objects, 11(741KB) LOS objects, 31% free, 34MB/50MB, paused 1.512ms total 94.948ms
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1256): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1256): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1256): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1256): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1256): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1256): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1256): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3605): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 3605): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024),
E/PlayEventLogger( 3605): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3605): 	,at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3605): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3605): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3605): Ignoring header User-Agent because its value was null.,
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3953): Connecting to GoogleApiClient
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3953): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3994): Soft error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3994): Sync error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3994): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 353300, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3953): IOException
E/KeepSync( 3953): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3953): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3953): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3953): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3953): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3953): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3953): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3953): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3953): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3953): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3953): 	... 10 more
W/KeepSync( 3953): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 353684, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 1130): P2P-FIND-STOPPED 
,E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3091): [311] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3091): [311] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3091): [311] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3091): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3091): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3091): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3091): [312] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3091): [312] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3091): [312] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3091): ,	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3091): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3091): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3091): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,I/art     ( 1256): Explicit concurrent mark sweep GC freed 53816(2MB) AllocSpace objects, 14(1543KB) LOS objects, 36% free, 27MB/43MB, paused 1.726ms total 44.559ms
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3223): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3223): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3223): 	at jdm.a(PG:82)
E/HttpOperation( 3223): 	at jcs.o(PG:406)
E/HttpOperation( 3223): 	at jcn.a(PG:1379)
E/HttpOperation( 3223): 	at jcs.i(PG:143)
E/HttpOperation( 3223): 	at blb.a(PG:3937)
E/HttpOperation( 3223): 	at czp.a(PG:18188)
E/HttpOperation( 3223): 	at czp.a(PG:9081)
E/HttpOperation( 3223): 	at czq.run(PG:1686)
E/HttpOperation( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3223): 	at jdj.a(PG:4091)
E/HttpOperation( 3223): 	at jdj.a(PG:1125)
E/HttpOperation( 3223): 	at jdm.a(PG:77)
E/HttpOperation( 3223): 	... 12 more
E/HttpOperation( 3223): Caused by: faj: BadAuthentication
E/HttpOperation( 3223): 	at fal.a(PG:38)
E/HttpOperation( 3223): 	at jdj.a(PG:4089)
E/HttpOperation( 3223): 	... 14 more
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3223): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3223): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3223): 	at jdm.a(PG:82)
E/HttpOperation( 3223): 	at jcs.o(PG:406)
E/HttpOperation( 3223): 	at jcn.a(PG:1379)
E/HttpOperation( 3223): 	at jcs.i(PG:143)
E/HttpOperation( 3223): 	at hec.a(PG:42)
E/HttpOperation( 3223): 	at hee.a(PG:102)
E/HttpOperation( 3223): 	at czr.a(PG:65)
E/HttpOperation( 3223): 	at kka.a(PG:108)
E/HttpOperation( 3223): 	at czp.a(PG:19176)
E/HttpOperation( 3223): 	at czp.a(PG:9081)
E/HttpOperation( 3223): 	at czq.run(PG:1686)
E/HttpOperation( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3223): 	at jdj.a(PG:4091)
E/HttpOperation( 3223): 	at jdj.a(PG:1125)
E/HttpOperation( 3223): 	at jdm.a(PG:77)
E/HttpOperation( 3223): 	... 15 more
E/HttpOperation( 3223): Caused by: faj: BadAuthentication
E/HttpOperation( 3223): 	at fal.a(PG:38)
E/HttpOperation( 3223): 	at jdj.a(PG:4089)
E/HttpOperation( 3223): 	... 17 more
E/ExperimentLoader( 3223): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3223): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3223): 	at jdm.a(PG:82)
E/ExperimentLoader( 3223): 	at jcs.o(PG:406)
E/ExperimentLoader( 3223): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3223): 	at jcs.i(PG:143)
E/ExperimentLoader( 3223): 	at hec.a(PG:42)
E/ExperimentLoader( 3223): 	at hee.a(PG:102)
E/ExperimentLoader( 3223): 	at czr.a(PG:65)
E/ExperimentLoader( 3223): 	at kka.a(PG:108)
E/ExperimentLoader( 3223): 	at czp.a(PG:19176)
E/ExperimentLoader( 3223): 	at czp.a(PG:9081)
E/ExperimentLoader( 3223): 	at czq.run(PG:1686)
E/ExperimentLoader( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3223): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3223): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3223): 	at jdm.a(PG:77)
E/ExperimentLoader( 3223): 	... 15 more
E/ExperimentLoader( 3223): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3223): 	at fal.a(PG:38)
E/ExperimentLoader( 3223): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3223): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 559709, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,I/art     (  824): Explicit concurrent mark sweep GC freed 34148(1506KB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 2.279ms total 84.711ms
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3994): Soft error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3994): Sync error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3994): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 634432, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3953): Connecting to GoogleApiClient
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1774): Handling authorization failure,
,E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication,
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): ,	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
,E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
,E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): ,	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3953): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3953): IOException
E/KeepSync( 3953): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3953): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3953): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3953): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3953): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3953): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3953): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3953): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3953): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3953): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3953): 	... 10 more
W/KeepSync( 3953): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 635035, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,I/ActivityManager(  824): Start proc 4254:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4254): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4254):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4254):   adb logcat -s GAv4
,W/GAv4    ( 4254): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4254): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4254): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  824): Killing 2496:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3091): [313] a.<init>: mAccountName set to: thalitester@gmail.com
,I/EventLogService( 1774): Opted in for usage reporting
I/EventLogService( 1774): Aggregate from 1454419861679 (log), 1454419861679 (data)
,W/EventLogAggregator( 1774): Unknown tag: snet_gcore
W/EventLogAggregator( 1774): Unknown tag: snet_launch_service
,V/GoogleAuthProtoRequest( 3091): [314] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ServiceDumpSys( 1774): dumping service [account]
,D/GCM     ( 1256): Message class com.google.f.a.a.i
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3091): [314] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3091): [314] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3091): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3091): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3091): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3091): [313] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3091): [313] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3091): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3091): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3091): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3091): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3091): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3223): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3223): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3223): 	at jdm.a(PG:82)
E/HttpOperation( 3223): 	at jcs.o(PG:406)
E/HttpOperation( 3223): 	at jcn.a(PG:1379)
E/HttpOperation( 3223): 	at jcs.i(PG:143)
E/HttpOperation( 3223): 	at blb.a(PG:3937)
E/HttpOperation( 3223): 	at czp.a(PG:18188)
E/HttpOperation( 3223): 	at czp.a(PG:9081)
E/HttpOperation( 3223): 	at czq.run(PG:1686)
E/HttpOperation( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3223): 	at jdj.a(PG:4091)
E/HttpOperation( 3223): 	at jdj.a(PG:1125)
E/HttpOperation( 3223): 	at jdm.a(PG:77)
E/HttpOperation( 3223): 	... 12 more
E/HttpOperation( 3223): Caused by: faj: BadAuthentication
E/HttpOperation( 3223): 	at fal.a(PG:38)
E/HttpOperation( 3223): 	at jdj.a(PG:4089)
E/HttpOperation( 3223): 	... 14 more
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3223): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3223): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3223): 	at jdm.a(PG:82)
E/HttpOperation( 3223): 	at jcs.o(PG:406)
E/HttpOperation( 3223): 	at jcn.a(PG:1379)
E/HttpOperation( 3223): 	at jcs.i(PG:143)
E/HttpOperation( 3223): 	at hec.a(PG:42)
E/HttpOperation( 3223): 	at hee.a(PG:102)
E/HttpOperation( 3223): 	at czr.a(PG:65)
E/HttpOperation( 3223): 	at kka.a(PG:108)
E/HttpOperation( 3223): 	at czp.a(PG:19176)
E/HttpOperation( 3223): 	at czp.a(PG:9081)
E/HttpOperation( 3223): 	at czq.run(PG:1686)
E/HttpOperation( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3223): 	at jdj.a(PG:4091)
E/HttpOperation( 3223): 	at jdj.a(PG:1125)
E/HttpOperation( 3223): 	at jdm.a(PG:77)
E/HttpOperation( 3223): 	... 15 more
E/HttpOperation( 3223): Caused by: faj: BadAuthentication
E/HttpOperation( 3223): 	at fal.a(PG:38)
,E/HttpOperation( 3223): 	at jdj.a(PG:4089)
E/HttpOperation( 3223): 	... 17 more
E/ExperimentLoader( 3223): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3223): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3223): 	at jdm.a(PG:82)
E/ExperimentLoader( 3223): 	at jcs.o(PG:406)
E/ExperimentLoader( 3223): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3223): 	at jcs.i(PG:143)
E/ExperimentLoader( 3223): 	at hec.a(PG:42)
E/ExperimentLoader( 3223): 	at hee.a(PG:102)
E/ExperimentLoader( 3223): 	at czr.a(PG:65)
,E/ExperimentLoader( 3223): 	at kka.a(PG:108)
E/ExperimentLoader( 3223): 	at czp.a(PG:19176)
E/ExperimentLoader( 3223): 	at czp.a(PG:9081)
E/ExperimentLoader( 3223): 	at czq.run(PG:1686)
E/ExperimentLoader( 3223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3223): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3223): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3223): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3223): 	at jdj.a(PG:1125),
E/ExperimentLoader( 3223): 	at jdm.a(PG:77)
E/ExperimentLoader( 3223): 	... 15 more
E/ExperimentLoader( 3223): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3223): 	at fal.a(PG:38)
E/ExperimentLoader( 3223): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3223): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1046636, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,I/art     ( 1256): Explicit concurrent mark sweep GC freed 60079(2MB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 26MB/42MB, paused 923us total 47.050ms
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,I/art     (  824): Explicit concurrent mark sweep GC freed 42540(2018KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 3.218ms total 108.251ms
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3994): Soft error,
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3994): Sync error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3994): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1150869, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btm  ( 2157): Request to stop oneshot timer with non empty queue
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,V/KeepSync( 3953): Connecting to GoogleApiClient
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3953): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3953): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1256): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1256): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1256): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1256): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1256): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3953): IOException
E/KeepSync( 3953): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3953): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3953): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3953): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3953): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3953): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3953): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3953): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3953): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3953): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3953): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3953): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3953): 	... 10 more
W/KeepSync( 3953): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1182058, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/UsageStatsService(  824): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2157): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4357): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4357): CheckJNI is OFF
D/AndroidRuntime( 4357): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  824): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  824): Killing 3745:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  824): Skipping PackageSetting{3a14bc9f com.example.hello/10273} due to missing metadata
E/libprocessgroup(  824): failed to kill 1 processes for processgroup 3745
W/ActivityManager(  824): Force removing ActivityRecord{246e8a34 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
E/JavaBinder(  824): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  824): !!! FAILED BINDER TRANSACTION !!!
D/BtGatt.GattService( 2157): Binder is dead - unregistering client (6)!
D/WifiService(  824): Client connection lost with reason: 4
D/BtGatt.GattService( 2157): Binder is dead - unregistering client (5)!
D/BtGatt.AdvertiseManager( 2157): message : 1
D/BtGatt.AdvertiseManager( 2157): stop advertise for client 6
D/BtGatt.GattService( 2157): stopScan() - queue size =1
D/BtGatt.AdvertiseManager( 2157): app died - unregistering client : 6
D/BtGatt.GattService( 2157): unregisterClient() - clientIf=6
V/ActivityManager(  824): Display changed displayId=0
D/BtGatt.GattService( 2157): onAdvertiseInstanceDisabled() - clientIf=255, status=0
E/BtGatt.ContextMap( 2157): Context not found for ID 255
D/BtGatt.GattService( 2157): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2157): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2157): stop scan
D/BtGatt.ScanManager( 2157): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2157): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2157): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.ScanManager( 2157): app died, unregister client - 5
D/BtGatt.GattService( 2157): unregisterClient() - clientIf=5
I/ActivityManager(  824): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
I/art     ( 1510): Explicit concurrent mark sweep GC freed 2989(209KB) AllocSpace objects, 1(24KB) LOS objects, 22% free, 26MB/34MB, paused 544us total 39.459ms
I/InputReader(  824): Reconfiguring input devices.  changes=0x00000010
D/TaskPersister(  824): removeObsoleteFile: deleting file=28_task.xml
D/BuaReceiver( 3486): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator( 1235): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1235): run()
I/Decoder ( 1235): createOrResetDecoder
I/art     ( 1067): Explicit concurrent mark sweep GC freed 73949(2MB) AllocSpace objects, 0(0B) LOS objects, 13% free, 102MB/118MB, paused 1.776ms total 77.522ms
I/ActivityManager(  824): Start proc 4373:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     (  824): Explicit concurrent mark sweep GC freed 27024(1548KB) AllocSpace objects, 10(348KB) LOS objects, 31% free, 34MB/50MB, paused 1.116ms total 94.615ms
I/ConfigService( 1256): onCreate
W/InputMethodManagerService(  824): Got RemoteException sending setActive(false) notification to pid 3745 uid 10265
I/Keyboard.Facilitator( 1235): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1235): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1235): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1235): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1235): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1235): run()
I/StatsUtilsManager( 1235): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1235): shouldRecordStats() = Too Soon
I/art     ( 1388): Explicit concurrent mark sweep GC freed 5086(371KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 927us total 23.714ms
W/LocationOracleImpl( 1510): Best location was null
I/HotwordRecognitionRnr( 1510): Starting hotword detection.
I/MicrophoneInputStream( 1510): mic_starting com.google.android.apps.gsa.speech.audio.u@2d2f42f4
I/AudioFlinger(  358): AudioFlinger's thread 0xb40ed000 ready to run
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1510): mic_started com.google.android.apps.gsa.speech.audio.u@2d2f42f4
D/JobSchedulerService(  824): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  824): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
D/VoicemailCleanupService( 4373): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  824): Start proc 4409:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/ContactLocale( 4373): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  824): Explicit concurrent mark sweep GC freed 8238(387KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 2.305ms total 163.591ms
I/HotwordWorker( 1510): onReady
D/WifiService(  824): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@33e8f7f2}
E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=40.75 rxSuccessRate=64.75 targetRoamBSSID=any RSSI=-51
I/ActivityManager(  824): Start proc 4430:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/art     ( 1791): Explicit concurrent mark sweep GC freed 16544(988KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 4.572ms total 31.221ms
E/DataBuffer( 1791): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3b764cbd)
I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 10.985ms
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 9.433ms
E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=24.38 rxSuccessRate=153.88 targetRoamBSSID=any RSSI=-51
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 9.740ms
W/ContextImpl( 4430): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1256): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1256): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1721218323
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
D/Launcher.Workspace( 1388): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1388): 11683562 - stripEmptyScreens()
I/ActivityManager(  824): Killing 3399:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1774): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1774): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1774): Clearing selected account for com.test.thalitest
I/art     ( 4357): System.exit called, status: 0
I/AndroidRuntime( 4357): VM exiting with result code 0.
I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1774): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1774): Removing dialog suppression flag for package com.test.thalitest
W/Launcher( 1388): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2d3fe67a new=com.google.android.velvet.VelvetApplication@2d3fe67a
I/UpdateIcingCorporaServi( 1510): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/GOOGLEHELP_CompatibleDatabase( 1774): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1774): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1774): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1774): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1774): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1774): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
E/SQLiteLog( 1774): (3850) statement aborts at 21: [DELETE FROM help_responses WHERE app_package_name="com.test.thalitest"] disk I/O error
D/GOOGLEHELP_CompatibleDatabase( 1774): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
--------- beginning of crash
E/AndroidRuntime( 1774): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1774): Process: com.google.android.gms, PID: 1774
E/AndroidRuntime( 1774): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1774): 	at com.google.android.gms.googlehelp.c.b.d(SourceFile:535)
E/AndroidRuntime( 1774): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
E/AndroidRuntime( 1774): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1774): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1774): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1774): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4373): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
E/SQLiteLog( 1510): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AndroidRuntime( 4373): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4373): Process: android.process.acore, PID: 4373
E/AndroidRuntime( 4373): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4373): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4373): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4373): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4373): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4373): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4373): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 4373): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 4373): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4373): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4373): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  824): Start proc 4463:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/ActivityManager(  824): Start proc 4480:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 1510): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 1510): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1510): Process: com.google.android.googlequicksearchbox:search, PID: 1510
E/AndroidRuntime( 1510): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1510): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1510): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1510): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1510): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1510): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1510): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1510): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1510): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1510): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1510): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1510): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1510): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1510): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1510): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1510): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1510): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1510): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1510): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  824): Start proc 4497:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/SQLiteDatabase( 1774): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1774): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1774): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1774): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1774): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1774): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1774): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1774): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1774): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1774): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1774): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  824): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  824): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  824): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  824): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  824): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  824): 	... 5 more
W/SQLiteOpenHelper( 1774): Opened phenotype.db in read-only mode
E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  824): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  824): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  824): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  824): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  824): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  824): 	... 5 more
D/OpenGLRenderer(  824): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  824): Validating map...
E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  824): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  824): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  824): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  824): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  824): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  824): 	... 5 more
W/ResourcesManager(  824): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  824): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ConfigFetchService( 1774): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1774): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
I/ConfigFetchService( 1774): service connected
W/ResourcesManager( 4497): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/BaseAppContext( 1774): Using Auth Proxy for data requests.
W/ResourcesManager( 4497): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/PeopleContactsSync( 1774): CP2 sync disabled
I/Icing   ( 1774): doRemovePackageData com.test.thalitest
W/BaseAppContext( 1774): Using Auth Proxy for data requests.
E/SQLiteDatabase( 1774): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1774): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1774): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1774): Runtime exception while performing operation
E/ClearPendingStateOp( 1774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1774): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1774): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1774): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1774): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1774): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1774): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1774): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1774): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1774): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1774): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1774): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1774): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  824): Can't write: system_app_wtf
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  824): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  824): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  824): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  824): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  824): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  824): 	... 5 more
I/OpenGLRenderer(  824): Initialized EGL, version 1.4
D/OpenGLRenderer(  824): Enabling debug mode 0
I/ActivityManager(  824): Killing 3376:com.android.providers.calendar/u0a3 (adj 15): empty #17
I/MultiDex( 4497): VM with version 2.1.0 has multidex support
I/MultiDex( 4497): install
I/MultiDex( 4497): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 4497): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/GFEEDBACK_SendErrorReportOperation( 1774): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 1774): Error saving report: java.io.IOException: failed to create reports directory
I/ProviderInstaller( 4497): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4497): Failed to open lock file
W/NativeLibraryUtils( 4497): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4497): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4497): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4497): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4497): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4497): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4497): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4497): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4497): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4497): 	... 3 more
I/ActivityManager(  824): Killing 3055:com.google.android.music:main/u0a66 (adj 15): empty #17
I/GAv4    ( 4463): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4463):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4463):   adb logcat -s GAv4
I/HotwordDetector( 1510): Closing mic
I/MicrophoneInputStream( 1510): mic_close com.google.android.apps.gsa.speech.audio.u@2d2f42f4
W/GAv4    ( 4463): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Search.SharedPreferencesProto( 1510): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
W/GAv4    ( 4463): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4463): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4463): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
E/SQLiteDatabase( 4463): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4463): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4463): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4463): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4463): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4463): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4463): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4463): 	at aen.run(PG:536)
E/SQLiteDatabase( 4463): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4463): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4463): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4463): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4463): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4463): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4463): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4463): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4463): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4463): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4463): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4463): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4463): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4463): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4463): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4463): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4463): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
E/SQLiteDatabase( 4463): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4463): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4463): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4463): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4463): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4463): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4463): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4463): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4463): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4463): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4463): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4463): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4463): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4463): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4463): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4463): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4463): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/HotwordRecognitionRnr( 1510): Hotword detection finished
W/GAv4    ( 4463): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/HotwordRecognitionRnr( 1510): Stopping hotword detection.
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4463): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4463): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4463): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4463): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4463): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4463): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/native  ( 1235): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1235): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4463): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4463): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 4463): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
E/SQLiteDatabase( 4463): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4463): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4463): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4463): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4463): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4463): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4463): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4463): 	at aej.c(PG:139)
E/SQLiteDatabase( 4463): 	at aej.b(PG:398)
E/SQLiteDatabase( 4463): 	at agf.f(PG:417)
E/SQLiteDatabase( 4463): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4463): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4463): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4463): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4463): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4463): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 4463): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/AbstractDatabaseInstance( 4463): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4463): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4463): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4463): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4463): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4463): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4463): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4463): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4463): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4463): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4463): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4463): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4463): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4463): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4463): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4463): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4463): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4463): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4463): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4463): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4463): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 4463): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/native  ( 1235): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1235): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4463): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 4463): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4463): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4463): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4463): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4463): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4463): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4463): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4463): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4463): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4463): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4463): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4463): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4463): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4463): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4463): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
V/JNIHelp ( 4463): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  824): Start proc 4547:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  824): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  824): addAppToken: AppWindowToken{22d68847 token=Token{27839786 ActivityRecord{33507061 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
E/native  ( 1235): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1235): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1235): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1235): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
I/Process ( 4463): Sending signal. PID: 4463 SIG: 9
E/lowmemorykiller(  276): Error writing /proc/4463/oom_score_adj; errno=22
E/JavaBinder(  824): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  824): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  824): android.os.TransactionTooLargeException
W/ActivityManager(  824): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  824): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  824): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  824): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  824): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  824): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  824): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  824): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  824): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  824): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  824): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  824): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  824): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  824): 	at android.os.Binder.execTransact(Binder.java:446)
I/ActivityManager(  824): Start proc 4564:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  824): Spurious death for ProcessRecord{bce92b0 4564:com.google.android.apps.docs/u0a46}, curProc for 4463: null
W/OpenGLRenderer( 1388): Incorrectly called buildLayer on View: ew, destroying layer...
E/kickstart(  872): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  872): WARNING: function: sahara_start:892 Retrying memory read request
E/SQLiteDatabase( 4547): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4547): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4547): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4547): 	at a,ndroid.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4547): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4547): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4547): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4547): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4547): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4547): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4547): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4547): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4547): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4547): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4547): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4547): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4547): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4547): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4547): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4547): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4547): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4547): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4547): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4547): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4547): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4547): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4547): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4547): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4547): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4547): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
I/ActivityManager(  824): Killing 3807:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
D/AndroidRuntime( 4547): Shutting down VM
E/AndroidRuntime( 4547): FATAL EXCEPTION: main
E/AndroidRuntime( 4547): Process: com.android.documentsui, PID: 4547
E/AndroidRuntime( 4547): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4547): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4547): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4547): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4547): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4547): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4547): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4547): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4547): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4547): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4547): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4547): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4547): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4547): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4547): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4547): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4547): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4547): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4547): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4547): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4547): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4547): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4547): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4547): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4547): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4547): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4547): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4547): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4547): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4547): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4547): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4547): 	... 9 more

```
