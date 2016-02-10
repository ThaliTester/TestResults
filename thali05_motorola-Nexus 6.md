#### Test 58380500a584679_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/HeadsetStateMachine( 2167): Disconnected process message: 10, size: 0
,D/AndroidRuntime( 3821): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3821): CheckJNI is OFF
--------- beginning of system
I/ActivityManager(  823): Killing 3385:com.google.android.deskclock/u0a44 (adj 15): empty #17
D/AndroidRuntime( 3821): Calling main entry com.android.commands.am.Am
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{3f1da9bc token=Token{ed731af ActivityRecord{3b70e58e u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3821): Shutting down VM
V/WindowManager(  823): Adding window Window{2b4e8c1 u0 Starting com.test.thalitest} at 2 of 7 (after Window{2ae11985 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1515): Closing mic
I/MicrophoneInputStream( 1515): mic_close com.google.android.apps.gsa.speech.audio.u@d125541
I/ActivityManager(  823): Start proc 3835:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/ActivityManager(  823): Killing 3080:com.android.settings/1000 (adj 15): empty #17
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1515): Stopping hotword detection.
I/HotwordRecognitionRnr( 1515): Hotword detection finished
,I/ActivityManager(  823): Killing 2579:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/WebViewFactory( 3835): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659471123
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/LibraryLoader( 3835): Time to load native libraries: 1 ms (timestamps 8685-8686)
,I/LibraryLoader( 3835): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3835): Binding Chromium to main looper Looper (main, tid 1) {2701a5d5}
I/LibraryLoader( 3835): Expected native library version number "",actual native library version number ""
,I/chromium( 3835): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3835): Initializing chromium process, singleProcess=true
W/art     ( 3835): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3835): ApplicationContext is null in ApplicationStatus
,W/chromium( 3835): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3835): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3835): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3835): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31a62bbb:true
,W/art     ( 3835): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3835): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3835): CordovaWebView is running on device made by: motorola
,W/art     ( 3835): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3835): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3835): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3835): Validating map...
,V/WindowManager(  823): Adding window Window{183579ab u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2b4e8c1 u0 Starting com.test.thalitest})
,W/chromium( 3835): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3835): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3835): Enabling debug mode 0
,I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +993ms
,I/Keyboard.Facilitator( 1239): onFinishInput()
,W/BindingManager( 3835): Cannot call determinedVisibility() - never saw a connection for the pid: 3835
,D/JsMessageQueue( 3835): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3835): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576401152
,I/chromium( 3835): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3835): Initializing JXcore engine
W/jxcore-log( 3835): JXcore engine is ready
,W/Thread-431( 3889): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10054]" dev="sockfs" ino=10054 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-431( 3889): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-431( 3889): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10199]" dev="sockfs" ino=10199 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-431( 3889): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23939]" dev="sockfs" ino=23939 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3835): Starting JXcore engine
,W/jxcore-log( 3835): Platform android
W/jxcore-log( 3835): 
,W/jxcore-log( 3835): Process ARCH arm
W/jxcore-log( 3835): 
,I/jxcore-log( 3835): JXcore Cordova bridge is ready!
I/jxcore-log( 3835): 
,W/jxcore-log( 3835): JXcore engine is started
,I/jxcore-log( 3835): Toggling radios to true
I/jxcore-log( 3835): 
D/BluetoothAdapter( 3835): enable(): BT is already enabled..!
,D/WifiService(  823): setWifiEnabled: true pid=3835, uid=10265
,E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  823): New client listening to asynchronous messages
,I/jxcore-log( 3835): Radios toggled
I/jxcore-log( 3835): 
,I/jxcore-log( 3835): My device name is: motorola-Nexus 6
I/jxcore-log( 3835): 
,I/wpa_supplicant( 1148): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state,
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1366): Read error: ssl=0x9cd80800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1366): SSL shutdown failed: ssl=0x9cd80800: I/O error during system call, Broken pipe
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  823): Start Disconnecting Watchdog 1
E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Disconnected - quitting
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  823): MasterInitialState.processMessage what=3
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering(  823): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1515): Network connectivity changed, type is: 6
,V/MusicLeanback( 3102): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1298): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1298): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/GpsLocationProvider(  823): No APN found to select.
,D/PhoneInterfaceManager( 1298): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1298): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,E/WifiConfigStore(  823): Setting BSSID for "NG7005g"WPA_PSK to any
,D/TelephonyManager(  823): getDataEnabled: retVal=false
E/WifiConfigStore(  823): will read network variables netId=0
,I/ActivityManager(  823): Start proc 3897:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,E/GpsLocationProvider(  823): No APN found to select.
,D/SprintDMReceiver( 3897): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3897): simOperator:  IMSI: null
D/SprintDMReceiver( 3897): Not Sprint UICC, don't do anything.
,I/ActivityManager(  823): Killing 3486:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/SystemUpdateService( 1778): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1778): onCreate
,D/SystemUpdateService( 1778): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,I/SystemUpdateService( 1778): active receiver: enabled
,I/iu.Environment( 1778): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1778): num queued entries: 0
I/iu.UploadsManager( 1778): num updated entries: 0
,I/iu.SyncManager( 1778): NEXT; no task
I/SystemUpdateService( 1778): showing system update notification
,D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1778): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/Babel   ( 3705): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1778): retry (wakeup: false) in 3599952 ms
,I/ActivityManager(  823): Start proc 3918:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1778): onDestroy
,I/GAv4    ( 3918): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3918):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3918):   adb logcat -s GAv4
,W/GAv4    ( 3918): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3918): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3918): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3918): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3918): Time to load native libraries: 4 ms (timestamps 2198-2202)
I/LibraryLoader( 3918): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3918): Binding Chromium to main looper Looper (main, tid 1) {2e086520}
,I/LibraryLoader( 3918): Expected native library version number "",actual native library version number ""
,I/chromium( 3918): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3918): Initializing chromium process, singleProcess=true
,W/art     ( 3918): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3918): ApplicationContext is null in ApplicationStatus
,W/chromium( 3918): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3918): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3918): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3918): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3918): Requires BLUETOOTH permission
,I/NSApplication( 3918): Starting up...
,I/ActivityManager(  823): Start proc 3974:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  823): Killing 3506:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3537:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,V/MusicLeanback( 3102): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3897): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3897): simOperator:  IMSI: null
D/SprintDMReceiver( 3897): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1778): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1778): onCreate
,D/SystemUpdateService( 1778): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1778): active receiver: enabled
,I/SystemUpdateService( 1778): showing system update notification
,I/ValidateNoPeople(  823): skipping global notification
,D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,V/SystemUpdateService( 1778): retry (wakeup: false) in 3599949 ms
,I/Kids    ( 1778): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1778): onDestroy
,I/wpa_supplicant( 1148): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  823): Waited long enough for: ServiceRecord{103bc9dd u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/wpa_supplicant( 1148): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1148): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP],
I/wpa_supplicant( 1148): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=],
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 2
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
,E/WifiStateMachine(  823):  my bss beacon rx: 186
E/WifiStateMachine(  823):  RSSI mgmt: -53
E/WifiStateMachine(  823):  BE :  rx=178 tx=160 lost=0 retries=0
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0,
E/WifiStateMachine(  823):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 10026 tx_time=152 rx_time=427 scan_time=0
,D/ConnectivityService(  823): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60,
,E/native  (  823): do suspend false,
,E/WifiStateMachine(  823): scanCount==0 - aborting,
,I/ActivityManager(  823): Killing 3119:android.process.acore/u0a5 (adj 15): empty #17
,I/dhcpcd  ( 4003): version 5.5.6 starting
,I/ActivityManager(  823): Killing 3666:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/dhcpcd  ( 4003): wlan0: rebinding lease of 192.168.1.122
,I/jxcore-log( 3835): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3835): 
,I/dhcpcd  ( 4003): wlan0: acknowledged 192.168.1.122 from 192.168.1.1,
,I/dhcpcd  ( 4003): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  823): Adding iface wlan0 to network 101
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/jxcore-log( 3835): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3835): 
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101,
,D/ConnectivityService(  823): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823):    accepting network in place of null
,D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/Tethering(  823): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3102): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1515): Network connectivity changed, type is: 2
,V/MusicLeanback( 3102): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1298): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1298): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3897): Received intent: android.net.conn.CONNECTIVITY_CHANGE
E/GpsLocationProvider(  823): No APN found to select.
,D/SprintDMHelper( 3897): simOperator:  IMSI: null
D/SprintDMReceiver( 3897): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1778): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1778): onCreate
,D/SystemUpdateService( 1778): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1778): active receiver: enabled
,I/SystemUpdateService( 1778): showing system update notification
,I/jxcore-log( 3835): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3835): 
,I/jxcore-log( 3835): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3835): 
,I/ActivityManager(  823): Start proc 4037:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Feb 2016 01:24:52 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455067492553], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455067492541]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Validated
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/iu.Environment( 1778): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1778): num queued entries: 0
I/iu.UploadsManager( 1778): num updated entries: 0
I/iu.SyncManager( 1778): NEXT; no task
,V/SystemUpdateService( 1778): retry (wakeup: false) in 3599911 ms
D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1778): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1778): onDestroy
,I/jxcore-log( 3835): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3835): 
,I/art     (  823): Explicit concurrent mark sweep GC freed 48152(2MB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 1.528ms total 91.188ms
I/ValidateNoPeople(  823): skipping global notification
,W/GAV2    ( 4037): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/jxcore-log( 3835): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3835): 
,V/Herrevad( 1778): NQAS connected
,I/BooksApp( 4037): Created application version: 3.6.8 (30608)
,I/Babel   ( 3705): connection state changed from DISCONNECTED to CONNECTED
,I/art     ( 1366): Explicit concurrent mark sweep GC freed 30012(1621KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.123ms total 82.775ms
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1366): Connected
,I/BooksSync( 4037): Starting books sync for 61035162, extras: ade
,E/HttpOperation( 3292): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at jdm.a(PG:82)
E/HttpOperation( 3292): 	at jcs.o(PG:406)
E/HttpOperation( 3292): 	at jcn.a(PG:1379)
E/HttpOperation( 3292): 	at jcs.i(PG:143)
E/HttpOperation( 3292): 	at blb.a(PG:3937)
E/HttpOperation( 3292): 	at czp.a(PG:18188)
E/HttpOperation( 3292): 	at czp.a(PG:9081)
E/HttpOperation( 3292): 	at czq.run(PG:1686)
E/HttpOperation( 3292): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3292): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3292): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3292): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3292): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3292): 	at jdj.a(PG:4091)
E/HttpOperation( 3292): 	at jdj.a(PG:1125)
E/HttpOperation( 3292): 	at jdm.a(PG:77)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: faj: BadAuthentication
E/HttpOperation( 3292): 	at fal.a(PG:38)
E/HttpOperation( 3292): 	at jdj.a(PG:4089)
E/HttpOperation( 3292): 	... 14 more
,D/GCM     ( 1366): Message class com.google.f.a.a.p
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3292): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at jdm.a(PG:82)
E/HttpOperation( 3292): 	at jcs.o(PG:406)
E/HttpOperation( 3292): 	at jcn.a(PG:1379)
E/HttpOperation( 3292): 	at jcs.i(PG:143)
E/HttpOperation( 3292): 	at hec.a(PG:42)
E/HttpOperation( 3292): 	at hee.a(PG:102)
E/HttpOperation( 3292): 	at czr.a(PG:65)
E/HttpOperation( 3292): 	at kka.a(PG:108)
E/HttpOperation( 3292): 	at czp.a(PG:19176)
E/HttpOperation( 3292): 	at czp.a(PG:9081)
E/HttpOperation( 3292): 	at czq.run(PG:1686)
E/HttpOperation( 3292): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3292): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3292): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3292): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3292): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3292): 	at jdj.a(PG:4091)
E/HttpOperation( 3292): 	at jdj.a(PG:1125)
E/HttpOperation( 3292): 	at jdm.a(PG:77)
E/HttpOperation( 3292): 	... 15 more
E/HttpOperation( 3292): Caused by: faj: BadAuthentication
E/HttpOperation( 3292): 	at fal.a(PG:38)
E/HttpOperation( 3292): 	at jdj.a(PG:4089)
E/HttpOperation( 3292): 	... 17 more
E/ExperimentLoader( 3292): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): 	at jdm.a(PG:82)
E/ExperimentLoader( 3292): 	at jcs.o(PG:406)
E/ExperimentLoader( 3292): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3292): 	at jcs.i(PG:143)
E/ExperimentLoader( 3292): 	at hec.a(PG:42)
E/ExperimentLoader( 3292): 	at hee.a(PG:102)
E/ExperimentLoader( 3292): 	at czr.a(PG:65)
E/ExperimentLoader( 3292): 	at kka.a(PG:108)
E/ExperimentLoader( 3292): 	at czp.a(PG:19176)
E/ExperimentLoader( 3292): 	at czp.a(PG:9081)
E/ExperimentLoader( 3292): 	at czq.run(PG:1686)
E/ExperimentLoader( 3292): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3292): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3292): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3292): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3292): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3292): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3292): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3292): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3292): 	at jdm.a(PG:77)
E/ExperimentLoader( 3292): 	... 15 more
E/ExperimentLoader( 3292): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3292): 	at fal.a(PG:38)
E/ExperimentLoader( 3292): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3292): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 75908, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Start proc 4078:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/BooksConfig( 4037): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4037): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4037): Soft error
E/BooksSync( 4037): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4037): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4037): Sync error
E/BooksSync( 4037): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4037): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4037): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 76117, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 4078): Connecting to GoogleApiClient
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4078): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4078): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4078): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4078): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/KeepSync( 4078): IOException
E/KeepSync( 4078): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4078): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4078): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4078): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4078): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4078): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4078): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4078): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4078): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4078): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4078): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4078): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4078): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4078): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4078): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4078): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4078): 	... 10 more
W/KeepSync( 4078): Sync result 2
,I/ActivityManager(  823): Killing 3615:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 76202, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3575): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3575): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3575): [1] 5.onFinished: Scheduling replication attempt 1.
,I/art     ( 1366): Explicit concurrent mark sweep GC freed 21344(1235KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.209ms total 31.652ms
,I/jxcore-log( 3835): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3835): 
,I/jxcore-log( 3835): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,I/jxcore-log( 3835): 
,I/jxcore-log( 3835): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3835): 
,I/jxcore-log( 3835): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3835): 
,I/GAV2    ( 4037): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.17 rxSuccessRate=9.38 targetRoamBSSID=any RSSI=-53,
,E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/ActivityManager(  823): Killing 3448:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/jxcore-log( 3835): Test app app.js loaded
I/jxcore-log( 3835): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3835): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3835): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3835): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3835): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3835): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3835): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3835): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3835): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3835): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3835): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2427def3 added. We now have 1 listener(s),
,I/jxcore-log( 3835): BLE advertisement is supported,
I/jxcore-log( 3835): 
,I/chromium( 3835): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=6.09 rxSuccessRate=7.19 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,D/Finsky  ( 3575): [380] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 34004(1550KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.646ms total 70.289ms
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3575): [380] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.13 rxSuccessRate=4.51 targetRoamBSSID=any RSSI=-53
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3575): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3575): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3575): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.44 rxSuccessRate=1.55 targetRoamBSSID=any RSSI=-53
,E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3575): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3575): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3575): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2167): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1239): run()
I/Keyboard.Facilitator( 1239): flushDynamicLanguageModels()
,I/ConfigService( 1366): onCreate
,I/ConfigService( 1366): onDestroy
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.72 rxSuccessRate=2.03 targetRoamBSSID=any RSSI=-53
,I/BooksSync( 4037): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4037): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3292): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at jdm.a(PG:82)
E/HttpOperation( 3292): 	at jcs.o(PG:406)
E/HttpOperation( 3292): 	at jcn.a(PG:1379)
E/HttpOperation( 3292): 	at jcs.i(PG:143)
E/HttpOperation( 3292): 	at blb.a(PG:3937)
E/HttpOperation( 3292): 	at czp.a(PG:18188)
E/HttpOperation( 3292): 	at czp.a(PG:9081)
E/HttpOperation( 3292): 	at czq.run(PG:1686)
E/HttpOperation( 3292): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3292): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3292): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3292): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3292): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3292): 	at jdj.a(PG:4091)
E/HttpOperation( 3292): 	at jdj.a(PG:1125)
E/HttpOperation( 3292): 	at jdm.a(PG:77)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: faj: BadAuthentication
E/HttpOperation( 3292): 	at fal.a(PG:38)
E/HttpOperation( 3292): 	at jdj.a(PG:4089)
E/HttpOperation( 3292): 	... 14 more
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4037): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4037): Soft error
E/BooksSync( 4037): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4037): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4037): Sync error
E/BooksSync( 4037): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4037): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4037): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 109942, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3292): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at jdm.a(PG:82)
E/HttpOperation( 3292): 	at jcs.o(PG:406)
E/HttpOperation( 3292): 	at jcn.a(PG:1379)
E/HttpOperation( 3292): 	at jcs.i(PG:143)
E/HttpOperation( 3292): 	at hec.a(PG:42)
E/HttpOperation( 3292): 	at hee.a(PG:102)
E/HttpOperation( 3292): 	at czr.a(PG:65)
E/HttpOperation( 3292): 	at kka.a(PG:108)
E/HttpOperation( 3292): 	at czp.a(PG:19176)
E/HttpOperation( 3292): 	at czp.a(PG:9081)
E/HttpOperation( 3292): 	at czq.run(PG:1686)
E/HttpOperation( 3292): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3292): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3292): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3292): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3292): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3292): 	at jdj.a(PG:4091)
E/HttpOperation( 3292): 	at jdj.a(PG:1125)
E/HttpOperation( 3292): 	at jdm.a(PG:77)
E/HttpOperation( 3292): 	... 15 more
E/HttpOperation( 3292): Caused by: faj: BadAuthentication
E/HttpOperation( 3292): 	at fal.a(PG:38)
E/HttpOperation( 3292): 	at jdj.a(PG:4089)
E/HttpOperation( 3292): 	... 17 more
E/ExperimentLoader( 3292): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): 	at jdm.a(PG:82)
E/ExperimentLoader( 3292): 	at jcs.o(PG:406)
E/ExperimentLoader( 3292): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3292): 	at jcs.i(PG:143)
E/ExperimentLoader( 3292): 	at hec.a(PG:42)
E/ExperimentLoader( 3292): 	at hee.a(PG:102)
E/ExperimentLoader( 3292): 	at czr.a(PG:65)
E/ExperimentLoader( 3292): 	at kka.a(PG:108)
E/ExperimentLoader( 3292): 	at czp.a(PG:19176)
E/ExperimentLoader( 3292): 	at czp.a(PG:9081)
E/ExperimentLoader( 3292): 	at czq.run(PG:1686)
E/ExperimentLoader( 3292): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3292): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3292): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3292): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3292): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3292): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3292): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3292): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3292): 	at jdm.a(PG:77)
E/ExperimentLoader( 3292): 	... 15 more
E/ExperimentLoader( 3292): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3292): 	at fal.a(PG:38)
E/ExperimentLoader( 3292): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3292): 	... 17 more
,V/KeepSync( 4078): Connecting to GoogleApiClient
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4078): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4078): (284) automatic index on blob_node(is_deleted)
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 107346, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/SQLiteLog( 4078): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4078): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4078): IOException
E/KeepSync( 4078): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4078): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4078): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4078): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4078): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4078): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4078): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4078): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4078): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4078): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4078): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4078): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4078): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.,
E/KeepSync( 4078): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4078): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4078): 	,at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4078): 	... 10 more
W/KeepSync( 4078): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 110027, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3575): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3575): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3575): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.17 rxSuccessRate=2.55 targetRoamBSSID=any RSSI=-53
,E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (240 us)
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
,D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  823): Display changed displayId=0
,I/kickstart(  873): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  873): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  873): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  873): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  823): Excessive delay in setPowerMode(): 255ms
,I/DreamManagerService(  823): Entering dreamland.,
I/PowerManagerService(  823): Dozing...
,I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  823): cancelDelayedScan -> 12
,E/native  (  823): do suspend false
,I/art     (  823): Explicit concurrent mark sweep GC freed 52065(2MB) AllocSpace objects, 23(556KB) LOS objects, 31% free, 34MB/50MB, paused 1.647ms total 97.564ms
,I/Keyboard.Facilitator( 1239): onFinishInput()
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  823): cancelDelayedScan -> 14
,E/native  (  823): do suspend true
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,D/Finsky  ( 3575): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3575): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3575): [1] 5.onFinished: Scheduling replication attempt 5.
,I/kickstart(  873): STATUS: Received file 'm9kefs2'
I/kickstart(  873): STATUS: 950272 bytes transferred in 0.990236 seconds
I/kickstart(  873): STATUS: Successfully downloaded files from target 
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  873): STATUS: Sahara protocol completed
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1366): Explicit concurrent mark sweep GC freed 34753(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.529ms total 54.857ms
,V/GoogleAuthProtoRequest( 3163): [315] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 2167): Disconnected process message: 10, size: 0
,W/ExperimentUpdateService( 3163): [315] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3163): [315] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3163): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3163): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3163): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3163): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3163): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3163): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3163): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3163): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3163): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3163): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1366): Vacuum at: now=1455067600917 tag=VacuumService
,I/GoogleURLConnFactory( 1366): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 3575): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 3575): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3575): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1366): No account for auth token provided
,W/Uploader( 1366): No account for auth token provided
,W/Uploader( 1366): No account for auth token provided
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1366): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1366): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1366): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1366): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1366): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1366): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1366): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1366): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1366): No account for auth token provided
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1366): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1366): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1366): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1366): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1366): No account for auth token provided
,W/Uploader( 1366): No account for auth token provided
,W/Uploader( 1366): No account for auth token provided
,W/Uploader( 1366): No account for auth token provided
,W/Uploader( 1366): No account for auth token provided
,W/Uploader( 1366): No account for auth token provided
,W/Uploader( 1366): No account for auth token provided
,W/Uploader( 1366):  no longer exists, so no auth token.
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1366): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1366): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1366): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1366): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1366): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1366): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1366): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1366): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1366): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1366): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2167): Disconnected process message: 10, size: 0
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3292): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at jdm.a(PG:82)
E/HttpOperation( 3292): 	at jcs.o(PG:406)
E/HttpOperation( 3292): 	at jcn.a(PG:1379)
E/HttpOperation( 3292): 	at jcs.i(PG:143)
E/HttpOperation( 3292): 	at blb.a(PG:3937)
E/HttpOperation( 3292): 	at czp.a(PG:18188)
E/HttpOperation( 3292): 	at czp.a(PG:9081)
E/HttpOperation( 3292): 	at czq.run(PG:1686)
E/HttpOperation( 3292): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3292): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3292): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3292): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3292): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3292): 	at jdj.a(PG:4091)
E/HttpOperation( 3292): 	at jdj.a(PG:1125)
E/HttpOperation( 3292): 	at jdm.a(PG:77)
E/HttpOperation( 3292): 	... 12 more
E/HttpOperation( 3292): Caused by: faj: BadAuthentication
E/HttpOperation( 3292): 	at fal.a(PG:38)
E/HttpOperation( 3292): 	at jdj.a(PG:4089)
E/HttpOperation( 3292): 	... 14 more
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3292): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3292): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3292): 	at jdm.a(PG:82)
E/HttpOperation( 3292): 	at jcs.o(PG:406)
E/HttpOperation( 3292): 	at jcn.a(PG:1379)
E/HttpOperation( 3292): 	at jcs.i(PG:143)
E/HttpOperation( 3292): 	at hec.a(PG:42)
E/HttpOperation( 3292): 	at hee.a(PG:102)
E/HttpOperation( 3292): 	at czr.a(PG:65)
E/HttpOperation( 3292): 	at kka.a(PG:108)
E/HttpOperation( 3292): 	at czp.a(PG:19176)
E/HttpOperation( 3292): 	at czp.a(PG:9081)
E/HttpOperation( 3292): 	at czq.run(PG:1686)
E/HttpOperation( 3292): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3292): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3292): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3292): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3292): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3292): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3292): 	at jdj.a(PG:4091)
E/HttpOperation( 3292): 	at jdj.a(PG:1125)
E/HttpOperation( 3292): 	at jdm.a(PG:77)
E/HttpOperation( 3292): 	... 15 more
E/HttpOperation( 3292): Caused by: faj: BadAuthentication
E/HttpOperation( 3292): 	at fal.a(PG:38)
E/HttpOperation( 3292): 	at jdj.a(PG:4089)
E/HttpOperation( 3292): 	... 17 more
,E/ExperimentLoader( 3292): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3292): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3292): 	at jdm.a(PG:82)
E/ExperimentLoader( 3292): 	,at jcs.o(PG:406)
E/ExperimentLoader( 3292): 	at jcn.a(PG:1379)
,E/ExperimentLoader( 3292): 	at jcs.i(PG:143)
,E/ExperimentLoader( 3292): 	at hec.a(PG:42)
E/ExperimentLoader( 3292): 	,at hee.a(PG:102)
E/ExperimentLoader( 3292): 	at czr.a(PG:65)
E/ExperimentLoader( 3292): 	at kka.a(PG:108)
E/ExperimentLoader( 3292): 	at czp.a(PG:19176)
,E/ExperimentLoader( 3292): 	at czp.a(PG:9081)
E/ExperimentLoader( 3292): 	at czq.run(PG:1686)
E/ExperimentLoader( 3292): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3292): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/ExperimentLoader( 3292): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3292): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3292): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3292): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3292): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3292): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3292): 	at jdm.a(PG:77)
E/ExperimentLoader( 3292): 	... 15 more
,E/ExperimentLoader( 3292): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3292): 	at fal.a(PG:38)
E/ExperimentLoader( 3292): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3292): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 197895, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3163): [316] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3163): [316] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3163): [316] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3163): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3163): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3163): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3163): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3163): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3163): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3163): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3163): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3163): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3163): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1239): run()
I/Keyboard.Facilitator( 1239): flushDynamicLanguageModels()
,I/ConfigService( 1366): onCreate
,I/art     (  823): Explicit concurrent mark sweep GC freed 38280(1690KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 1.500ms total 82.818ms
,I/BooksSync( 4037): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4078): Connecting to GoogleApiClient
,I/BooksConfig( 4037): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4078): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4078): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4078): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4078): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4037): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4037): Soft error
E/BooksSync( 4037): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4037): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4037): Sync error
E/BooksSync( 4037): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4037): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4037): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 202600, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4078): IOException
E/KeepSync( 4078): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4078): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4078): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4078): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4078): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4078): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4078): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4078): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4078): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4078): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4078): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4078): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4078): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4078): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4078): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4078): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4078): 	... 10 more
,W/KeepSync( 4078): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 202454, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1366): onDestroy
,D/HeadsetStateMachine( 2167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2167): Disconnected process message: 10, size: 0
,I/jxcore-log( 3835): --= Surplus to requirements =--
I/jxcore-log( 3835): 
I/jxcore-log( 3835): ****TEST TOOK:  ms ****
I/jxcore-log( 3835): 
,I/jxcore-log( 3835): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3835): 
,D/AndroidRuntime( 4201): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4201): CheckJNI is OFF
,D/AndroidRuntime( 4201): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  823): Killing 3835:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest,
,W/PackageSettings(  823): Skipping PackageSetting{14ac2661 com.example.hello/10273} due to missing metadata
,E/libprocessgroup(  823): failed to kill 1 processes for processgroup 3835
,W/ActivityManager(  823): Force removing ActivityRecord{3b70e58e u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
E/JavaBinder(  823): !!! FAILED BINDER TRANSACTION !!!
,D/WifiService(  823): Client connection lost with reason: 4
,W/InputDispatcher(  823): channel '183579ab com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  823): channel '183579ab com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  823): Attempted to unregister already unregistered input channel '183579ab com.test.thalitest/com.test.thalitest.MainActivity (server)'
,W/WindowManager(  823): Failed looking up window
W/WindowManager(  823): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@6d39ffa does not exist
W/WindowManager(  823): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
W/WindowManager(  823): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
W/WindowManager(  823): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1142)
W/WindowManager(  823): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
I/WindowState(  823): WIN DEATH: null
,V/ActivityManager(  823): Display changed displayId=0
,I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,I/Keyboard.Facilitator( 1239): resetDictionaries() : en_US
,I/InputReader(  823): Reconfiguring input devices.  changes=0x00000010
,D/BuaReceiver( 3467): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/Keyboard.Facilitator.DecoderInitializer( 1239): run()
,I/Decoder ( 1239): createOrResetDecoder
,D/TaskPersister(  823): removeObsoleteFile: deleting file=28_task.xml
,W/InputMethodManagerService(  823): Got RemoteException sending setActive(false) notification to pid 3835 uid 10265
,I/Keyboard.Facilitator( 1239): onFinishInput()
,I/art     ( 1067): Explicit concurrent mark sweep GC freed 57014(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 5.552ms total 68.867ms
,I/art     ( 1515): Explicit concurrent mark sweep GC freed 2536(183KB) AllocSpace objects, 1(25KB) LOS objects, 36% free, 27MB/43MB, paused 2.370ms total 70.868ms
,I/art     (  823): Explicit concurrent mark sweep GC freed 18518(1137KB) AllocSpace objects, 9(615KB) LOS objects, 31% free, 34MB/50MB, paused 1.679ms total 91.555ms
,I/art     (  823): WaitForGcToComplete blocked for 37.782ms for cause Explicit
,I/ActivityManager(  823): Start proc 4217:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 9.284ms
,I/art     ( 1337): Explicit concurrent mark sweep GC freed 5705(420KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.032ms total 28.054ms
,I/ConfigService( 1366): onCreate
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 334us total 18.340ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 253us total 14.095ms
,I/art     ( 1366): Explicit concurrent mark sweep GC freed 66950(3MB) AllocSpace objects, 7(698KB) LOS objects, 36% free, 27MB/43MB, paused 912us total 28.405ms
,W/LocationOracleImpl( 1515): Best location was null
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1239): run()
,I/HotwordRecognitionRnr( 1515): Starting hotword detection.
I/MicrophoneInputStream( 1515): mic_starting com.google.android.apps.gsa.speech.audio.u@f696cd1
,I/AudioFlinger(  358): AudioFlinger's thread 0xb4079000 ready to run
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1515): mic_started com.google.android.apps.gsa.speech.audio.u@f696cd1
,D/JobSchedulerService(  823): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  823): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
I/Keyboard.Facilitator.MainLanguageModelLoader( 1239): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1239): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1239): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1239): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1239): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1239): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1239): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1239): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1239): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1239): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1239): run()
I/StatsUtilsManager( 1239): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1239): shouldRecordStats() = Too Soon
,D/VoicemailCleanupService( 4217): Cleaning up data for package: com.test.thalitest
,I/art     (  823): Explicit concurrent mark sweep GC freed 5499(244KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 1.524ms total 154.459ms
,I/ActivityManager(  823): Start proc 4253:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@81ab1e9}
,I/HotwordWorker( 1515): onReady
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
,I/ActivityManager(  823): Start proc 4272:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/ContactLocale( 4217): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659471123
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,D/Launcher.Workspace( 1337): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1337): 11683562 - stripEmptyScreens()
,W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,I/art     ( 4201): System.exit called, status: 0
I/AndroidRuntime( 4201): VM exiting with result code 0.
,E/NetworkScheduler.SchedulerReceiver( 1366): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1366): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,V/GoogleAuthProtoRequest( 3163): [317] a.<init>: mAccountName set to: thalitester@gmail.com
,D/PackageBroadcastService( 1778): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1778): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1778): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1778): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1778): Removing dialog suppression flag for package com.test.thalitest
,I/UpdateIcingCorporaServi( 1515): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1337): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1692af24 new=com.google.android.velvet.VelvetApplication@1692af24
,D/GOOGLEHELP_CompatibleDatabase( 1778): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1778): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1778): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1778): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1778): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1778): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1778): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1778): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1778): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,I/ActivityManager(  823): Start proc 4303:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,D/GOOGLEHELP_CompatibleDatabase( 1778): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1778): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1778): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1778): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  823): Start proc 4321:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1778): Using Auth Proxy for data requests.
,W/ResourcesManager( 4321): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4321): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/BaseAppContext( 1778): Using Auth Proxy for data requests.
,I/ConfigFetchService( 1778): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/MultiDex( 4321): VM with version 2.1.0 has multidex support
I/MultiDex( 4321): install
I/MultiDex( 4321): VM has multidex support, MultiDex support library is disabled.
,I/UpdateIcingCorporaServi( 1515): UpdateCorporaTask done [took 108 ms] updated apps [took 108 ms] 
,W/ExperimentUpdateService( 3163): [317] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3163): [317] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3163): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3163): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3163): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3163): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3163): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3163): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3163): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3163): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3163): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3163): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  823): Killing 3640:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ConfigFetchService( 1778): service connected
,I/PeopleContactsSync( 1778): CP2 sync disabled
V/JNIHelp ( 4321): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4321): Installed default security provider GmsCore_OpenSSL
,I/Icing   ( 1778): doRemovePackageData com.test.thalitest
,W/NativeLibraryUtils( 4321): Failed to open lock file
W/NativeLibraryUtils( 4321): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4321): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4321): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4321): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4321): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4321): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4321): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4321): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4321): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4321): 	... 3 more
,I/ActivityManager(  823): Killing 2458:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/GAv4    ( 4303): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4303):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4303):   adb logcat -s GAv4
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0

```
