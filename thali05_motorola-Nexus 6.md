#### Test 58135655e9e7eb8_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/CheckinService( 1793): Done disabling old GoogleServicesFramework version
I/ConfigService( 1262): onDestroy
,D/AndroidRuntime( 3772): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3772): CheckJNI is OFF
D/AndroidRuntime( 3772): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{14947adf token=Token{4fdd57e ActivityRecord{23a58b39 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3772): Shutting down VM
V/WindowManager(  821): Adding window Window{32d99618 u0 Starting com.test.thalitest} at 2 of 7 (after Window{2cc2ea5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1518): Closing mic
I/MicrophoneInputStream( 1518): mic_close com.google.android.apps.gsa.speech.audio.u@b5c565b
I/ActivityManager(  821): Start proc 3786:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1518): Hotword detection finished
I/HotwordRecognitionRnr( 1518): Stopping hotword detection.
I/ActivityManager(  821): Killing 3348:com.google.android.keep/u0a79 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659614483
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/WebViewFactory( 3786): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3786): Time to load native libraries: 4 ms (timestamps 7524-7528)
I/LibraryLoader( 3786): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3786): Binding Chromium to main looper Looper (main, tid 1) {2a908fd7}
,I/LibraryLoader( 3786): Expected native library version number "",actual native library version number ""
I/chromium( 3786): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3786): Initializing chromium process, singleProcess=true
W/art     ( 3786): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3786): ApplicationContext is null in ApplicationStatus
,W/chromium( 3786): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3786): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3786): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3786): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b882b3a:true
,W/art     ( 3786): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3786): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3786): CordovaWebView is running on device made by: motorola
,W/art     ( 3786): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3786): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3786): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3786): Validating map...,
,V/WindowManager(  821): Adding window Window{4e1d6ea u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{32d99618 u0 Starting com.test.thalitest})
,W/chromium( 3786): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3786): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3786): Enabling debug mode 0
,I/GAV2    ( 3645): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +637ms
,I/Keyboard.Facilitator( 1244): onFinishInput()
,W/BindingManager( 3786): Cannot call determinedVisibility() - never saw a connection for the pid: 3786
,D/JsMessageQueue( 3786): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  821): Killing 3372:com.qualcomm.timeservice/1000 (adj 15): empty #17
,D/jxcore_app_log( 3786): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580585600
,I/chromium( 3786): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  821): Killing 3393:com.google.android.deskclock/u0a44 (adj 15): empty #17
,W/jxcore-log( 3786): Initializing JXcore engine
W/jxcore-log( 3786): JXcore engine is ready
,W/Thread-418( 3844): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12939]" dev="sockfs" ino=12939 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-418( 3844): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-418( 3844): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9548]" dev="sockfs" ino=9548 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-418( 3844): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23620]" dev="sockfs" ino=23620 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3786): Starting JXcore engine
,W/jxcore-log( 3786): Platform android
W/jxcore-log( 3786): 
W/jxcore-log( 3786): Process ARCH arm
W/jxcore-log( 3786): 
,I/jxcore-log( 3786): JXcore Cordova bridge is ready!
I/jxcore-log( 3786): 
W/jxcore-log( 3786): JXcore engine is started
,I/jxcore-log( 3786): Toggling radios to true
I/jxcore-log( 3786): 
,D/BluetoothAdapter( 3786): enable(): BT is already enabled..!
,D/WifiService(  821): New client listening to asynchronous messages
,D/WifiService(  821): setWifiEnabled: true pid=3786, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3786): Radios toggled
I/jxcore-log( 3786): 
I/jxcore-log( 3786): My device name is: motorola-Nexus 6
I/jxcore-log( 3786): 
,I/wpa_supplicant( 1141): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1262): Read error: ssl=0xb4888800: I/O error during system call, Connection timed out,
,V/NativeCrypto( 1262): SSL shutdown failed: ssl=0xb4888800: I/O error during system call, Broken pipe,
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011,
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  821): Start Disconnecting Watchdog 1
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1074): CM callback handler got msg 524292
D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
,D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  821): MasterInitialState.processMessage what=3
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/NetworkMonitor( 3126): type=WIFI subType= reason=null isConnected=false
,D/Tethering(  821): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3126): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1336): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1336): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/WifiConfigStore(  821): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): will read network variables netId=0
,I/ActivityManager(  821): Start proc 3852:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,E/GpsLocationProvider(  821): No APN found to select.
,D/PhoneInterfaceManager( 1336): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1336): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 3852): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3852): simOperator:  IMSI: null
D/SprintDMReceiver( 3852): Not Sprint UICC, don't do anything.
,I/ActivityManager(  821): Killing 3459:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/SystemUpdateService( 1793): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1793): onCreate
,D/SystemUpdateService( 1793): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1793): active receiver: enabled
,I/SystemUpdateService( 1793): showing system update notification
,I/iu.Environment( 1793): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1793): num queued entries: 0
,I/iu.UploadsManager( 1793): num updated entries: 0
,I/iu.SyncManager( 1793): NEXT; no task
,I/ValidateNoPeople(  821): skipping global notification
,D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1793): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/Babel   ( 2813): connection state changed from CONNECTED to DISCONNECTED
,V/SystemUpdateService( 1793): retry (wakeup: false) in 3599951 ms
,I/ActivityManager(  821): Start proc 3872:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1793): onDestroy
,I/GAv4    ( 3872): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3872):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3872):   adb logcat -s GAv4
,W/GAv4    ( 3872): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3872): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3872): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3872): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3872): Time to load native libraries: 1 ms (timestamps 1068-1069)
I/LibraryLoader( 3872): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3872): Binding Chromium to main looper Looper (main, tid 1) {1e7ef4a}
,I/LibraryLoader( 3872): Expected native library version number "",actual native library version number ""
,I/chromium( 3872): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3872): Initializing chromium process, singleProcess=true
,W/art     ( 3872): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3872): ApplicationContext is null in ApplicationStatus
,W/chromium( 3872): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3872): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3872): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3872): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3872): Requires BLUETOOTH permission
,I/NSApplication( 3872): Starting up...
,I/ActivityManager(  821): Start proc 3928:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  821): Killing 3481:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3529:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,V/MusicLeanback( 3126): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3852): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3852): simOperator:  IMSI: null
D/SprintDMReceiver( 3852): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1793): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) },
,D/SystemUpdateService( 1793): onCreate
,D/SystemUpdateService( 1793): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1793): active receiver: enabled
,I/SystemUpdateService( 1793): showing system update notification
,D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
I/Kids    ( 1793): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,V/SystemUpdateService( 1793): retry (wakeup: false) in 3599955 ms
,D/SystemUpdateService( 1793): onDestroy
,I/wpa_supplicant( 1141): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 1141): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1141): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP],
I/wpa_supplicant( 1141): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} },
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 2
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 182
E/WifiStateMachine(  821):  RSSI mgmt: -51
E/WifiStateMachine(  821):  BE :  rx=171 tx=147 lost=0 retries=1
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 10473 tx_time=152 rx_time=360 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 3959): version 5.5.6 starting
,I/dhcpcd  ( 3959): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3959): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3959): wlan0: leased 192.168.1.122 for 86400 seconds,
,I/ActivityManager(  821): Killing 1435:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3670:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/jxcore-log( 3786): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3786): 
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 101
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  821): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1074): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3126): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3126): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1336): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1336): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3852): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMHelper( 3852): simOperator:  IMSI: null
D/SprintDMReceiver( 3852): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1793): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1793): onCreate
,D/SystemUpdateService( 1793): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1793): active receiver: enabled
,I/SystemUpdateService( 1793): showing system update notification
,I/iu.Environment( 1793): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1793): num queued entries: 0
,I/iu.UploadsManager( 1793): num updated entries: 0
I/iu.SyncManager( 1793): NEXT; no task
,D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,I/Kids    ( 1793): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,V/SystemUpdateService( 1793): retry (wakeup: false) in 3599979 ms
,D/SystemUpdateService( 1793): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 12:37:26 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455021446137], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455021446115]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1074): CM callback handler got msg 524290
,V/Herrevad( 1793): NQAS connected
,I/Babel   ( 2813): connection state changed from DISCONNECTED to CONNECTED
,I/art     (  821): Explicit concurrent mark sweep GC freed 49143(2MB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 2.639ms total 66.108ms
,D/GCM     ( 1262): Connected
,D/GCM     ( 1262): Message class com.google.f.a.a.p
,I/jxcore-log( 3786): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3786): 
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{be1d4cb u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/jxcore-log( 3786): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3786): 
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3565): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3565): [1] 5.onFinished: Scheduling replication attempt 1.
,I/jxcore-log( 3786): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3786): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.52 rxSuccessRate=9.77 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3786): Test app app.js loaded,
I/jxcore-log( 3786): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51cc9fd added. We now have 1 listener(s)
,I/chromium( 3786): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3786): BLE advertisement is supported
I/jxcore-log( 3786): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.26 rxSuccessRate=5.88 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,I/art     ( 1262): Explicit concurrent mark sweep GC freed 32288(1795KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.252ms total 39.091ms
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.52 rxSuccessRate=5.12 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3565): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3565): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  821): Start proc 4014:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at blb.a(PG:3937)
E/HttpOperation( 3305): 	at czp.a(PG:18188)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 12 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 14 more
,V/KeepSync( 4014): Connecting to GoogleApiClient
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at hec.a(PG:42)
E/HttpOperation( 3305): 	at hee.a(PG:102)
E/HttpOperation( 3305): 	at czr.a(PG:65)
E/HttpOperation( 3305): 	at kka.a(PG:108)
E/HttpOperation( 3305): 	at czp.a(PG:19176)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 15 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 17 more
,E/ExperimentLoader( 3305): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): 	at jdm.a(PG:82)
E/ExperimentLoader( 3305): 	at jcs.o(PG:406)
E/ExperimentLoader( 3305): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3305): 	at jcs.i(PG:143)
E/ExperimentLoader( 3305): 	at hec.a(PG:42),
E/ExperimentLoader( 3305): 	at hee.a(PG:102)
E/ExperimentLoader( 3305): 	at czr.a(PG:65)
E/ExperimentLoader( 3305): 	at kka.a(PG:108)
E/ExperimentLoader( 3305): 	at czp.a(PG:19176)
E/ExperimentLoader( 3305): 	at czp.a(PG:9081)
E/ExperimentLoader( 3305): 	at czq.run(PG:1686)
E/ExperimentLoader( 3305): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3305): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3305): 	at jdj.a(PG:1125)
,E/ExperimentLoader( 3305): 	at jdm.a(PG:77)
E/ExperimentLoader( 3305): 	... 15 more
E/ExperimentLoader( 3305): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3305): 	at fal.a(PG:38)
E/ExperimentLoader( 3305): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3305): 	... 17 more
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1793): Handling authorization failure
E/ClientConnectionOperation( 1793): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1793): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1793): 	... 7 more
,V/KeepSync( 4014): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 77919, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Start proc 4045:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4014): IOException
E/KeepSync( 4014): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4014): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4014): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4014): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4014): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4014): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4014): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4014): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4014): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4014): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4014): 	... 10 more
,W/KeepSync( 4014): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 77369, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,W/GAV2    ( 4045): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4045): Created application version: 3.6.8 (30608)
,I/art     ( 1262): Explicit concurrent mark sweep GC freed 17501(990KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 26MB/42MB, paused 1.694ms total 44.391ms,
,I/BooksSync( 4045): Starting books sync for 61035162, extras: ade
,I/art     (  821): Explicit concurrent mark sweep GC freed 36938(1713KB) AllocSpace objects, 7(112KB) LOS objects, 32% free, 33MB/49MB, paused 1.810ms total 73.667ms
,I/BooksConfig( 4045): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4045): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 4045): Soft error,
E/BooksSync( 4045): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4045): Sync error
E/BooksSync( 4045): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4045): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78396, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Killing 3645:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3609:com.google.android.gms:car/u0a11 (adj 15): empty #18
,I/GAV2    ( 4045): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.35 rxSuccessRate=1.87 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3565): [375] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3565): [375] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3565): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3565): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1244): run()
I/Keyboard.Facilitator( 1244): flushDynamicLanguageModels()
,I/ConfigService( 1262): onCreate
,I/ConfigService( 1262): onDestroy
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.58 rxSuccessRate=12.66 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3565): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3565): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.83 rxSuccessRate=5.43 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (237 us)
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  821): Display changed displayId=0
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,I/kickstart(  876): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  876): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  876): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  876): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  821): Excessive delay in setPowerMode(): 259ms
,I/DreamManagerService(  821): Entering dreamland.
,I/PowerManagerService(  821): Dozing...
I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 12
,E/native  (  821): do suspend false
,I/Keyboard.Facilitator( 1244): onFinishInput()
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  821): cancelDelayedScan -> 14
E/native  (  821): do suspend true
,I/art     ( 1837): Explicit concurrent mark sweep GC freed 15769(948KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.411ms total 43.176ms
,E/DataBuffer( 1837): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3fb51622)
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3565): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3565): [1] 5.onFinished: Scheduling replication attempt 5.
,I/kickstart(  876): STATUS: Received file 'm9kefs2'
I/kickstart(  876): STATUS: 950272 bytes transferred in 0.989766 seconds
I/kickstart(  876): STATUS: Successfully downloaded files from target 
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  876): STATUS: Sahara protocol completed
,V/KeepSync( 4014): Connecting to GoogleApiClient
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at blb.a(PG:3937)
E/HttpOperation( 3305): 	at czp.a(PG:18188)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 12 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 14 more
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1793): Handling authorization failure
E/ClientConnectionOperation( 1793): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1793): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1793): 	... 7 more
,V/KeepSync( 4014): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
E/HttpOperation( 3305): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at hec.a(PG:42)
E/HttpOperation( 3305): 	at hee.a(PG:102)
E/HttpOperation( 3305): 	at czr.a(PG:65)
E/HttpOperation( 3305): 	at kka.a(PG:108)
E/HttpOperation( 3305): 	at czp.a(PG:19176)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 15 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 17 more
E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
E/ExperimentLoader( 3305): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): 	at jdm.a(PG:82)
E/ExperimentLoader( 3305): 	at jcs.o(PG:406)
E/ExperimentLoader( 3305): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3305): 	at jcs.i(PG:143)
E/ExperimentLoader( 3305): 	at hec.a(PG:42)
E/ExperimentLoader( 3305): 	at hee.a(PG:102)
E/ExperimentLoader( 3305): 	at czr.a(PG:65)
E/ExperimentLoader( 3305): 	at kka.a(PG:108)
E/ExperimentLoader( 3305): 	at czp.a(PG:19176)
E/ExperimentLoader( 3305): 	at czp.a(PG:9081)
E/ExperimentLoader( 3305): 	at czq.run(PG:1686)
E/ExperimentLoader( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3305): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3305): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3305): 	at jdm.a(PG:77)
E/ExperimentLoader( 3305): 	... 15 more
E/ExperimentLoader( 3305): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3305): 	at fal.a(PG:38)
E/ExperimentLoader( 3305): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3305): 	... 17 more
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 135993, reason: Periodic, SyncResult: stats [ numIoExceptions: 1],
,I/BooksSync( 4045): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4045): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  821): Explicit concurrent mark sweep GC freed 48531(2MB) AllocSpace objects, 16(350KB) LOS objects, 31% free, 34MB/50MB, paused 1.550ms total 57.445ms
,E/KeepSync( 4014): IOException
E/KeepSync( 4014): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4014): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4014): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4014): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4014): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4014): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4014): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4014): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4014): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4014): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4014): 	... 10 more
W/KeepSync( 4014): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 135665, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4045): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4045): Soft error
E/BooksSync( 4045): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4045): Sync error
E/BooksSync( 4045): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4045): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 137150, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3170): [311] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1262): Vacuum at: now=1455021556501 tag=VacuumService
,I/art     ( 1262): Explicit concurrent mark sweep GC freed 37279(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 2.460ms total 38.132ms
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3170): [311] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3170): [311] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3170): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3170): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3170): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3170): 	at com.a.a.k.run(SourceFile:110)
,D/Finsky  ( 3565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3565): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3565): [1] 5.onFinished: Giving up after 6 failures.
,I/GoogleURLConnFactory( 1262): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1262): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1262): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1262): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1262): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1262): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1262): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1262): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1262): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1262): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1262): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1262): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1262): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262): No account for auth token provided
,W/Uploader( 1262):  no longer exists, so no auth token.
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1262): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1262): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1262): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1262): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1262): No account for auth token provided
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,E/Uploader( 1262): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1262): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1262): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1262): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1262): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1262): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1262): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1262): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1262): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1262): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GoogleAuthProtoRequest( 3170): [312] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3170): [312] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3170): [312] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3170): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3170): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3170): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3170): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1244): run()
I/Keyboard.Facilitator( 1244): flushDynamicLanguageModels()
,I/ConfigService( 1262): onCreate
,V/KeepSync( 4014): Connecting to GoogleApiClient
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1793): Handling authorization failure
E/ClientConnectionOperation( 1793): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1793): 	,at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1793): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1793): 	,at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1793): 	,at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1793): 	... 7 more
,V/KeepSync( 4014): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4014): IOException
E/KeepSync( 4014): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4014): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4014): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4014): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4014): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4014): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4014): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4014): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4014): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4014): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4014): 	... 10 more
W/KeepSync( 4014): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 226009, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  821): Explicit concurrent mark sweep GC freed 36930(1613KB) AllocSpace objects, 3(142KB) LOS objects, 31% free, 34MB/50MB, paused 1.736ms total 84.600ms
,I/ConfigService( 1262): onDestroy
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,I/BooksSync( 4045): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4045): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at blb.a(PG:3937)
E/HttpOperation( 3305): 	at czp.a(PG:18188)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 12 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 14 more
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at hec.a(PG:42)
E/HttpOperation( 3305): 	at hee.a(PG:102)
E/HttpOperation( 3305): 	at czr.a(PG:65)
E/HttpOperation( 3305): 	at kka.a(PG:108)
E/HttpOperation( 3305): 	at czp.a(PG:19176)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 15 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 17 more
,E/ExperimentLoader( 3305): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3305): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): 	at jdm.a(PG:82)
E/ExperimentLoader( 3305): 	at jcs.o(PG:406),
E/ExperimentLoader( 3305): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3305): 	at jcs.i(PG:143)
E/ExperimentLoader( 3305): 	at hec.a(PG:42)
E/ExperimentLoader( 3305): 	at hee.a(PG:102)
E/ExperimentLoader( 3305): 	at czr.a(PG:65)
E/ExperimentLoader( 3305): 	at kka.a(PG:108)
E/ExperimentLoader( 3305): 	at czp.a(PG:19176)
E/ExperimentLoader( 3305): 	at czp.a(PG:9081)
E/ExperimentLoader( 3305): 	at czq.run(PG:1686)
E/ExperimentLoader( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3305): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3305): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3305): 	at jdm.a(PG:77)
E/ExperimentLoader( 3305): 	... 15 more
E/ExperimentLoader( 3305): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3305): 	,at fal.a(PG:38)
E/ExperimentLoader( 3305): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3305): 	... 17 more
E/BooksAccountManager( 4045): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4045): Soft error
E/BooksSync( 4045): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4045): Sync error
E/BooksSync( 4045): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4045): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 227340, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 226786, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3786): TAP version 13
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # multiplex can send data
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 1 String should be length:200
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # enqueue and run in order
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 2 firstPromise setTimeout
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 3 firstPromise result
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 4 firstPromise testValue
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 5 secondPromise setTimeout
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 6 secondPromise result
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 7 secondPromise testValue
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 8 thirdPromise in promise
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 9 thirdPromise result
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 10 thirdPromise testValue
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # basic
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 11 sane
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # another
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 12 sane
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 13 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 14 null
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 15 (unnamed assert)
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 16 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 17 should not throw,
I/jxcore-log( 3786): 
I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 18 (unnamed assert)
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 19 (unnamed assert)
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 20 should not throw
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 21 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 22 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 23 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # failed to get mobile documents path
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 24 should be equal
,I/jxcore-log( 3786): 
I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #init should register the peerAvailabilityChanged event,
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown,
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 25 should be equal,
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 26 should be equal,
I/jxcore-log( 3786): 
I/jxcore-log( 3786): ok 27 should be equal
I/jxcore-log( 3786): 
I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #init should register the networkChanged event
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 28 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #startBroadcasting should throw on null device name
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 29 should throw
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 30 should throw
I/jxcore-log( 3786): ,
I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 31 should throw
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 32 should throw
I/jxcore-log( 3786): ,
I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #startBroadcasting should throw on negative port
I/jxcore-log( 3786): ,
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 33 should throw
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #startBroadcasting should throw on too large port
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 34 should throw
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 35 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 36 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 37 should be equal
I/jxcore-log( 3786): 
I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 38 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 39 should be equal
I/jxcore-log( 3786): 
I/jxcore-log( 3786): ok 40 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 41 should be equal
I/jxcore-log( 3786): ,
I/jxcore-log( 3786): ok 42 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 43 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 44 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 45 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 46 should be equal
I/jxcore-log( 3786): 
I/jxcore-log( 3786): ok 47 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 48 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 49 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 50 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 51 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 52 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 53 should be equal
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #start should fail if called twice in a row
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 54 specific error should be received
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 55 specific error should be returned
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # should be able to call #stopListeningForAdvertisements many times
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 56 error should be null
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 57 error should be null
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # should be able to call #startListeningForAdvertisements many times
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 58 error should be null
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 59 error should be null
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # should be able to call #startUpdateAdvertisingAndListening many times
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 60 error should be null
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 61 error should be null
,I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): ok 62 specific error should be returned
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # setup
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3786): 
,I/jxcore-log( 3786): # teardown
I/jxcore-log( 3786): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Automate Bluetooth MAC address resolution: true, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297b46f2 added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): setDiscoveryMode: BLE_AND_WIFI -> WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455021665588.3786
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3786): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665588.3786","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): start: OK
I/io.jxcore.node.ConnectionHelper( 3786): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3786): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455021665588.3786, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3786): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3786): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3786): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665588.3786","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665588.3786","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3786): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665588.3786","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3786): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onIsWifiPeerDiscoveryStartedChanged: true,
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: OK
I/io.jxcore.node.ConnectionHelper( 3786): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455021665588.3786, mode: WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3786): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 3786): 
,I/io.jxcore.node.ConnectionHelper( 3786): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3786): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3786): Exiting thread
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): onServerStopped
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3786): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3786): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3786): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: STARTED
I/wpa_supplicant( 1141): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3786): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3786): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3786): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3786): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3786): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3786): Service requests cleared successfully
I/jxcore-log( 3786): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 3786): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20308e9f added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455021665654.3786
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): initialize: My bluetooth address is F8:CF:C5:D9:E5:61,
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3786): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665654.3786","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): start: OK
I/io.jxcore.node.ConnectionHelper( 3786): start: Using peer discovery mode: BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3786): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3786): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3786): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455021665654.3786, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3786): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3786): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3786): createAdvertiseData: From: 1455021665654.3786 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2174): registerClient() - UUID=1f387229-4b69-4b6b-901b-fb27c494ad97
,D/BtGatt.GattService( 2174): onClientRegistered() - UUID=1f387229-4b69-4b6b-901b-fb27c494ad97, clientIf=5
,D/BluetoothLeScanner( 3786): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2174): start scan with filters
,D/BtGatt.ScanManager( 2174): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3786): setState: State changed from NOT_STARTED to STARTING
,D/BluetoothAdapterService( 2174): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aaf0c4
,D/BtGatt.GattService( 2174): registerClient() - UUID=387e43fb-5769-4b98-9223-28c8c809c832
,D/BtGatt.GattService( 2174): onClientRegistered() - UUID=387e43fb-5769-4b98-9223-28c8c809c832, clientIf=6
D/BluetoothLeAdvertiser( 3786): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2174): message : 0
,D/BtGatt.GattService( 2174): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2174): callback done for clientIf - 5 status - 0
,D/BtGatt.AdvertiseManager( 2174): starting multi advertising
,D/BtGatt.GattService( 2174): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2174): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2174): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2174): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.GattService( 2174): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2174): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3786): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665654.3786","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665654.3786","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3786): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665654.3786","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onIsWifiPeerDiscoveryStartedChanged: true
,I/wpa_supplicant( 1141): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: OK
I/io.jxcore.node.ConnectionHelper( 3786): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455021665654.3786, mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3786): createAdvertiseData: From: 1455021665654.3786 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/jxcore-log( 3786): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 3786): 
,D/BtGatt.AdvertiseManager( 2174): message : 1
D/BtGatt.AdvertiseManager( 2174): stop advertise for client 6
I/io.jxcore.node.ConnectionHelper( 3786): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3786): shutdown
,D/BtGatt.GattService( 2174): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2174): Client app is not null!
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3786): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): release: 1 listener(s) left
,D/BtGatt.GattService( 2174): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2174): registerClient() - UUID=b2f9b199-a4dd-4272-a577-85a3dfe47f6a
,D/BtGatt.GattService( 2174): onClientRegistered() - UUID=b2f9b199-a4dd-4272-a577-85a3dfe47f6a, clientIf=6
D/BluetoothLeAdvertiser( 3786): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2174): message : 0
,D/BtGatt.AdvertiseManager( 2174): starting multi advertising
,D/BtGatt.GattService( 2174): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2174): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3786): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3786): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3786): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3786): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): P2P device discovery started successfully
I/wpa_supplicant( 1141): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3786): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): onStartSuccess
D/BtGatt.AdvertiseManager( 2174): message : 1
D/BtGatt.AdvertiseManager( 2174): stop advertise for client 6
,D/BtGatt.GattService( 2174): onAdvertiseInstanceDisabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2174): Client app is not null!
D/BtGatt.GattService( 2174): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onIsBlePeerDiscovererStateChanged: [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): onIsAdvertiserStartedChanged: true
,D/BtGatt.GattService( 2174): stopScan() - queue size =1
,D/BtGatt.GattService( 2174): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3786): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3786): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
,D/BtGatt.GattService( 2174): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2174): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2174): stop scan
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): P2P device discovery stopped successfully
D/BtGatt.ScanManager( 2174): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2174): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/BtGatt.ScanManager( 2174): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3786): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onIsWifiPeerDiscoveryStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3786): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3786): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3786): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3786): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3786): ok 66 Should be able to call stopBroadcasting without error
I/jxcore-log( 3786): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	,Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c8b916 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to WIFI,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455021665801.3786
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3786): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665801.3786","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3786): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): start: OK
I/io.jxcore.node.ConnectionHelper( 3786): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455021665801.3786, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3786): bind: Binding a new listener
W/BluetoothAdapter( 3786): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3786): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3786): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665801.3786","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665801.3786","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3786): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665801.3786","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455021665801.3786, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3786): start: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3786): ok 67 Should be able to call startBroadcasting without error
I/jxcore-log( 3786): 
I/wpa_supplicant( 1141): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: OK
I/io.jxcore.node.ConnectionHelper( 3786): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3786): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1141): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3786): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3786): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3786): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3786): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3786): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3786): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3786): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3786): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3786): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3786): Service requests cleared successfully
,I/jxcore-log( 3786): ok 68 Should be able to call stopBroadcasting without error
I/jxcore-log( 3786): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3786): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	,Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b0f50a2 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3786): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455021665870.3786
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3786): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665870.3786","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): start: OK
I/io.jxcore.node.ConnectionHelper( 3786): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3786): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3786): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455021665870.3786, mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3786): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3786): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3786): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3786): createAdvertiseData: From: 1455021665870.3786 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2174): registerClient() - UUID=617616dd-fe86-411f-9406-21f2da75cf52
,D/BtGatt.GattService( 2174): onClientRegistered() - UUID=617616dd-fe86-411f-9406-21f2da75cf52, clientIf=5,
D/BluetoothLeScanner( 3786): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2174): start scan with filters,
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3786): setState: State changed from NOT_STARTED to STARTING,
,D/BtGatt.ScanManager( 2174): handling starting scan,
,D/BtGatt.GattService( 2174): registerClient() - UUID=f2de45c3-2659-4e8a-80a1-cef33874a401,
,D/BtGatt.GattService( 2174): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
D/BtGatt.ScanManager( 2174): callback done for clientIf - 5 status - 0,
D/BtGatt.GattService( 2174): onClientRegistered() - UUID=f2de45c3-2659-4e8a-80a1-cef33874a401, clientIf=6
,D/BluetoothLeAdvertiser( 3786): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2174): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2174): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2174): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2174): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/BtGatt.AdvertiseManager( 2174): message : 0
,D/BtGatt.AdvertiseManager( 2174): starting multi advertising
,D/BtGatt.GattService( 2174): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2174): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3786): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665870.3786","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665870.3786","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3786): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455021665870.3786","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3786): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): startWifiPeerDiscovery: Wi-Fi Direct OK,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: OK
I/io.jxcore.node.ConnectionHelper( 3786): start: OK,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455021665870.3786, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3786): createAdvertiseData: From: 1455021665870.3786 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/wpa_supplicant( 1141): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3786): ok 69 Should be able to call startBroadcasting without error
,I/jxcore-log( 3786): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/io.jxcore.node.ConnectionHelper( 3786): stop,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3786): shutdown,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3786): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3786): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3786): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3786): setState: NOT_STARTED
D/BtGatt.AdvertiseManager( 2174): message : 1,
D/BtGatt.AdvertiseManager( 2174): stop advertise for client 6
D/BtGatt.GattService( 2174): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2174): Client app is not null!
D/BtGatt.GattService( 2174): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2174): registerClient() - UUID=9b87ce4b-e82a-4674-b1c8-18186ce24db9
,D/BtGatt.GattService( 2174): onClientRegistered() - UUID=9b87ce4b-e82a-4674-b1c8-18186ce24db9, clientIf=6
,D/BluetoothLeAdvertiser( 3786): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2174): message : 0
,D/BtGatt.AdvertiseManager( 2174): starting multi advertising,
,D/BtGatt.GattService( 2174): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2174): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3786): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3786): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3786): setState: State changed from STARTING to RUNNING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3786): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3786): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): stop
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3786): onIsAdvertiserStartedChanged: true
,V/GoogleAuthProtoRequest( 3170): [313] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3170): [313] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3170): [313] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3170): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3170): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3170): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3170): 	at com.a.a.k.run(SourceFile:110)
,I/wpa_supplicant( 1141): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 1141): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3c5d0e02}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,V/KeepSync( 4014): Connecting to GoogleApiClient
,I/art     ( 1262): Explicit concurrent mark sweep GC freed 69318(3MB) AllocSpace objects, 10(931KB) LOS objects, 36% free, 28MB/44MB, paused 1.796ms total 69.468ms
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1793): Handling authorization failure
E/ClientConnectionOperation( 1793): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1793): 	,at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1793): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1793): 	... 7 more
,V/KeepSync( 4014): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4014): IOException
E/KeepSync( 4014): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4014): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4014): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4014): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4014): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4014): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4014): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4014): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4014): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4014): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4014): 	... 10 more
W/KeepSync( 4014): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 348062, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3c5d0e02}
,D/btif_config_util( 2174): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1262): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1262): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1262): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1262): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1262): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1262): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1262): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3565): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 3565): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3565): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3565): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3565): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3565): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3565): 	,at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3565): Ignoring header User-Agent because its value was null.
,I/wpa_supplicant( 1141): P2P-DEVICE-LOST p2p_dev_addr=de:4a:3e:0f:89:ad
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,I/BooksSync( 4045): Starting books sync for 61035162, extras: ade
,I/art     (  821): Explicit concurrent mark sweep GC freed 35275(1612KB) AllocSpace objects, 14(1072KB) LOS objects, 31% free, 34MB/50MB, paused 1.680ms total 64.906ms
,I/BooksConfig( 4045): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at blb.a(PG:3937)
E/HttpOperation( 3305): 	at czp.a(PG:18188)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 12 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 14 more
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at hec.a(PG:42)
E/HttpOperation( 3305): 	at hee.a(PG:102)
E/HttpOperation( 3305): 	at czr.a(PG:65)
E/HttpOperation( 3305): 	at kka.a(PG:108)
E/HttpOperation( 3305): 	at czp.a(PG:19176)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 15 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 17 more
E/BooksAccountManager( 4045): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): Soft error
E/BooksSync( 4045): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4045): Sync error
E/BooksSync( 4045): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/ExperimentLoader( 3305): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): 	at jdm.a(PG:82)
E/ExperimentLoader( 3305): 	at jcs.o(PG:406)
E/ExperimentLoader( 3305): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3305): 	at jcs.i(PG:143)
E/ExperimentLoader( 3305): 	at hec.a(PG:42)
E/ExperimentLoader( 3305): 	at hee.a(PG:102)
E/ExperimentLoader( 3305): 	at czr.a(PG:65)
E/ExperimentLoader( 3305): 	at kka.a(PG:108)
E/ExperimentLoader( 3305): 	at czp.a(PG:19176)
E/ExperimentLoader( 3305): 	at czp.a(PG:9081)
E/ExperimentLoader( 3305): 	at czq.run(PG:1686)
E/ExperimentLoader( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3305): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3305): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3305): 	at jdm.a(PG:77)
E/ExperimentLoader( 3305): 	... 15 more
E/ExperimentLoader( 3305): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3305): 	at fal.a(PG:38)
E/ExperimentLoader( 3305): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3305): 	... 17 more
I/BooksSync( 4045): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 380409, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 379770, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 1141): P2P-FIND-STOPPED 
,V/GoogleAuthProtoRequest( 3170): [314] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3170): [314] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3170): [314] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3170): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3170): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3170): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3170): 	at com.a.a.k.run(SourceFile:110)
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1141): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,I/ActivityManager(  821): Start proc 4224:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4224): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4224):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4224):   adb logcat -s GAv4
,W/GAv4    ( 4224): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4224): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4224): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  821): Killing 2427:com.google.android.calendar/u0a37 (adj 15): empty #17
,V/KeepSync( 4014): Connecting to GoogleApiClient
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1793): Handling authorization failure
E/ClientConnectionOperation( 1793): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1793): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1793): 	... 7 more
,V/KeepSync( 4014): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4014): IOException
E/KeepSync( 4014): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4014): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4014): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4014): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4014): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4014): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4014): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4014): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4014): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4014): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4014): 	... 10 more
W/KeepSync( 4014): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 591665, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at blb.a(PG:3937)
E/HttpOperation( 3305): 	at czp.a(PG:18188)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 12 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 14 more
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [getmobileexperiments] Unexpected exception
,E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
,E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at hec.a(PG:42)
E/HttpOperation( 3305): 	at hee.a(PG:102)
E/HttpOperation( 3305): 	at czr.a(PG:65),
E/HttpOperation( 3305): 	at kka.a(PG:108),
E/HttpOperation( 3305): 	at czp.a(PG:19176)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
,E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	,at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	,at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 15 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 17 more
,E/ExperimentLoader( 3305): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): 	at jdm.a(PG:82)
E/ExperimentLoader( 3305): 	at jcs.o(PG:406)
E/ExperimentLoader( 3305): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3305): ,	at jcs.i(PG:143)
E/ExperimentLoader( 3305): 	at hec.a(PG:42)
E/ExperimentLoader( 3305): 	at hee.a(PG:102)
E/ExperimentLoader( 3305): 	at czr.a(PG:65)
E/ExperimentLoader( 3305): 	at kka.a(PG:108)
E/ExperimentLoader( 3305): ,	at czp.a(PG:19176)
E/ExperimentLoader( 3305): 	at czp.a(PG:9081)
E/ExperimentLoader( 3305): 	at czq.run(PG:1686)
E/ExperimentLoader( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3305): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3305): 	,at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3305): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3305): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3305): 	at jdm.a(PG:77),
E/ExperimentLoader( 3305): 	... 15 more
E/ExperimentLoader( 3305): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3305): 	at fal.a(PG:38)
E/ExperimentLoader( 3305): 	at jdj.a(PG:4089),
E/ExperimentLoader( 3305): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 655253, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,I/BooksSync( 4045): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4045): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 36850(1691KB) AllocSpace objects, 12(474KB) LOS objects, 31% free, 34MB/50MB, paused 1.491ms total 59.284ms
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4045): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4045): Soft error
E/BooksSync( 4045): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4045): Sync error
E/BooksSync( 4045): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4045): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 656632, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1262): Explicit concurrent mark sweep GC freed 54108(2MB) AllocSpace objects, 19(2MB) LOS objects, 36% free, 27MB/43MB, paused 1.500ms total 58.870ms
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/Finsky  ( 3565): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GoogleAuthProtoRequest( 3170): [315] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3565): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/ExperimentUpdateService( 3170): [315] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3170): [315] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3170): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3170): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3170): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3170): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3170): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3170): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 3565): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 3565): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 3565): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,D/Finsky  ( 3565): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3565): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 1837): client connected with version: 7571000
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3565): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3565): [1] 5.onFinished: Scheduling replication attempt 1.
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3565): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3565): [1] 5.onFinished: Scheduling replication attempt 2.
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3565): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3565): [1] 5.onFinished: Scheduling replication attempt 3.
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3565): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3565): [1] 5.onFinished: Scheduling replication attempt 4.
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 29046(1254KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 2.193ms total 90.798ms
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3565): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3565): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3565): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3565): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3565): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/GCM     ( 1262): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,V/KeepSync( 4014): Connecting to GoogleApiClient
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1262): Explicit concurrent mark sweep GC freed 55492(2MB) AllocSpace objects, 13(1434KB) LOS objects, 37% free, 26MB/42MB, paused 1.324ms total 57.667ms
,E/ClientConnectionOperation( 1793): Handling authorization failure
E/ClientConnectionOperation( 1793): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1793): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1793): 	... 7 more
,V/KeepSync( 4014): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4014): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4014): IOException
E/KeepSync( 4014): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4014): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4014): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4014): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4014): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4014): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4014): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4014): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4014): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4014): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4014): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4014): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4014): 	... 10 more
W/KeepSync( 4014): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1078516, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0,
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at blb.a(PG:3937)
E/HttpOperation( 3305): 	at czp.a(PG:18188)
E/HttpOperation( 3305): 	at czp.a(PG:9087)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 12 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 14 more
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at blb.a(PG:3937)
E/HttpOperation( 3305): 	at czp.a(PG:18188)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 12 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 14 more
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at hec.a(PG:42)
E/HttpOperation( 3305): 	at hee.a(PG:102)
E/HttpOperation( 3305): 	at czr.a(PG:65)
E/HttpOperation( 3305): 	at kka.a(PG:108)
E/HttpOperation( 3305): 	at czp.a(PG:19176)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 15 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 17 more
,E/ExperimentLoader( 3305): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): 	at jdm.a(PG:82)
E/ExperimentLoader( 3305): 	,at jcs.o(PG:406)
E/ExperimentLoader( 3305): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3305): 	at jcs.i(PG:143)
E/ExperimentLoader( 3305): 	at hec.a(PG:42)
E/ExperimentLoader( 3305): 	at hee.a(PG:102)
E/ExperimentLoader( 3305): 	at czr.a(PG:65)
E/ExperimentLoader( 3305): 	at kka.a(PG:108)
E/ExperimentLoader( 3305): 	at czp.a(PG:19176)
E/ExperimentLoader( 3305): 	at czp.a(PG:9081)
E/ExperimentLoader( 3305): 	at czq.run(PG:1686)
E/ExperimentLoader( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3305): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3305): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3305): 	at jdm.a(PG:77)
E/ExperimentLoader( 3305): 	... 15 more
E/ExperimentLoader( 3305): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3305): 	at fal.a(PG:38)
,E/ExperimentLoader( 3305): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3305): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 655700, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btm  ( 2174): Request to stop oneshot timer with non empty queue
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,I/BooksSync( 4045): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4045): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at blb.a(PG:3937)
E/HttpOperation( 3305): 	at czp.a(PG:18188)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 12 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 14 more
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3305): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at hec.a(PG:42)
E/HttpOperation( 3305): 	at hee.a(PG:102)
E/HttpOperation( 3305): 	at czr.a(PG:65)
E/HttpOperation( 3305): 	at kka.a(PG:108)
E/HttpOperation( 3305): 	at czp.a(PG:19176)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 15 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 17 more
,E/ExperimentLoader( 3305): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): 	at jdm.a(PG:82)
E/ExperimentLoader( 3305): 	at jcs.o(PG:406)
,E/ExperimentLoader( 3305): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3305): 	at jcs.i(PG:143)
E/ExperimentLoader( 3305): 	at hec.a(PG:42)
E/ExperimentLoader( 3305): 	at hee.a(PG:102)
E/ExperimentLoader( 3305): 	at czr.a(PG:65)
E/ExperimentLoader( 3305): 	at kka.a(PG:108)
E/ExperimentLoader( 3305): 	at czp.a(PG:19176)
E/ExperimentLoader( 3305): 	at czp.a(PG:9081),
E/ExperimentLoader( 3305): 	at czq.run(PG:1686)
E/ExperimentLoader( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ExperimentLoader( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/ExperimentLoader( 3305): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3305): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3305): 	at jdm.a(PG:77)
E/ExperimentLoader( 3305): 	... 15 more
E/ExperimentLoader( 3305): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3305): 	at fal.a(PG:38)
E/ExperimentLoader( 3305): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3305): 	... 17 more
,E/BooksAccountManager( 4045): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4045): Soft error
E/BooksSync( 4045): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4045): Sync error
E/BooksSync( 4045): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4045): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4045): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1182012, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1182576, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,I/art     (  821): Explicit concurrent mark sweep GC freed 45490(2MB) AllocSpace objects, 12(286KB) LOS objects, 31% free, 34MB/50MB, paused 1.652ms total 84.571ms
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2174): Disconnected process message: 10, size: 0
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3305): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at blb.a(PG:3937)
E/HttpOperation( 3305): 	at czp.a(PG:18188)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 12 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 14 more
,I/GLSUser ( 1262): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1262): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1262): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1262): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1262): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3305): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3305): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3305): 	at jdm.a(PG:82)
E/HttpOperation( 3305): 	at jcs.o(PG:406)
E/HttpOperation( 3305): 	at jcn.a(PG:1379)
E/HttpOperation( 3305): 	at jcs.i(PG:143)
E/HttpOperation( 3305): 	at hec.a(PG:42)
E/HttpOperation( 3305): 	at hee.a(PG:102)
E/HttpOperation( 3305): 	at czr.a(PG:65)
E/HttpOperation( 3305): 	at kka.a(PG:108)
E/HttpOperation( 3305): 	at czp.a(PG:19176)
E/HttpOperation( 3305): 	at czp.a(PG:9081)
E/HttpOperation( 3305): 	at czq.run(PG:1686)
E/HttpOperation( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3305): 	at jdj.a(PG:4091)
E/HttpOperation( 3305): 	at jdj.a(PG:1125)
E/HttpOperation( 3305): 	at jdm.a(PG:77)
E/HttpOperation( 3305): 	... 15 more
E/HttpOperation( 3305): Caused by: faj: BadAuthentication
E/HttpOperation( 3305): 	at fal.a(PG:38)
E/HttpOperation( 3305): 	at jdj.a(PG:4089)
E/HttpOperation( 3305): 	... 17 more
,E/ExperimentLoader( 3305): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3305): 	at jdm.a(PG:82)
E/ExperimentLoader( 3305): 	at jcs.o(PG:406)
E/ExperimentLoader( 3305): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3305): 	at jcs.i(PG:143)
E/ExperimentLoader( 3305): 	at hec.a(PG:42)
E/ExperimentLoader( 3305): 	at hee.a(PG:102)
E/ExperimentLoader( 3305): 	at czr.a(PG:65)
E/ExperimentLoader( 3305): 	at kka.a(PG:108)
E/ExperimentLoader( 3305): 	at czp.a(PG:19176)
E/ExperimentLoader( 3305): 	at czp.a(PG:9081)
E/ExperimentLoader( 3305): 	at czq.run(PG:1686)
E/ExperimentLoader( 3305): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3305): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3305): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3305): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3305): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3305): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3305): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3305): 	at jdm.a(PG:77)
E/ExperimentLoader( 3305): 	... 15 more
E/ExperimentLoader( 3305): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3305): 	at fal.a(PG:38)
E/ExperimentLoader( 3305): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3305): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1274750, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4402): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4402): CheckJNI is OFF
D/AndroidRuntime( 4402): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3786:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  821): Skipping PackageSetting{3987c603 com.example.hello/10273} due to missing metadata
E/JavaBinder( 2174): !!! FAILED BINDER TRANSACTION !!!
E/BtGatt.GattService( 2174): Exception: android.os.TransactionTooLargeException
D/BtGatt.GattService( 2174): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2174): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2174): stop scan
D/BtGatt.ScanManager( 2174): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2174): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2174): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.GattService( 2174): Binder is dead - unregistering client (6)!
D/WifiService(  821): Client connection lost with reason: 4
I/WindowState(  821): WIN DEATH: Window{4e1d6ea u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/BtGatt.AdvertiseManager( 2174): message : 1
D/BtGatt.AdvertiseManager( 2174): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2174): app died - unregistering client : 6
D/BtGatt.GattService( 2174): unregisterClient() - clientIf=6
D/BtGatt.GattService( 2174): onAdvertiseInstanceDisabled() - clientIf=255, status=0
E/BtGatt.ContextMap( 2174): Context not found for ID 255
W/ActivityManager(  821): Force removing ActivityRecord{23a58b39 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
V/ActivityManager(  821): Display changed displayId=0
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
W/ActivityManager(  821): Spurious death for ProcessRecord{13a53138 3786:com.test.thalitest/u0a265}, curProc for 3786: null
I/Keyboard.Facilitator( 1244): resetDictionaries() : en_US
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1244): run()
D/BuaReceiver( 3442): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Decoder ( 1244): createOrResetDecoder
D/TaskPersister(  821): removeObsoleteFile: deleting file=28_task.xml
I/art     ( 1518): Explicit concurrent mark sweep GC freed 2005(174KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 404us total 62.403ms
I/art     ( 1074): Explicit concurrent mark sweep GC freed 73029(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 2.553ms total 60.318ms
I/ActivityManager(  821): Start proc 4417:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/ConfigService( 1262): onCreate
I/art     (  821): Explicit concurrent mark sweep GC freed 14999(1012KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 2.129ms total 94.715ms
I/art     (  821): WaitForGcToComplete blocked for 40.626ms for cause Explicit
W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3786 uid 10265
I/Keyboard.Facilitator( 1244): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1244): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1244): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1244): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1244): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1244): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1244): run() : Loading LM = history
W/LocationOracleImpl( 1518): Best location was null
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1244): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1244): run() : Loading LM = user
I/HotwordRecognitionRnr( 1518): Starting hotword detection.
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1244): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1244): run() : Loaded (exit)
I/MicrophoneInputStream( 1518): mic_starting com.google.android.apps.gsa.speech.audio.u@d53de5
I/Keyboard.Facilitator.Delight2FileSweeper( 1244): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1244): run()
I/StatsUtilsManager( 1244): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1244): shouldRecordStats() = Too Soon
I/AudioFlinger(  359): AudioFlinger's thread 0xb408a000 ready to run
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/art     ( 1365): Explicit concurrent mark sweep GC freed 5097(372KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 853us total 36.583ms
I/MicrophoneInputStream( 1518): mic_started com.google.android.apps.gsa.speech.audio.u@d53de5
D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/VoicemailCleanupService( 4417): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  821): Start proc 4457:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
D/Launcher.Workspace( 1365): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1365): 11683562 - stripEmptyScreens()
I/art     (  821): Explicit concurrent mark sweep GC freed 7168(328KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 2.167ms total 162.145ms
D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2436d8a3}
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=79.25 rxSuccessRate=123.00 targetRoamBSSID=any RSSI=-51
I/HotwordWorker( 1518): onReady
I/ContactLocale( 4417): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  821): Start proc 4477:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/art     (  370): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 280us total 9.124ms
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=44.62 rxSuccessRate=162.00 targetRoamBSSID=any RSSI=-51
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 10.583ms
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659614483
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 326us total 8.687ms
W/ContextImpl( 4477): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1262): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1262): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/art     ( 4402): System.exit called, status: 0
I/AndroidRuntime( 4402): VM exiting with result code 0.
I/kickstart(  876): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/ActivityManager(  821): Killing 3501:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  876): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  876): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1793): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1793): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1793): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1793): Module APK com.google.android.play.games already loaded
I/UpdateIcingCorporaServi( 1518): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteLog( 1793): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1793): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1793): disk I/O error (code 3850)
E/DriveAsyncService( 1793): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1793): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1793): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1793): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1793): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1793): 	at java.lang.Thread.run(Thread.java:818)
W/Launcher( 1365): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@26a5e72e new=com.google.android.velvet.VelvetApplication@26a5e72e
I/LocationSettingsChecker( 1793): Removing dialog suppression flag for package com.test.thalitest
--------- beginning of crash
E/AndroidRuntime( 1793): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1793): Process: com.google.android.gms, PID: 1793
E/AndroidRuntime( 1793): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1793): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1793): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1793): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1793): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1793): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1793): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1793): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1793): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1793): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1793): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1365): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
E/SQLiteDatabase( 1793): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1793): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1793): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1793): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1793): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1793): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1793): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1793): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1793): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1793): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1793): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1793): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1793): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1793): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1793): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1793): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1793): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1793): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1793): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1793): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1793): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1793): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1793): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1793): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1793): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1793): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1793): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1793): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1793): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1793): Sending signal. PID: 1793 SIG: 9
W/ResourcesManager(  821): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  821): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteLog( 1518): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  821): Validating map...
E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
D/WifiService(  821): Client connection lost with reason: 4
I/ActivityManager(  821): Start proc 4509:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 1518): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 1518): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1518): Process: com.google.android.googlequicksearchbox:search, PID: 1518
E/AndroidRuntime( 1518): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1518): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1518): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1518): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1518): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1518): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1518): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1518): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1518): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1518): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1518): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1518): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1518): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1518): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1518): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1518): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1518): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1518): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1518): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1518): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1518): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  821): Start proc 4527:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/ActivityManager(  821): Process com.google.android.gms (pid 1793) has died
I/OpenGLRenderer(  821): Initialized EGL, version 1.4
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10883ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10883ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10883ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20883ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20883ms
D/OpenGLRenderer(  821): Enabling debug mode 0
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  821): Start proc 4549:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
W/ResourcesManager( 4549): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4549): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 4549): VM with version 2.1.0 has multidex support
I/MultiDex( 4549): install
I/MultiDex( 4549): VM has multidex support, MultiDex support library is disabled.
I/HotwordDetector( 1518): Closing mic
I/MicrophoneInputStream( 1518): mic_close com.google.android.apps.gsa.speech.audio.u@d53de5
E/Search.SharedPreferencesProto( 1518): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
W/InputMethodManagerService(  821): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3f8fec1d attribute=null, token = android.os.BinderProxy@2114849c
I/OpenGLRenderer(  821): Initialized EGL, version 1.4
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1518): Stopping hotword detection.
I/HotwordRecognitionRnr( 1518): Hotword detection finished
E/Search.SharedPreferencesProto( 1518): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
E/SQLiteDatabase( 4549): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4549): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4549): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 4549): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 4549): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4549): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4549): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4549): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4549): 	at java.lang.Thread.run(Thread.java:818)
W/LocationOracleImpl( 1518): Best location was null
E/SQLiteDatabase( 4549): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4549): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4549): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 4549): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 4549): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4549): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4549): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4549): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4549): 	at java.lang.Thread.run(Thread.java:818)
E/Search.SharedPreferencesProto( 1518): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/HotwordRecognitionRnr( 1518): Starting hotword detection.
I/MicrophoneInputStream( 1518): mic_starting com.google.android.apps.gsa.speech.audio.u@1fdd74a3
I/AudioFlinger(  359): AudioFlinger's thread 0xb4ccf000 ready to run
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
W/BroadcastQueue(  821): Skipping deliver [background] BroadcastRecord{7f99e8e u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{10ebc042 1518 com.google.android.googlequicksearchbox:search/10028/u0 remote:1ea9168d}: process crashing
I/MicrophoneInputStream( 1518): mic_started com.google.android.apps.gsa.speech.audio.u@1fdd74a3
I/HotwordDetector( 1518): Closing mic
I/MicrophoneInputStream( 1518): mic_close com.google.android.apps.gsa.speech.audio.u@1fdd74a3
I/art     ( 1262): Explicit concurrent mark sweep GC freed 45004(2MB) AllocSpace objects, 2(32KB) LOS objects, 37% free, 26MB/42MB, paused 1.281ms total 36.331ms
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
V/JNIHelp ( 4549): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/HotwordRecognitionRnr( 1518): Hotword detection finished
I/HotwordRecognitionRnr( 1518): Stopping hotword detection.
E/Search.SharedPreferencesProto( 1518): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
E/Search.SharedPreferencesProto( 1518): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/ProviderInstaller( 4549): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4549): Failed to open lock file
W/NativeLibraryUtils( 4549): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4549): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4549): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4549): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4549): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4549): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4549): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4549): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4549): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4549): 	... 3 more
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=44.62 rxSuccessRate=162.00 targetRoamBSSID=any RSSI=-51
E/SQLiteDatabase( 4549): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 4549): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4549): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteDatabase( 4549): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4549): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4549): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 4549): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 4549): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteDatabase( 4549): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteDatabase( 4549): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4549): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4549): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4549): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 4549): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 4549): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4549): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteOpenHelper( 4549): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteOpenHelper( 4549): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteOpenHelper( 4549): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteOpenHelper( 4549): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteOpenHelper( 4549): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteOpenHelper( 4549): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteOpenHelper( 4549): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteOpenHelper( 4549): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4549): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 4549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4549): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager(  821): Killing 3126:com.google.android.music:main/u0a66 (adj 15): empty #17
W/SQLiteOpenHelper( 4549): Opened reminders.db in read-only mode
I/GAv4    ( 4527): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4527):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4527):   adb logcat -s GAv4
E/native  ( 1244): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1244): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
W/GAv4    ( 4527): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/native  ( 1244): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1244): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/SharedPreferencesImpl( 4527): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4527): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4527): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4527): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4527): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4549): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 4549): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4549): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/SQLiteDatabase( 4549): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 4549): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 4549): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4549): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4549): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4549): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4549): FATAL EXCEPTION: AsyncTask #3
E/AndroidRuntime( 4549): Process: com.google.android.gms, PID: 4549
E/AndroidRuntime( 4549): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 4549): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/AndroidRuntime( 4549): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 4549): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 4549): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 4549): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 4549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4549): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4549): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4549): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4549): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/AndroidRuntime( 4549): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 4549): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 4549): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AndroidRuntime( 4549): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4549): 	... 4 more
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
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
W/AnalyticsTrackerProxyImpl( 4527): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
I/Icing   ( 4549): Storage manager: low false usage 1.98MB avail 20.74GB capacity 22.09GB
E/SQLiteDatabase( 4527): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4527): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4527): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4527): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4527): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4527): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4527): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4527): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4527): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4527): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4527): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4527): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4527): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4527): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4527): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4527): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4527): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4527): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4527): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4527): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4527): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4527): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4527): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4527): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4527): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4527): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4527): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 4527): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4527): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4527): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4527): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4527): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/native  ( 1244): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1244): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1244): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1244): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/SQLiteDatabase( 4527): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4527): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4527): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4527): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4527): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4527): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4527): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4527): 	at aen.run(PG:536)
W/Icing   ( 4549): Received bad json for section weights override -- ignoring.
D/GFEEDBACK_SendErrorReportOperation( 4549): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 4549): Error saving report: java.io.IOException: failed to create reports directory
I/GAv4-SVC( 4549): Google Analytics 7.8.99 is starting up.
W/Icing   ( 4549): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4549): Received bad json for section weights override -- ignoring.
W/Icing   ( 4549): Received bad json for corpus context scoring override -- ignoring.
E/Icing   ( 4549): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids for write failed: Read-only file system
E/Icing   ( 4549): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids
E/Icing   ( 4549): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata for write failed: Read-only file system
E/Icing   ( 4549): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
E/Icing   ( 4549): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring for write failed: Read-only file system
E/Icing   ( 4549): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
E/Icing   ( 4549): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs for write failed: Read-only file system
E/Icing   ( 4549): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs
E/Icing   ( 4549): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.tags.h for write failed: Read-only file system
E/Icing   ( 4549): Trie initialize fail
E/Icing   ( 4549): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
E/Icing   ( 4549): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h for write failed: Read-only file system
E/Icing   ( 4549): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
E/Icing   ( 4549): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
E/Icing   ( 4549): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
E/Icing   ( 4549): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
E/Icing   ( 4549): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
E/Icing   ( 4549): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage for write failed: Read-only file system
E/Icing   ( 4549): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
E/Icing   ( 4549): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage for write failed: Read-only file system
E/Icing   ( 4549): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
E/Icing   ( 4549): Init docstore failed
E/Icing   ( 4549): Index init failed, resetting corpora
W/GAv4    ( 4527): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4527): Job execution failed: android.database.sqlite.SQLiteException: Databa,se open failed
E/SharedPreferencesImpl( 4527): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4527): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4527): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4527): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4527): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4527): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4527): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4527): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4527): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4527): 	at aej.c(PG:139)
E/SQLiteDatabase( 4527): 	at aej.b(PG:398)
E/SQLiteDatabase( 4527): 	at agf.f(PG:417)
E/SQLiteDatabase( 4527): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4527): 	at java.lang.Thread.run(Thread.java:818)

```
