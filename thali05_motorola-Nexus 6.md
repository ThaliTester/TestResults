#### Test 5065027881383b1_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=2.32 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/AndroidRuntime( 3778): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3778): CheckJNI is OFF
D/AndroidRuntime( 3778): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{1421e0a4 token=Token{158fd337 ActivityRecord{9d87836 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3778): Shutting down VM
I/MicrophoneInputStream( 1531): mic_close com.google.android.apps.gsa.speech.audio.u@401e94f
I/HotwordDetector( 1531): Closing mic
V/WindowManager(  820): Adding window Window{340f3e09 u0 Starting com.test.thalitest} at 3 of 8 (after Window{a141fea u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/ActivityManager(  820): Start proc 3792:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1531): Hotword detection finished
I/HotwordRecognitionRnr( 1531): Stopping hotword detection.
I/ActivityManager(  820): Killing 3075:com.google.android.music:main/u0a66 (adj 15): empty #17
I/ActivityManager(  820): Killing 3272:com.google.android.apps.photos/u0a71 (adj 15): empty #18
,I/WebViewFactory( 3792): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3792): Time to load native libraries: 1 ms (timestamps 2887-2888)
I/LibraryLoader( 3792): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3792): Binding Chromium to main looper Looper (main, tid 1) {370b3fa6}
,I/LibraryLoader( 3792): Expected native library version number "",actual native library version number ""
,I/chromium( 3792): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659131155
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/BrowserStartupController( 3792): Initializing chromium process, singleProcess=true
,W/art     ( 3792): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3792): ApplicationContext is null in ApplicationStatus
,W/chromium( 3792): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3792): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3792): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3792): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d86bb79:true
I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,W/art     ( 3792): Attempt to remove local handle scope entry from IRT, ignoring
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,W/AwContents( 3792): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3792): CordovaWebView is running on device made by: motorola
,W/art     ( 3792): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3792): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3792): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3792): Validating map...
,V/WindowManager(  820): Adding window Window{195074e9 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{340f3e09 u0 Starting com.test.thalitest})
,W/chromium( 3792): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3792): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3792): Enabling debug mode 0
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +763ms (total +1m50s467ms)
,I/Keyboard.Facilitator( 1259): onFinishInput()
,W/BindingManager( 3792): Cannot call determinedVisibility() - never saw a connection for the pid: 3792
,D/JsMessageQueue( 3792): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3792): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576262784
D/JX-Cordova( 3792): jxcore cordova android initializing
,I/kickstart(  872): STATUS: Received file 'm9kefs1'
,I/kickstart(  872): STATUS: 950272 bytes transferred in 0.991194 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,W/jxcore-log( 3792): Initializing JXcore engine
W/jxcore-log( 3792): JXcore engine is ready
,W/jxcore-log( 3792): Starting JXcore engine
,W/.test.thalitest( 3792): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12926]" dev="sockfs" ino=12926 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
W/.test.thalitest( 3792): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3792): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9978]" dev="sockfs" ino=9978 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3792): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[24577]" dev="sockfs" ino=24577 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
,W/jxcore-log( 3792): Platform android
W/jxcore-log( 3792): 
W/jxcore-log( 3792): Process ARCH arm
W/jxcore-log( 3792): 
,I/jxcore-log( 3792): JXcore Cordova bridge is ready!
I/jxcore-log( 3792): 
W/jxcore-log( 3792): JXcore engine is started
,I/Choreographer( 3792): Skipped 136 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3792): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3792): Toggling radios to true
I/jxcore-log( 3792): 
,D/BluetoothAdapter( 3792): enable(): BT is already enabled..!
,D/WifiService(  820): setWifiEnabled: true pid=3792, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled,
D/WifiService(  820): New client listening to asynchronous messages
,I/jxcore-log( 3792): Radios toggled
I/jxcore-log( 3792): 
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/jxcore-log( 3792): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3792): 
E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,I/jxcore-log( 3792): Perf Test app loaded loaded
I/jxcore-log( 3792): 
I/Choreographer( 3792): Skipped 64 frames!  The application may be doing too much work on its main thread.
V/NativeCrypto( 1280): Read error: ssl=0x9cd98200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1280): SSL shutdown failed: ssl=0x9cd98200: I/O error during system call, Broken pipe
,I/jxcore-log( 3792): check test folder
I/jxcore-log( 3792): 
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  820): Start Disconnecting Watchdog 1
I/jxcore-log( 3792): found test : ./testFindPeers.js
I/jxcore-log( 3792): 
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  353): Clearing all IP addresses on wlan0
I/jxcore-log( 3792): found test : ./testSendData.js
I/jxcore-log( 3792): 
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1072): CM callback handler got msg 524292
D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true,
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
,D/PhoneInterfaceManager( 1345): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1345): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/WifiConfigStore(  820): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): will read network variables netId=0
,I/ActivityManager(  820): Start proc 3852:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  820): MasterInitialState.processMessage what=3
,E/WifiConfigStore(  820): will read network variables netId=0
,E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,I/wpa_supplicant( 1155): wlan0: Trying to associate with SSID 'NG7005g'
,E/GpsLocationProvider(  820): No APN found to select.
,D/PhoneInterfaceManager( 1345): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1345): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,I/chromium( 3792): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/MusicStore( 3852): Database version: 120
,W/ResourcesManager( 3852): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3852): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3852): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3852): Installed default security provider GmsCore_OpenSSL,
,D/AndroidMusic( 3852): GMSCore installation verified
,I/ConfigStore( 3852): Config Database version: 1
,I/art     ( 1280): Explicit concurrent mark sweep GC freed 23674(1349KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.838ms total 49.252ms
,I/wpa_supplicant( 1155): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1155): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg,
E/WifiStateMachine(  820): Start Dhcp Watchdog 2
,E/WifiStateMachine(  820):  WifiLinkLayerStats: ,
E/WifiStateMachine(  820):  my bss beacon rx: 551
E/WifiStateMachine(  820):  RSSI mgmt: -52
E/WifiStateMachine(  820):  BE :  rx=229 tx=118 lost=0 retries=1
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 13348 tx_time=220 rx_time=537 scan_time=0
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60,
,I/art     (  820): Explicit concurrent mark sweep GC freed 46865(2MB) AllocSpace objects, 15(334KB) LOS objects, 32% free, 33MB/49MB, paused 1.288ms total 91.356ms
,I/MediaRouter( 3852): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3852): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/ActivityManager(  820): Start proc 3889:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,I/GHttpClientFactory( 3852): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3852): Using platform SSLCertificateSocketFactory
,I/art     ( 1531): WaitForGcToComplete blocked for 77.241ms for cause HomogeneousSpaceCompact
,I/ActivityManager(  820): Start proc 3918:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  820): Killing 3421:com.google.android.gm/u0a78 (adj 15): empty #17
,I/dhcpcd  ( 3935): version 5.5.6 starting
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SprintDMReceiver( 3918): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3918): simOperator:  IMSI: null
,D/SprintDMReceiver( 3918): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1850): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dhcpcd  ( 3935): wlan0: rebinding lease of 192.168.1.122
,D/SystemUpdateService( 1850): onCreate
,D/SystemUpdateService( 1850): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/Finsky  ( 2891): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2891): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2891): [1] 5.onFinished: Scheduling replication attempt 3.
,I/SystemUpdateService( 1850): active receiver: enabled
,I/iu.Environment( 1850): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1850): showing system update notification
,I/iu.UploadsManager( 1850): num queued entries: 0
,I/iu.UploadsManager( 1850): num updated entries: 0
I/ActivityManager(  820): Killing 2500:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/iu.SyncManager( 1850): NEXT; no task
,D/ChimeraCfgMgr( 1850): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1850): retry (wakeup: false) in 3599849 ms
,I/Babel   ( 2816): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  820): Start proc 3945:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1850): onDestroy
,I/ActivityManager(  820): Killing 3383:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/GAv4    ( 3945): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3945):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3945):   adb logcat -s GAv4
,W/GAv4    ( 3945): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3945): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3945): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3945): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3945): Time to load native libraries: 4 ms (timestamps 8681-8685)
I/LibraryLoader( 3945): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3945): Binding Chromium to main looper Looper (main, tid 1) {2e68ef45}
,I/LibraryLoader( 3945): Expected native library version number "",actual native library version number ""
,I/chromium( 3945): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3945): Initializing chromium process, singleProcess=true
,W/art     ( 3945): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3945): ApplicationContext is null in ApplicationStatus
,W/chromium( 3945): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3945): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3945): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3945): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3945): Requires BLUETOOTH permission
I/NSApplication( 3945): Starting up...
,I/ActivityManager(  820): Killing 3251:android.process.acore/u0a5 (adj 15): empty #17
,I/dhcpcd  ( 3935): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3935): wlan0: leased 192.168.1.122 for 86400 seconds
,I/ActivityManager(  820): Start proc 4004:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,V/MusicLeanback( 3852): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  820): Killing 3604:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/SprintDMReceiver( 3918): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 101
,D/SprintDMHelper( 3918): simOperator:  IMSI: null
D/SprintDMReceiver( 3918): Not Sprint UICC, don't do anything.
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
,I/SystemUpdateService( 1850): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1850): onCreate
,D/SystemUpdateService( 1850): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1850): active receiver: enabled
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  820): Setting Dns servers for network 101 to [/192.168.1.1]
,I/SystemUpdateService( 1850): showing system update notification
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ChimeraCfgMgr( 1850): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1072): CM callback handler got msg 524290
,I/ValidateNoPeople(  820): skipping global notification
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ChimeraCfgMgr( 1850): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/Tethering(  820): MasterInitialState.processMessage what=3
V/SystemUpdateService( 1850): retry (wakeup: false) in 3599963 ms
,I/NetworkMonitor( 3852): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1345): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1345): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/SystemUpdateService( 1850): onDestroy
,E/GpsLocationProvider(  820): No APN found to select.
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/MusicLeanback( 3852): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3918): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 13:09:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449752976401], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449752976387]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1072): CM callback handler got msg 524290
,D/SprintDMHelper( 3918): simOperator:  IMSI: null
D/SprintDMReceiver( 3918): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1850): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1850): onCreate
,D/SystemUpdateService( 1850): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1850): active receiver: enabled
,W/Kids    ( 1850): [AccountUtils] Account not ready
W/Kids    ( 1850): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1850): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1850): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1850): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1850): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1850): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1850): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1850): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1850): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1850): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1850): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1850): 	at java.lang.Thread.run(Thread.java:818)
,I/Babel   ( 2816): connection state changed from DISCONNECTED to CONNECTED
,I/SystemUpdateService( 1850): showing system update notification
,I/iu.Environment( 1850): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1850): retry (wakeup: false) in 3599972 ms
,I/iu.UploadsManager( 1850): num queued entries: 0
I/iu.UploadsManager( 1850): num updated entries: 0
,I/iu.SyncManager( 1850): NEXT; no task
,D/ChimeraCfgMgr( 1850): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1850): onDestroy
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1850): [AccountUtils] Account not ready
W/Kids    ( 1850): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1850): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1850): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1850): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1850): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1850): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1850): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1850): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1850): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1850): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1850): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1850): 	at java.lang.Thread.run(Thread.java:818)
,V/Herrevad( 1850): NQAS connected
,D/GCM     ( 1280): Connected
,D/GCM     ( 1280): Message class com.google.f.a.a.p
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3792): BLE supported!!
I/jxcore-log( 3792): 
,D/WearableService( 3403): callingUid 10011, callindPid: 3403
,I/art     (  820): Explicit concurrent mark sweep GC freed 32132(1473KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 1.442ms total 64.442ms
,I/MusicLeanback( 3852): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 3852): Stop autocaching.
,E/GmsUtils( 3852): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3852): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=7.56 rxSuccessRate=9.52 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=4.28 rxSuccessRate=6.26 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (200 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  820): Display changed displayId=0,
,D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  279): hwc_setPowerMode: Setting mode 0 on display: 0
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  279): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  820): Excessive delay in setPowerMode(): 248ms
,I/DreamManagerService(  820): Entering dreamland.,
I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,I/PowerManagerService(  820): Dozing...
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 12
,E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1259): onFinishInput()
,E/WifiStateMachine(  820): cancelDelayedScan -> 14
,E/native  (  820): do suspend true
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off,
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,I/BooksSync( 3731): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3731): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3731): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3731): Soft error
E/BooksSync( 3731): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3731): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3731): Sync error
E/BooksSync( 3731): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3731): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3731): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163608, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2891): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2891): [1] 5.onFinished: Installation state replication failed.,
,D/Finsky  ( 2891): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1280): Vacuum at: now=1449753014379 tag=VacuumService
,V/GoogleAuthProtoRequest( 3889): [421] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3889): [421] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3889): [421] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3889): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3889): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3889): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3889): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3889): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3889): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3889): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3889): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3889): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3889): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1280): Using platform SSLCertificateSocketFactory
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,I/art     ( 1280): Explicit concurrent mark sweep GC freed 41699(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 2.430ms total 73.363ms
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1280): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1280): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1280): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1280): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1280): No account for auth token provided
,W/Uploader( 1280): No account for auth token provided
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1280): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1280): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1280): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1280): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1280): No account for auth token provided
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2891): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2891): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2891): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 1280): No account for auth token provided
,W/Uploader( 1280): No account for auth token provided
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1280): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1280): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1280): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337),
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1280): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1280): No account for auth token provided
,W/Uploader( 1280): No account for auth token provided
,W/Uploader( 1280): No account for auth token provided
,W/Uploader( 1280): No account for auth token provided
,W/Uploader( 1280): No account for auth token provided,
,W/Uploader( 1280): No account for auth token provided
,W/Uploader( 1280):  no longer exists, so no auth token.
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1280): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1280): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1280): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1280): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1280): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1280): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1280): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1280): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
,E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1280): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1280): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/art     (  820): Explicit concurrent mark sweep GC freed 36693(1735KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 2.089ms total 104.370ms
,V/KeepSync( 3701): Connecting to GoogleApiClient
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1850): Handling authorization failure
E/ClientConnectionOperation( 1850): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143),
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1850): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1850): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1850): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1850): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
,E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1850): 	... 7 more
,V/KeepSync( 3701): GoogleApiClient failed to connect with error code: 4
E/HttpOperation( 3229): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3229): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3229): 	at jdm.a(PG:82)
E/HttpOperation( 3229): 	at jcs.o(PG:406)
E/HttpOperation( 3229): 	at jcn.a(PG:1379)
E/HttpOperation( 3229): 	at jcs.i(PG:143)
E/HttpOperation( 3229): 	at blb.a(PG:3937)
E/HttpOperation( 3229): 	at czp.a(PG:18188)
E/HttpOperation( 3229): 	at czp.a(PG:9081)
E/HttpOperation( 3229): 	at czq.run(PG:1686)
E/HttpOperation( 3229): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3229): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3229): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3229): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3229): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3229): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3229): 	at jdj.a(PG:4091)
E/HttpOperation( 3229): 	at jdj.a(PG:1125)
E/HttpOperation( 3229): 	at jdm.a(PG:77)
E/HttpOperation( 3229): 	... 12 more
E/HttpOperation( 3229): Caused by: faj: BadAuthentication
E/HttpOperation( 3229): 	at fal.a(PG:38)
E/HttpOperation( 3229): 	at jdj.a(PG:4089)
E/HttpOperation( 3229): 	... 14 more
E/SQLiteLog( 3701): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3701): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3701): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3229): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3229): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3229): 	at jdm.a(PG:82)
E/HttpOperation( 3229): 	at jcs.o(PG:406)
E/HttpOperation( 3229): 	at jcn.a(PG:1379)
E/HttpOperation( 3229): 	at jcs.i(PG:143)
E/HttpOperation( 3229): 	at hec.a(PG:42)
E/HttpOperation( 3229): 	at hee.a(PG:102)
E/HttpOperation( 3229): 	at czr.a(PG:65)
E/HttpOperation( 3229): 	at kka.a(PG:108)
E/HttpOperation( 3229): 	at czp.a(PG:19176)
E/HttpOperation( 3229): 	at czp.a(PG:9081)
E/HttpOperation( 3229): 	at czq.run(PG:1686)
E/HttpOperation( 3229): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3229): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3229): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3229): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3229): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3229): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3229): 	at jdj.a(PG:4091)
E/HttpOperation( 3229): 	at jdj.a(PG:1125)
E/HttpOperation( 3229): 	at jdm.a(PG:77)
E/HttpOperation( 3229): 	... 15 more
E/HttpOperation( 3229): Caused by: faj: BadAuthentication
E/HttpOperation( 3229): 	at fal.a(PG:38)
E/HttpOperation( 3229): 	at jdj.a(PG:4089)
E/HttpOperation( 3229): 	... 17 more
,E/ExperimentLoader( 3229): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3229): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3229): 	at jdm.a(PG:82)
E/ExperimentLoader( 3229): 	at jcs.o(PG:406)
E/ExperimentLoader( 3229): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3229): 	at jcs.i(PG:143)
E/ExperimentLoader( 3229): 	at hec.a(PG:42)
E/ExperimentLoader( 3229): 	at hee.a(PG:102)
E/ExperimentLoader( 3229): 	at czr.a(PG:65)
E/ExperimentLoader( 3229): 	at kka.a(PG:108)
E/ExperimentLoader( 3229): 	at czp.a(PG:19176),
E/ExperimentLoader( 3229): 	at czp.a(PG:9081)
E/ExperimentLoader( 3229): 	at czq.run(PG:1686)
E/ExperimentLoader( 3229): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3229): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3229): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3229): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3229): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3229): Caused by: android.accounts.AuthenticatorException: Recoverable error,
E/ExperimentLoader( 3229): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3229): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3229): 	at jdm.a(PG:77)
E/ExperimentLoader( 3229): 	... 15 more
E/ExperimentLoader( 3229): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3229): 	at fal.a(PG:38)
,E/ExperimentLoader( 3229): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3229): 	... 17 more
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3701): IOException
E/KeepSync( 3701): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3701): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3701): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3701): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3701): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3701): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3701): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3701): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3701): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3701): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3701): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3701): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3701): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3701): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3701): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3701): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3701): 	... 10 more
W/KeepSync( 3701): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 165760, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 164496, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3889): [422] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3889): [422] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3889): [422] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3889): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3889): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3889): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3889): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3889): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3889): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3889): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3889): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3889): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3889): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2891): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2891): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2891): [1] 5.onFinished: Giving up after 6 failures.,
,I/Keyboard.Facilitator.LanguageModelFlusher( 1259): run()
I/Keyboard.Facilitator( 1259): flushDynamicLanguageModels()
,I/ConfigService( 1280): onCreate
,I/BooksSync( 3731): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3731): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3731): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3731): Soft error
E/BooksSync( 3731): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3731): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3731): Sync error
E/BooksSync( 3731): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3731): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3731): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 194462, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1280): onDestroy
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,V/KeepSync( 3701): Connecting to GoogleApiClient
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1850): Handling authorization failure
E/ClientConnectionOperation( 1850): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1850): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1850): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1850): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1850): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1850): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1850): 	... 7 more
E/HttpOperation( 3229): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3229): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3229): 	at jdm.a(PG:82)
E/HttpOperation( 3229): 	at jcs.o(PG:406)
E/HttpOperation( 3229): 	at jcn.a(PG:1379)
E/HttpOperation( 3229): 	at jcs.i(PG:143)
E/HttpOperation( 3229): 	at blb.a(PG:3937)
E/HttpOperation( 3229): 	at czp.a(PG:18188)
E/HttpOperation( 3229): 	at czp.a(PG:9081)
E/HttpOperation( 3229): 	at czq.run(PG:1686)
E/HttpOperation( 3229): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3229): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3229): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3229): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3229): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3229): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3229): 	at jdj.a(PG:4091)
E/HttpOperation( 3229): 	at jdj.a(PG:1125)
E/HttpOperation( 3229): 	at jdm.a(PG:77)
E/HttpOperation( 3229): 	... 12 more
E/HttpOperation( 3229): Caused by: faj: BadAuthentication
E/HttpOperation( 3229): 	at fal.a(PG:38)
E/HttpOperation( 3229): 	at jdj.a(PG:4089)
E/HttpOperation( 3229): 	... 14 more
,V/KeepSync( 3701): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3701): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3701): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3701): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3229): [getmobileexperiments] Unexpected exception,
,E/HttpOperation( 3229): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3229): ,	at jdm.a(PG:82)
E/HttpOperation( 3229): 	at jcs.o(PG:406),
E/HttpOperation( 3229): 	at jcn.a(PG:1379)
E/HttpOperation( 3229): ,	at jcs.i(PG:143)
E/HttpOperation( 3229): 	at hec.a(PG:42),
E/HttpOperation( 3229): 	at hee.a(PG:102)
E/HttpOperation( 3229): ,	at czr.a(PG:65)
E/HttpOperation( 3229): 	at kka.a(PG:108)
E/HttpOperation( 3229): 	,at czp.a(PG:19176)
E/HttpOperation( 3229): 	at czp.a(PG:9081)
E/HttpOperation( 3229): 	,at czq.run(PG:1686)
E/HttpOperation( 3229): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3229): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3229): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3229): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3229): ,	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3229): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3229): 	at jdj.a(PG:4091)
,E/HttpOperation( 3229): 	at jdj.a(PG:1125)
E/HttpOperation( 3229): ,	at jdm.a(PG:77)
E/HttpOperation( 3229): 	... 15 more
,E/HttpOperation( 3229): Caused by: faj: BadAuthentication
E/HttpOperation( 3229): 	at fal.a(PG:38)
E/HttpOperation( 3229): 	,at jdj.a(PG:4089)
E/HttpOperation( 3229): 	... 17 more,
,E/ExperimentLoader( 3229): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3229): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3229): ,	at jdm.a(PG:82)
,E/ExperimentLoader( 3229): 	,at jcs.o(PG:406)
E/ExperimentLoader( 3229): 	at jcn.a(PG:1379)
,E/ExperimentLoader( 3229): 	at jcs.i(PG:143)
E/ExperimentLoader( 3229): 	at hec.a(PG:42),
E/ExperimentLoader( 3229): 	at hee.a(PG:102)
,E/ExperimentLoader( 3229): 	at czr.a(PG:65)
E/ExperimentLoader( 3229): 	,at kka.a(PG:108)
E/ExperimentLoader( 3229): 	at czp.a(PG:19176)
E/ExperimentLoader( 3229): 	at czp.a(PG:9081)
E/ExperimentLoader( 3229): 	at czq.run(PG:1686)
E/ExperimentLoader( 3229): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3229): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3229): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/ExperimentLoader( 3229): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3229): 	at java.lang.Thread.run(Thread.java:818),
E/ExperimentLoader( 3229): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3229): 	at jdj.a(PG:4091)
,E/ExperimentLoader( 3229): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3229): 	at jdm.a(PG:77)
E/ExperimentLoader( 3229): 	... 15 more
E/ExperimentLoader( 3229): Caused by: faj: BadAuthentication,
E/ExperimentLoader( 3229): 	at fal.a(PG:38)
E/ExperimentLoader( 3229): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3229): 	... 17 more
I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3701): IOException
E/KeepSync( 3701): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3701): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3701): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3701): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3701): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3701): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3701): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3701): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3701): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3701): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3701): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3701): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3701): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3701): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3701): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3701): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3701): 	... 10 more
W/KeepSync( 3701): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 226181, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 224779, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  820): Explicit concurrent mark sweep GC freed 31830(1354KB) AllocSpace objects, 12(757KB) LOS objects, 31% free, 34MB/50MB, paused 3.033ms total 96.685ms
,I/EventLogService( 1850): Opted in for usage reporting
I/EventLogService( 1850): Aggregate from 1449751289636 (log), 1449751289636 (data)
,I/art     ( 1280): Explicit concurrent mark sweep GC freed 65227(3MB) AllocSpace objects, 11(961KB) LOS objects, 36% free, 28MB/44MB, paused 1.307ms total 63.557ms
,W/EventLogAggregator( 1850): Unknown tag: snet_gcore
W/EventLogAggregator( 1850): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1850): dumping service [account]
,V/GoogleAuthProtoRequest( 3889): [423] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3889): [423] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3889): [423] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3889): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3889): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3889): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3889): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3889): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3889): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3889): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3889): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3889): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3889): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2187): Disconnected process message: 10, size: 0
,I/BooksSync( 3731): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3731): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1280): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1280): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1280): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1280): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3731): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3731): Soft error
,E/BooksSync( 3731): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3731): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3731): Sync error
E/BooksSync( 3731): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3731): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3731): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 285047, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]

```
