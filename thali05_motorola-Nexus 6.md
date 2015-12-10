#### Test 50650278d6c551a_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=2.62 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/AndroidRuntime( 3844): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3844): CheckJNI is OFF
D/AndroidRuntime( 3844): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{c33d671 token=Token{286dfc18 ActivityRecord{239e23fb u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3844): Shutting down VM
I/HotwordDetector( 1524): Closing mic
I/MicrophoneInputStream( 1524): mic_close com.google.android.apps.gsa.speech.audio.u@cb9de70
V/WindowManager(  820): Adding window Window{226577e2 u0 Starting com.test.thalitest} at 3 of 8 (after Window{3b1af91c u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/ActivityManager(  820): Start proc 3858:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1524): Stopping hotword detection.
I/HotwordRecognitionRnr( 1524): Hotword detection finished
I/ActivityManager(  820): Killing 3066:com.google.android.music:main/u0a66 (adj 15): empty #17
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659417875
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  820): Killing 2813:com.google.android.talk/u0a61 (adj 15): empty #18
,I/kickstart(  873): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  873): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  873): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3858): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3858): Time to load native libraries: 4 ms (timestamps 2634-2638)
,I/LibraryLoader( 3858): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3858): Binding Chromium to main looper Looper (main, tid 1) {2c501142}
,I/LibraryLoader( 3858): Expected native library version number "",actual native library version number ""
I/chromium( 3858): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3858): Initializing chromium process, singleProcess=true,
W/art     ( 3858): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3858): ApplicationContext is null in ApplicationStatus
,W/chromium( 3858): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3858): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3858): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3858): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@181f9d92:true
,W/art     ( 3858): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3858): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3858): CordovaWebView is running on device made by: motorola
,W/art     ( 3858): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3858): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3858): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3858): Validating map...,
,V/WindowManager(  820): Adding window Window{27468f42 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{226577e2 u0 Starting com.test.thalitest}),
,W/chromium( 3858): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3858): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3858): Enabling debug mode 0
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +914ms (total +1m50s494ms)
,I/Keyboard.Facilitator( 1241): onFinishInput()
,W/BindingManager( 3858): Cannot call determinedVisibility() - never saw a connection for the pid: 3858
,D/JsMessageQueue( 3858): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3858): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576275456
,D/JX-Cordova( 3858): jxcore cordova android initializing
,I/kickstart(  873): STATUS: Received file 'm9kefs2'
I/kickstart(  873): STATUS: 950272 bytes transferred in 0.993199 seconds
I/kickstart(  873): STATUS: Successfully downloaded files from target 
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  873): STATUS: Sahara protocol completed
,W/jxcore-log( 3858): Initializing JXcore engine
W/jxcore-log( 3858): JXcore engine is ready
,W/jxcore-log( 3858): Starting JXcore engine,
,W/.test.thalitest( 3858): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11783]" dev="sockfs" ino=11783 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
W/.test.thalitest( 3858): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3858): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11851]" dev="sockfs" ino=11851 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3858): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[25607]" dev="sockfs" ino=25607 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3858): Platform android
W/jxcore-log( 3858): 
W/jxcore-log( 3858): Process ARCH arm
W/jxcore-log( 3858): 
,I/jxcore-log( 3858): JXcore Cordova bridge is ready!
I/jxcore-log( 3858): 
W/jxcore-log( 3858): JXcore engine is started
I/Choreographer( 3858): Skipped 128 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3858): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3858): Toggling radios to true
I/jxcore-log( 3858): 
,D/BluetoothAdapter( 3858): enable(): BT is already enabled..!
,D/WifiService(  820): New client listening to asynchronous messages
D/WifiService(  820): setWifiEnabled: true pid=3858, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3858): Radios toggled,
I/jxcore-log( 3858): 
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3858): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3858): 
,I/jxcore-log( 3858): Perf Test app loaded loaded
I/jxcore-log( 3858): 
I/Choreographer( 3858): Skipped 61 frames!  The application may be doing too much work on its main thread.
,I/wpa_supplicant( 1159): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/jxcore-log( 3858): check test folder
I/jxcore-log( 3858): 
E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3858): found test : ./testFindPeers.js
I/jxcore-log( 3858): 
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1371): Read error: ssl=0x9cc50800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1371): SSL shutdown failed: ssl=0x9cc50800: I/O error during system call, Broken pipe
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  820): Start Disconnecting Watchdog 1
E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
I/jxcore-log( 3858): found test : ./testSendData.js
I/jxcore-log( 3858): 
,I/ActivityManager(  820): Start proc 3918:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524292
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/NetworkChangeNotifierAutoDetect( 1524): Network connectivity changed, type is: 6
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1311): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1311): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,W/ResourcesManager( 3918): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/GpsLocationProvider(  820): No APN found to select.
,E/WifiConfigStore(  820): Setting BSSID for "NG7005g"WPA_PSK to any
,I/chromium( 3858): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
E/WifiConfigStore(  820): will read network variables netId=0
,D/PhoneInterfaceManager( 1311): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1311): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
E/WifiConfigStore(  820): will read network variables netId=0
E/GpsLocationProvider(  820): No APN found to select.
,I/Babel_SMS( 3918): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3918): MmsConfig.loadMmsSettings
,I/Babel_SMS( 3918): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,I/Babel_SMS( 3918): MmsConfig.loadFromDatabase
,E/Babel_SMS( 3918): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3918): MmsConfig.loadFromResources
E/Babel_SMS( 3918): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 3918): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,W/Settings( 3918): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 3918): startup - clean
,I/Babel   ( 3918): deleted: false for 0
,I/Babel_telephony( 3918): TeleModule.launchCompleted
,W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 3918): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 3918): BAM#gBA: invalid account id: -1
,W/Babel   ( 3918): BAM#gBA: invalid account id: -1
I/Babel_telephony( 3918): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
,W/VideoCapabilities( 3918): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 3918): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager(  820): Start proc 3951:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
W/VideoCapabilities( 3918): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3918): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3918): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3918): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  820): Killing 3437:com.google.android.gm/u0a78 (adj 15): empty #17
,I/MusicStore( 3951): Database version: 120
,I/vclib   ( 3918): onServiceConnected
,W/Babel   ( 3918): Attempted to change video mute state without an active call.
,I/art     (  820): Explicit concurrent mark sweep GC freed 42542(2MB) AllocSpace objects, 11(270KB) LOS objects, 32% free, 33MB/49MB, paused 1.288ms total 60.828ms
,W/ResourcesManager( 3951): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3951): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3951): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3951): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 3951): GMSCore installation verified
,I/ConfigStore( 3951): Config Database version: 1
,I/MediaRouter( 3951): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3951): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  820): Start proc 3986:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,I/GHttpClientFactory( 3951): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3951): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  820): Killing 3544:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 4015:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  820): Killing 2518:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/SprintDMReceiver( 4015): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4015): simOperator:  IMSI: null
,D/SprintDMReceiver( 4015): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1829): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1829): onCreate
,D/SystemUpdateService( 1829): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1829): active receiver: enabled
,I/SystemUpdateService( 1829): showing system update notification
,I/iu.Environment( 1829): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1829): num queued entries: 0
,I/iu.UploadsManager( 1829): num updated entries: 0
,I/iu.SyncManager( 1829): NEXT; no task
D/ChimeraCfgMgr( 1829): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1829): retry (wakeup: false) in 3599957 ms,
,D/SystemUpdateService( 1829): onDestroy
,I/wpa_supplicant( 1159): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  820): Start proc 4035:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 3918): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  820): Killing 3396:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/GAv4    ( 4035): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4035):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4035):   adb logcat -s GAv4
,W/GAv4    ( 4035): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4035): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4035): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/wpa_supplicant( 1159): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1159): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1159): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 2
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 556
E/WifiStateMachine(  820):  RSSI mgmt: -52
E/WifiStateMachine(  820):  BE :  rx=245 tx=154 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 15404 tx_time=291 rx_time=619 scan_time=0
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/WebViewFactory( 4035): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4035): Time to load native libraries: 3 ms (timestamps 9005-9008)
I/LibraryLoader( 4035): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4035): Binding Chromium to main looper Looper (main, tid 1) {c98f111}
,I/LibraryLoader( 4035): Expected native library version number "",actual native library version number ""
,I/chromium( 4035): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4035): Initializing chromium process, singleProcess=true
,W/art     ( 4035): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4035): ApplicationContext is null in ApplicationStatus
,W/chromium( 4035): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4035): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4035): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 4035): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 4035): Requires BLUETOOTH permission
,I/NSApplication( 4035): Starting up...
,I/ActivityManager(  820): Killing 1435:android.process.acore/u0a5 (adj 15): empty #17
,I/dhcpcd  ( 4092): version 5.5.6 starting
,I/dhcpcd  ( 4092): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  820): Start proc 4099:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,V/MusicLeanback( 3951): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  820): Killing 3672:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/SprintDMReceiver( 4015): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4015): simOperator:  IMSI: null
,D/SprintDMReceiver( 4015): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1829): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1829): onCreate
,D/SystemUpdateService( 1829): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1829): active receiver: enabled
,I/SystemUpdateService( 1829): showing system update notification
,D/ChimeraCfgMgr( 1829): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification,
,V/SystemUpdateService( 1829): retry (wakeup: false) in 3599947 ms
,D/SystemUpdateService( 1829): onDestroy
,I/dhcpcd  ( 4092): wlan0: acknowledged 192.168.1.122 from 192.168.1.1,
,I/dhcpcd  ( 4092): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 101
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  820): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820):    accepting network in place of null
,D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1311): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1311): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/NetworkChangeNotifierAutoDetect( 1524): Network connectivity changed, type is: 2
I/NetworkMonitor( 3951): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  820): No APN found to select.
,V/MusicLeanback( 3951): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 4015): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4015): simOperator:  IMSI: null
,D/SprintDMReceiver( 4015): Not Sprint UICC, don't do anything.
I/SystemUpdateService( 1829): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1829): onCreate
,D/SystemUpdateService( 1829): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1829): active receiver: enabled
,I/SystemUpdateService( 1829): showing system update notification
,I/iu.Environment( 1829): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1829): num queued entries: 0
I/iu.UploadsManager( 1829): num updated entries: 0
,I/ValidateNoPeople(  820): skipping global notification
,I/iu.SyncManager( 1829): NEXT; no task
,V/SystemUpdateService( 1829): retry (wakeup: false) in 3599981 ms
,D/ChimeraCfgMgr( 1829): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1829): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1829): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 13:41:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449754862361], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449754862341]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524290
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1829): [AccountUtils] Account not ready
W/Kids    ( 1829): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1829): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1829): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1829): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1829): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1829): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1829): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1829): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1829): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1829): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1829): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1829): 	at java.lang.Thread.run(Thread.java:818)
,V/Herrevad( 1829): NQAS connected
,I/jxcore-log( 3858): BLE supported!!
I/jxcore-log( 3858): 
,I/Babel   ( 3918): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1371): Connected
,D/GCM     ( 1371): Message class com.google.f.a.a.p
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/WearableService( 3417): callingUid 10011, callindPid: 3417
,I/MusicLeanback( 3951): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 3951): Stop autocaching.
,E/GmsUtils( 3951): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3951): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 39029(1846KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 1.357ms total 80.470ms
,I/art     ( 1371): Explicit concurrent mark sweep GC freed 24032(1372KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.177ms total 27.443ms
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3500): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3500): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3500): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.83 rxSuccessRate=12.20 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.46 rxSuccessRate=4.80 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (238 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  820): Display changed displayId=0
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3219): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3219): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3219): 	at jdm.a(PG:82)
E/HttpOperation( 3219): 	at jcs.o(PG:406)
E/HttpOperation( 3219): 	at jcn.a(PG:1379)
E/HttpOperation( 3219): 	at jcs.i(PG:143)
E/HttpOperation( 3219): 	at blb.a(PG:3937)
E/HttpOperation( 3219): 	at czp.a(PG:18188)
E/HttpOperation( 3219): 	at czp.a(PG:9081)
E/HttpOperation( 3219): 	at czq.run(PG:1686)
E/HttpOperation( 3219): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3219): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3219): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3219): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3219): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3219): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3219): 	at jdj.a(PG:4091)
E/HttpOperation( 3219): 	at jdj.a(PG:1125)
E/HttpOperation( 3219): 	at jdm.a(PG:77)
E/HttpOperation( 3219): 	... 12 more
E/HttpOperation( 3219): Caused by: faj: BadAuthentication
E/HttpOperation( 3219): 	at fal.a(PG:38)
E/HttpOperation( 3219): 	at jdj.a(PG:4089)
E/HttpOperation( 3219): 	... 14 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3219): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3219): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3219): 	at jdm.a(PG:82)
E/HttpOperation( 3219): 	at jcs.o(PG:406)
E/HttpOperation( 3219): 	at jcn.a(PG:1379)
,E/HttpOperation( 3219): 	at jcs.i(PG:143)
E/HttpOperation( 3219): 	at hec.a(PG:42)
E/HttpOperation( 3219): 	at hee.a(PG:102),
E/HttpOperation( 3219): 	at czr.a(PG:65)
E/HttpOperation( 3219): 	at kka.a(PG:108)
E/HttpOperation( 3219): 	,at czp.a(PG:19176)
E/HttpOperation( 3219): 	at czp.a(PG:9081)
E/HttpOperation( 3219): 	at czq.run(PG:1686)
,E/HttpOperation( 3219): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3219): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3219): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3219): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3219): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3219): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3219): 	at jdj.a(PG:4091)
E/HttpOperation( 3219): 	at jdj.a(PG:1125),
E/HttpOperation( 3219): 	at jdm.a(PG:77)
,E/HttpOperation( 3219): 	... 15 more
E/HttpOperation( 3219): Caused by: faj: BadAuthentication
,E/HttpOperation( 3219): 	at fal.a(PG:38)
E/HttpOperation( 3219): 	,at jdj.a(PG:4089)
E/HttpOperation( 3219): 	... 17 more
,E/ExperimentLoader( 3219): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3219): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3219): 	at jdm.a(PG:82)
E/ExperimentLoader( 3219): ,	at jcs.o(PG:406)
E/ExperimentLoader( 3219): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3219): 	at jcs.i(PG:143)
E/ExperimentLoader( 3219): 	at hec.a(PG:42)
E/ExperimentLoader( 3219): 	at hee.a(PG:102)
E/ExperimentLoader( 3219): 	at czr.a(PG:65)
E/ExperimentLoader( 3219): 	at kka.a(PG:108)
E/ExperimentLoader( 3219): 	at czp.a(PG:19176)
E/ExperimentLoader( 3219): 	at czp.a(PG:9081)
E/ExperimentLoader( 3219): 	at czq.run(PG:1686)
E/ExperimentLoader( 3219): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3219): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3219): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3219): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3219): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3219): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3219): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3219): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3219): 	at jdm.a(PG:77)
E/ExperimentLoader( 3219): 	... 15 more
E/ExperimentLoader( 3219): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3219): 	at fal.a(PG:38)
E/ExperimentLoader( 3219): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3219): 	... 17 more
I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0,
D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  820): Excessive delay in setPowerMode(): 257ms
I/DreamManagerService(  820): Entering dreamland.
I/PowerManagerService(  820): Dozing...
I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
E/WifiStateMachine(  820): cancelDelayedScan -> 12
E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1241): onFinishInput()
,E/WifiStateMachine(  820): cancelDelayedScan -> 14
,E/native  (  820): do suspend true
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 163209, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3500): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3500): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3500): [1] 5.onFinished: Scheduling replication attempt 5.
,I/EventLogService( 1829): Opted in for usage reporting
,I/EventLogService( 1829): Aggregate from 1449753660889 (log), 1449753089967 (data)
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/EventLogAggregator( 1829): Unknown tag: snet_gcore
,W/EventLogAggregator( 1829): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1829): dumping service [account]
,I/VacuumService( 1371): Vacuum at: now=1449754890263 tag=VacuumService
,V/GoogleAuthProtoRequest( 3986): [430] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3986): [430] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3986): [430] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3986): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3986): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3986): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3986): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3986): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3986): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3986): 	,at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3986): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3986): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3986): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1371): Using platform SSLCertificateSocketFactory
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1371): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1371): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1371): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1371): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1371): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1371): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371): No account for auth token provided
,W/Uploader( 1371):  no longer exists, so no auth token.
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1371): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1371): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1371): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1371): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1371): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/BooksSync( 3797): Starting books sync for 61035162, extras: ade
,I/art     (  820): Explicit concurrent mark sweep GC freed 37350(1819KB) AllocSpace objects, 3(142KB) LOS objects, 31% free, 34MB/50MB, paused 2.366ms total 75.528ms
,V/KeepSync( 3769): Connecting to GoogleApiClient
,I/BooksConfig( 3797): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1829): Handling authorization failure
E/ClientConnectionOperation( 1829): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1829): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1829): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1829): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1829): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1829): 	... 7 more
,V/KeepSync( 3769): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3769): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3769): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3769): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3797): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3797): Soft error
E/BooksSync( 3797): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3797): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3797): Sync error
E/BooksSync( 3797): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3797): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3797): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 169357, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3769): IOException
E/KeepSync( 3769): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3769): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3769): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3769): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3769): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3769): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3769): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3769): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3769): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3769): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3769): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3769): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3769): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3769): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3769): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3769): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3769): 	... 10 more
W/KeepSync( 3769): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 166851, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1371): Explicit concurrent mark sweep GC freed 64160(3MB) AllocSpace objects, 8(713KB) LOS objects, 36% free, 27MB/43MB, paused 1.359ms total 73.736ms
,D/Finsky  ( 3500): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3500): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3500): [1] 5.onFinished: Giving up after 6 failures.
,V/GoogleAuthProtoRequest( 3986): [431] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3986): [431] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3986): [431] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3986): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3986): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3986): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3986): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3986): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3986): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3986): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3986): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3986): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3986): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3219): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3219): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3219): 	at jdm.a(PG:82)
E/HttpOperation( 3219): 	at jcs.o(PG:406)
E/HttpOperation( 3219): 	at jcn.a(PG:1379)
E/HttpOperation( 3219): 	at jcs.i(PG:143)
E/HttpOperation( 3219): 	at blb.a(PG:3937)
E/HttpOperation( 3219): 	at czp.a(PG:18188)
E/HttpOperation( 3219): 	at czp.a(PG:9081)
E/HttpOperation( 3219): 	at czq.run(PG:1686)
E/HttpOperation( 3219): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3219): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3219): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3219): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3219): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3219): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3219): 	at jdj.a(PG:4091)
E/HttpOperation( 3219): 	at jdj.a(PG:1125)
E/HttpOperation( 3219): 	at jdm.a(PG:77)
E/HttpOperation( 3219): 	... 12 more
E/HttpOperation( 3219): Caused by: faj: BadAuthentication
E/HttpOperation( 3219): 	at fal.a(PG:38)
E/HttpOperation( 3219): 	at jdj.a(PG:4089)
E/HttpOperation( 3219): 	... 14 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1241): run()
I/Keyboard.Facilitator( 1241): flushDynamicLanguageModels()
,E/HttpOperation( 3219): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3219): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3219): 	at jdm.a(PG:82)
E/HttpOperation( 3219): 	at jcs.o(PG:406)
E/HttpOperation( 3219): 	at jcn.a(PG:1379)
E/HttpOperation( 3219): 	at jcs.i(PG:143)
E/HttpOperation( 3219): 	at hec.a(PG:42)
E/HttpOperation( 3219): 	at hee.a(PG:102)
E/HttpOperation( 3219): 	at czr.a(PG:65)
E/HttpOperation( 3219): 	at kka.a(PG:108)
E/HttpOperation( 3219): 	at czp.a(PG:19176)
E/HttpOperation( 3219): 	at czp.a(PG:9081)
E/HttpOperation( 3219): 	at czq.run(PG:1686)
E/HttpOperation( 3219): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3219): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3219): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3219): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3219): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3219): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3219): 	at jdj.a(PG:4091),
E/HttpOperation( 3219): 	,at jdj.a(PG:1125)
E/HttpOperation( 3219): 	at jdm.a(PG:77),
,E/HttpOperation( 3219): 	... 15 more
E/HttpOperation( 3219): Caused by: faj: BadAuthentication
,E/HttpOperation( 3219): 	,at fal.a(PG:38)
E/HttpOperation( 3219): 	at jdj.a(PG:4089),
E/HttpOperation( 3219): 	... 17 more
E/ExperimentLoader( 3219): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3219): java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3219): 	at jdm.a(PG:82)
E/ExperimentLoader( 3219): 	at jcs.o(PG:406)
E/ExperimentLoader( 3219): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3219): 	at jcs.i(PG:143)
E/ExperimentLoader( 3219): 	at hec.a(PG:42)
E/ExperimentLoader( 3219): 	at hee.a(PG:102)
E/ExperimentLoader( 3219): 	at czr.a(PG:65)
E/ExperimentLoader( 3219): 	at kka.a(PG:108)
E/ExperimentLoader( 3219): 	at czp.a(PG:19176)
E/ExperimentLoader( 3219): 	at czp.a(PG:9081)
E/ExperimentLoader( 3219): 	at czq.run(PG:1686)
E/ExperimentLoader( 3219): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3219): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3219): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3219): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3219): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3219): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3219): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3219): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3219): 	at jdm.a(PG:77)
E/ExperimentLoader( 3219): 	... 15 more
E/ExperimentLoader( 3219): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3219): 	at fal.a(PG:38)
E/ExperimentLoader( 3219): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3219): 	... 17 more
I/ConfigService( 1371): onCreate
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 196009, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1371): onDestroy
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/BooksSync( 3797): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3769): Connecting to GoogleApiClient
,I/BooksConfig( 3797): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1829): Handling authorization failure,
E/ClientConnectionOperation( 1829): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1829): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1829): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1829): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1829): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.auth.p.a(SourceFile:310),
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1829): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1829): 	... 7 more
,V/KeepSync( 3769): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3769): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3769): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3769): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3797): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3797): Soft error
E/BooksSync( 3797): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3797): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3797): Sync error
E/BooksSync( 3797): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3797): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3797): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 225106, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 28643(1225KB) AllocSpace objects, 10(631KB) LOS objects, 31% free, 34MB/50MB, paused 1.671ms total 88.075ms
,E/KeepSync( 3769): IOException
E/KeepSync( 3769): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3769): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3769): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3769): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3769): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3769): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3769): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3769): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3769): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3769): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3769): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3769): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3769): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3769): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3769): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3769): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3769): 	... 10 more
W/KeepSync( 3769): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 225163, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,V/GoogleAuthProtoRequest( 3986): [432] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3986): [432] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3986): [432] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3986): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3986): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3986): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3986): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3986): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3986): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3986): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3986): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3986): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3986): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3219): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3219): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3219): 	at jdm.a(PG:82)
E/HttpOperation( 3219): 	at jcs.o(PG:406)
E/HttpOperation( 3219): 	at jcn.a(PG:1379)
E/HttpOperation( 3219): 	at jcs.i(PG:143)
E/HttpOperation( 3219): 	at blb.a(PG:3937)
E/HttpOperation( 3219): 	at czp.a(PG:18188)
E/HttpOperation( 3219): 	at czp.a(PG:9081)
E/HttpOperation( 3219): 	at czq.run(PG:1686)
E/HttpOperation( 3219): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3219): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3219): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3219): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3219): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3219): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3219): 	at jdj.a(PG:4091)
E/HttpOperation( 3219): 	at jdj.a(PG:1125)
E/HttpOperation( 3219): 	at jdm.a(PG:77)
E/HttpOperation( 3219): 	... 12 more
E/HttpOperation( 3219): Caused by: faj: BadAuthentication
E/HttpOperation( 3219): 	at fal.a(PG:38)
E/HttpOperation( 3219): 	at jdj.a(PG:4089)
E/HttpOperation( 3219): 	... 14 more
,I/GLSUser ( 1371): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1371): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1371): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1371): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3219): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3219): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3219): 	at jdm.a(PG:82)
E/HttpOperation( 3219): 	at jcs.o(PG:406)
E/HttpOperation( 3219): 	at jcn.a(PG:1379)
E/HttpOperation( 3219): 	at jcs.i(PG:143)
E/HttpOperation( 3219): 	at hec.a(PG:42)
E/HttpOperation( 3219): 	at hee.a(PG:102)
E/HttpOperation( 3219): 	at czr.a(PG:65)
E/HttpOperation( 3219): 	at kka.a(PG:108)
E/HttpOperation( 3219): 	at czp.a(PG:19176)
E/HttpOperation( 3219): 	at czp.a(PG:9081)
E/HttpOperation( 3219): 	at czq.run(PG:1686)
E/HttpOperation( 3219): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3219): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3219): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3219): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3219): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3219): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3219): 	at jdj.a(PG:4091)
E/HttpOperation( 3219): 	at jdj.a(PG:1125)
E/HttpOperation( 3219): 	at jdm.a(PG:77)
E/HttpOperation( 3219): 	... 15 more
E/HttpOperation( 3219): Caused by: faj: BadAuthentication
E/HttpOperation( 3219): 	at fal.a(PG:38)
E/HttpOperation( 3219): 	at jdj.a(PG:4089)
E/HttpOperation( 3219): 	... 17 more
E/ExperimentLoader( 3219): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3219): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3219): 	at jdm.a(PG:82)
E/ExperimentLoader( 3219): 	at jcs.o(PG:406)
E/ExperimentLoader( 3219): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3219): 	at jcs.i(PG:143)
E/ExperimentLoader( 3219): 	at hec.a(PG:42)
E/ExperimentLoader( 3219): 	at hee.a(PG:102)
E/ExperimentLoader( 3219): 	at czr.a(PG:65)
E/ExperimentLoader( 3219): 	at kka.a(PG:108)
E/ExperimentLoader( 3219): 	at czp.a(PG:19176)
E/ExperimentLoader( 3219): 	at czp.a(PG:9081)
E/ExperimentLoader( 3219): 	at czq.run(PG:1686)
E/ExperimentLoader( 3219): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3219): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3219): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3219): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3219): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3219): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3219): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3219): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3219): 	at jdm.a(PG:77)
E/ExperimentLoader( 3219): 	... 15 more
E/ExperimentLoader( 3219): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3219): 	at fal.a(PG:38)
E/ExperimentLoader( 3219): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3219): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 288406, reason: 10074, SyncResult: stats [ numIoExceptions: 1]

```
