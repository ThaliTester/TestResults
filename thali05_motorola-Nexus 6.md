#### Test 57924002a578a80_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  824): Killing 3380:com.google.android.deskclock/u0a44 (adj 15): empty #17
,--------- beginning of main
D/AndroidRuntime( 3817): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3817): CheckJNI is OFF
D/AndroidRuntime( 3817): Calling main entry com.android.commands.am.Am
I/ActivityManager(  824): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  824): addAppToken: AppWindowToken{3a1141b4 token=Token{faace87 ActivityRecord{38000ec6 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3817): Shutting down VM
I/HotwordDetector( 1516): Closing mic
I/MicrophoneInputStream( 1516): mic_close com.google.android.apps.gsa.speech.audio.u@39a677a
V/WindowManager(  824): Adding window Window{c75ded9 u0 Starting com.test.thalitest} at 2 of 7 (after Window{24096fea u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  824): Start proc 3831:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1516): Hotword detection finished
I/HotwordRecognitionRnr( 1516): Stopping hotword detection.
I/ActivityManager(  824): Killing 3071:com.android.settings/1000 (adj 15): empty #17
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660769555
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3831): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3831): Time to load native libraries: 2 ms (timestamps 508-510)
I/LibraryLoader( 3831): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3831): Binding Chromium to main looper Looper (main, tid 1) {3876cbcb}
I/LibraryLoader( 3831): Expected native library version number "",actual native library version number ""
I/chromium( 3831): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3831): Initializing chromium process, singleProcess=true
W/art     ( 3831): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3831): ApplicationContext is null in ApplicationStatus
W/chromium( 3831): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3831): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3831): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3831): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ce80413:true
W/art     ( 3831): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3831): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3831): CordovaWebView is running on device made by: motorola
W/art     ( 3831): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3831): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3831): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3831): Validating map...
V/WindowManager(  824): Adding window Window{23aa1803 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{c75ded9 u0 Starting com.test.thalitest})
W/chromium( 3831): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3831): Initialized EGL, version 1.4
D/OpenGLRenderer( 3831): Enabling debug mode 0
I/Keyboard.Facilitator( 1238): onFinishInput()
I/ActivityManager(  824): Displayed com.test.thalitest/.MainActivity: +639ms
W/BindingManager( 3831): Cannot call determinedVisibility() - never saw a connection for the pid: 3831
D/JsMessageQueue( 3831): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3831): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576399232
I/chromium( 3831): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3831): Initializing JXcore engine
W/jxcore-log( 3831): JXcore engine is ready
,W/Thread-426( 3886): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10391]" dev="sockfs" ino=10391 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-426( 3886): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-426( 3886): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9953]" dev="sockfs" ino=9953 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-426( 3886): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[24636]" dev="sockfs" ino=24636 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3831): Starting JXcore engine,
,W/jxcore-log( 3831): Platform android,
W/jxcore-log( 3831): 
W/jxcore-log( 3831): Process ARCH arm,
W/jxcore-log( 3831): 
,I/jxcore-log( 3831): JXcore Cordova bridge is ready!
I/jxcore-log( 3831): 
W/jxcore-log( 3831): JXcore engine is started
,I/jxcore-log( 3831): Toggling radios to true
I/jxcore-log( 3831): 
,D/BluetoothAdapter( 3831): enable(): BT is already enabled..!
,D/WifiService(  824): setWifiEnabled: true pid=3831, uid=10265
,E/WifiService(  824): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3831): Radios toggled
I/jxcore-log( 3831): 
D/WifiService(  824): New client listening to asynchronous messages
I/jxcore-log( 3831): My device name is: motorola-Nexus 6
I/jxcore-log( 3831): 
,I/wpa_supplicant( 1148): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  824): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1255): Read error: ssl=0xaed55600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1255): SSL shutdown failed: ssl=0xaed55600: I/O error during system call, Broken pipe
,E/WifiStateMachine(  824): Start Disconnecting Watchdog 1
D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  824): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  824): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/ConnectivityService(  824): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/WifiNetworkAgent(  824): NetworkAgent: NetworkAgent channel lost
D/CSLegacyTypeTracker(  824): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Disconnected - quitting
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  824): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  824): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  824): MasterInitialState.processMessage what=3
,D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  824): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkChangeNotifierAutoDetect( 1516): Network connectivity changed, type is: 6
,D/ConnectivityService(  824): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,I/NetworkMonitor( 3092): type=WIFI subType= reason=null isConnected=false
,D/Tethering(  824): MasterInitialState.processMessage what=3
D/PhoneInterfaceManager( 1324): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1324): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  824): getDataEnabled: retVal=false
,V/MusicLeanback( 3092): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  824): No APN found to select.
,E/WifiConfigStore(  824): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  824): will read network variables netId=0
,D/PhoneInterfaceManager( 1324): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1324): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  824): getDataEnabled: retVal=false
I/ActivityManager(  824): Start proc 3894:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  824): CMD_AUTO_CONNECT did save config ->  nid=0
E/WifiConfigStore(  824): will read network variables netId=0
E/GpsLocationProvider(  824): No APN found to select.
,I/ActivityManager(  824): Start proc 3920:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  824): Killing 2553:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/SprintDMReceiver( 3920): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3920): simOperator:  IMSI: null
D/SprintDMReceiver( 3920): Not Sprint UICC, don't do anything.
,I/ActivityManager(  824): Killing 3484:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/SystemUpdateService( 1778): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1778): onCreate
,D/SystemUpdateService( 1778): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1778): active receiver: enabled
,I/SystemUpdateService( 1778): showing system update notification
,I/iu.Environment( 1778): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1778): num queued entries: 0
I/iu.UploadsManager( 1778): num updated entries: 0
,I/iu.SyncManager( 1778): NEXT; no task
,I/ValidateNoPeople(  824): skipping global notification
,V/SystemUpdateService( 1778): retry (wakeup: false) in 3599972 ms
,D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1778): onDestroy
,I/Babel   ( 3700): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  824): Start proc 3940:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GAv4    ( 3940): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3940):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3940):   adb logcat -s GAv4
,W/GAv4    ( 3940): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3940): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3940): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3940): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3940): Time to load native libraries: 2 ms (timestamps 4651-4653)
,I/LibraryLoader( 3940): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3940): Binding Chromium to main looper Looper (main, tid 1) {2a84ca4e}
,I/LibraryLoader( 3940): Expected native library version number "",actual native library version number ""
I/chromium( 3940): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3940): Initializing chromium process, singleProcess=true
,W/art     ( 3940): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3940): ApplicationContext is null in ApplicationStatus
,W/chromium( 3940): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3940): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3940): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3940): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/NSApplication( 3940): Starting up...
,W/AudioManagerAndroid( 3940): Requires BLUETOOTH permission
,I/ActivityManager(  824): Start proc 3996:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  824): Killing 3545:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/wpa_supplicant( 1148): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  824): Killing 3569:com.android.musicfx/u0a18 (adj 15): empty #17
,V/MusicLeanback( 3092): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3920): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3920): simOperator:  IMSI: null
D/SprintDMReceiver( 3920): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1778): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/ActivityManager(  824): Killing 3596:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/wpa_supplicant( 1148): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1148): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1148): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  824): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
E/WifiStateMachine(  824): Start Dhcp Watchdog 2
,D/SystemUpdateService( 1778): onCreate
,E/WifiStateMachine(  824):  WifiLinkLayerStats: 
E/WifiStateMachine(  824):  my bss beacon rx: 192
E/WifiStateMachine(  824):  RSSI mgmt: -52
E/WifiStateMachine(  824):  BE :  rx=158 tx=145 lost=0 retries=0
E/WifiStateMachine(  824):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  on_time : 10144 tx_time=160 rx_time=323 scan_time=0
,D/SystemUpdateService( 1778): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/ConnectivityService(  824): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,I/SystemUpdateService( 1778): active receiver: enabled
,I/SystemUpdateService( 1778): showing system update notification
,D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  824): skipping global notification
,V/SystemUpdateService( 1778): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1778): onDestroy
,I/ActivityManager(  824): Killing 3290:android.process.acore/u0a5 (adj 15): empty #17
,E/native  (  824): do suspend false
,E/WifiStateMachine(  824): scanCount==0 - aborting
,I/ActivityManager(  824): Waited long enough for: ServiceRecord{25dc6da4 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/dhcpcd  ( 4024): version 5.5.6 starting
,I/dhcpcd  ( 4024): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 4024): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 4024): wlan0: leased 192.168.1.122 for 86400 seconds,
,D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  824): Adding iface wlan0 to network 101
,E/WifiStateMachine(  824): Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
,E/ConnectivityService(  824): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  824): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  824): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  824): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101,
,D/ConnectivityService(  824): Setting Dns servers for network 101 to [/192.168.1.1],
,D/ConnectivityService(  824): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101],
,D/ConnectivityService(  824): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  824): rematching NetworkAgentInfo [WIFI () - 101],
,D/ConnectivityService(  824):    accepting network in place of null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  824): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  824): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  824): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  824): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  824): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  824): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  824): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
,D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  824): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3092): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1516): Network connectivity changed, type is: 2
,V/MusicLeanback( 3092): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  824): Start proc 4056:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,D/PhoneInterfaceManager( 1324): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1324): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  824): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3920): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  824): No APN found to select.
,D/SprintDMHelper( 3920): simOperator:  IMSI: null
D/SprintDMReceiver( 3920): Not Sprint UICC, don't do anything.
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  824): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 00:41:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454460091978], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454460091964]}
,I/art     (  824): Explicit concurrent mark sweep GC freed 47996(2MB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 1.443ms total 63.760ms
,I/SystemUpdateService( 1778): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  824): Validated
D/ConnectivityService(  824): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  824): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  824): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  824): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  824): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
,I/ActivityManager(  824): Start proc 4074:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,D/SystemUpdateService( 1778): onCreate
,D/SystemUpdateService( 1778): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1778): active receiver: enabled
,I/SystemUpdateService( 1778): showing system update notification
,I/ValidateNoPeople(  824): skipping global notification
,I/iu.Environment( 1778): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1778): num queued entries: 0
,I/iu.UploadsManager( 1778): num updated entries: 0
,I/iu.SyncManager( 1778): NEXT; no task
,V/SystemUpdateService( 1778): retry (wakeup: false) in 3599965 ms
,D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1778): onDestroy
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 28548(1543KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 877us total 22.741ms
,D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/GAV2    ( 4074): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4074): Created application version: 3.6.8 (30608)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 3700): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1778): [AccountUtils] Account not ready
W/Kids    ( 1778): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1778): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1778): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1778): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1778): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1778): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1778): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1778): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1778): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1778): 	at java.lang.Thread.run(Thread.java:818)
,V/Herrevad( 1778): NQAS connected
,V/KeepSync( 4056): Connecting to GoogleApiClient
,D/GCM     ( 1255): Connected
,I/BooksSync( 4074): Starting books sync for 61035162, extras: ade
,I/GCM     ( 1778): Message from null null
E/GCM     ( 1778): Dropping message from null
,D/GCM     ( 1255): Message class com.google.f.a.a.p
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1778): Handling authorization failure
E/ClientConnectionOperation( 1778): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1778): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1778): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1778): 	... 7 more
,V/KeepSync( 4056): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksConfig( 4074): GmsCore Version = 7.8.99 (2134222-430)
,E/KeepSync( 4056): IOException
E/KeepSync( 4056): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4056): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4056): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4056): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4056): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4056): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4056): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4056): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4056): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4056): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4056): 	... 10 more
W/KeepSync( 4056): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 75681, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4074): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4074): Soft error
E/BooksSync( 4074): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4074): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4074): Sync error
E/BooksSync( 4074): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4074): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4074): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 76834, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  824): Killing 3421:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/ConnectivityService(  824): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3831): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3831): 
,I/jxcore-log( 3831): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3831): 
,I/jxcore-log( 3831): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3831): 
,I/jxcore-log( 3831): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3831): 
,I/jxcore-log( 3831): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3831): 
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3634): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 3634): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 3634): [1] 5.onFinished: Scheduling replication attempt 1.,
,I/ActivityManager(  824): Start proc 4129:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 322us total 16.948ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 239us total 10.442ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 9.428ms
,W/ResourcesManager( 4129): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 4129): Created com.android.providers.calendar.CalendarAlarmManager@101c669a(com.android.providers.calendar.CalendarProvider2@3876cbcb)
,I/art     (  824): Explicit concurrent mark sweep GC freed 27022(1213KB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 34MB/50MB, paused 1.163ms total 48.598ms
,E/SQLiteLog( 4129): (284) automatic index on view_events(_id)
,I/CalendarProvider2( 4129): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4129): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/GAV2    ( 4074): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3831): Test app app.js loaded
I/jxcore-log( 3831): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3831): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3831): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3831): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3831): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3831): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3831): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3831): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3831): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3831): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3831): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14e9d63e added. We now have 1 listener(s)
,I/jxcore-log( 3831): BLE advertisement is supported
I/jxcore-log( 3831): 
I/chromium( 3831): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.48 rxSuccessRate=9.56 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.48 rxSuccessRate=9.56 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,I/ActivityManager(  824): Killing 3461:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  824): Killing 3674:com.google.android.gms:car/u0a11 (adj 15): empty #18
,D/Finsky  ( 3634): [385] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 22003(1243KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.898ms total 39.960ms
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3634): [385] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.36 rxSuccessRate=5.71 targetRoamBSSID=any RSSI=-52
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3634): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3634): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3634): [1] 5.onFinished: Scheduling replication attempt 2.
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at blb.a(PG:3937)
E/HttpOperation( 3268): 	at czp.a(PG:18188)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 12 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at hec.a(PG:42)
E/HttpOperation( 3268): 	at hee.a(PG:102)
E/HttpOperation( 3268): 	at czr.a(PG:65)
E/HttpOperation( 3268): 	at kka.a(PG:108)
E/HttpOperation( 3268): 	at czp.a(PG:19176)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 15 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 17 more
E/ExperimentLoader( 3268): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): 	at jdm.a(PG:82)
E/ExperimentLoader( 3268): 	at jcs.o(PG:406)
E/ExperimentLoader( 3268): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3268): 	at jcs.i(PG:143)
E/ExperimentLoader( 3268): 	at hec.a(PG:42)
E/ExperimentLoader( 3268): 	at hee.a(PG:102)
E/ExperimentLoader( 3268): 	at czr.a(PG:65)
E/ExperimentLoader( 3268): 	at kka.a(PG:108)
E/ExperimentLoader( 3268): 	at czp.a(PG:19176)
E/ExperimentLoader( 3268): 	at czp.a(PG:9081)
E/ExperimentLoader( 3268): 	at czq.run(PG:1686)
E/ExperimentLoader( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3268): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3268): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3268): 	at jdm.a(PG:77)
E/ExperimentLoader( 3268): 	... 15 more
E/ExperimentLoader( 3268): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3268): 	at fal.a(PG:38)
E/ExperimentLoader( 3268): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3268): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 78694, reason: Periodic, SyncResult: stats [ numIoExceptions: 1],
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.44 rxSuccessRate=2.33 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  824): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3634): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3634): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3634): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1238): run()
,I/Keyboard.Facilitator( 1238): flushDynamicLanguageModels()
,I/ConfigService( 1255): onCreate
,I/ConfigService( 1255): onDestroy
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.44 rxSuccessRate=3.31 targetRoamBSSID=any RSSI=-52,
,I/BooksSync( 4074): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4056): Connecting to GoogleApiClient
,I/BooksConfig( 4074): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1778): Handling authorization failure
E/ClientConnectionOperation( 1778): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1778): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1778): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1778): 	... 7 more
,V/KeepSync( 4056): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4074): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4074): Soft error
E/BooksSync( 4074): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4074): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4074): Sync error
,E/BooksSync( 4074): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4074): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4074): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 108815, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  824): Explicit concurrent mark sweep GC freed 43511(1988KB) AllocSpace objects, 15(522KB) LOS objects, 31% free, 34MB/50MB, paused 2.348ms total 104.980ms
,E/KeepSync( 4056): IOException
E/KeepSync( 4056): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4056): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4056): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4056): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4056): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4056): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4056): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4056): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4056): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4056): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4056): 	... 10 more
,W/KeepSync( 4056): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 107905, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3634): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3634): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3634): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.16 rxSuccessRate=3.55 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  824): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  824): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  824): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  261): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (234 us)
,D/SurfaceFlinger(  261): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  261): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService(  824): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  824): Display changed displayId=0
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  261): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  261): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  824): Excessive delay in setPowerMode(): 276ms
,I/DreamManagerService(  824): Entering dreamland.
I/PowerManagerService(  824): Dozing...
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,I/DreamController(  824): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,E/WifiStateMachine(  824): cancelDelayedScan -> 12
,E/native  (  824): do suspend false
,I/Keyboard.Facilitator( 1238): onFinishInput()
,E/WifiStateMachine(  824): cancelDelayedScan -> 14
,E/native  (  824): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3634): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3634): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3634): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  871): STATUS: Received file 'm9kefs1'
,I/kickstart(  871): STATUS: 950272 bytes transferred in 0.993021 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at blb.a(PG:3937)
E/HttpOperation( 3268): 	at czp.a(PG:18188)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 12 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at hec.a(PG:42)
E/HttpOperation( 3268): 	at hee.a(PG:102)
E/HttpOperation( 3268): 	at czr.a(PG:65)
E/HttpOperation( 3268): 	at kka.a(PG:108)
E/HttpOperation( 3268): 	at czp.a(PG:19176)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 15 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 17 more
E/ExperimentLoader( 3268): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): 	at jdm.a(PG:82)
E/ExperimentLoader( 3268): 	at jcs.o(PG:406)
E/ExperimentLoader( 3268): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3268): 	at jcs.i(PG:143),
,E/ExperimentLoader( 3268): 	at hec.a(PG:42)
E/ExperimentLoader( 3268): 	at hee.a(PG:102)
E/ExperimentLoader( 3268): 	at czr.a(PG:65)
E/ExperimentLoader( 3268): 	at kka.a(PG:108),
,E/ExperimentLoader( 3268): 	at czp.a(PG:19176),
E/ExperimentLoader( 3268): 	at czp.a(PG:9081)
E/ExperimentLoader( 3268): 	at czq.run(PG:1686)
E/ExperimentLoader( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3268): 	at java.lang.Thread.run(Thread.java:818),
E/ExperimentLoader( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3268): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3268): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3268): 	at jdm.a(PG:77)
E/ExperimentLoader( 3268): 	... 15 more
E/ExperimentLoader( 3268): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3268): 	at fal.a(PG:38)
E/ExperimentLoader( 3268): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3268): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 139592, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 36809(2MB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 26MB/42MB, paused 1.383ms total 40.333ms,
,V/GoogleAuthProtoRequest( 3894): [421] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1255): Vacuum at: now=1454460201248 tag=VacuumService
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3634): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3634): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3634): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3894): [421] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3894): [421] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3894): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3894): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3894): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3894): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1255): Using platform SSLCertificateSocketFactory
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1255): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1255): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1255): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1255): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1255): No account for auth token provided
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1255): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1255): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1255): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1255): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1255): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1255): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1255): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
,E/Uploader( 1255): ,	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1255): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255):  no longer exists, so no auth token.
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1255): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1255): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1255): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1255): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  824): Explicit concurrent mark sweep GC freed 44769(2MB) AllocSpace objects, 11(270KB) LOS objects, 31% free, 34MB/50MB, paused 2.560ms total 92.944ms
,E/Uploader( 1255): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1255): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1255): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1255): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GoogleAuthProtoRequest( 3894): [422] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3894): [422] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3894): [422] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3894): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3894): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3894): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3894): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1238): run()
I/Keyboard.Facilitator( 1238): flushDynamicLanguageModels()
,I/ConfigService( 1255): onCreate
,I/BooksSync( 4074): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4056): Connecting to GoogleApiClient,
,I/BooksConfig( 4074): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1778): Handling authorization failure
E/ClientConnectionOperation( 1778): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1778): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1778): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1778): 	... 7 more
,V/KeepSync( 4056): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4074): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4074): Soft error
E/BooksSync( 4074): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4074): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4074): Sync error
E/BooksSync( 4074): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4074): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4074): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 200067, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4056): IOException
E/KeepSync( 4056): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4056): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4056): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4056): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4056): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4056): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4056): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4056): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4056): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4056): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4056): 	... 10 more
W/KeepSync( 4056): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 198555, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1255): onDestroy
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at blb.a(PG:3937)
E/HttpOperation( 3268): 	at czp.a(PG:18188)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 12 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at hec.a(PG:42)
E/HttpOperation( 3268): 	at hee.a(PG:102)
E/HttpOperation( 3268): 	at czr.a(PG:65)
E/HttpOperation( 3268): 	at kka.a(PG:108)
E/HttpOperation( 3268): 	at czp.a(PG:19176)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 15 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 17 more
,E/ExperimentLoader( 3268): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): 	at jdm.a(PG:82)
E/ExperimentLoader( 3268): 	at jcs.o(PG:406)
E/ExperimentLoader( 3268): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3268): 	at jcs.i(PG:143)
E/ExperimentLoader( 3268): 	at hec.a(PG:42)
E/ExperimentLoader( 3268): 	at hee.a(PG:102)
E/ExperimentLoader( 3268): 	at czr.a(PG:65)
E/ExperimentLoader( 3268): 	at kka.a(PG:108)
E/ExperimentLoader( 3268): 	at czp.a(PG:19176)
E/ExperimentLoader( 3268): 	at czp.a(PG:9081)
E/ExperimentLoader( 3268): 	at czq.run(PG:1686)
E/ExperimentLoader( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3268): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3268): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3268): 	at jdm.a(PG:77)
E/ExperimentLoader( 3268): 	... 15 more
E/ExperimentLoader( 3268): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3268): 	at fal.a(PG:38)
E/ExperimentLoader( 3268): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3268): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 232051, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  824): Start proc 4236:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4236): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4236):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4236):   adb logcat -s GAv4
,W/GAv4    ( 4236): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4236): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4236): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  824): Killing 3441:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3894): [423] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 70967(3MB) AllocSpace objects, 8(743KB) LOS objects, 36% free, 28MB/44MB, paused 1.172ms total 43.403ms
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3894): [423] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3894): [423] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3894): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3894): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3894): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3894): 	at com.a.a.k.run(SourceFile:110)
,I/EventLogService( 1778): Opted in for usage reporting
I/EventLogService( 1778): Aggregate from 1454458506017 (log), 1454458506017 (data)
,D/WifiService(  824): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@144ea02f}
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,W/EventLogAggregator( 1778): Unknown tag: snet_gcore
W/EventLogAggregator( 1778): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1778): dumping service [account]
,D/WifiService(  824): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@144ea02f}
,D/WifiService(  824): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@30360fc5}
,E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/art     (  824): Explicit concurrent mark sweep GC freed 35714(1697KB) AllocSpace objects, 14(695KB) LOS objects, 31% free, 34MB/50MB, paused 1.588ms total 77.101ms
,V/KeepSync( 4056): Connecting to GoogleApiClient
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1778): Handling authorization failure
E/ClientConnectionOperation( 1778): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1778): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1778): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1778): 	... 7 more
,V/KeepSync( 4056): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 4056): IOException
E/KeepSync( 4056): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4056): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4056): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4056): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4056): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4056): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4056): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4056): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4056): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4056): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4056): 	... 10 more
W/KeepSync( 4056): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 349778, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1255): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1255): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1255): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1255): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1255): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1255): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1255): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3634): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3634): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3634): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3634): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3634): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3634): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3634): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3634): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/WifiService(  824): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@30360fc5}
,I/BooksSync( 4074): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4074): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4074): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4074): Soft error
E/BooksSync( 4074): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4074): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4074): Sync error
E/BooksSync( 4074): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4074): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4074): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 352989, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at blb.a(PG:3937)
E/HttpOperation( 3268): 	at czp.a(PG:18188)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 12 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at hec.a(PG:42)
E/HttpOperation( 3268): 	at hee.a(PG:102)
E/HttpOperation( 3268): 	,at czr.a(PG:65)
E/HttpOperation( 3268): 	at kka.a(PG:108)
E/HttpOperation( 3268): 	at czp.a(PG:19176)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 15 more
,E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 17 more
E/ExperimentLoader( 3268): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): 	at jdm.a(PG:82)
E/ExperimentLoader( 3268): 	at jcs.o(PG:406)
E/ExperimentLoader( 3268): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3268): 	at jcs.i(PG:143)
E/ExperimentLoader( 3268): 	at hec.a(PG:42)
E/ExperimentLoader( 3268): 	at hee.a(PG:102)
E/ExperimentLoader( 3268): 	at czr.a(PG:65)
E/ExperimentLoader( 3268): 	at kka.a(PG:108)
E/ExperimentLoader( 3268): 	at czp.a(PG:19176)
E/ExperimentLoader( 3268): 	at czp.a(PG:9081)
E/ExperimentLoader( 3268): 	at czq.run(PG:1686)
E/ExperimentLoader( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3268): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3268): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3268): 	at jdm.a(PG:77)
E/ExperimentLoader( 3268): 	... 15 more,
E/ExperimentLoader( 3268): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3268): 	at fal.a(PG:38)
E/ExperimentLoader( 3268): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3268): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 386711, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3894): [424] a.<init>: mAccountName set to: thalitester@gmail.com,
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3894): [424] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3894): [424] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3894): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3894): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3894): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3894): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,V/KeepSync( 4056): Connecting to GoogleApiClient
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1778): Handling authorization failure
E/ClientConnectionOperation( 1778): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1778): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1778): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1778): 	... 7 more
,V/KeepSync( 4056): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
,I/art     (  824): Explicit concurrent mark sweep GC freed 38058(1666KB) AllocSpace objects, 8(410KB) LOS objects, 31% free, 34MB/50MB, paused 2.520ms total 76.683ms
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4056): IOException
E/KeepSync( 4056): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4056): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4056): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4056): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4056): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4056): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4056): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4056): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4056): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4056): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4056): 	... 10 more
W/KeepSync( 4056): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 595188, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,I/BooksSync( 4074): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4074): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 52248(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.285ms total 64.387ms
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4074): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4074): Soft error
E/BooksSync( 4074): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4074): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4074): Sync error
E/BooksSync( 4074): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4074): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4074): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 631888, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3894): [425] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3894): [425] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3894): [425] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3894): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3894): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3894): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3894): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at blb.a(PG:3937)
E/HttpOperation( 3268): 	at czp.a(PG:18188)
E/HttpOperation( 3268): 	at czp.a(PG:9087)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 12 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at blb.a(PG:3937)
E/HttpOperation( 3268): 	at czp.a(PG:18188)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 12 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3268): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at hec.a(PG:42)
E/HttpOperation( 3268): 	at hee.a(PG:102)
E/HttpOperation( 3268): 	at czr.a(PG:65)
E/HttpOperation( 3268): 	at kka.a(PG:108)
E/HttpOperation( 3268): 	at czp.a(PG:19176)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 15 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 17 more
,E/ExperimentLoader( 3268): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3268): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): 	at jdm.a(PG:82)
E/ExperimentLoader( 3268): 	at jcs.o(PG:406)
E/ExperimentLoader( 3268): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3268): 	at jcs.i(PG:143)
E/ExperimentLoader( 3268): 	,at hec.a(PG:42)
E/ExperimentLoader( 3268): 	at hee.a(PG:102)
E/ExperimentLoader( 3268): 	at czr.a(PG:65)
E/ExperimentLoader( 3268): 	at kka.a(PG:108)
E/ExperimentLoader( 3268): 	at czp.a(PG:19176)
E/ExperimentLoader( 3268): 	at czp.a(PG:9081)
E/ExperimentLoader( 3268): 	at czq.run(PG:1686)
E/ExperimentLoader( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3268): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3268): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3268): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3268): 	at jdm.a(PG:77)
,E/ExperimentLoader( 3268): 	... 15 more
E/ExperimentLoader( 3268): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3268): 	at fal.a(PG:38)
E/ExperimentLoader( 3268): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3268): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 410502, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at blb.a(PG:3937)
E/HttpOperation( 3268): 	at czp.a(PG:18188)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 12 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at hec.a(PG:42)
E/HttpOperation( 3268): 	at hee.a(PG:102)
E/HttpOperation( 3268): 	at czr.a(PG:65)
E/HttpOperation( 3268): 	at kka.a(PG:108)
E/HttpOperation( 3268): 	at czp.a(PG:19176)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 15 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 17 more
E/ExperimentLoader( 3268): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): 	at jdm.a(PG:82)
E/ExperimentLoader( 3268): 	at jcs.o(PG:406)
E/ExperimentLoader( 3268): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3268): 	at jcs.i(PG:143)
E/ExperimentLoader( 3268): 	at hec.a(PG:42)
E/ExperimentLoader( 3268): 	at hee.a(PG:102)
E/ExperimentLoader( 3268): 	at czr.a(PG:65)
E/ExperimentLoader( 3268): 	at kka.a(PG:108)
E/ExperimentLoader( 3268): 	at czp.a(PG:19176)
E/ExperimentLoader( 3268): 	at czp.a(PG:9081)
E/ExperimentLoader( 3268): 	at czq.run(PG:1686)
E/ExperimentLoader( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3268): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3268): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3268): 	at jdm.a(PG:77)
E/ExperimentLoader( 3268): 	... 15 more
E/ExperimentLoader( 3268): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3268): 	at fal.a(PG:38)
E/ExperimentLoader( 3268): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3268): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 718594, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at blb.a(PG:3937)
E/HttpOperation( 3268): 	at czp.a(PG:18188)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 12 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at hec.a(PG:42)
E/HttpOperation( 3268): 	at hee.a(PG:102)
E/HttpOperation( 3268): 	at czr.a(PG:65)
E/HttpOperation( 3268): 	at kka.a(PG:108)
E/HttpOperation( 3268): 	at czp.a(PG:19176)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 15 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 17 more
,E/ExperimentLoader( 3268): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): 	at jdm.a(PG:82)
E/ExperimentLoader( 3268): 	at jcs.o(PG:406)
E/ExperimentLoader( 3268): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3268): 	at jcs.i(PG:143)
E/ExperimentLoader( 3268): 	at hec.a(PG:42)
E/ExperimentLoader( 3268): 	at hee.a(PG:102)
E/ExperimentLoader( 3268): 	at czr.a(PG:65)
E/ExperimentLoader( 3268): 	at kka.a(PG:108)
E/ExperimentLoader( 3268): 	at czp.a(PG:19176)
E/ExperimentLoader( 3268): 	at czp.a(PG:9081)
E/ExperimentLoader( 3268): 	at czq.run(PG:1686)
E/ExperimentLoader( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3268): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3268): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3268): 	at jdm.a(PG:77)
E/ExperimentLoader( 3268): 	... 15 more
E/ExperimentLoader( 3268): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3268): 	at fal.a(PG:38)
E/ExperimentLoader( 3268): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3268): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 811075, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at blb.a(PG:3937)
E/HttpOperation( 3268): 	at czp.a(PG:18188)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 12 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 14 more
,I/art     (  824): Explicit concurrent mark sweep GC freed 45430(1991KB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.463ms total 100.491ms
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at hec.a(PG:42)
E/HttpOperation( 3268): 	at hee.a(PG:102)
E/HttpOperation( 3268): 	at czr.a(PG:65)
E/HttpOperation( 3268): 	at kka.a(PG:108)
E/HttpOperation( 3268): 	at czp.a(PG:19176)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 15 more,
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 17 more
E/ExperimentLoader( 3268): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): 	at jdm.a(PG:82)
E/ExperimentLoader( 3268): 	at jcs.o(PG:406)
E/ExperimentLoader( 3268): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3268): 	at jcs.i(PG:143)
E/ExperimentLoader( 3268): 	at hec.a(PG:42)
E/ExperimentLoader( 3268): 	at hee.a(PG:102)
E/ExperimentLoader( 3268): 	at czr.a(PG:65)
E/ExperimentLoader( 3268): 	at kka.a(PG:108)
E/ExperimentLoader( 3268): 	at czp.a(PG:19176)
E/ExperimentLoader( 3268): 	at czp.a(PG:9081)
E/ExperimentLoader( 3268): 	at czq.run(PG:1686)
E/ExperimentLoader( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3268): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3268): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3268): 	at jdm.a(PG:77)
E/ExperimentLoader( 3268): 	... 15 more
E/ExperimentLoader( 3268): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3268): 	at fal.a(PG:38)
E/ExperimentLoader( 3268): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3268): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 941733, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btm  ( 2162): Stopping oneshot timer
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 53371(2MB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 26MB/42MB, paused 1.579ms total 45.127ms
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,V/KeepSync( 4056): Connecting to GoogleApiClient
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1778): Handling authorization failure
E/ClientConnectionOperation( 1778): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1778): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1778): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1778): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1778): 	... 7 more
,V/KeepSync( 4056): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4056): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4056): IOException
E/KeepSync( 4056): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4056): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4056): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4056): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4056): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4056): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4056): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4056): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4056): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4056): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4056): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4056): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4056): 	... 10 more
W/KeepSync( 4056): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1085498, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/GCM     ( 1255): Message class com.google.f.a.a.i
,V/GoogleAuthProtoRequest( 3894): [426] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3894): [426] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3894): [426] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3894): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3894): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3894): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3894): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3894): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3894): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 4074): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4074): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4074): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4074): Soft error
E/BooksSync( 4074): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4074): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4074): Sync error
E/BooksSync( 4074): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4074): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4074): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1158790, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at blb.a(PG:3937)
E/HttpOperation( 3268): 	at czp.a(PG:18188)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 12 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3268): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3268): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3268): 	at jdm.a(PG:82)
E/HttpOperation( 3268): 	at jcs.o(PG:406)
E/HttpOperation( 3268): 	at jcn.a(PG:1379)
E/HttpOperation( 3268): 	at jcs.i(PG:143)
E/HttpOperation( 3268): 	at hec.a(PG:42)
E/HttpOperation( 3268): 	at hee.a(PG:102)
E/HttpOperation( 3268): 	at czr.a(PG:65)
E/HttpOperation( 3268): 	at kka.a(PG:108)
E/HttpOperation( 3268): 	at czp.a(PG:19176)
E/HttpOperation( 3268): 	at czp.a(PG:9081)
E/HttpOperation( 3268): 	at czq.run(PG:1686)
E/HttpOperation( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3268): 	at jdj.a(PG:4091)
E/HttpOperation( 3268): 	at jdj.a(PG:1125)
E/HttpOperation( 3268): 	at jdm.a(PG:77)
E/HttpOperation( 3268): 	... 15 more
E/HttpOperation( 3268): Caused by: faj: BadAuthentication
E/HttpOperation( 3268): 	at fal.a(PG:38)
E/HttpOperation( 3268): 	at jdj.a(PG:4089)
E/HttpOperation( 3268): 	... 17 more
,E/ExperimentLoader( 3268): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3268): 	at jdm.a(PG:82)
E/ExperimentLoader( 3268): 	at jcs.o(PG:406)
E/ExperimentLoader( 3268): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3268): 	at jcs.i(PG:143)
E/ExperimentLoader( 3268): 	at hec.a(PG:42)
E/ExperimentLoader( 3268): 	at hee.a(PG:102)
E/ExperimentLoader( 3268): 	at czr.a(PG:65)
E/ExperimentLoader( 3268): 	at kka.a(PG:108)
E/ExperimentLoader( 3268): 	at czp.a(PG:19176)
E/ExperimentLoader( 3268): 	at czp.a(PG:9081)
E/ExperimentLoader( 3268): 	at czq.run(PG:1686)
E/ExperimentLoader( 3268): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3268): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3268): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3268): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3268): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3268): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3268): 	at jdm.a(PG:77)
E/ExperimentLoader( 3268): 	... 15 more
E/ExperimentLoader( 3268): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3268): 	at fal.a(PG:38)
E/ExperimentLoader( 3268): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3268): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1202689, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/UsageStatsService(  824): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2162): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4486): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4486): CheckJNI is OFF
D/AndroidRuntime( 4486): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  824): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  824): Killing 3831:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  824): Skipping PackageSetting{26974037 com.example.hello/10273} due to missing metadata
D/WifiService(  824): Client connection lost with reason: 4
E/libprocessgroup(  824): failed to kill 1 processes for processgroup 3831
W/InputDispatcher(  824): channel '23aa1803 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  824): channel '23aa1803 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
W/ActivityManager(  824): Force removing ActivityRecord{38000ec6 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
I/WindowState(  824): WIN DEATH: Window{23aa1803 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputDispatcher(  824): Attempted to unregister already unregistered input channel '23aa1803 com.test.thalitest/com.test.thalitest.MainActivity (server)'
V/ActivityManager(  824): Display changed displayId=0
I/ActivityManager(  824): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
I/Keyboard.Facilitator( 1238): resetDictionaries() : en_US
I/InputReader(  824): Reconfiguring input devices.  changes=0x00000010
D/BuaReceiver( 3527): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator.DecoderInitializer( 1238): run()
D/TaskPersister(  824): removeObsoleteFile: deleting file=28_task.xml
I/Decoder ( 1238): createOrResetDecoder
I/ActivityManager(  824): Start proc 4501:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     ( 1067): Explicit concurrent mark sweep GC freed 76334(3MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 1.057ms total 68.794ms
I/art     ( 1516): Explicit concurrent mark sweep GC freed 3872(265KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 365us total 70.442ms
I/art     (  824): Explicit concurrent mark sweep GC freed 41853(2MB) AllocSpace objects, 12(380KB) LOS objects, 31% free, 34MB/50MB, paused 1.911ms total 83.782ms
I/art     (  824): WaitForGcToComplete blocked for 73.566ms for cause Explicit
W/InputMethodManagerService(  824): Got RemoteException sending setActive(false) notification to pid 3831 uid 10265
I/ConfigService( 1255): onCreate
I/Keyboard.Facilitator( 1238): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1238): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1238): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
W/LocationOracleImpl( 1516): Best location was null
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1238): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1238): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1238): run()
I/StatsUtilsManager( 1238): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1238): shouldRecordStats() = Too Soon
I/art     ( 1357): Explicit concurrent mark sweep GC freed 5701(419KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 646us total 26.519ms
I/HotwordRecognitionRnr( 1516): Starting hotword detection.
I/MicrophoneInputStream( 1516): mic_starting com.google.android.apps.gsa.speech.audio.u@102bf83
I/AudioFlinger(  358): AudioFlinger's thread 0xb4cd0000 ready to run
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1516): mic_started com.google.android.apps.gsa.speech.audio.u@102bf83
D/JobSchedulerService(  824): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  824): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
E/DataBuffer( 1803): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@104303c9)
I/art     ( 1803): Explicit concurrent mark sweep GC freed 17523(1055KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.896ms total 33.255ms
I/art     (  824): Explicit concurrent mark sweep GC freed 6724(312KB) AllocSpace objects, 1(110KB) LOS objects, 31% free, 34MB/50MB, paused 2.008ms total 153.857ms
I/ActivityManager(  824): Start proc 4540:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
D/VoicemailCleanupService( 4501): Cleaning up data for package: com.test.thalitest
I/HotwordWorker( 1516): onReady
I/ContactLocale( 4501): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/WifiService(  824): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@ad0a028}
E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=26.75 rxSuccessRate=32.50 targetRoamBSSID=any RSSI=-52
I/art     ( 4486): System.exit called, status: 0
I/AndroidRuntime( 4486): VM exiting with result code 0.
I/ActivityManager(  824): Start proc 4561:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=68.88 rxSuccessRate=186.75 targetRoamBSSID=any RSSI=-52
W/ContextImpl( 4561): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660769555
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/NetworkScheduler.SchedulerReceiver( 1255): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1255): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/Launcher.Workspace( 1357): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1357): 11683562 - stripEmptyScreens()
D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1778): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1778): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1778): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1778): Clearing selected account for com.test.thalitest
I/UpdateIcingCorporaServi( 1516): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  824): Killing 3092:com.google.android.music:main/u0a66 (adj 15): empty #17
W/Launcher( 1357): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@37192ef2 new=com.google.android.velvet.VelvetApplication@37192ef2
I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
E/SQLiteLog( 1778): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1778): disk I/O error (code 3850)
E/DriveAsyncService( 1778): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1778): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1778): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1778): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1778): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1778): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1778): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1778): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1778): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1778): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1778): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1778): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1778): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1516): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AppDataSearchHelper( 1516): Exception thrown from onTableChanged
E/AppDataSearchHelper( 1516): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1516): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 1516): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 1516): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AppDataSearchHelper( 1516): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 1516): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 1516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 1516): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 1516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 1516): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1516): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 1516): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 1516): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 1516): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 1516): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 1516): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 1516): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 1516): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 1516): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 1516): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 1516): 	... 16 more
W/AppDataSearchHelper( 1516): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 1516): UpdateCorporaTask done [took 122 ms] updated apps [took 122 ms] 
E/SQLiteLog( 4501): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 4501): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4501): Process: android.process.acore, PID: 4501
E/AndroidRuntime( 4501): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4501): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4501): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4501): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4501): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4501): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4501): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 4501): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 4501): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4501): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4501): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4501): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  824): Start proc 4589:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/LocationSettingsChecker( 1778): Removing dialog suppression flag for package com.test.thalitest
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
E/SQLiteDatabase( 1778): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1778): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1778): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1778): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1778): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1778): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1778): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1778): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1778): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1778): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1778): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1778): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1778): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1778): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1778): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1778): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1778): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1778): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1778): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1778): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1778): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 1778): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1778): Process: com.google.android.gms, PID: 1778
E/AndroidRuntime( 1778): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1778): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1778): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1778): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1778): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1778): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1778): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1778): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1778): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1778): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1778): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  824): Start proc 4609:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/SQLiteDatabase( 1778): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1778): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1778): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1778): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1778): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1778): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1778): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1778): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1778): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1778): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1778): Opened phenotype.db in read-only mode
D/OpenGLRenderer(  824): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  824): Validating map...
E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
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
I/ConfigFetchService( 1778): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
W/ResourcesManager( 4609): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4609): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager(  824): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  824): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/SharedPreferencesImpl( 1778): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
I/ConfigFetchService( 1778): service connected
I/PeopleContactsSync( 1778): CP2 sync disabled
W/BaseAppContext( 1778): Using Auth Proxy for data requests.
I/Icing   ( 1778): doRemovePackageData com.test.thalitest
I/OpenGLRenderer(  824): Initialized EGL, version 1.4
W/BaseAppContext( 1778): Using Auth Proxy for data requests.
D/OpenGLRenderer(  824): Enabling debug mode 0
E/SQLiteDatabase( 1778): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1778): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1778): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1778): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1778): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1778): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1778): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1778): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1778): Runtime exception while performing operation
E/ClearPendingStateOp( 1778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1778): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1778): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1778): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1778): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1778): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1778): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1778): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1778): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1778): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1778): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1778): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1778): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1778): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1778): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1778): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1778): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  824): Can't write: system_app_wtf
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
I/MultiDex( 4609): VM with version 2.1.0 has multidex support
I/MultiDex( 4609): install
I/MultiDex( 4609): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 4609): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ProviderInstaller( 4609): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4609): Failed to open lock file
W/NativeLibraryUtils( 4609): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4609): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4609): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4609): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4609): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4609): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4609): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4609): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4609): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4609): 	... 3 more
I/ActivityManager(  824): Killing 3920:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
I/MicrophoneInputStream( 1516): mic_close com.google.android.apps.gsa.speech.audio.u@102bf83
I/HotwordDetector( 1516): Closing mic
E/Search.SharedPreferencesProto( 1516): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/ActivityManager(  824): Killing 3940:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1516): Hotword detection finished
I/HotwordRecognitionRnr( 1516): Stopping hotword detection.
I/GAv4    ( 4589): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4589):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4589):   adb logcat -s GAv4
W/GAv4    ( 4589): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4589): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4589): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4589): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4589): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4589): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4589): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4589): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4589): 	at aen.run(PG:536)
E/SQLiteDatabase( 4589): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4589): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4589): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4589): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4589): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4589): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4589): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4589): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4589): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4589): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4589): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4589): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4589): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4589): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4589): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4589): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4589): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4589): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4589): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4589): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4589): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4589): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4589): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4589): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4589): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4589): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4589): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4589): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4589): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4589): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4589): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 4589): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4589): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4589): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4589): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4589): 	at aej.c(PG:139)
E/SQLiteDatabase( 4589): 	at aej.b(PG:398)
E/SQLiteDatabase( 4589): 	at agf.f(PG:417)
E/SQLiteDatabase( 4589): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4589): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4589): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4589): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4589): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4589): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4589): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4589): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4589): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4589): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4589): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4589): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4589): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4589): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4589): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4589): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4589): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4589): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4589): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4589): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4589): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4589): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4589): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4589): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4589): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4589): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4589): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 4589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4589): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4589): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4589): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4589): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 4589): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4589): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/native  ( 1238): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1238): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/ActivityManager(  824): Start proc 4655:com.android.docume,ntsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  824): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  824): addAppToken: AppWindowToken{3f171ea9 token=Token{1fdce230 ActivityRecord{26eef373 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4589): Sending signal. PID: 4589 SIG: 9
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
I/ActivityManager(  824): Start proc 4672:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  824): Spurious death for ProcessRecord{12f68d8a 4672:com.google.android.apps.docs/u0a46}, curProc for 4589: null
W/OpenGLRenderer( 1357): Incorrectly called buildLayer on View: ew, destroying layer...
E/native  ( 1238): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1238): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1238): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1238): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1238): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1238): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/SQLiteDatabase( 4655): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4655): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4655): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4655): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4655): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4655): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4655): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4655): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4655): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4655): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4655): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4655): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4655): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4655): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4655): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4655): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4655): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4655): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4655): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4655): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4655): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4655): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4655): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4655): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4655): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4655): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)

```
