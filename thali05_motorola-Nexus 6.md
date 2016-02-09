#### Test 584164489c56086_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
--------- beginning of system
I/ActivityManager(  822): Killing 3362:com.google.android.deskclock/u0a44 (adj 15): empty #17
I/ActivityManager(  822): Killing 3119:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,D/AndroidRuntime( 3798): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3798): CheckJNI is OFF
D/AndroidRuntime( 3798): Calling main entry com.android.commands.am.Am
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{172f534c token=Token{2d86477f ActivityRecord{32da709e u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3798): Shutting down VM
V/WindowManager(  822): Adding window Window{d57a777 u0 Starting com.test.thalitest} at 2 of 7 (after Window{b58c0af u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/MicrophoneInputStream( 1505): mic_close com.google.android.apps.gsa.speech.audio.u@3cc3fa39
I/HotwordDetector( 1505): Closing mic
I/ActivityManager(  822): Start proc 3812:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1505): Stopping hotword detection.
I/HotwordRecognitionRnr( 1505): Hotword detection finished
I/ActivityManager(  822): Killing 3063:com.android.settings/1000 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1701938451
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3812): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3812): Time to load native libraries: 1 ms (timestamps 9011-9012)
,I/LibraryLoader( 3812): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3812): Binding Chromium to main looper Looper (main, tid 1) {588f787}
,I/LibraryLoader( 3812): Expected native library version number "",actual native library version number ""
I/chromium( 3812): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3812): Initializing chromium process, singleProcess=true
W/art     ( 3812): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3812): ApplicationContext is null in ApplicationStatus
,W/chromium( 3812): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3812): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3812): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3812): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e4edf81:true
,W/art     ( 3812): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3812): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3812): CordovaWebView is running on device made by: motorola
,W/art     ( 3812): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3812): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  822): Explicit concurrent mark sweep GC freed 22030(1096KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 2.400ms total 115.640ms
,D/OpenGLRenderer( 3812): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3812): Validating map...
V/WindowManager(  822): Adding window Window{3a0daaf1 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{d57a777 u0 Starting com.test.thalitest})
W/chromium( 3812): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3812): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3812): Enabling debug mode 0,
,I/Keyboard.Facilitator( 1237): onFinishInput()
I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +644ms
,W/BindingManager( 3812): Cannot call determinedVisibility() - never saw a connection for the pid: 3812
,D/JsMessageQueue( 3812): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3812): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576380672
,I/chromium( 3812): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3812): Initializing JXcore engine
W/jxcore-log( 3812): JXcore engine is ready
,W/Thread-426( 3864): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[13017]" dev="sockfs" ino=13017 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-426( 3864): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-426( 3864): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13131]" dev="sockfs" ino=13131 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-426( 3864): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23654]" dev="sockfs" ino=23654 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3812): Starting JXcore engine
,W/jxcore-log( 3812): Platform android
W/jxcore-log( 3812): 
W/jxcore-log( 3812): Process ARCH arm
W/jxcore-log( 3812): 
,I/jxcore-log( 3812): JXcore Cordova bridge is ready!
I/jxcore-log( 3812): 
,W/jxcore-log( 3812): JXcore engine is started
,I/jxcore-log( 3812): Toggling radios to true
,I/jxcore-log( 3812): 
,D/BluetoothAdapter( 3812): enable(): BT is already enabled..!
,D/WifiService(  822): New client listening to asynchronous messages
,D/WifiService(  822): setWifiEnabled: true pid=3812, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3812): Radios toggled
I/jxcore-log( 3812): 
I/jxcore-log( 3812): My device name is: motorola-Nexus 6
I/jxcore-log( 3812): 
,I/wpa_supplicant( 1149): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1311): Read error: ssl=0xaed02200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1311): SSL shutdown failed: ssl=0xaed02200: I/O error during system call, Broken pipe
D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  354): Clearing all IP addresses on wlan0
D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkChangeNotifierAutoDetect( 1505): Network connectivity changed, type is: 6
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 3082): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  822): MasterInitialState.processMessage what=3
,E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,V/MusicLeanback( 3082): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1379): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1379): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/WifiConfigStore(  822): will read network variables netId=0
,E/GpsLocationProvider(  822): No APN found to select.
,I/ActivityManager(  822): Start proc 3872:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,D/PhoneInterfaceManager( 1379): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1379): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,I/ActivityManager(  822): Start proc 3898:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  822): Killing 2557:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/SprintDMReceiver( 3898): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3898): simOperator:  IMSI: null
,D/SprintDMReceiver( 3898): Not Sprint UICC, don't do anything.
I/ActivityManager(  822): Killing 3468:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/SystemUpdateService( 1773): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1773): onCreate
,D/SystemUpdateService( 1773): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1773): active receiver: enabled
,I/SystemUpdateService( 1773): showing system update notification
,I/iu.Environment( 1773): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1773): retry (wakeup: false) in 3599967 ms
,I/iu.UploadsManager( 1773): num queued entries: 0
I/iu.UploadsManager( 1773): num updated entries: 0
I/iu.SyncManager( 1773): NEXT; no task
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1773): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/SystemUpdateService( 1773): onDestroy
,I/Babel   ( 3683): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  822): Start proc 3919:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GAv4    ( 3919): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3919):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3919):   adb logcat -s GAv4
,W/GAv4    ( 3919): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3919): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3919): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3919): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3919): Time to load native libraries: 1 ms (timestamps 2881-2882)
I/LibraryLoader( 3919): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3919): Binding Chromium to main looper Looper (main, tid 1) {2ba21b6b}
I/LibraryLoader( 3919): Expected native library version number "",actual native library version number ""
I/chromium( 3919): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3919): Initializing chromium process, singleProcess=true
,W/art     ( 3919): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3919): ApplicationContext is null in ApplicationStatus
,W/chromium( 3919): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3919): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3919): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3919): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3919): Requires BLUETOOTH permission
,I/NSApplication( 3919): Starting up...
,I/ActivityManager(  822): Start proc 3975:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  822): Killing 3524:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3546:com.android.musicfx/u0a18 (adj 15): empty #17
,V/MusicLeanback( 3082): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3898): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3898): simOperator:  IMSI: null
,D/SprintDMReceiver( 3898): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1773): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1773): onCreate
,D/SystemUpdateService( 1773): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,I/wpa_supplicant( 1149): wlan0: Trying to associate with SSID 'NG7005g'
,I/SystemUpdateService( 1773): active receiver: enabled
,I/SystemUpdateService( 1773): showing system update notification
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1773): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1773): retry (wakeup: false) in 3599937 ms
,D/SystemUpdateService( 1773): onDestroy
,I/wpa_supplicant( 1149): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1149): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1149): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
,E/WifiStateMachine(  822):  my bss beacon rx: 181
E/WifiStateMachine(  822):  RSSI mgmt: -53
E/WifiStateMachine(  822):  BE :  rx=180 tx=145 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=7 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 8841 tx_time=148 rx_time=320 scan_time=0
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/dhcpcd  ( 4003): version 5.5.6 starting
,I/dhcpcd  ( 4003): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  822): Killing 3277:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3575:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,I/dhcpcd  ( 4003): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 4003): wlan0: leased 192.168.1.122 for 86400 seconds
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{20dbf6c2 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 101,
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101],
,D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  822): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3082): type=WIFI subType= reason=null isConnected=true
D/NetworkChangeNotifierAutoDetect( 1505): Network connectivity changed, type is: 2
,D/PhoneInterfaceManager( 1379): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1379): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,V/MusicLeanback( 3082): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMReceiver( 3898): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3898): simOperator:  IMSI: null
D/SprintDMReceiver( 3898): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1773): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1773): onCreate
,D/SystemUpdateService( 1773): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1773): active receiver: enabled
,I/SystemUpdateService( 1773): showing system update notification
,I/iu.Environment( 1773): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1773): num queued entries: 0
,I/iu.UploadsManager( 1773): num updated entries: 0
,I/iu.SyncManager( 1773): NEXT; no task
I/ValidateNoPeople(  822): skipping global notification
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1773): retry (wakeup: false) in 3599981 ms
,I/Kids    ( 1773): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1773): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 09:19:46 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455009586484], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455009586460]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
,V/Herrevad( 1773): NQAS connected
,I/Babel   ( 3683): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1311): Connected
,D/GCM     ( 1311): Message class com.google.f.a.a.p
,I/jxcore-log( 3812): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3812): 
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3812): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3812): 
,I/jxcore-log( 3812): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3812): 
,I/jxcore-log( 3812): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3812): 
,I/jxcore-log( 3812): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
,I/jxcore-log( 3812): 
,I/jxcore-log( 3812): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3812): 
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3613): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3613): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3613): [1] 5.onFinished: Scheduling replication attempt 1.
,I/art     ( 1311): Explicit concurrent mark sweep GC freed 31196(1697KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 941us total 25.402ms
,I/jxcore-log( 3812): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3812): 
,I/jxcore-log( 3812): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 3812): 
,I/jxcore-log( 3812): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3812): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.48 rxSuccessRate=10.08 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3812): Test app app.js loaded
I/jxcore-log( 3812): 
,I/chromium( 3812): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3812): load: 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3812): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3812): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3812): 	,Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3812): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3812): 	Peer expiration time in milliseconds: 60000, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3812): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3812): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3812): ,	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3812): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36bd3729 added. We now have 1 listener(s)
,I/jxcore-log( 3812): BLE advertisement is supported,
I/jxcore-log( 3812): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.74 rxSuccessRate=6.54 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.30 rxSuccessRate=3.60 targetRoamBSSID=any RSSI=-53
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 58660(2MB) AllocSpace objects, 12(286KB) LOS objects, 32% free, 33MB/49MB, paused 2.823ms total 88.913ms
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3613): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3613): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3613): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  822): Start proc 4057:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3257): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3257): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3257): 	at jdm.a(PG:82)
E/HttpOperation( 3257): 	at jcs.o(PG:406)
E/HttpOperation( 3257): 	at jcn.a(PG:1379)
E/HttpOperation( 3257): 	at jcs.i(PG:143)
E/HttpOperation( 3257): 	at blb.a(PG:3937)
E/HttpOperation( 3257): 	at czp.a(PG:18188)
E/HttpOperation( 3257): 	at czp.a(PG:9081)
E/HttpOperation( 3257): 	at czq.run(PG:1686)
E/HttpOperation( 3257): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3257): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3257): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3257): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3257): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3257): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3257): 	at jdj.a(PG:4091)
E/HttpOperation( 3257): 	at jdj.a(PG:1125)
E/HttpOperation( 3257): 	at jdm.a(PG:77)
E/HttpOperation( 3257): 	... 12 more
E/HttpOperation( 3257): Caused by: faj: BadAuthentication
E/HttpOperation( 3257): 	at fal.a(PG:38)
E/HttpOperation( 3257): 	at jdj.a(PG:4089)
E/HttpOperation( 3257): 	... 14 more
,V/KeepSync( 4057): Connecting to GoogleApiClient,
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3257): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3257): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3257): 	at jdm.a(PG:82)
E/HttpOperation( 3257): 	at jcs.o(PG:406)
E/HttpOperation( 3257): 	at jcn.a(PG:1379)
E/HttpOperation( 3257): 	at jcs.i(PG:143)
E/HttpOperation( 3257): 	at hec.a(PG:42)
E/HttpOperation( 3257): 	at hee.a(PG:102)
E/HttpOperation( 3257): 	at czr.a(PG:65)
E/HttpOperation( 3257): 	at kka.a(PG:108)
E/HttpOperation( 3257): 	at czp.a(PG:19176)
E/HttpOperation( 3257): 	at czp.a(PG:9081)
E/HttpOperation( 3257): 	at czq.run(PG:1686)
E/HttpOperation( 3257): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3257): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3257): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3257): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3257): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3257): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3257): 	at jdj.a(PG:4091)
E/HttpOperation( 3257): 	at jdj.a(PG:1125)
E/HttpOperation( 3257): 	at jdm.a(PG:77)
E/HttpOperation( 3257): 	... 15 more
E/HttpOperation( 3257): Caused by: faj: BadAuthentication
E/HttpOperation( 3257): 	at fal.a(PG:38)
E/HttpOperation( 3257): 	at jdj.a(PG:4089)
E/HttpOperation( 3257): 	... 17 more
,E/ExperimentLoader( 3257): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3257): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3257): 	at jdm.a(PG:82)
E/ExperimentLoader( 3257): 	at jcs.o(PG:406)
E/ExperimentLoader( 3257): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3257): 	at jcs.i(PG:143)
E/ExperimentLoader( 3257): 	at hec.a(PG:42)
E/ExperimentLoader( 3257): 	at hee.a(PG:102)
E/ExperimentLoader( 3257): 	at czr.a(PG:65)
E/ExperimentLoader( 3257): 	at kka.a(PG:108)
E/ExperimentLoader( 3257): 	at czp.a(PG:19176)
E/ExperimentLoader( 3257): 	at czp.a(PG:9081)
E/ExperimentLoader( 3257): 	at czq.run(PG:1686)
E/ExperimentLoader( 3257): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3257): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3257): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3257): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3257): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3257): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3257): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3257): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3257): 	at jdm.a(PG:77)
E/ExperimentLoader( 3257): 	... 15 more
E/ExperimentLoader( 3257): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3257): 	at fal.a(PG:38)
E/ExperimentLoader( 3257): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3257): 	... 17 more
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1773): Handling authorization failure,
E/ClientConnectionOperation( 1773): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
,E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
,E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
,E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1773): 	at java.lang.Thread.run(Thread.java:818)
,E/ClientConnectionOperation( 1773): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:370),
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1773): 	,at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1773): 	... 7 more
,V/KeepSync( 4057): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4057): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4057): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4057): (284) automatic index on blob_node(is_deleted)
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 77407, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  822): Start proc 4089:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4057): IOException
E/KeepSync( 4057): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4057): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4057): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4057): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4057): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4057): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4057): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4057): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4057): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4057): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4057): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4057): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4057): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4057): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4057): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4057): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4057): 	... 10 more
W/KeepSync( 4057): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 77349, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/GAV2    ( 4089): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/art     ( 1311): Explicit concurrent mark sweep GC freed 19225(1166KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 26MB/42MB, paused 986us total 24.788ms,
,I/BooksApp( 4089): Created application version: 3.6.8 (30608)
,I/BooksSync( 4089): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4089): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4089): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4089): Soft error,
E/BooksSync( 4089): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 4089): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4089): Sync error
E/BooksSync( 4089): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 4089): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4089): Finished books sync,
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78801, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 3443:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3654:com.google.android.gms:car/u0a11 (adj 15): empty #18
,I/GAV2    ( 4089): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.66 rxSuccessRate=2.59 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3613): [385] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3613): [385] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 36432(1699KB) AllocSpace objects, 7(112KB) LOS objects, 31% free, 34MB/50MB, paused 1.573ms total 99.602ms
,D/Finsky  ( 3613): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3613): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3613): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1237): run()
I/Keyboard.Facilitator( 1237): flushDynamicLanguageModels()
,I/ConfigService( 1311): onCreate
,I/ConfigService( 1311): onDestroy
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.38 rxSuccessRate=2.81 targetRoamBSSID=any RSSI=-52
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3613): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3613): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3613): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.79 rxSuccessRate=2.42 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (326 us)
,D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb6082000
I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/qdhwcomposer(  280): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  822): Display changed displayId=0
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  280): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 279ms
,I/DreamManagerService(  822): Entering dreamland.
,I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0,
I/PowerManagerService(  822): Dozing...,
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1237): onFinishInput()
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): cancelDelayedScan -> 14
,E/native  (  822): do suspend true
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3613): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3613): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3613): [1] 5.onFinished: Scheduling replication attempt 5.
,I/kickstart(  872): STATUS: Received file 'm9kefs1'
I/kickstart(  872): STATUS: 950272 bytes transferred in 1.004055 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed,
,I/BooksSync( 4089): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4089): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3257): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3257): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3257): 	at jdm.a(PG:82)
E/HttpOperation( 3257): 	at jcs.o(PG:406)
E/HttpOperation( 3257): 	at jcn.a(PG:1379)
E/HttpOperation( 3257): 	at jcs.i(PG:143)
E/HttpOperation( 3257): 	at blb.a(PG:3937)
E/HttpOperation( 3257): 	at czp.a(PG:18188)
E/HttpOperation( 3257): 	at czp.a(PG:9081)
E/HttpOperation( 3257): 	at czq.run(PG:1686)
E/HttpOperation( 3257): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3257): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3257): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3257): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3257): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3257): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3257): 	at jdj.a(PG:4091)
E/HttpOperation( 3257): 	at jdj.a(PG:1125)
E/HttpOperation( 3257): 	at jdm.a(PG:77)
E/HttpOperation( 3257): 	... 12 more
E/HttpOperation( 3257): Caused by: faj: BadAuthentication
E/HttpOperation( 3257): 	at fal.a(PG:38)
E/HttpOperation( 3257): 	at jdj.a(PG:4089)
E/HttpOperation( 3257): 	... 14 more
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3257): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3257): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3257): 	at jdm.a(PG:82)
E/HttpOperation( 3257): 	at jcs.o(PG:406)
E/HttpOperation( 3257): 	at jcn.a(PG:1379)
E/HttpOperation( 3257): 	at jcs.i(PG:143)
E/HttpOperation( 3257): 	at hec.a(PG:42)
E/HttpOperation( 3257): 	at hee.a(PG:102)
E/HttpOperation( 3257): 	at czr.a(PG:65)
E/HttpOperation( 3257): 	at kka.a(PG:108)
E/HttpOperation( 3257): 	at czp.a(PG:19176)
E/HttpOperation( 3257): 	at czp.a(PG:9081)
E/HttpOperation( 3257): 	at czq.run(PG:1686)
E/HttpOperation( 3257): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3257): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3257): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3257): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3257): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3257): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3257): 	at jdj.a(PG:4091)
E/HttpOperation( 3257): 	at jdj.a(PG:1125)
E/HttpOperation( 3257): 	at jdm.a(PG:77)
E/HttpOperation( 3257): 	... 15 more
E/HttpOperation( 3257): Caused by: faj: BadAuthentication
E/HttpOperation( 3257): 	at fal.a(PG:38)
E/HttpOperation( 3257): 	at jdj.a(PG:4089)
E/HttpOperation( 3257): 	... 17 more
E/ExperimentLoader( 3257): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3257): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3257): 	at jdm.a(PG:82)
E/ExperimentLoader( 3257): 	at jcs.o(PG:406)
E/ExperimentLoader( 3257): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3257): 	at jcs.i(PG:143)
E/ExperimentLoader( 3257): 	at hec.a(PG:42)
E/ExperimentLoader( 3257): 	at hee.a(PG:102)
E/ExperimentLoader( 3257): 	at czr.a(PG:65)
E/ExperimentLoader( 3257): 	at kka.a(PG:108)
E/ExperimentLoader( 3257): 	at czp.a(PG:19176)
E/ExperimentLoader( 3257): 	at czp.a(PG:9081)
E/ExperimentLoader( 3257): 	at czq.run(PG:1686)
E/ExperimentLoader( 3257): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3257): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3257): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3257): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3257): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3257): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3257): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3257): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3257): 	at jdm.a(PG:77)
E/ExperimentLoader( 3257): 	... 15 more
E/ExperimentLoader( 3257): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3257): 	at fal.a(PG:38)
E/ExperimentLoader( 3257): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3257): 	... 17 more
,E/BooksAccountManager( 4089): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4089): Soft error
E/BooksSync( 4089): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4089): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4089): Sync error
E/BooksSync( 4089): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4089): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4089): Finished books sync
D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 136864, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 4057): Connecting to GoogleApiClient
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 138002, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1773): Handling authorization failure
E/ClientConnectionOperation( 1773): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1773): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1773): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1773): 	... 7 more
,V/KeepSync( 4057): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4057): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4057): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4057): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4057): IOException
E/KeepSync( 4057): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4057): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4057): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4057): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4057): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4057): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4057): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4057): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4057): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4057): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4057): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4057): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4057): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4057): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4057): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4057): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4057): 	... 10 more
W/KeepSync( 4057): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 138396, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,I/VacuumService( 1311): Vacuum at: now=1455009696258 tag=VacuumService
,I/art     ( 1311): Explicit concurrent mark sweep GC freed 38591(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 2.087ms total 46.874ms
,V/GoogleAuthProtoRequest( 3872): [420] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     (  822): Explicit concurrent mark sweep GC freed 46295(2MB) AllocSpace objects, 12(380KB) LOS objects, 31% free, 34MB/50MB, paused 2.004ms total 80.983ms
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3872): [420] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3872): [420] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3872): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3872): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3872): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3872): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3872): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3872): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3872): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3872): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3872): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3872): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1311): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 3613): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3613): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3613): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1311): No account for auth token provided
,W/Uploader( 1311): No account for auth token provided
,W/Uploader( 1311): No account for auth token provided
,W/Uploader( 1311): No account for auth token provided
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1311): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1311): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1311): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
,E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125),
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1311): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1311): No account for auth token provided
,W/Uploader( 1311): No account for auth token provided
,W/Uploader( 1311): No account for auth token provided
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1311): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1311): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1311): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1311): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1311): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1311): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1311): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1311): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1311): No account for auth token provided
,W/Uploader( 1311): No account for auth token provided
,W/Uploader( 1311):  no longer exists, so no auth token.
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1311): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1311): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1311): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1311): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1311): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1311): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1311): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1311): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1311): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1311): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3872): [421] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3872): [421] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3872): [421] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3872): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3872): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3872): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3872): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3872): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3872): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3872): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3872): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3872): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3872): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1237): run()
I/Keyboard.Facilitator( 1237): flushDynamicLanguageModels()
,I/ConfigService( 1311): onCreate
,I/BooksSync( 4089): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4089): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4089): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4089): Soft error
E/BooksSync( 4089): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 4089): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4089): Sync error
E/BooksSync( 4089): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4089): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4089): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 226336, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1311): onDestroy
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,V/KeepSync( 4057): Connecting to GoogleApiClient
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1773): Handling authorization failure
E/ClientConnectionOperation( 1773): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1773): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1773): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1773): 	... 7 more
,V/KeepSync( 4057): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4057): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4057): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4057): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 3257): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3257): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3257): 	at jdm.a(PG:82)
E/HttpOperation( 3257): 	at jcs.o(PG:406)
E/HttpOperation( 3257): 	at jcn.a(PG:1379)
E/HttpOperation( 3257): 	at jcs.i(PG:143)
E/HttpOperation( 3257): 	at blb.a(PG:3937)
E/HttpOperation( 3257): 	at czp.a(PG:18188)
E/HttpOperation( 3257): 	at czp.a(PG:9081)
E/HttpOperation( 3257): 	at czq.run(PG:1686)
E/HttpOperation( 3257): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3257): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3257): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3257): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3257): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3257): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3257): 	at jdj.a(PG:4091)
E/HttpOperation( 3257): 	at jdj.a(PG:1125)
E/HttpOperation( 3257): 	at jdm.a(PG:77)
E/HttpOperation( 3257): 	... 12 more
E/HttpOperation( 3257): Caused by: faj: BadAuthentication
E/HttpOperation( 3257): 	at fal.a(PG:38)
E/HttpOperation( 3257): 	at jdj.a(PG:4089)
E/HttpOperation( 3257): 	... 14 more
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3257): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3257): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3257): 	at jdm.a(PG:82)
E/HttpOperation( 3257): 	at jcs.o(PG:406)
E/HttpOperation( 3257): 	at jcn.a(PG:1379)
E/HttpOperation( 3257): 	at jcs.i(PG:143)
E/HttpOperation( 3257): 	at hec.a(PG:42)
E/HttpOperation( 3257): 	at hee.a(PG:102)
E/HttpOperation( 3257): 	at czr.a(PG:65)
E/HttpOperation( 3257): 	at kka.a(PG:108)
E/HttpOperation( 3257): 	at czp.a(PG:19176)
E/HttpOperation( 3257): 	at czp.a(PG:9081)
E/HttpOperation( 3257): 	at czq.run(PG:1686)
E/HttpOperation( 3257): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3257): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3257): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3257): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3257): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3257): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3257): 	at jdj.a(PG:4091)
E/HttpOperation( 3257): 	at jdj.a(PG:1125)
E/HttpOperation( 3257): 	at jdm.a(PG:77)
E/HttpOperation( 3257): 	... 15 more
E/HttpOperation( 3257): Caused by: faj: BadAuthentication
E/HttpOperation( 3257): 	at fal.a(PG:38)
E/HttpOperation( 3257): 	at jdj.a(PG:4089)
E/HttpOperation( 3257): 	... 17 more
,E/ExperimentLoader( 3257): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3257): java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 3257): 	at jdm.a(PG:82)
E/ExperimentLoader( 3257): 	at jcs.o(PG:406)
E/ExperimentLoader( 3257): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3257): 	at jcs.i(PG:143)
E/ExperimentLoader( 3257): 	at hec.a(PG:42),
E/ExperimentLoader( 3257): 	at hee.a(PG:102)
E/ExperimentLoader( 3257): 	at czr.a(PG:65)
E/ExperimentLoader( 3257): 	at kka.a(PG:108)
E/ExperimentLoader( 3257): 	at czp.a(PG:19176)
E/ExperimentLoader( 3257): 	at czp.a(PG:9081)
E/ExperimentLoader( 3257): ,	at czq.run(PG:1686)
E/ExperimentLoader( 3257): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3257): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3257): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3257): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3257): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3257): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3257): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3257): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3257): 	at jdm.a(PG:77),
E/ExperimentLoader( 3257): 	... 15 more
E/ExperimentLoader( 3257): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3257): 	at fal.a(PG:38)
E/ExperimentLoader( 3257): 	at jdj.a(PG:4089)
,E/ExperimentLoader( 3257): 	... 17 more
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 31118(1374KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 2.561ms total 52.365ms
,E/KeepSync( 4057): IOException
E/KeepSync( 4057): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4057): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4057): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4057): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4057): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4057): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4057): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4057): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4057): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4057): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4057): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4057): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4057): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4057): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4057): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4057): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4057): 	... 10 more
W/KeepSync( 4057): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 231055, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 230216, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,I/jxcore-log( 3812): --= Surplus to requirements =--
I/jxcore-log( 3812): 
I/jxcore-log( 3812): ****TEST TOOK:  ms ****
I/jxcore-log( 3812): 
I/jxcore-log( 3812): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3812): 
,D/AndroidRuntime( 4204): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4204): CheckJNI is OFF
,D/AndroidRuntime( 4204): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 3812:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  822): Skipping PackageSetting{116a6270 com.example.hello/10273} due to missing metadata
,I/WindowState(  822): WIN DEATH: Window{3a0daaf1 u0 com.test.thalitest/com.test.thalitest.MainActivity},
E/libprocessgroup(  822): failed to kill 1 processes for processgroup 3812
,W/ActivityManager(  822): Force removing ActivityRecord{32da709e u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
D/WifiService(  822): Client connection lost with reason: 4
,V/ActivityManager(  822): Display changed displayId=0
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/TaskPersister(  822): removeObsoleteFile: deleting file=28_task.xml
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,D/BuaReceiver( 3501): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator( 1237): resetDictionaries() : en_US
,I/art     (  369): Background concurrent mark sweep GC freed 781(33KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 5.719ms total 14.240ms
,I/ActivityManager(  822): Start proc 4220:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3812 uid 10265
,I/art     ( 1065): Explicit concurrent mark sweep GC freed 57406(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 1.197ms total 50.998ms
,I/Keyboard.Facilitator.DecoderInitializer( 1237): run()
,I/Keyboard.Facilitator( 1237): onFinishInput()
,I/art     (  369): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 193us total 21.846ms
,I/art     (  822): Explicit concurrent mark sweep GC freed 9947(751KB) AllocSpace objects, 10(725KB) LOS objects, 31% free, 34MB/50MB, paused 1.634ms total 77.151ms
I/Decoder ( 1237): createOrResetDecoder
,I/art     (  369): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 207us total 15.547ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 195us total 9.198ms
,I/art     ( 1405): Explicit concurrent mark sweep GC freed 5708(420KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 767us total 23.761ms
,I/art     ( 1505): Explicit concurrent mark sweep GC freed 2236(169KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 1.128ms total 124.416ms
,I/art     (  822): WaitForGcToComplete blocked for 101.444ms for cause Explicit
,W/LocationOracleImpl( 1505): Best location was null
,I/ConfigService( 1311): onCreate
,I/HotwordRecognitionRnr( 1505): Starting hotword detection.
,I/MicrophoneInputStream( 1505): mic_starting com.google.android.apps.gsa.speech.audio.u@31e6e7d0
,I/AudioFlinger(  358): AudioFlinger's thread 0xb4fba000 ready to run
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1505): mic_started com.google.android.apps.gsa.speech.audio.u@31e6e7d0
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1237): run()
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
,D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1237): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1237): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1237): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1237): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1237): run()
I/StatsUtilsManager( 1237): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1237): shouldRecordStats() = Too Soon
,I/art     ( 1311): Explicit concurrent mark sweep GC freed 66741(3MB) AllocSpace objects, 10(961KB) LOS objects, 36% free, 28MB/44MB, paused 2.642ms total 47.973ms
,D/VoicemailCleanupService( 4220): Cleaning up data for package: com.test.thalitest
,I/art     (  822): Explicit concurrent mark sweep GC freed 7555(346KB) AllocSpace objects, 1(110KB) LOS objects, 31% free, 34MB/50MB, paused 2.959ms total 129.781ms
,I/HotwordWorker( 1505): onReady
,I/ActivityManager(  822): Start proc 4258:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,D/Launcher.Workspace( 1405): 11683562 - stripEmptyScreens()
D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@19aef73a}
D/Launcher.Workspace( 1405): 11683562 - stripEmptyScreens()
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,I/ContactLocale( 4220): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  822): Start proc 4278:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/art     ( 4204): System.exit called, status: 0
I/AndroidRuntime( 4204): VM exiting with result code 0.
,W/ContextImpl( 4278): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1701938451
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/NetworkScheduler.SchedulerReceiver( 1311): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1311): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,V/GoogleAuthProtoRequest( 3872): [422] a.<init>: mAccountName set to: thalitester@gmail.com
,D/PackageBroadcastService( 1773): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1773): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1773): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1773): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1773): Removing dialog suppression flag for package com.test.thalitest
,W/Launcher( 1405): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2bef507f new=com.google.android.velvet.VelvetApplication@2bef507f
I/UpdateIcingCorporaServi( 1505): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  822): Start proc 4308:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,D/GOOGLEHELP_CompatibleDatabase( 1773): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1773): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1773): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1773): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1773): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1773): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1773): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/BaseAppContext( 1773): Using Auth Proxy for data requests.
,I/ConfigFetchService( 1773): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/GOOGLEHELP_CompatibleDatabase( 1773): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1773): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1773): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1773): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1773): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1773): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 1773): Using Auth Proxy for data requests.
,I/GLSUser ( 1311): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1311): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1311): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1311): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3872): [422] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3872): [422] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3872): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3872): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3872): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3872): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3872): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3872): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3872): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3872): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3872): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3872): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  822): Killing 2438:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/ConfigFetchService( 1773): service connected
,I/PeopleContactsSync( 1773): CP2 sync disabled
,I/Icing   ( 1773): doRemovePackageData com.test.thalitest
,I/UpdateIcingCorporaServi( 1505): UpdateCorporaTask done [took 341 ms] updated apps [took 341 ms] 
,I/GAv4    ( 4308): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4308):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4308):   adb logcat -s GAv4
,W/GAv4    ( 4308): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4308): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4308): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 4308): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4308): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4308): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4308): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4308): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4308): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4308): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4308): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4308): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4308): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4308): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4308): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4308): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4308): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4308): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4308): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4308): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4308): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4308): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4308): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4308): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4308): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4308): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4308): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4308): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4308): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4308): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4308): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4308): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4308): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4308): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4308): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 4308): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4308): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4308): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4308): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4308): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4308): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4308): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4308): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SQLiteDatabase( 4308): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4308): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4308): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4308): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4308): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4308): 	at aej.c(PG:139)
E/SQLiteDatabase( 4308): 	at aej.b(PG:398)
E/SQLiteDatabase( 4308): 	at agf.f(PG:417)
E/SQLiteDatabase( 4308): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4308): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4308): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4308): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4308): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4308): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4308): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4308): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4308): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/Abstract,DatabaseInstance( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4308): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4308): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4308): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4308): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4308): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4308): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4308): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4308): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4308): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4308): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4308): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4308): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4308): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4308): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4308): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4308): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4308): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/ResourcesManager( 4308): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4308): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4308): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4308): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4308): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 4308): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4308): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4308): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4308): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4308): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4308): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4308): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4308): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4308): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4308): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4308): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4308): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4308): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4308): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4308): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4308): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,V/JNIHelp ( 4308): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  822): Start proc 4348:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  822): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{3b16de4a token=Token{3a0547b5 ActivityRecord{112d17ec u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4308): Sending signal. PID: 4308 SIG: 9
I/HotwordDetector( 1505): Closing mic
I/MicrophoneInputStream( 1505): mic_close com.google.android.apps.gsa.speech.audio.u@31e6e7d0
E/lowmemorykiller(  277): Error writing /proc/4308/oom_score_adj; errno=22
E/JavaBinder(  822): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  822): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  822): android.os.TransactionTooLargeException
W/ActivityManager(  822): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  822): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  822): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  822): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  822): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  822): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  822): 	at android.os.Binder.execTransact(Binder.java:446)
,D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record,
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0,
I/HotwordRecognitionRnr( 1505): Hotword detection finished
I/HotwordRecognitionRnr( 1505): Stopping hotword detection.
,I/ActivityManager(  822): Start proc 4365:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,W/ActivityManager(  822): Spurious death for ProcessRecord{419d254 4365:com.google.android.apps.docs/u0a46}, curProc for 4308: null
,E/native  ( 1237): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1237): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,W/OpenGLRenderer( 1405): Incorrectly called buildLayer on View: ew, destroying layer...
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,E/native  ( 1237): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1237): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1237): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1237): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1237): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1237): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/Search.SharedPreferencesProto( 1505): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  822): Killing 3082:com.google.android.music:main/u0a66 (adj 15): empty #17
,E/SQLiteDatabase( 4348): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4348): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4348): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4348): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4348): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4348): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4348): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4348): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4348): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4348): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4348): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4348): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4348): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4348): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4348): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4348): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4348): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4348): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4348): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4348): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4348): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4348): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4348): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4348): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4348): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4348): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4348): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4348): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4348): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4348): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4348): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 4348): FATAL EXCEPTION: main
E/AndroidRuntime( 4348): Process: com.android.documentsui, PID: 4348
E/AndroidRuntime( 4348): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4348): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4348): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4348): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4348): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4348): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4348): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4348): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRu,ntime( 4348): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4348): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4348): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4348): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4348): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4348): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4348): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4348): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4348): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4348): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4348): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4348): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4348): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4348): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4348): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4348): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4348): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4348): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4348): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4348): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4348): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4348): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4348): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4348): 	... 9 more
,I/ActivityManager(  822): Start proc 4388:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
I/ActivityManager(  822): Killing 3898:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/GAv4    ( 4365): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4365):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4365):   adb logcat -s GAv4
,I/ActivityManager(  822): Killing 3919:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/Icing   ( 1773): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,W/GAv4    ( 4365): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
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
,D/ExternalStorage( 4388): After updating volumes, found 1 active roots
,D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  822): Validating map...
,W/GAv4    ( 4365): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4365): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/OpenGLRenderer(  822): Initialized EGL, version 1.4
,E/SQLiteDatabase( 4365): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4365): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4365): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4365): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4365): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4365): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4365): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4365): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4365): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4365): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4365): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4365): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4365): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4365): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4365): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4365): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4365): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4365): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4365): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4365): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4365): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4365): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4365): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4365): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4365): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4365): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4365): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4365): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4365): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4365): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/OpenGLRenderer(  822): Enabling debug mode 0
E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4365): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4365): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/Icing   ( 1773): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1773): Could not init tag ds.tag.deleted
,W/AnalyticsTrackerProxyImpl( 4365): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4365): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4365): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4365): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4365): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4365): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4365): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4365): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4365): 	at aen.run(PG:536)
,I/Icing   ( 1773): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,E/Icing   ( 1773): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1773): Writing status failed
,E/Icing   ( 1773): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/SQLiteDatabase( 4365): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4365): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4365): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4365): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4365): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4365): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4365): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4365): 	at aej.c(PG:139)
E/SQLiteDatabase( 4365): 	at aej.b(PG:398)
E/SQLiteDatabase( 4365): 	at agf.f(PG:417)
E/SQLiteDatabase( 4365): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4365): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4365): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4365): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4365): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4365): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4365): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4365): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/Abstract,DatabaseInstance( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4365): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4365): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4365): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4365): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4365): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4365): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4365): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4365): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4365): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4365): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 4365): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4365): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ErrorNotificationActivity( 4365): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
,V/JNIHelp ( 4365): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/OpenGLRenderer( 4365): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 4365): Validating map...
,V/WindowManager(  822): Adding window Window{1ecf6402 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 8 (after Window{b58c0af u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@19aef73a}
,V/WindowManager(  822): Adding window Window{6594f50 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 9 (before Window{1ecf6402 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
,I/ProviderInstaller( 4365): Installed default security provider GmsCore_OpenSSL
,W/GAv4    ( 4365): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4365): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4365): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4365): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4365): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,E/SQLiteDatabase( 4365): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4365): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4365): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4365): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4365): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4365): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4365): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4365): 	at aej.c(PG:139)
E/SQLiteDatabase( 4365): 	at aej.a(PG:358)
E/SQLiteDatabase( 4365): 	at aej.a(PG:345)
E/SQLiteDatabase( 4365): 	at agf.d(PG:281)
E/SQLiteDatabase( 4365): 	at agf.b(PG:312)
E/SQLiteDatabase( 4365): 	at agf.a(PG:221)
E/SQLiteDatabase( 4365): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/SQLiteDatabase( 4365): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/SQLiteDatabase( 4365): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4365): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4365): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 4365): 	at android.os.Binder.execTransact(Binder.java:446)
E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/AbstractDatabaseInstance( 4365): Failed to query Account133 object
E/AbstractDatabaseInstance( 4365): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791),
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4365): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4365): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4365): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4365): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4365): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4365): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4365): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4365): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4365): 	at agf.d(PG:281)
E/AbstractDatabaseInstance( 4365): 	at agf.b(PG:312)
E/AbstractDatabaseInstance( 4365): 	at agf.a(PG:221)
E/AbstractDatabaseInstance( 4365): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/AbstractDatabaseInstance( 4365): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/AbstractDatabaseInstance( 4365): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AbstractDatabaseInstance( 4365): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AbstractDatabaseInstance( 4365): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/AbstractDatabaseInstance( 4365): 	at android.os.Binder.execTransact(Binder.java:446)
E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4365): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/DatabaseUtils( 4365): Writing exception to parcel
E/DatabaseUtils( 4365): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 4365): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/DatabaseUtils( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DatabaseUtils( 4365): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DatabaseUtils( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DatabaseUtils( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DatabaseUtils( 4365): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/DatabaseUtils( 4365): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/DatabaseUtils( 4365): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/DatabaseUtils( 4365): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/DatabaseUtils( 4365): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/DatabaseUtils( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 4365): 	at aev.getWritableDatabase(PG:238)
E/DatabaseUtils( 4365): 	at ael.a(PG:1521)
E/DatabaseUtils( 4365): 	at hix$a.a(PG:125)
E/DatabaseUtils( 4365): 	at aej.c(PG:139)
E/DatabaseUtils( 4365): 	at aej.a(PG:358)
E/DatabaseUtils( 4365): 	at aej.a(PG:345)
E/DatabaseUtils( 4365): 	at agf.d(PG:281)
E/DatabaseUtils( 4365): 	at agf.b(PG:312)
E/DatabaseUtils( 4365): 	at agf.a(PG:221)
E/DatabaseUtils( 4365): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/DatabaseUtils( 4365): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/DatabaseUtils( 4365): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 4365): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 4365): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 4365): 	at android.os.Binder.execTransact(Binder.java:446)
,E/GAv4    ( 4365): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4365): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4365): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 4365): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4365): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4365): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4365): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
,E/CAKEMIX_CRASHED( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4365): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4365): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4365): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4365): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4365): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4365): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4365): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4365): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4365): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4365): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4365): 	at aen.run(PG:536)
,E/SharedPreferencesImpl( 4365): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/Documents( 4348): Failed to load some roots from com.google.android.apps.docs.storage: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/Documents( 4348): Update found 6 roots in 641ms
,I/ActivityManager(  822): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,I/Process ( 4365): Sending signal. PID: 4365 SIG: 9
,I/WindowState(  822): WIN DEATH: Window{1ecf6402 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,W/InputDispatcher(  822): channel '6594f50 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  822): channel '6594f50 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,I/ActivityManager(  822): Process com.google.android.apps.docs (pid 4365) has died
,I/WindowState(  822): WIN DEATH: Window{6594f50 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
W/InputDispatcher(  822): Attempted to unregister already unregistered input channel '6594f50 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
,W/ActivityManager(  822): Force removing ActivityRecord{112d17ec u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}: app died, no saved state
,I/ActivityManager(  822): Killing 3975:com.android.chrome/u0a40 (adj 15): empty #17
,E/SQLiteDatabase( 1311): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1311): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1311): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1311): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1311): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1311): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1311): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1311): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1311): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1311): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1311): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1311): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1311): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1311): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1311): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1311): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 1311): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1311): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1311): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1311): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1311): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1311): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1311): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1311): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1311): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1311): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1311): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1311): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1311): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1311): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1311): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1311): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1311): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 1311): Opened phenotype.db in read-only mode
E/SQLiteLog( 1311): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1311): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1311): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1311): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1311): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1311): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1311): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1311): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1311): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1311): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1311): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1311): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1311): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1311): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1311): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1311): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1311): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1311): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1311): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1311): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1311): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1311): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1311): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1311): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1311): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1311): 	at java.lang.Thread.run(Thread.java:818)
,E/Search.SharedPreferencesProto( 1505): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,E/QMI_FW  (  822): xport_send: Sendto failed for port 3840
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1701938451
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/kickstart(  872): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
,E/kickstart(  872): ERROR: function: sahara_main:1143 Sahara protocol error
E/kickstart(  872): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/ConfigService( 1311): onDestroy
,D/        (  358): csd_client_error_cb: error -2 cb_data 0xb604f060,
D/        (  358): csd_client_error_cb: MDM reset
,E/        (  358): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
E/        (  358): csd_service_deinit: Error -1 deiniting CSD
E/ThermalEngine(  366): qmi_clnt_error_cb: with error -2 called for clnt FUSION
,E/ThermalEngine(  366): modem_clnt_error_cb: with -2 called for clnt 0x6
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb0
I/Atfwd_Daemon(  375): Modem Out Of Service --> Release ATCOP service client handles, if any
I/Atfwd_Daemon(  375): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
,I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb2,
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb3
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb5
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb6
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb7
I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb4,
,I/Atfwd_Daemon(  375): Received sys_event: 2 from QMI devId: rmnet_usb1,
,I/ThermalEngine(  366): qmi: Instance id 157 for fusion TS,
,E/        (  358): csd_service_deinit: notifier handle release rc:0
,D/        (  358): csd_service_init: qmi_client_notifier_init() successful
,E/ThermalEngine(  366): qmi_clnt_error_cb: with error -2 called for clnt MODEM,
,V/ImsSenderRxr( 1379): Read packet: 15 bytes
V/ImsSenderRxr( 1379): processResponse
D/ImsSenderRxr( 1379): Response data: [12, 13, -1, -1, -1, -1, 16, 3, 24, -43, 1, 32, 0, 8, 0]
D/ImsSenderRxr( 1379):  Tag -1 3 213 0
,I/str_params(  358): key: 'all_call_states' value: ''
I/str_params(  358): key: 'all_call_states' value: ''
,I/str_params(  358): key: 'all_call_states' value: ''
E/LocSvc_ApiV02(  822): E/void LocApiV02::errorCb(locClientHandleType, locClientErrorEnumType):2688]: Service unavailable error
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -2
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/art     (  822): Explicit concurrent mark sweep GC freed 23307(1223KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 34MB/50MB, paused 1.539ms total 78.470ms

```
