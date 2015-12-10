#### Test 50650278c17c777_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 3451): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3451): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3451): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3789): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3789): CheckJNI is OFF
D/AndroidRuntime( 3789): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{12fa0d33 token=Token{3717aca2 ActivityRecord{1159786d u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3789): Shutting down VM
I/HotwordDetector( 1512): Closing mic
I/MicrophoneInputStream( 1512): mic_close com.google.android.apps.gsa.speech.audio.u@3c04afa
V/WindowManager(  820): Adding window Window{509141c u0 Starting com.test.thalitest} at 3 of 8 (after Window{26fcd5b8 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/ActivityManager(  820): Start proc 3803:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1512): Hotword detection finished
I/HotwordRecognitionRnr( 1512): Stopping hotword detection.
I/ActivityManager(  820): Killing 3084:com.google.android.music:main/u0a66 (adj 15): empty #17
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659696403
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  820): Killing 3274:com.google.android.apps.photos/u0a71 (adj 15): empty #18
,I/kickstart(  875): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  875): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  875): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  875): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3803): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3803): Time to load native libraries: 4 ms (timestamps 234-238)
I/LibraryLoader( 3803): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3803): Binding Chromium to main looper Looper (main, tid 1) {382c36c3}
,I/LibraryLoader( 3803): Expected native library version number "",actual native library version number ""
I/chromium( 3803): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3803): Initializing chromium process, singleProcess=true
,W/art     ( 3803): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3803): ApplicationContext is null in ApplicationStatus
,W/chromium( 3803): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3803): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3803): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3803): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@947bc4c:true
,W/art     ( 3803): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3803): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3803): CordovaWebView is running on device made by: motorola
,W/art     ( 3803): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3803): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3803): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3803): Validating map...
,V/WindowManager(  820): Adding window Window{3458d07c u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{509141c u0 Starting com.test.thalitest})
,W/chromium( 3803): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3803): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3803): Enabling debug mode 0
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +856ms (total +1m47s72ms)
,I/Keyboard.Facilitator( 1231): onFinishInput()
,W/BindingManager( 3803): Cannot call determinedVisibility() - never saw a connection for the pid: 3803
,D/JsMessageQueue( 3803): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3803): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580454528
D/JX-Cordova( 3803): jxcore cordova android initializing
,I/kickstart(  875): STATUS: Received file 'm9kefs2'
I/kickstart(  875): STATUS: 950272 bytes transferred in 0.992557 seconds
I/kickstart(  875): STATUS: Successfully downloaded files from target 
I/kickstart(  875): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  875): STATUS: Sahara protocol completed
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=5.44 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,W/jxcore-log( 3803): Initializing JXcore engine
W/jxcore-log( 3803): JXcore engine is ready
,W/jxcore-log( 3803): Starting JXcore engine
,W/.test.thalitest( 3803): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10658]" dev="sockfs" ino=10658 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3803): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3803): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10826]" dev="sockfs" ino=10826 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3803): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[24727]" dev="sockfs" ino=24727 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3803): Platform android
,W/jxcore-log( 3803): 
W/jxcore-log( 3803): Process ARCH arm
W/jxcore-log( 3803): 
,I/jxcore-log( 3803): JXcore Cordova bridge is ready!
I/jxcore-log( 3803): 
W/jxcore-log( 3803): JXcore engine is started
,I/chromium( 3803): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 3803): Skipped 142 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3803): Toggling radios to true
I/jxcore-log( 3803): 
,D/BluetoothAdapter( 3803): enable(): BT is already enabled..!
,D/WifiService(  820): New client listening to asynchronous messages
,D/WifiService(  820): setWifiEnabled: true pid=3803, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3803): Radios toggled
I/jxcore-log( 3803): 
,I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1336): Read error: ssl=0x9cc67200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1336): SSL shutdown failed: ssl=0x9cc67200: I/O error during system call, Broken pipe
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  820): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/ActivityManager(  820): Start proc 3862:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,D/CommandListener(  353): Clearing all IP addresses on wlan0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524292
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  820): MasterInitialState.processMessage what=3
,W/ResourcesManager( 3862): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/NetworkChangeNotifierAutoDetect( 1512): Network connectivity changed, type is: 6
,E/WifiConfigStore(  820): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): will read network variables netId=0
,D/PhoneInterfaceManager( 1296): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1296): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,I/wpa_supplicant( 1150): wlan0: Trying to associate with SSID 'NG7005g'
E/GpsLocationProvider(  820): No APN found to select.
,D/PhoneInterfaceManager( 1296): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1296): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,I/Babel_SMS( 3862): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3862): MmsConfig.loadMmsSettings
I/Babel_SMS( 3862): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 3862): MmsConfig.loadFromDatabase
,E/Babel_SMS( 3862): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3862): MmsConfig.loadFromResources
,E/Babel_SMS( 3862): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 3862): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,W/Settings( 3862): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 3862): startup - clean,
,I/Babel   ( 3862): deleted: false for 0
,I/Babel_telephony( 3862): TeleModule.launchCompleted
,W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 3862): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 3862): BAM#gBA: invalid account id: -1
W/Babel   ( 3862): BAM#gBA: invalid account id: -1
I/Babel_telephony( 3862): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
,I/ActivityManager(  820): Start proc 3894:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,W/VideoCapabilities( 3862): Unrecognized profile 2130706433 for video/avc
,I/wpa_supplicant( 1150): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/VideoCapabilities( 3862): Unsupported profile 4 for video/mp4v-es
I/wpa_supplicant( 1150): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 2
,W/VideoCapabilities( 3862): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3862): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3862): Unrecognized profile 2130706433 for video/avc
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 536
E/WifiStateMachine(  820):  RSSI mgmt: -52
E/WifiStateMachine(  820):  BE :  rx=222 tx=152 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 13244 tx_time=225 rx_time=488 scan_time=0
,W/VideoCapabilities( 3862): Unrecognized profile 2130706433 for video/avc
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,I/ActivityManager(  820): Killing 2956:com.google.android.gm/u0a78 (adj 15): empty #17
,I/MusicStore( 3894): Database version: 120
,E/native  (  820): do suspend false,
,E/WifiStateMachine(  820): scanCount==0 - aborting,
,I/vclib   ( 3862): onServiceConnected
W/Babel   ( 3862): Attempted to change video mute state without an active call.
,I/art     ( 1336): Explicit concurrent mark sweep GC freed 25655(1500KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 931us total 22.245ms
,W/ResourcesManager( 3894): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3894): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3894): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3894): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3894): GMSCore installation verified
,I/ConfigStore( 3894): Config Database version: 1
,I/dhcpcd  ( 3921): version 5.5.6 starting
I/art     (  820): Explicit concurrent mark sweep GC freed 47636(2MB) AllocSpace objects, 15(334KB) LOS objects, 32% free, 33MB/49MB, paused 1.599ms total 56.830ms
,I/dhcpcd  ( 3921): wlan0: rebinding lease of 192.168.1.122
,I/MediaRouter( 3894): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3894): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  820): Start proc 3932:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,I/GHttpClientFactory( 3894): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3894): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  820): Killing 3493:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 3964:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  820): Killing 2454:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/SprintDMReceiver( 3964): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3964): simOperator:  IMSI: null
D/SprintDMReceiver( 3964): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1843): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1843): onCreate
,D/SystemUpdateService( 1843): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1843): active receiver: enabled
,I/SystemUpdateService( 1843): showing system update notification
,I/iu.Environment( 1843): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1843): num queued entries: 0
I/iu.UploadsManager( 1843): num updated entries: 0
I/iu.SyncManager( 1843): NEXT; no task
,I/ValidateNoPeople(  820): skipping global notification
,D/ChimeraCfgMgr( 1843): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1843): retry (wakeup: false) in 3599969 ms
,I/ActivityManager(  820): Start proc 3984:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1843): onDestroy
,I/Babel   ( 3862): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  820): Killing 3392:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/GAv4    ( 3984): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3984):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3984):   adb logcat -s GAv4
,W/GAv4    ( 3984): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3984): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3984): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3984): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3984): Time to load native libraries: 1 ms (timestamps 5737-5738)
,I/LibraryLoader( 3984): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3984): Binding Chromium to main looper Looper (main, tid 1) {41130a6}
I/LibraryLoader( 3984): Expected native library version number "",actual native library version number ""
,I/chromium( 3984): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3984): Initializing chromium process, singleProcess=true
,W/art     ( 3984): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3984): ApplicationContext is null in ApplicationStatus
,I/dhcpcd  ( 3921): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,W/chromium( 3984): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3984): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3984): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3984): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3984): Requires BLUETOOTH permission
I/dhcpcd  ( 3921): wlan0: leased 192.168.1.122 for 86400 seconds
,I/NSApplication( 3984): Starting up...
,I/ActivityManager(  820): Killing 3253:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 4057:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 101
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/MusicLeanback( 3894): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  820): Killing 3619:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  820): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/SprintDMReceiver( 3964): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820):    accepting network in place of null
,D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/SprintDMHelper( 3964): simOperator:  IMSI: null
D/SprintDMReceiver( 3964): Not Sprint UICC, don't do anything.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/SystemUpdateService( 1843): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1512): Network connectivity changed, type is: 2
,I/NetworkMonitor( 3894): type=WIFI subType= reason=null isConnected=true
,D/SystemUpdateService( 1843): onCreate
,D/SystemUpdateService( 1843): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1843): active receiver: enabled
,D/PhoneInterfaceManager( 1296): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1296): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/SystemUpdateService( 1843): showing system update notification
,E/GpsLocationProvider(  820): No APN found to select.
,I/iu.Environment( 1843): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1843): num queued entries: 0
,I/iu.UploadsManager( 1843): num updated entries: 0
,I/iu.SyncManager( 1843): NEXT; no task
,D/ChimeraCfgMgr( 1843): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,D/ChimeraCfgMgr( 1843): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1843): retry (wakeup: false) in 3599972 ms
,D/SystemUpdateService( 1843): onDestroy
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/MusicLeanback( 3894): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SprintDMReceiver( 3964): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3964): simOperator:  IMSI: null
D/SprintDMReceiver( 3964): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1843): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1843): onCreate
,D/SystemUpdateService( 1843): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/Kids    ( 1843): [AccountUtils] Account not ready
W/Kids    ( 1843): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1843): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1843): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1843): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1843): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1843): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1843): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1843): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1843): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1843): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1843): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1843): 	at java.lang.Thread.run(Thread.java:818)
,I/SystemUpdateService( 1843): active receiver: enabled
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 11:18:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449746298155], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449746298134]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
,I/SystemUpdateService( 1843): showing system update notification
I/Babel   ( 3862): connection state changed from DISCONNECTED to CONNECTED
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1843): retry (wakeup: false) in 3599971 ms
,D/SystemUpdateService( 1843): onDestroy
,D/ChimeraCfgMgr( 1843): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1843): [AccountUtils] Account not ready
W/Kids    ( 1843): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1843): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1843): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1843): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1843): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1843): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1843): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1843): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1843): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1843): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1843): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1843): 	at java.lang.Thread.run(Thread.java:818)
,V/Herrevad( 1843): NQAS connected
,D/GCM     ( 1336): Connected
,D/GCM     ( 1336): Message class com.google.f.a.a.p
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/MusicLeanback( 3894): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 3894): Stop autocaching.
,D/WearableService( 3413): callingUid 10011, callindPid: 3413
,E/GmsUtils( 3894): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3894): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,I/jxcore-log( 3803): Test app app.js loaded
I/jxcore-log( 3803): 
,I/Choreographer( 3803): Skipped 382 frames!  The application may be doing too much work on its main thread.,
,I/chromium( 3803): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/art     (  820): Explicit concurrent mark sweep GC freed 31063(1440KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 1.945ms total 86.439ms
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.56 rxSuccessRate=9.97 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3451): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3451): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3451): [1] 5.onFinished: Scheduling replication attempt 4.
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (242 us)
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.82 rxSuccessRate=2.50 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  820): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  820): Excessive delay in setPowerMode(): 256ms
,I/DreamManagerService(  820): Entering dreamland.
,I/PowerManagerService(  820): Dozing...
,I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 12
,E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1231): onFinishInput()
,E/WifiStateMachine(  820): cancelDelayedScan -> 14,
,E/native  (  820): do suspend true
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/KeepSync( 3714): Connecting to GoogleApiClient
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1843): Handling authorization failure
E/ClientConnectionOperation( 1843): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
,E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1843): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1843): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1843): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1843): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1843): 	,at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1843): 	,at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1843): 	... 7 more,
V/KeepSync( 3714): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3714): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3714): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3714): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3714): IOException
E/KeepSync( 3714): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3714): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3714): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3714): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3714): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3714): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3714): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3714): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3714): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3714): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3714): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3714): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3714): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3714): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3714): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3714): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3714): 	... 10 more
W/KeepSync( 3714): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 167959, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3745): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3745): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3745): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3745): Soft error
E/BooksSync( 3745): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3745): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3745): Sync error
E/BooksSync( 3745): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3745): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3745): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 168336, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1336): Explicit concurrent mark sweep GC freed 31118(1802KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 27MB/43MB, paused 1.717ms total 41.500ms
,I/VacuumService( 1336): Vacuum at: now=1449746331889 tag=VacuumService
,V/GoogleAuthProtoRequest( 3932): [425] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1336): Using platform SSLCertificateSocketFactory
,W/ExperimentUpdateService( 3932): [425] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3932): [425] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3932): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3932): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3932): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3932): 	at com.a.a.k.run(SourceFile:110)
,W/Uploader( 1336): No account for auth token provided
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3451): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3451): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3451): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 1336): No account for auth token provided
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1336): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1336): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1336): 	at com.google.android.gms.auth.p.e(SourceFile:1268),
E/Uploader( 1336): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1336): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1336): No account for auth token provided
,W/Uploader( 1336): No account for auth token provided
,I/art     (  820): Explicit concurrent mark sweep GC freed 36180(1687KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.463ms total 95.722ms
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1336): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1336): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1336): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1336): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1336): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1336): No account for auth token provided
,W/Uploader( 1336): No account for auth token provided
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1336): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1336): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1336): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1336): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1336): No account for auth token provided
,W/Uploader( 1336): No account for auth token provided
,W/Uploader( 1336): No account for auth token provided
,W/Uploader( 1336):  no longer exists, so no auth token.,
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1336): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1336): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1336): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1336): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1336): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1336): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1336): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1336): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1336): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1336): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3233): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3233): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3233): 	at jdm.a(PG:82)
E/HttpOperation( 3233): 	at jcs.o(PG:406)
E/HttpOperation( 3233): 	at jcn.a(PG:1379)
E/HttpOperation( 3233): 	at jcs.i(PG:143)
E/HttpOperation( 3233): 	at blb.a(PG:3937)
E/HttpOperation( 3233): 	at czp.a(PG:18188)
E/HttpOperation( 3233): 	at czp.a(PG:9081)
E/HttpOperation( 3233): 	at czq.run(PG:1686)
E/HttpOperation( 3233): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3233): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3233): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3233): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3233): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3233): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3233): 	at jdj.a(PG:4091)
E/HttpOperation( 3233): 	at jdj.a(PG:1125)
E/HttpOperation( 3233): 	at jdm.a(PG:77)
E/HttpOperation( 3233): 	... 12 more
E/HttpOperation( 3233): Caused by: faj: BadAuthentication
E/HttpOperation( 3233): 	at fal.a(PG:38)
E/HttpOperation( 3233): 	at jdj.a(PG:4089)
E/HttpOperation( 3233): 	... 14 more
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3233): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3233): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3233): 	at jdm.a(PG:82)
E/HttpOperation( 3233): 	at jcs.o(PG:406)
E/HttpOperation( 3233): 	at jcn.a(PG:1379)
E/HttpOperation( 3233): 	at jcs.i(PG:143)
E/HttpOperation( 3233): 	at hec.a(PG:42)
E/HttpOperation( 3233): 	at hee.a(PG:102)
E/HttpOperation( 3233): 	at czr.a(PG:65)
E/HttpOperation( 3233): 	at kka.a(PG:108)
E/HttpOperation( 3233): 	at czp.a(PG:19176)
E/HttpOperation( 3233): 	at czp.a(PG:9081)
E/HttpOperation( 3233): 	at czq.run(PG:1686)
E/HttpOperation( 3233): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3233): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3233): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3233): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3233): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3233): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3233): 	at jdj.a(PG:4091)
E/HttpOperation( 3233): 	at jdj.a(PG:1125)
E/HttpOperation( 3233): 	at jdm.a(PG:77)
E/HttpOperation( 3233): 	... 15 more
E/HttpOperation( 3233): Caused by: faj: BadAuthentication
E/HttpOperation( 3233): 	at fal.a(PG:38)
E/HttpOperation( 3233): 	at jdj.a(PG:4089)
E/HttpOperation( 3233): 	... 17 more
E/ExperimentLoader( 3233): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3233): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3233): 	at jdm.a(PG:82)
E/ExperimentLoader( 3233): 	at jcs.o(PG:406)
E/ExperimentLoader( 3233): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3233): 	at jcs.i(PG:143)
E/ExperimentLoader( 3233): 	at hec.a(PG:42)
E/ExperimentLoader( 3233): 	at hee.a(PG:102)
E/ExperimentLoader( 3233): 	at czr.a(PG:65)
E/ExperimentLoader( 3233): 	at kka.a(PG:108)
E/ExperimentLoader( 3233): 	at czp.a(PG:19176)
E/ExperimentLoader( 3233): 	at czp.a(PG:9081)
E/ExperimentLoader( 3233): 	at czq.run(PG:1686)
E/ExperimentLoader( 3233): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3233): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3233): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3233): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3233): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3233): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3233): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3233): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3233): 	at jdm.a(PG:77)
E/ExperimentLoader( 3233): 	... 15 more
E/ExperimentLoader( 3233): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3233): 	at fal.a(PG:38)
E/ExperimentLoader( 3233): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3233): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 169178, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3451): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3451): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3451): [1] 5.onFinished: Giving up after 6 failures.
,V/GoogleAuthProtoRequest( 3932): [426] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3932): [426] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3932): [426] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
,W/ExperimentUpdateService( 3932): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3932): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3932): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3932): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3932): 	,at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1231): run()
I/Keyboard.Facilitator( 1231): flushDynamicLanguageModels()
,I/ConfigService( 1336): onCreate
,I/BooksSync( 3745): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3714): Connecting to GoogleApiClient
,I/BooksConfig( 3745): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1843): Handling authorization failure
E/ClientConnectionOperation( 1843): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1843): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1843): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1843): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1843): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1843): 	... 7 more
,V/KeepSync( 3714): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3714): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3714): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3714): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3745): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3745): Soft error
E/BooksSync( 3745): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3745): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3745): Sync error
E/BooksSync( 3745): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3745): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3745): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 201351, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3714): IOException,
E/KeepSync( 3714): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3714): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3714): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3714): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3714): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3714): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3714): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3714): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3714): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3714): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3714): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
,E/KeepSync( 3714): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3714): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3714): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3714): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3714): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3714): 	... 10 more
W/KeepSync( 3714): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 200179, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1336): onDestroy
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1336): Explicit concurrent mark sweep GC freed 62374(3MB) AllocSpace objects, 13(1264KB) LOS objects, 36% free, 27MB/43MB, paused 1.745ms total 62.583ms
,E/HttpOperation( 3233): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3233): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3233): 	at jdm.a(PG:82)
E/HttpOperation( 3233): 	at jcs.o(PG:406)
E/HttpOperation( 3233): 	at jcn.a(PG:1379)
E/HttpOperation( 3233): 	at jcs.i(PG:143)
E/HttpOperation( 3233): 	at blb.a(PG:3937)
E/HttpOperation( 3233): 	at czp.a(PG:18188)
E/HttpOperation( 3233): 	at czp.a(PG:9081)
E/HttpOperation( 3233): 	at czq.run(PG:1686)
E/HttpOperation( 3233): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3233): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3233): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3233): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3233): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3233): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3233): 	at jdj.a(PG:4091)
E/HttpOperation( 3233): 	at jdj.a(PG:1125)
E/HttpOperation( 3233): 	at jdm.a(PG:77)
E/HttpOperation( 3233): 	... 12 more
E/HttpOperation( 3233): Caused by: faj: BadAuthentication
E/HttpOperation( 3233): 	at fal.a(PG:38)
E/HttpOperation( 3233): 	at jdj.a(PG:4089)
E/HttpOperation( 3233): 	... 14 more
,I/art     (  820): Explicit concurrent mark sweep GC freed 31938(1388KB) AllocSpace objects, 7(394KB) LOS objects, 31% free, 34MB/50MB, paused 1.291ms total 65.441ms
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3233): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3233): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3233): 	at jdm.a(PG:82)
E/HttpOperation( 3233): 	at jcs.o(PG:406)
E/HttpOperation( 3233): 	at jcn.a(PG:1379)
E/HttpOperation( 3233): 	at jcs.i(PG:143)
E/HttpOperation( 3233): 	at hec.a(PG:42)
E/HttpOperation( 3233): 	at hee.a(PG:102)
E/HttpOperation( 3233): 	at czr.a(PG:65)
E/HttpOperation( 3233): 	at kka.a(PG:108)
E/HttpOperation( 3233): 	at czp.a(PG:19176)
E/HttpOperation( 3233): 	at czp.a(PG:9081)
E/HttpOperation( 3233): 	at czq.run(PG:1686)
E/HttpOperation( 3233): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3233): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3233): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3233): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3233): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3233): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3233): 	at jdj.a(PG:4091)
E/HttpOperation( 3233): 	at jdj.a(PG:1125)
E/HttpOperation( 3233): 	at jdm.a(PG:77)
E/HttpOperation( 3233): 	... 15 more
E/HttpOperation( 3233): Caused by: faj: BadAuthentication
E/HttpOperation( 3233): 	at fal.a(PG:38)
E/HttpOperation( 3233): 	at jdj.a(PG:4089)
E/HttpOperation( 3233): 	... 17 more
E/ExperimentLoader( 3233): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3233): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3233): 	at jdm.a(PG:82)
E/ExperimentLoader( 3233): 	at jcs.o(PG:406)
E/ExperimentLoader( 3233): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3233): 	at jcs.i(PG:143)
E/ExperimentLoader( 3233): 	at hec.a(PG:42)
E/ExperimentLoader( 3233): 	at hee.a(PG:102)
E/ExperimentLoader( 3233): 	at czr.a(PG:65)
E/ExperimentLoader( 3233): 	at kka.a(PG:108)
E/ExperimentLoader( 3233): 	at czp.a(PG:19176)
E/ExperimentLoader( 3233): 	at czp.a(PG:9081)
E/ExperimentLoader( 3233): 	at czq.run(PG:1686)
E/ExperimentLoader( 3233): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3233): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3233): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3233): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3233): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3233): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3233): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3233): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3233): 	at jdm.a(PG:77)
E/ExperimentLoader( 3233): 	... 15 more
E/ExperimentLoader( 3233): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3233): 	at fal.a(PG:38)
E/ExperimentLoader( 3233): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3233): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 231330, reason: Periodic, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3932): [428] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3932): [428] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3932): [428] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3932): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3932): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3932): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3932): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,I/BooksSync( 3745): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3714): Connecting to GoogleApiClient
,I/BooksConfig( 3745): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1843): Handling authorization failure
E/ClientConnectionOperation( 1843): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1843): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1843): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1843): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1843): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1843): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1843): 	... 7 more
,V/KeepSync( 3714): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3714): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3714): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3714): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/BooksAccountManager( 3745): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/BooksSync( 3745): Soft error
E/BooksSync( 3745): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3745): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3745): Sync error
E/BooksSync( 3745): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3745): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3745): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 293426, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,E/KeepSync( 3714): IOException
E/KeepSync( 3714): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3714): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3714): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3714): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3714): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3714): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3714): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3714): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3714): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3714): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3714): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3714): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3714): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3714): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3714): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3714): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3714): 	... 10 more
W/KeepSync( 3714): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 291966, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3233): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3233): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3233): 	at jdm.a(PG:82)
E/HttpOperation( 3233): 	at jcs.o(PG:406)
E/HttpOperation( 3233): 	at jcn.a(PG:1379)
E/HttpOperation( 3233): 	at jcs.i(PG:143)
E/HttpOperation( 3233): 	at blb.a(PG:3937)
E/HttpOperation( 3233): 	at czp.a(PG:18188)
E/HttpOperation( 3233): 	at czp.a(PG:9081)
E/HttpOperation( 3233): 	at czq.run(PG:1686)
E/HttpOperation( 3233): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3233): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3233): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3233): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3233): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3233): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3233): 	at jdj.a(PG:4091)
E/HttpOperation( 3233): 	at jdj.a(PG:1125)
E/HttpOperation( 3233): 	at jdm.a(PG:77)
E/HttpOperation( 3233): 	... 12 more
E/HttpOperation( 3233): Caused by: faj: BadAuthentication
E/HttpOperation( 3233): 	at fal.a(PG:38)
E/HttpOperation( 3233): 	at jdj.a(PG:4089)
E/HttpOperation( 3233): 	... 14 more
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3233): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3233): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3233): 	at jdm.a(PG:82)
E/HttpOperation( 3233): 	at jcs.o(PG:406)
E/HttpOperation( 3233): 	at jcn.a(PG:1379)
E/HttpOperation( 3233): 	at jcs.i(PG:143)
E/HttpOperation( 3233): 	at hec.a(PG:42)
E/HttpOperation( 3233): 	at hee.a(PG:102)
E/HttpOperation( 3233): 	at czr.a(PG:65)
E/HttpOperation( 3233): 	at kka.a(PG:108)
E/HttpOperation( 3233): 	at czp.a(PG:19176)
E/HttpOperation( 3233): 	at czp.a(PG:9081)
E/HttpOperation( 3233): 	at czq.run(PG:1686)
E/HttpOperation( 3233): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3233): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3233): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3233): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3233): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3233): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3233): 	at jdj.a(PG:4091)
E/HttpOperation( 3233): 	at jdj.a(PG:1125)
E/HttpOperation( 3233): 	at jdm.a(PG:77)
E/HttpOperation( 3233): 	... 15 more
E/HttpOperation( 3233): Caused by: faj: BadAuthentication
E/HttpOperation( 3233): 	at fal.a(PG:38)
E/HttpOperation( 3233): 	at jdj.a(PG:4089)
E/HttpOperation( 3233): 	... 17 more
E/ExperimentLoader( 3233): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3233): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3233): 	at jdm.a(PG:82)
E/ExperimentLoader( 3233): 	at jcs.o(PG:406)
E/ExperimentLoader( 3233): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3233): 	at jcs.i(PG:143)
E/ExperimentLoader( 3233): 	at hec.a(PG:42)
E/ExperimentLoader( 3233): 	at hee.a(PG:102)
E/ExperimentLoader( 3233): 	at czr.a(PG:65)
E/ExperimentLoader( 3233): 	at kka.a(PG:108)
E/ExperimentLoader( 3233): 	at czp.a(PG:19176)
E/ExperimentLoader( 3233): 	at czp.a(PG:9081)
E/ExperimentLoader( 3233): 	at czq.run(PG:1686)
E/ExperimentLoader( 3233): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3233): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3233): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3233): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3233): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3233): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3233): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3233): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3233): 	at jdm.a(PG:77)
E/ExperimentLoader( 3233): 	... 15 more
E/ExperimentLoader( 3233): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3233): 	at fal.a(PG:38)
E/ExperimentLoader( 3233): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3233): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 324285, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1336): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1336): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1336): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1336): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1336): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1336): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1336): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3451): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3451): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3451): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3451): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3451): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3451): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3451): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3451): Ignoring header User-Agent because its value was null.,
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1660a66a}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1660a66a}
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@8b01bf8}
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2177): Disconnected process message: 10, size: 0
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@8b01bf8}
,I/jxcore-log( 3803): Toggling radios to false
I/jxcore-log( 3803): 
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  820): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@82a0e37 mBinding = false
,D/BluetoothManagerService(  820): Message: 2,
D/BluetoothManagerService(  820): Sending off request.,
D/BluetoothAdapterState( 2177): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF,
D/BluetoothAdapterProperties( 2177): Setting state to 13
I/BluetoothAdapterState( 2177): Bluetooth adapter state changed: 12-> 13
,D/WifiService(  820): setWifiEnabled: false pid=3803, uid=10265
,E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled,
D/BluetoothAdapterProperties( 2177): onBluetoothDisable()
I/BluetoothAdapterState( 2177): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true,
D/BluetoothManagerService(  820): Message: 60,
,D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  820): Bluetooth State Change Intent: 12 -> 13,
D/BluetoothMapService( 2177): onReceive
,D/BluetoothMapService( 2177): STATE_TURNING_OFF
D/BluetoothMapService( 2177): MAP Service closeService in
D/BluetoothMapMasInstance( 2177): MAP Service shutdown,
V/BluetoothMapMasInstance( 2177): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2177): java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
,V/BluetoothMapMasInstance( 2177): 	,at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2177): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2177): 	,at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2177): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
I/BtOppRfcommListener( 2177): stopping Accept Thread
,E/BtOppRfcommListener( 2177): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 2177): BluetoothSocket listen thread finished
,I/jxcore-log( 3803): Radios toggled
I/jxcore-log( 3803): 
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  820): do suspend true
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1336): Read error: ssl=0x9cc67200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1336): SSL shutdown failed: ssl=0x9cc67200: I/O error during system call, Broken pipe
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Forcing reevaluation
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ActivityManager(  820): Start proc 4226:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/BluetoothAdapterProperties( 2177): Scan Mode:20
D/BluetoothAdapterState( 2177): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 2177): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-btif ( 2177): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2177): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0017 not found for deregistration
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  820): scanCount==0 - aborting
,D/WifiScanningService(  820): SCAN_AVAILABLE : 1,
D/WifiScanningService(  820): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState
D/RttService(  820): SCAN_AVAILABLE : 1
D/RttService(  820): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost,
E/native  (  820): do suspend true
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  820): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524292
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Disconnected - quitting
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkChangeNotifierAutoDetect( 1512): Network connectivity changed, type is: 6
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1296): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1296): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/wpa_supplicant( 1150): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/art     (  820): Explicit concurrent mark sweep GC freed 42240(1970KB) AllocSpace objects, 15(805KB) LOS objects, 31% free, 34MB/50MB, paused 1.332ms total 77.083ms
,E/GpsLocationProvider(  820): No APN found to select.
,W/ContextImpl( 4226): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@358756d3:true
,D/BluetoothManagerService(  820): Message: 30
,D/PhoneInterfaceManager( 1296): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1296): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,W/bt-btif ( 2177): ag scb idx 1 not allocated
E/bt-btif ( 2177): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2177): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2177): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2177): RX termination
,W/bt_userial( 2177): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2177): Leaving userial_read_thread()
,D/bt_userial( 2177): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2177): hw_epilog_process
I/bt_userial_vendor( 2177): device fd = 53 close
,I/ActivityManager(  820): Start proc 4248:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 4226): Adding local MAP profile
,D/BluetoothMap( 4226): Create BluetoothMap proxy object
,D/BluetoothManagerService(  820): Message: 30
,I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 577us total 12.069ms
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 4226): LocalBluetoothProfileManager construction complete
,E/GpsLocationProvider(  820): No APN found to select.
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 213us total 10.945ms
,D/DockEventReceiver( 4226): finishStartingService: stopping service
,D/BluetoothInputDevice( 4226): Proxy object connected
,D/HidProfile( 4226): Bluetooth service connected
,D/BluetoothPan( 4226): BluetoothPAN Proxy object connected
,D/PanProfile( 4226): Bluetooth service connected
,D/BluetoothMap( 4226): Proxy object connected
D/MapProfile( 4226): Bluetooth service connected
D/BluetoothMap( 4226): getConnectedDevices()
,D/BluetoothMap( 4226): Bluetooth is Not enabled
,I/ActivityManager(  820): Killing 3639:com.android.musicfx/u0a18 (adj 15): empty #17
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 460us total 12.358ms
,I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  820): InitialState.processMessage what=4
E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/GKI_LINUX( 2177): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2177): GKI_exit_task 0 done
I/GKI_LINUX( 2177): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2177): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/Tethering(  820): sendTetherStateChangedBroadcast 0, 0, 0
,D/HeadsetService( 2177): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 2177): Exit Disconnected: -1
,D/BluetoothHeadset(  820): Proxy object disconnected
D/BluetoothHeadset( 1296): Proxy object disconnected
D/BluetoothHeadset( 1065): Proxy object disconnected
,D/BluetoothHeadset(  820): Proxy object disconnected
D/BluetoothHeadset(  820): Proxy object disconnected
D/A2dpService( 2177): Received stop request...Stopping profile...
D/A2dpStateMachine( 2177): Exit Disconnected: -1
D/BluetoothAdapterState( 2177): Stopping profile services that were post enabled
W/Settings( 3862): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1819): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothA2dp(  820): Proxy object disconnected
,D/BluetoothA2dp( 1065): Proxy object disconnected,
D/HidService( 2177): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 1065): Proxy object disconnected
D/BluetoothInputDevice( 4226): Proxy object disconnected
D/HidProfile( 4226): Bluetooth service disconnected
D/HealthService( 2177): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 2177): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2177): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2177): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 2177): Received stop request...Stopping profile...
D/BtGatt.DebugUtils( 2177): handleDebugAction() action=null
,D/BluetoothPan( 1065): BluetoothPAN Proxy object disconnected
D/BtGatt.GattService( 2177): Received stop request...Stopping profile...
D/BtGatt.GattService( 2177): stop()
D/BtGatt.AdvertiseManager( 2177): advertise clients cleared
D/BluetoothPan( 4226): BluetoothPAN Proxy object disconnected
D/PanProfile( 4226): Bluetooth service disconnected
,D/BluetoothMapService( 2177): Received stop request...Stopping profile...
D/BluetoothMapService( 2177): stop()
,D/BluetoothMapEmailAppObserver( 2177): deinitObservers()
D/BluetoothMapEmailAppObserver( 2177): removeReceiver()
,D/BluetoothMap( 4226): Proxy object disconnected
D/MapProfile( 4226): Bluetooth service disconnected
D/BluetoothMap( 1065): Proxy object disconnected
I/GKI_LINUX( 2177): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2177): GKI_exit_task 2 done
I/GKI_LINUX( 2177): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 2177): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2177): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2177): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2177): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2177): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2177): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2177): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 2177): MAP Service closeService in
D/BluetoothAdapterState( 2177): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 2177): cleanup()
D/BluetoothMapService( 2177): MAP Service closeService in
,D/BluetoothAdapterProperties( 2177): Setting state to 10
I/BluetoothAdapterState( 2177): Bluetooth adapter state changed: 13-> 10
I/BluetoothAdapterState( 2177): Entering OffState
D/BluetoothManagerService(  820): Message: 60
,D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  820): Broadcasting onBluetoothStateChange(false) to 17 receivers.
D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
D/BluetoothMap( 4226): onBluetoothStateChange: up=false
D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1065): onBluetoothStateChange: up=false
,D/BluetoothMap( 1065): onBluetoothStateChange: up=false
,D/BluetoothPbap( 4226): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1065): onBluetoothStateChange: up=false
D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
,D/BluetoothA2dpSink( 1065): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1065): 
E/BluetoothA2dpSink( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@108c8209
E/BluetoothA2dpSink( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1065): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothA2dp(  820): onBluetoothStateChange: up=false
D/BluetoothAvrcpController( 1065): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1065): 
E/BluetoothAvrcpController( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@37684c0e
E/BluetoothAvrcpController( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1065): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothHeadsetClient( 1065): onBluetoothStateChange: up=false
,E/BluetoothHeadsetClient( 1065): 
E/BluetoothHeadsetClient( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@3f68d62f
E/BluetoothHeadsetClient( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1065): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset( 1296): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 4226): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 1065): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  820): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  820): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  820): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@82a0e37 mBinding = false
,D/BluetoothManagerService(  820): Sending unbind request.
,D/BluetoothManagerService(  820): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1065): 467963344: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1065): 467963344: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1065): 467963344: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2177): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2177): GKI_exit_task 1 done
I/GKI_LINUX( 2177): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2177): cleanupNative: return from cleanup
,I/art     ( 2177): System.exit called, status: 0
,I/AndroidRuntime( 2177): VM exiting with result code 0, cleanup skipped.
,I/ActivityManager(  820): Process com.android.bluetooth (pid 2177) has died
,D/StrictMode( 4248): StrictMode policy violation; ~duration=228 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4248): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4248): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4248): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4248): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4248): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 4248): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 4248): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=228 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4248): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4248): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4248): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=226 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4248): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4248): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4248): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4248): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4248): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4248): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 4248): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=222 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4248): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 4248): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4248): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4248): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4248): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4248): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4248): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 4248): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 4248): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 4248): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 4248): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 4248): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 4248): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 4248): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 4248): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 4248): # via Binder call with stack:
D/StrictMode( 4248): android.os.StrictMode$LogStackTrace
D/StrictMode( 4248): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 4248): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 4248): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 4248): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 4248): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 4248): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 4248): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 4248): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 4248): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4248): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4248): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4248): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4248): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4248): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 4248): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4248): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4248): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4248): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4248): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4248): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4248): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4248): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4248): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4248): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4248): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4248): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4248): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4248): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 4248): 	at com.google.p.j.a(PG:121)
D/StrictMode( 4248): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 4248): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 4248): 	at com.google.p.e.a(PG:170)
D/StrictMode( 4248): 	at com.google.p.e.b(PG:21)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 4248): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17db9f3b:true
I/ActivityManager(  820): Killing 3671:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1336): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/MusicLeanback( 3894): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3964): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3964): simOperator:  IMSI: null
,D/SprintDMReceiver( 3964): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1843): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1843): onCreate
,D/SystemUpdateService( 1843): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1843): active receiver: enabled
,I/SystemUpdateService( 1843): showing system update notification
,I/iu.Environment( 1843): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1843): num queued entries: 0
,I/ValidateNoPeople(  820): skipping global notification
,I/iu.UploadsManager( 1843): num updated entries: 0
,I/iu.SyncManager( 1843): NEXT; no task
V/SystemUpdateService( 1843): retry (wakeup: false) in 3599978 ms
,D/ChimeraCfgMgr( 1843): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1843): onDestroy
,I/Babel   ( 3862): connection state changed from CONNECTED to DISCONNECTED
,V/MusicLeanback( 3894): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3964): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3964): simOperator:  IMSI: null
,D/SprintDMReceiver( 3964): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1843): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1843): onCreate
,D/SystemUpdateService( 1843): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1843): active receiver: enabled
,I/SystemUpdateService( 1843): showing system update notification
,D/ChimeraCfgMgr( 1843): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1843): retry (wakeup: false) in 3599961 ms
,D/SystemUpdateService( 1843): onDestroy
,W/ContextImpl( 4226): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  820): Start proc 4283:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,D/DockEventReceiver( 4226): finishStartingService: stopping service
,W/ResourcesManager( 4283): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 4283): Adding HeadsetService,
,D/AdapterServiceConfig( 4283): Adding A2dpService
,D/AdapterServiceConfig( 4283): Adding HidService
D/AdapterServiceConfig( 4283): Adding HealthService
D/AdapterServiceConfig( 4283): Adding PanService
D/AdapterServiceConfig( 4283): Adding GattService
D/AdapterServiceConfig( 4283): Adding BluetoothMapService
,I/ActivityManager(  820): Killing 3576:com.android.defcontainer/u0a7 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1336): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/GoogleAuthProtoRequest( 3932): [429] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3932): [429] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3932): [429] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3932): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3932): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3932): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3932): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  820): Failed to find a new network - expiring NetTransition Wakelock
,I/art     ( 1336): Explicit concurrent mark sweep GC freed 55290(2MB) AllocSpace objects, 17(1874KB) LOS objects, 37% free, 27MB/43MB, paused 2.119ms total 45.200ms
,V/GoogleAuthProtoRequest( 3932): [430] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3932): [430] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3932): [430] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3932): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3932): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3932): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3932): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  820): Start proc 4384:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4384): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4384):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4384):   adb logcat -s GAv4
,W/GAv4    ( 4384): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4384): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4384): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,I/ActivityManager(  820): Killing 3413:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/UsageStatsService(  820): User[0] Flushing usage stats to disk
,V/GoogleAuthProtoRequest( 3932): [431] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  820): Explicit concurrent mark sweep GC freed 42550(2MB) AllocSpace objects, 8(410KB) LOS objects, 32% free, 33MB/49MB, paused 1.557ms total 53.981ms
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3932): [431] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3932): [431] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3932): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3932): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3932): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3932): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3932): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3932): 	at com.a.a.k.run(SourceFile:110)
,I/EventLogService( 1843): Opted in for usage reporting
I/EventLogService( 1843): Aggregate from 1449745645874 (log), 1449745645874 (data)
,W/EventLogAggregator( 1843): Unknown tag: snet_gcore
,W/EventLogAggregator( 1843): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1843): dumping service [account]
,I/ProcessStatsService(  820): Prepared write state in 7ms
,I/ProcessStatsService(  820): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-11-38.bin
,I/GLSUser ( 1336): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1336): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1336): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1336): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1336): Explicit concurrent mark sweep GC freed 87005(3MB) AllocSpace objects, 9(993KB) LOS objects, 37% free, 27MB/43MB, paused 901us total 32.116ms
,TIME-OUT KILL (timeout was 1800000ms)
```
