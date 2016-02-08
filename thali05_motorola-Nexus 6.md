#### Test 58380500055030c_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/GAV2    ( 3584): Thread[GAThread,5,main]: No campaign data found.
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
--------- beginning of system
I/ActivityManager(  820): Killing 3295:com.google.android.keep/u0a79 (adj 15): empty #17
D/AndroidRuntime( 3714): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3714): CheckJNI is OFF
D/AndroidRuntime( 3714): Calling main entry com.android.commands.am.Am
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{192d20f1 token=Token{34abe098 ActivityRecord{294aca7b u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3714): Shutting down VM
V/WindowManager(  820): Adding window Window{31403862 u0 Starting com.test.thalitest} at 2 of 7 (after Window{3742e75e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/MicrophoneInputStream( 1499): mic_close com.google.android.apps.gsa.speech.audio.u@2f33d0cb
I/HotwordDetector( 1499): Closing mic
I/ActivityManager(  820): Killing 3317:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1499): Stopping hotword detection.
I/HotwordRecognitionRnr( 1499): Hotword detection finished
I/ActivityManager(  820): Start proc 3729:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
,I/ActivityManager(  820): Killing 3339:com.google.android.deskclock/u0a44 (adj 15): empty #17
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660671251
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3729): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3729): Time to load native libraries: 3 ms (timestamps 8490-8493)
,I/LibraryLoader( 3729): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3729): Binding Chromium to main looper Looper (main, tid 1) {3c1d3b12}
I/LibraryLoader( 3729): Expected native library version number "",actual native library version number ""
I/chromium( 3729): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3729): Initializing chromium process, singleProcess=true
,W/art     ( 3729): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3729): ApplicationContext is null in ApplicationStatus
,W/chromium( 3729): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3729): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3729): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3729): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@447f074:true
,W/art     ( 3729): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3729): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3729): CordovaWebView is running on device made by: motorola
,W/art     ( 3729): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3729): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3729): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3729): Validating map...,
,V/WindowManager(  820): Adding window Window{4025ea4 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{31403862 u0 Starting com.test.thalitest})
,W/chromium( 3729): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3729): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3729): Enabling debug mode 0
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +874ms
,I/Keyboard.Facilitator( 1226): onFinishInput()
,W/BindingManager( 3729): Cannot call determinedVisibility() - never saw a connection for the pid: 3729
,D/JsMessageQueue( 3729): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3729): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576316032
,I/chromium( 3729): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3729): Initializing JXcore engine
W/jxcore-log( 3729): JXcore engine is ready
,W/Thread-417( 3785): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12930]" dev="sockfs" ino=12930 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-417( 3785): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-417( 3785): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9750]" dev="sockfs" ino=9750 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-417( 3785): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22729]" dev="sockfs" ino=22729 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3729): Starting JXcore engine
,W/jxcore-log( 3729): Platform android
W/jxcore-log( 3729): 
W/jxcore-log( 3729): Process ARCH arm
W/jxcore-log( 3729): 
,I/jxcore-log( 3729): JXcore Cordova bridge is ready!
I/jxcore-log( 3729): 
W/jxcore-log( 3729): JXcore engine is started
,I/jxcore-log( 3729): Toggling radios to true
I/jxcore-log( 3729): 
,D/BluetoothAdapter( 3729): enable(): BT is already enabled..!
,D/WifiService(  820): New client listening to asynchronous messages,
D/WifiService(  820): setWifiEnabled: true pid=3729, uid=10265,
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3729): Radios toggled
I/jxcore-log( 3729): 
I/jxcore-log( 3729): My device name is: motorola-Nexus 6,
I/jxcore-log( 3729): 
,I/wpa_supplicant( 1065): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1128): Read error: ssl=0xb4888800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1128): SSL shutdown failed: ssl=0xb4888800: I/O error during system call, Broken pipe
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
E/WifiStateMachine(  820): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000,
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524292
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 3050): type=WIFI subType= reason=null isConnected=false
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,V/MusicLeanback( 3050): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1322): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1322): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/WifiConfigStore(  820): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): will read network variables netId=0
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
E/GpsLocationProvider(  820): No APN found to select.
,E/WifiConfigStore(  820): will read network variables netId=0
,I/ActivityManager(  820): Start proc 3792:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/PhoneInterfaceManager( 1322): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1322): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 3792): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3792): simOperator:  IMSI: null
D/SprintDMReceiver( 3792): Not Sprint UICC, don't do anything.
,I/ActivityManager(  820): Killing 3408:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,I/iu.Environment( 1771): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1771): num queued entries: 0
,I/iu.UploadsManager( 1771): num updated entries: 0,
I/iu.SyncManager( 1771): NEXT; no task
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1771): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599935 ms
,I/Babel   ( 2783): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  820): Start proc 3812:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1771): onDestroy
,I/GAv4    ( 3812): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3812):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3812):   adb logcat -s GAv4
,W/GAv4    ( 3812): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3812): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3812): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3812): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3812): Time to load native libraries: 1 ms (timestamps 2278-2279)
,I/LibraryLoader( 3812): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3812): Binding Chromium to main looper Looper (main, tid 1) {1b4d1f21}
,I/LibraryLoader( 3812): Expected native library version number "",actual native library version number ""
I/chromium( 3812): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3812): Initializing chromium process, singleProcess=true
,W/art     ( 3812): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3812): ApplicationContext is null in ApplicationStatus
,W/chromium( 3812): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3812): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3812): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3812): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3812): Requires BLUETOOTH permission
,I/NSApplication( 3812): Starting up...
,I/ActivityManager(  820): Start proc 3869:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  820): Killing 3428:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3476:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,V/MusicLeanback( 3050): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3792): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3792): simOperator:  IMSI: null
,D/SprintDMReceiver( 3792): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1771): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599946 ms
,D/SystemUpdateService( 1771): onDestroy
,I/wpa_supplicant( 1065): wlan0: Trying to associate with SSID 'NG7005g'
,I/art     ( 1499): WaitForGcToComplete blocked for 50.890ms for cause HomogeneousSpaceCompact
,I/wpa_supplicant( 1065): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1065): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1065): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 2
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 173
E/WifiStateMachine(  820):  RSSI mgmt: -55
E/WifiStateMachine(  820):  BE :  rx=136 tx=126 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 8133 tx_time=147 rx_time=385 scan_time=0
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/dhcpcd  ( 3899): version 5.5.6 starting
,I/dhcpcd  ( 3899): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  820): Killing 3252:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3614:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/ActivityManager(  820): Waited long enough for: ServiceRecord{15a68a79 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/dhcpcd  ( 3899): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3899): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 101
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  820): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3050): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3050): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1322): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1322): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/SprintDMReceiver( 3792): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/SprintDMHelper( 3792): simOperator:  IMSI: null
,D/SprintDMReceiver( 3792): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,E/GpsLocationProvider(  820): No APN found to select.
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 22:32:17 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454970737928], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454970737907]}
,I/ActivityManager(  820): Start proc 3934:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/jxcore-log( 3729): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3729): 
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599934 ms
,I/iu.Environment( 1771): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1771): num queued entries: 0
I/iu.UploadsManager( 1771): num updated entries: 0
I/iu.SyncManager( 1771): NEXT; no task
,D/SystemUpdateService( 1771): onDestroy
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1771): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,V/Herrevad( 1771): NQAS connected
,I/Babel   ( 2783): connection state changed from DISCONNECTED to CONNECTED
,I/art     (  820): Explicit concurrent mark sweep GC freed 47823(2MB) AllocSpace objects, 9(238KB) LOS objects, 32% free, 33MB/49MB, paused 1.345ms total 51.710ms
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1128): Explicit concurrent mark sweep GC freed 33159(1827KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 816us total 25.960ms
,D/GCM     ( 1128): Connected
,E/HttpOperation( 3232): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3232): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3232): 	at jdm.a(PG:82)
E/HttpOperation( 3232): 	at jcs.o(PG:406)
E/HttpOperation( 3232): 	at jcn.a(PG:1379)
E/HttpOperation( 3232): 	at jcs.i(PG:143)
E/HttpOperation( 3232): 	at blb.a(PG:3937)
E/HttpOperation( 3232): 	at czp.a(PG:18188)
E/HttpOperation( 3232): 	at czp.a(PG:9081)
E/HttpOperation( 3232): 	at czq.run(PG:1686)
E/HttpOperation( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3232): 	at jdj.a(PG:4091)
E/HttpOperation( 3232): 	at jdj.a(PG:1125)
E/HttpOperation( 3232): 	at jdm.a(PG:77)
E/HttpOperation( 3232): 	... 12 more
E/HttpOperation( 3232): Caused by: faj: BadAuthentication
E/HttpOperation( 3232): 	at fal.a(PG:38)
E/HttpOperation( 3232): 	at jdj.a(PG:4089)
E/HttpOperation( 3232): 	... 14 more
,D/GCM     ( 1128): Message class com.google.f.a.a.p
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3232): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3232): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3232): 	at jdm.a(PG:82)
E/HttpOperation( 3232): 	at jcs.o(PG:406)
E/HttpOperation( 3232): 	at jcn.a(PG:1379)
E/HttpOperation( 3232): 	at jcs.i(PG:143)
E/HttpOperation( 3232): 	at hec.a(PG:42)
E/HttpOperation( 3232): 	at hee.a(PG:102)
E/HttpOperation( 3232): 	at czr.a(PG:65)
E/HttpOperation( 3232): 	at kka.a(PG:108)
E/HttpOperation( 3232): 	at czp.a(PG:19176)
E/HttpOperation( 3232): 	at czp.a(PG:9081)
E/HttpOperation( 3232): 	at czq.run(PG:1686)
E/HttpOperation( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3232): 	at jdj.a(PG:4091)
E/HttpOperation( 3232): 	at jdj.a(PG:1125)
E/HttpOperation( 3232): 	at jdm.a(PG:77)
E/HttpOperation( 3232): 	... 15 more
E/HttpOperation( 3232): Caused by: faj: BadAuthentication
E/HttpOperation( 3232): 	at fal.a(PG:38)
E/HttpOperation( 3232): 	at jdj.a(PG:4089)
E/HttpOperation( 3232): 	... 17 more
E/ExperimentLoader( 3232): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3232): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3232): 	at jdm.a(PG:82)
E/ExperimentLoader( 3232): 	at jcs.o(PG:406)
E/ExperimentLoader( 3232): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3232): 	at jcs.i(PG:143)
E/ExperimentLoader( 3232): 	at hec.a(PG:42)
E/ExperimentLoader( 3232): 	at hee.a(PG:102)
E/ExperimentLoader( 3232): 	at czr.a(PG:65)
E/ExperimentLoader( 3232): 	at kka.a(PG:108)
E/ExperimentLoader( 3232): 	at czp.a(PG:19176)
E/ExperimentLoader( 3232): 	at czp.a(PG:9081)
E/ExperimentLoader( 3232): 	at czq.run(PG:1686)
E/ExperimentLoader( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3232): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3232): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3232): 	at jdm.a(PG:77)
E/ExperimentLoader( 3232): 	... 15 more
E/ExperimentLoader( 3232): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3232): 	at fal.a(PG:38)
E/ExperimentLoader( 3232): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3232): 	... 17 more
,V/KeepSync( 3934): Connecting to GoogleApiClient
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1771): Handling authorization failure
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1771): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1771): 	... 7 more
,V/KeepSync( 3934): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 74846, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3934): IOException
E/KeepSync( 3934): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3934): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3934): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3934): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3934): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3934): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3934): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3934): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3934): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3934): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3934): 	... 10 more
W/KeepSync( 3934): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 74468, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3729): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
,I/jxcore-log( 3729): 
,I/jxcore-log( 3729): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
,I/jxcore-log( 3729): 
,I/jxcore-log( 3729): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3729): 
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3729): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3729): 
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3513): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3513): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3513): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  820): Killing 3553:com.google.android.gms:car/u0a11 (adj 15): empty #17
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.69 rxSuccessRate=9.00 targetRoamBSSID=any RSSI=-55
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3729): Test app app.js loaded
I/jxcore-log( 3729): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34f16f8a added. We now have 1 listener(s)
,I/chromium( 3729): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3729): BLE advertisement is supported
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): TAP version 13
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 1 should be equal
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 2 should be equal
I/jxcore-log( 3729): 
I/jxcore-log( 3729): ok 3 should be equal
I/jxcore-log( 3729): 
I/jxcore-log( 3729): ok 4 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 5 should be equal
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 6 should throw
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 7 should throw
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): ,
I/jxcore-log( 3729): # #parseBeacons no beacons returns null
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 8 should be equal,
,I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # setup
,I/jxcore-log( 3729): 
I/jxcore-log( 3729): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 9 should throw
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 10 should be equal,
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): ,
I/jxcore-log( 3729): # #parseBeacons addressBookCallback returns null for all
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 11 (unnamed assert),
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 12 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # #parseBeacons addressBookCallback returns public key,
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 13 (unnamed assert),
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 14 (unnamed assert)
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # #parseBeacons with beacons both for and not for the user,
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 15 (unnamed assert)
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # teardown,
I/jxcore-log( 3729): 
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=6.34 rxSuccessRate=6.50 targetRoamBSSID=any RSSI=-55
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.33 rxSuccessRate=4.72 targetRoamBSSID=any RSSI=-55
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3513): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3513): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3513): [1] 5.onFinished: Scheduling replication attempt 2.,
,I/ActivityManager(  820): Start proc 3985:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/GAV2    ( 3985): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3985): Created application version: 3.6.8 (30608)
,I/BooksSync( 3985): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3985): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  820): Explicit concurrent mark sweep GC freed 37487(1709KB) AllocSpace objects, 5(80KB) LOS objects, 31% free, 34MB/50MB, paused 1.702ms total 86.201ms
,E/BooksAccountManager( 3985): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3985): Soft error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3985): Sync error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3985): Finished books sync
,I/ActivityManager(  820): Killing 3584:com.google.android.gm/u0a78 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 77641, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GAV2    ( 3985): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.66 rxSuccessRate=2.09 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3513): [375] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1128): Explicit concurrent mark sweep GC freed 24187(1427KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.487ms total 39.508ms
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3513): [375] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3513): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3513): [1] 5.onFinished: Installation state replication failed.,
,D/Finsky  ( 3513): [1] 5.onFinished: Scheduling replication attempt 3.,
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1226): run()
I/Keyboard.Facilitator( 1226): flushDynamicLanguageModels()
,I/ConfigService( 1128): onCreate
,I/ConfigService( 1128): onDestroy
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.41 rxSuccessRate=2.46 targetRoamBSSID=any RSSI=-54
,V/KeepSync( 3934): Connecting to GoogleApiClient
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3232): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3232): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3232): 	at jdm.a(PG:82)
E/HttpOperation( 3232): 	at jcs.o(PG:406)
E/HttpOperation( 3232): 	at jcn.a(PG:1379)
E/HttpOperation( 3232): 	at jcs.i(PG:143)
E/HttpOperation( 3232): 	at blb.a(PG:3937)
E/HttpOperation( 3232): 	at czp.a(PG:18188)
E/HttpOperation( 3232): 	at czp.a(PG:9081)
E/HttpOperation( 3232): 	at czq.run(PG:1686)
E/HttpOperation( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3232): 	at jdj.a(PG:4091)
E/HttpOperation( 3232): 	at jdj.a(PG:1125)
E/HttpOperation( 3232): 	at jdm.a(PG:77)
E/HttpOperation( 3232): 	... 12 more
E/HttpOperation( 3232): Caused by: faj: BadAuthentication
E/HttpOperation( 3232): 	at fal.a(PG:38)
E/HttpOperation( 3232): 	at jdj.a(PG:4089)
E/HttpOperation( 3232): 	... 14 more
,E/ClientConnectionOperation( 1771): Handling authorization failure
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1771): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1771): 	... 7 more
,V/KeepSync( 3934): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3232): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3232): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3232): 	at jdm.a(PG:82)
E/HttpOperation( 3232): 	at jcs.o(PG:406)
E/HttpOperation( 3232): 	at jcn.a(PG:1379)
E/HttpOperation( 3232): 	at jcs.i(PG:143)
E/HttpOperation( 3232): 	at hec.a(PG:42)
E/HttpOperation( 3232): 	at hee.a(PG:102)
E/HttpOperation( 3232): 	at czr.a(PG:65)
E/HttpOperation( 3232): 	at kka.a(PG:108)
E/HttpOperation( 3232): 	at czp.a(PG:19176)
E/HttpOperation( 3232): 	at czp.a(PG:9081)
E/HttpOperation( 3232): 	at czq.run(PG:1686)
E/HttpOperation( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3232): 	at jdj.a(PG:4091)
E/HttpOperation( 3232): 	at jdj.a(PG:1125)
E/HttpOperation( 3232): 	at jdm.a(PG:77)
E/HttpOperation( 3232): 	... 15 more
E/HttpOperation( 3232): Caused by: faj: BadAuthentication
E/HttpOperation( 3232): 	at fal.a(PG:38)
E/HttpOperation( 3232): 	at jdj.a(PG:4089)
E/HttpOperation( 3232): 	... 17 more
,E/ExperimentLoader( 3232): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3232): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3232): 	at jdm.a(PG:82)
E/ExperimentLoader( 3232): 	at jcs.o(PG:406)
E/ExperimentLoader( 3232): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3232): 	at jcs.i(PG:143)
E/ExperimentLoader( 3232): 	at hec.a(PG:42)
E/ExperimentLoader( 3232): 	at hee.a(PG:102)
E/ExperimentLoader( 3232): 	at czr.a(PG:65)
,E/ExperimentLoader( 3232): 	at kka.a(PG:108)
E/ExperimentLoader( 3232): 	at czp.a(PG:19176)
E/ExperimentLoader( 3232): 	at czp.a(PG:9081)
E/ExperimentLoader( 3232): 	at czq.run(PG:1686)
E/ExperimentLoader( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3232): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3232): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3232): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3232): 	at jdm.a(PG:77)
E/ExperimentLoader( 3232): 	... 15 more
E/ExperimentLoader( 3232): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3232): 	at fal.a(PG:38)
,E/ExperimentLoader( 3232): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3232): 	... 17 more
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3934): IOException
E/KeepSync( 3934): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3934): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3934): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3934): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3934): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3934): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3934): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3934): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3934): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3934): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3934): 	... 10 more
W/KeepSync( 3934): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 109197, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 107355, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3513): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3513): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3513): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.83 rxSuccessRate=2.86 targetRoamBSSID=any RSSI=-54
,E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (198 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  280): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  820): Display changed displayId=0
,I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  280): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  820): Excessive delay in setPowerMode(): 270ms
,I/DreamManagerService(  820): Entering dreamland.,
I/PowerManagerService(  820): Dozing...,
,I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on,
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 12
,E/native  (  820): do suspend false
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Keyboard.Facilitator( 1226): onFinishInput()
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  820): cancelDelayedScan -> 14
,E/native  (  820): do suspend true
,D/Finsky  ( 3513): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3513): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3513): [1] 5.onFinished: Scheduling replication attempt 5.
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  870): STATUS: Received file 'm9kefs2'
,I/kickstart(  870): STATUS: 950272 bytes transferred in 0.974742 seconds
I/kickstart(  870): STATUS: Successfully downloaded files from target 
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  870): STATUS: Sahara protocol completed
,I/BooksSync( 3985): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3985): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 48023(2MB) AllocSpace objects, 18(476KB) LOS objects, 31% free, 34MB/50MB, paused 2.406ms total 88.300ms
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3985): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3985): Soft error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3985): Sync error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3985): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 138855, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1128): Vacuum at: now=1454970846656 tag=VacuumService
,V/GoogleAuthProtoRequest( 3094): [305] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3513): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3513): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3513): [1] 5.onFinished: Giving up after 6 failures.
W/ExperimentUpdateService( 3094): [305] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3094): [305] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3094): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3094): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3094): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3094): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1128): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1128): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1128): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,W/Uploader( 1128): No account for auth token provided
,W/Uploader( 1128): No account for auth token provided
,W/Uploader( 1128): No account for auth token provided
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1128): Explicit concurrent mark sweep GC freed 51353(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.598ms total 59.393ms
,E/Uploader( 1128): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1128): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1128): No account for auth token provided
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1128): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1128): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1128): No account for auth token provided
,W/Uploader( 1128): No account for auth token provided
,W/Uploader( 1128): No account for auth token provided
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1128): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1128): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1128): No account for auth token provided
,W/Uploader( 1128): No account for auth token provided,
,W/Uploader( 1128): No account for auth token provided
,W/Uploader( 1128):  no longer exists, so no auth token.
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1128): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1128): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1128): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1128): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1128): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1128): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3094): [307] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3094): [307] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3094): [307] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3094): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3094): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3094): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3094): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1226): run()
I/Keyboard.Facilitator( 1226): flushDynamicLanguageModels()
,I/ConfigService( 1128): onCreate
,V/KeepSync( 3934): Connecting to GoogleApiClient
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1771): Handling authorization failure
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1771): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1771): 	... 7 more
,V/KeepSync( 3934): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3232): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3232): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3232): 	at jdm.a(PG:82)
E/HttpOperation( 3232): 	at jcs.o(PG:406)
E/HttpOperation( 3232): 	at jcn.a(PG:1379)
E/HttpOperation( 3232): 	at jcs.i(PG:143)
E/HttpOperation( 3232): 	at blb.a(PG:3937)
E/HttpOperation( 3232): 	at czp.a(PG:18188)
E/HttpOperation( 3232): 	at czp.a(PG:9081)
E/HttpOperation( 3232): 	at czq.run(PG:1686)
E/HttpOperation( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3232): 	at jdj.a(PG:4091)
E/HttpOperation( 3232): 	at jdj.a(PG:1125)
E/HttpOperation( 3232): 	at jdm.a(PG:77)
E/HttpOperation( 3232): 	... 12 more
E/HttpOperation( 3232): Caused by: faj: BadAuthentication
E/HttpOperation( 3232): 	at fal.a(PG:38)
E/HttpOperation( 3232): 	at jdj.a(PG:4089)
E/HttpOperation( 3232): 	... 14 more
,I/art     (  820): Explicit concurrent mark sweep GC freed 33533(1467KB) AllocSpace objects, 2(126KB) LOS objects, 31% free, 34MB/50MB, paused 1.515ms total 53.239ms
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3232): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3232): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3232): 	at jdm.a(PG:82)
E/HttpOperation( 3232): 	at jcs.o(PG:406)
E/HttpOperation( 3232): ,	at jcn.a(PG:1379)
E/HttpOperation( 3232): 	at jcs.i(PG:143)
E/HttpOperation( 3232): 	at hec.a(PG:42)
,E/HttpOperation( 3232): 	at hee.a(PG:102)
E/HttpOperation( 3232): 	at czr.a(PG:65)
E/HttpOperation( 3232): 	at kka.a(PG:108)
E/HttpOperation( 3232): 	at czp.a(PG:19176)
E/HttpOperation( 3232): 	at czp.a(PG:9081)
,E/HttpOperation( 3232): 	at czq.run(PG:1686)
E/HttpOperation( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3232): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3232): 	,at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3232): 	at jdj.a(PG:4091)
E/HttpOperation( 3232): 	at jdj.a(PG:1125)
E/HttpOperation( 3232): 	at jdm.a(PG:77)
E/HttpOperation( 3232): 	... 15 more
E/HttpOperation( 3232): Caused by: faj: BadAuthentication,
E/HttpOperation( 3232): 	at fal.a(PG:38)
E/HttpOperation( 3232): 	at jdj.a(PG:4089)
E/HttpOperation( 3232): 	,... 17 more
E/ExperimentLoader( 3232): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3232): java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 3232): 	at jdm.a(PG:82)
E/ExperimentLoader( 3232): 	at jcs.o(PG:406)
E/ExperimentLoader( 3232): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3232): 	at jcs.i(PG:143)
E/ExperimentLoader( 3232): 	at hec.a(PG:42)
E/ExperimentLoader( 3232): 	,at hee.a(PG:102)
E/ExperimentLoader( 3232): 	at czr.a(PG:65)
E/ExperimentLoader( 3232): 	at kka.a(PG:108)
E/ExperimentLoader( 3232): 	,at czp.a(PG:19176)
E/ExperimentLoader( 3232): 	at czp.a(PG:9081)
E/ExperimentLoader( 3232): 	at czq.run(PG:1686)
E/ExperimentLoader( 3232): ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3232): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3232): ,	at jdj.a(PG:4091)
E/ExperimentLoader( 3232): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3232): 	at jdm.a(PG:77),
E/ExperimentLoader( 3232): 	... 15 more
E/ExperimentLoader( 3232): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3232): 	,at fal.a(PG:38)
E/ExperimentLoader( 3232): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3232): 	... 17 more
,E/KeepSync( 3934): IOException
,E/KeepSync( 3934): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3934): ,	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3934): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3934): ,	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3934): 	,at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3934): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3934): 	,at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3934): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3934): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,E/KeepSync( 3934): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3934): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3934): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3934): 	,at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3934): 	... 10 more
W/KeepSync( 3934): Sync result 2,
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 202159, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 198628, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1128): onDestroy
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,I/BooksSync( 3985): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3985): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3985): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3985): Soft error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3985): Sync error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3985): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 230366, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # multiplex can send data
,I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 16 String should be length:200
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # enqueue and run in order
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 17 firstPromise setTimeout
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 18 firstPromise result
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 19 firstPromise testValue
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 20 secondPromise setTimeout
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 21 secondPromise result
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 22 secondPromise testValue
I/jxcore-log( 3729): 
I/jxcore-log( 3729): ok 23 thirdPromise in promise
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 24 thirdPromise result,
I/jxcore-log( 3729): 
I/jxcore-log( 3729): ok 25 thirdPromise testValue
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): ,
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # basic
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 26 sane
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # another
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 27 sane
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 28 should be equal
I/jxcore-log( 3729): ,
,I/jxcore-log( 3729): ok 29 null
,I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 30 (unnamed assert)
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 31 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 32 should not throw
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
,I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 33 (unnamed assert)
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 34 (unnamed assert)
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 35 should not throw
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 36 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 37 should be equal
I/jxcore-log( 3729): 
I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 38 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # failed to get mobile documents path
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 39 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #init should register the peerAvailabilityChanged event
,I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 40 should be equal
,I/jxcore-log( 3729): 
I/jxcore-log( 3729): ok 41 should be equal
I/jxcore-log( 3729): 
I/jxcore-log( 3729): ok 42 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #init should register the networkChanged event
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 43 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #startBroadcasting should throw on null device name
,I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 44 should throw
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 45 should throw
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 46 should throw
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 47 should throw
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #startBroadcasting should throw on negative port
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 48 should throw
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #startBroadcasting should throw on too large port
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 49 should throw
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
,I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 50 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 51 should be equal
I/jxcore-log( 3729): 
I/jxcore-log( 3729): ok 52 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 53 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 54 should be equal
I/jxcore-log( 3729): 
I/jxcore-log( 3729): ok 55 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 56 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 57 should be equal
I/jxcore-log( 3729): ,
I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 58 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 59 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #connect should call Mobile("Connect") with a port and without an error,
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 60 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 61 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 62 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 63 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 64 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # should call Mobile("Disconnect") without an error,
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 65 should be equal,
I/jxcore-log( 3729): 
I/jxcore-log( 3729): ok 66 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # teardown,
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): ,
,I/jxcore-log( 3729): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 67 should be equal
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): ok 68 should be equal
I/jxcore-log( 3729): 
V/GoogleAuthProtoRequest( 3094): [308] a.<init>: mAccountName set to: thalitester@gmail.com
,I/jxcore-log( 3729): # teardown
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # setup
I/jxcore-log( 3729): 
,I/jxcore-log( 3729): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3729): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2984b9fb added. We now have 2 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): setDiscoveryMode: BLE_AND_WIFI -> WIFI
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966719.3729
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966719.3729","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): start: Using peer discovery mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966719.3729, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3729): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966719.3729","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966719.3729","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966719.3729","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
W/ExperimentUpdateService( 3094): [308] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3094): [308] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3094): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3094): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3094): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3094): 	at com.a.a.k.run(SourceFile:110)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966719.3729, mode: WIFI
,I/jxcore-log( 3729): ok 69 Should be able to call startBroadcasting without error
I/jxcore-log( 3729): 
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 3729): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: NOT_STARTED
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3729): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3729): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: NOT_STARTED
I/wpa_supplicant( 1065): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3729): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 3729): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Maximum number of connection attempt retries: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3729): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26747fc4 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966776.3729
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966776.3729","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966776.3729, mode: BLE_AND_WIFI
W/BluetoothAdapter( 3729): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3729): createAdvertiseData: From: 1454970966776.3729 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2160): registerClient() - UUID=5454cef0-7849-4a58-ad1c-3121832ac083
,D/BtGatt.GattService( 2160): onClientRegistered() - UUID=5454cef0-7849-4a58-ad1c-3121832ac083, clientIf=5
,D/BluetoothLeScanner( 3729): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2160): start scan with filters
,D/BtGatt.ScanManager( 2160): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): setState: State changed from NOT_STARTED to STARTING
,D/BluetoothAdapterService( 2160): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25dd2e3
,D/BtGatt.GattService( 2160): registerClient() - UUID=b8069dd8-237d-44a9-9666-f1210319dbff,
D/BtGatt.GattService( 2160): onClientRegistered() - UUID=b8069dd8-237d-44a9-9666-f1210319dbff, clientIf=6
D/BluetoothLeAdvertiser( 3729): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2160): message : 0
,D/BtGatt.AdvertiseManager( 2160): starting multi advertising,
,D/BtGatt.GattService( 2160): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2160): callback done for clientIf - 5 status - 0,
,D/BtGatt.GattService( 2160): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2160): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2160): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.GattService( 2160): onAdvertiseDataSet() - clientIf=6, status=0,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966776.3729","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966776.3729","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966776.3729","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966776.3729, mode: BLE_AND_WIFI
I/wpa_supplicant( 1065): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3729): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 3729): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3729): createAdvertiseData: From: 1454970966776.3729 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/io.jxcore.node.ConnectionHelper( 3729): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): stopListeningForIncomingConnections: Stopping...,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: NOT_STARTED
D/BtGatt.AdvertiseManager( 2160): message : 1
D/BtGatt.AdvertiseManager( 2160): stop advertise for client 6
,D/BtGatt.GattService( 2160): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2160): Client app is not null!
,D/BtGatt.GattService( 2160): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2160): registerClient() - UUID=50349933-1641-40c0-abd1-0c54fb55429d
D/BtGatt.GattService( 2160): onClientRegistered() - UUID=50349933-1641-40c0-abd1-0c54fb55429d, clientIf=6
D/BluetoothLeAdvertiser( 3729): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2160): message : 0
,D/BtGatt.AdvertiseManager( 2160): starting multi advertising
,D/BtGatt.GattService( 2160): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2160): onAdvertiseDataSet() - clientIf=6, status=0,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3729): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): stop
I/wpa_supplicant( 1065): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: RESTARTING
D/BtGatt.AdvertiseManager( 2160): message : 1
D/BtGatt.AdvertiseManager( 2160): stop advertise for client 6
,D/BtGatt.GattService( 2160): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2160): Client app is not null!
D/BtGatt.GattService( 2160): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): onIsAdvertiserStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsBlePeerDiscovererStateChanged: [SCANNING]
D/BtGatt.GattService( 2160): stopScan() - queue size =1
,D/BtGatt.GattService( 2160): unregisterClient() - clientIf=5
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): updateState(): State changed from [SCANNING] to [NOT_STARTED]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsBlePeerDiscovererStateChanged: [NOT_STARTED]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopWifiPeerDiscovery: Stopped,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: No more listeners, de-initializing...,
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3729): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local services cleared successfully
I/jxcore-log( 3729): ok 72 Should be able to call stopBroadcasting without error
I/jxcore-log( 3729): ,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3729): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): load: ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Peer expiration time in milliseconds: 60000, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23f46dcf added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
D/BtGatt.GattService( 2160): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2160): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2160): stop scan
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966860.3729
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966860.3729","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3729): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966860.3729, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966860.3729","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966860.3729","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966860.3729","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966860.3729, mode: WIFI
I/wpa_supplicant( 1065): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3729): ok 73 Should be able to call startBroadcasting without error
I/jxcore-log( 3729): 
,I/io.jxcore.node.ConnectionHelper( 3729): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3729): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: RUNNING_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): stop: Stopping P2P device discovery...
I/wpa_supplicant( 1065): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3729): clear,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3729): ok 74 Should be able to call stopBroadcasting without error
I/jxcore-log( 3729): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f417eb added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3729): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966890.3729,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966890.3729","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: RUNNING,
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3729): getBluetoothService() called with no BluetoothManagerCallback,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966890.3729, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3729): createAdvertiseData: From: 1454970966890.3729 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2160): registerClient() - UUID=f3f2c44c-33c3-46ab-925b-501a8f939d0f
D/BtGatt.GattService( 2160): onClientRegistered() - UUID=f3f2c44c-33c3-46ab-925b-501a8f939d0f, clientIf=5
D/BluetoothLeScanner( 3729): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2160): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): setState: State changed from NOT_STARTED to STARTING
D/BtGatt.ScanManager( 2160): handling starting scan
,D/BtGatt.GattService( 2160): registerClient() - UUID=7f819e76-f8b0-44e9-87c1-0958504cf26b
D/BtGatt.GattService( 2160): onClientRegistered() - UUID=7f819e76-f8b0-44e9-87c1-0958504cf26b, clientIf=6
D/BtGatt.GattService( 2160): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2160): callback done for clientIf - 5 status - 0
,D/BluetoothLeAdvertiser( 3729): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2160): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2160): callback done for clientIf - 5 status - 0
D/BtGatt.AdvertiseManager( 2160): message : 0
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.AdvertiseManager( 2160): starting multi advertising
,D/BtGatt.GattService( 2160): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2160): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966890.3729","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966890.3729","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966890.3729","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966890.3729, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3729): createAdvertiseData: From: 1454970966890.3729 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/jxcore-log( 3729): ok 75 Should be able to call startBroadcasting without error
I/jxcore-log( 3729): 
,I/io.jxcore.node.ConnectionHelper( 3729): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): onServerStopped
D/BtGatt.AdvertiseManager( 2160): message : 1
I/wpa_supplicant( 1065): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: NOT_STARTED
D/BtGatt.AdvertiseManager( 2160): stop advertise for client 6
D/BtGatt.GattService( 2160): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2160): Client app is not null!
D/BtGatt.GattService( 2160): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2160): registerClient() - UUID=1758b235-768e-4682-a363-ea4aac4c973d
,D/BtGatt.GattService( 2160): onClientRegistered() - UUID=1758b235-768e-4682-a363-ea4aac4c973d, clientIf=6,
D/BluetoothLeAdvertiser( 3729): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2160): message : 0
,D/BtGatt.AdvertiseManager( 2160): starting multi advertising
,D/BtGatt.GattService( 2160): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2160): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3729): stopProvideBluetoothMacAddressMode
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): onStartSuccess
D/BtGatt.AdvertiseManager( 2160): message : 1
D/BtGatt.AdvertiseManager( 2160): stop advertise for client 6
,D/BtGatt.GattService( 2160): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2160): Client app is not null!
D/BtGatt.GattService( 2160): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from STARTING to NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): updateState(): State changed from [NOT_STARTED] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsBlePeerDiscovererStateChanged: [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): onIsAdvertiserStartedChanged: true
D/BtGatt.GattService( 2160): stopScan() - queue size =1
D/BtGatt.GattService( 2160): unregisterClient() - clientIf=5
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local services cleared successfully
I/wpa_supplicant( 1065): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3729): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3729): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 3729): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise mode: 1, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@229f3d1d added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): setDiscoveryMode: BLE_AND_WIFI -> WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
D/BtGatt.GattService( 2160): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2160): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2160): stop scan
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3729): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966976.3729
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966976.3729","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): startListeningForIncomingConnections: Starting...,
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: OK
,I/io.jxcore.node.ConnectionHelper( 3729): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966976.3729, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
W/BluetoothAdapter( 3729): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966976.3729","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966976.3729","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454970966976.3729","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: RUNNING_WIFI
I/wpa_supplicant( 1065): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970966976.3729, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3729): start: OK
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: STARTED
I/wpa_supplicant( 1065): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3729): ok 77 Should be able to call startBroadcasting without error,
I/jxcore-log( 3729): 
I/io.jxcore.node.ConnectionHelper( 3729): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3729): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopWifiPeerDiscovery: Stopped,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3729): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3729): ok 78 Should be able to call stopBroadcasting without error
I/jxcore-log( 3729): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local services cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): ,	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Peer expiration time in milliseconds: 60000, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f78e19 added. We now have 7 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3729): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970967024.3729
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970967024.3729","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: RUNNING
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3729): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3729): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970967024.3729, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3729): createAdvertiseData: From: 1454970967024.3729 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2160): registerClient() - UUID=f4b926fe-27d1-43db-94f9-8a40bca97246,
D/BtGatt.GattService( 2160): onClientRegistered() - UUID=f4b926fe-27d1-43db-94f9-8a40bca97246, clientIf=5
D/BluetoothLeScanner( 3729): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2160): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): setState: State changed from NOT_STARTED to STARTING
D/BtGatt.ScanManager( 2160): handling starting scan
,D/BtGatt.GattService( 2160): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,D/BtGatt.ScanManager( 2160): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2160): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2160): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.GattService( 2160): registerClient() - UUID=a200be73-df53-4e48-986f-d14a5de89026
D/BtGatt.GattService( 2160): onClientRegistered() - UUID=a200be73-df53-4e48-986f-d14a5de89026, clientIf=6
,D/BluetoothLeAdvertiser( 3729): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2160): message : 0
,D/BtGatt.AdvertiseManager( 2160): starting multi advertising
,D/BtGatt.GattService( 2160): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2160): onAdvertiseDataSet() - clientIf=6, status=0,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970967024.3729","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970967024.3729","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454970967024.3729","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/wpa_supplicant( 1065): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970967024.3729, mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3729): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3729): createAdvertiseData: From: 1454970967024.3729 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.AdvertiseManager( 2160): message : 1
,I/jxcore-log( 3729): ok 79 Should be able to call startBroadcasting without error
I/jxcore-log( 3729): 
I/io.jxcore.node.ConnectionHelper( 3729): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): onServerStopped
,D/BtGatt.AdvertiseManager( 2160): stop advertise for client 6
,D/BtGatt.GattService( 2160): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2160): Client app is not null!
D/BtGatt.GattService( 2160): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2160): registerClient() - UUID=594db1cf-298e-4a24-9ff0-bae7e62826bc
D/BtGatt.GattService( 2160): onClientRegistered() - UUID=594db1cf-298e-4a24-9ff0-bae7e62826bc, clientIf=6
,D/BluetoothLeAdvertiser( 3729): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2160): message : 0
,D/BtGatt.AdvertiseManager( 2160): starting multi advertising
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/BtGatt.GattService( 2160): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2160): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3729): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): stop
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: STARTED
I/wpa_supplicant( 1065): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): onStartSuccess
,D/BtGatt.AdvertiseManager( 2160): message : 1
D/BtGatt.AdvertiseManager( 2160): stop advertise for client 6
,D/BtGatt.GattService( 2160): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2160): Client app is not null!
D/BtGatt.GattService( 2160): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): onIsAdvertiserStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsBlePeerDiscovererStateChanged: [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): onIsAdvertiserStartedChanged: true
D/BtGatt.GattService( 2160): stopScan() - queue size =1
,D/BtGatt.GattService( 2160): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopBlePeerDiscoverer: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: RESTARTING
D/BtGatt.GattService( 2160): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2160): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2160): stop scan
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - queue=0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local services cleared successfully
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3729): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3729): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3729): ok 80 Should be able to call stopBroadcasting without error
I/jxcore-log( 3729): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): ,	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	,Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): ,	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22aed1db added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970967163.3729
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970967163.3729","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3729): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970967163.3729, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970967163.3729","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970967163.3729","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454970967163.3729","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970967163.3729, mode: WIFI
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/wpa_supplicant( 1065): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3729): ok 81 Should be able to call startBroadcasting without error
I/jxcore-log( 3729): 
I/io.jxcore.node.ConnectionHelper( 3729): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stop: Stopping peer discovery...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local service added successfully,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3729): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: RUNNING_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: NOT_INITIALIZED
I/wpa_supplicant( 1065): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3729): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3729): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): Local services cleared successfully
I/jxcore-log( 3729): ok 82 Should be able to call stopBroadcasting without error,
I/jxcore-log( 3729): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3729): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	,Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise mode: 1, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@233eb0b7 added. We now have 9 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3729): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3729): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970967236.3729
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970967236.3729","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: RUNNING
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/io.jxcore.node.ConnectionHelper( 3729): onConnectionManagerStateChanged: RUNNING
W/BluetoothAdapter( 3729): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970967236.3729, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3729): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3729): createAdvertiseData: From: 1454970967236.3729 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,D/BtGatt.GattService( 2160): registerClient() - UUID=69328559-496d-439e-b669-5e24ca7f0adb
,D/BtGatt.GattService( 2160): onClientRegistered() - UUID=69328559-496d-439e-b669-5e24ca7f0adb, clientIf=5
D/BluetoothLeScanner( 3729): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2160): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): setState: State changed from NOT_STARTED to STARTING
D/BtGatt.ScanManager( 2160): handling starting scan
,D/BtGatt.GattService( 2160): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2160): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2160): registerClient() - UUID=776e12d1-934a-42d6-ab0a-0e58b77990d9
,D/BtGatt.GattService( 2160): onClientRegistered() - UUID=776e12d1-934a-42d6-ab0a-0e58b77990d9, clientIf=6
D/BluetoothLeAdvertiser( 3729): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2160): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2160): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/BtGatt.AdvertiseManager( 2160): message : 0
,D/BtGatt.AdvertiseManager( 2160): starting multi advertising
,D/BtGatt.GattService( 2160): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2160): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3729): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970967236.3729","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454970967236.3729","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3729): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454970967236.3729","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3729): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/io.jxcore.node.ConnectionHelper( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454970967236.3729, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3729): createAdvertiseData: From: 1454970967236.3729 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/wpa_supplicant( 1065): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3729): ok 83 Should be able to call startBroadcasting without error
I/jxcore-log( 3729): 
I/io.jxcore.node.ConnectionHelper( 3729): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): shutdown
D/BtGatt.AdvertiseManager( 2160): message : 1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3729): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3729): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3729): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3729): setState: NOT_STARTED
D/BtGatt.AdvertiseManager( 2160): stop advertise for client 6
,D/BtGatt.GattService( 2160): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2160): Client app is not null!
,D/BtGatt.GattService( 2160): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2160): registerClient() - UUID=6fcf5bce-4057-4998-86b2-0d421791e91d
,D/BtGatt.GattService( 2160): onClientRegistered() - UUID=6fcf5bce-4057-4998-86b2-0d421791e91d, clientIf=6
D/BluetoothLeAdvertiser( 3729): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2160): message : 0
,D/BtGatt.AdvertiseManager( 2160): starting multi advertising
,D/BtGatt.GattService( 2160): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2160): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3729): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3729): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3729): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3729): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): stop
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3729): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3729): onIsAdvertiserStartedChanged: true
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/btif_config_util( 2160): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3232): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3232): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3232): 	at jdm.a(PG:82)
E/HttpOperation( 3232): 	at jcs.o(PG:406)
E/HttpOperation( 3232): 	at jcn.a(PG:1379)
E/HttpOperation( 3232): 	at jcs.i(PG:143)
E/HttpOperation( 3232): 	at blb.a(PG:3937)
E/HttpOperation( 3232): 	at czp.a(PG:18188)
E/HttpOperation( 3232): 	at czp.a(PG:9081)
E/HttpOperation( 3232): 	at czq.run(PG:1686)
E/HttpOperation( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3232): 	at jdj.a(PG:4091)
E/HttpOperation( 3232): 	at jdj.a(PG:1125)
E/HttpOperation( 3232): 	at jdm.a(PG:77)
E/HttpOperation( 3232): 	... 12 more
E/HttpOperation( 3232): Caused by: faj: BadAuthentication
E/HttpOperation( 3232): 	at fal.a(PG:38)
E/HttpOperation( 3232): 	at jdj.a(PG:4089)
E/HttpOperation( 3232): 	... 14 more
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3232): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3232): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3232): 	at jdm.a(PG:82)
E/HttpOperation( 3232): 	at jcs.o(PG:406)
E/HttpOperation( 3232): 	at jcn.a(PG:1379)
E/HttpOperation( 3232): 	at jcs.i(PG:143)
E/HttpOperation( 3232): 	at hec.a(PG:42)
E/HttpOperation( 3232): 	at hee.a(PG:102)
E/HttpOperation( 3232): 	at czr.a(PG:65)
E/HttpOperation( 3232): 	at kka.a(PG:108)
E/HttpOperation( 3232): 	at czp.a(PG:19176)
E/HttpOperation( 3232): 	at czp.a(PG:9081)
E/HttpOperation( 3232): 	at czq.run(PG:1686)
E/HttpOperation( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3232): 	at jdj.a(PG:4091)
E/HttpOperation( 3232): 	at jdj.a(PG:1125)
E/HttpOperation( 3232): 	at jdm.a(PG:77)
E/HttpOperation( 3232): 	... 15 more
E/HttpOperation( 3232): Caused by: faj: BadAuthentication
E/HttpOperation( 3232): 	at fal.a(PG:38)
E/HttpOperation( 3232): 	at jdj.a(PG:4089)
E/HttpOperation( 3232): 	... 17 more
,E/ExperimentLoader( 3232): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3232): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3232): 	at jdm.a(PG:82)
E/ExperimentLoader( 3232): 	at jcs.o(PG:406)
E/ExperimentLoader( 3232): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3232): 	at jcs.i(PG:143)
E/ExperimentLoader( 3232): 	at hec.a(PG:42)
E/ExperimentLoader( 3232): 	at hee.a(PG:102)
E/ExperimentLoader( 3232): 	at czr.a(PG:65)
E/ExperimentLoader( 3232): 	at kka.a(PG:108)
E/ExperimentLoader( 3232): 	at czp.a(PG:19176)
E/ExperimentLoader( 3232): 	at czp.a(PG:9081)
E/ExperimentLoader( 3232): 	at czq.run(PG:1686)
E/ExperimentLoader( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3232): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3232): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3232): 	at jdm.a(PG:77),
E/ExperimentLoader( 3232): 	... 15 more
E/ExperimentLoader( 3232): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3232): 	at fal.a(PG:38)
E/ExperimentLoader( 3232): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3232): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 351300, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1128): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3513): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 3513): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3513): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024),
E/PlayEventLogger( 3513): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3513): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867),
E/PlayEventLogger( 3513): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3513): 	at android.os.Binder.execTransact(Binder.java:446)
,I/art     ( 1128): Explicit concurrent mark sweep GC freed 58962(3MB) AllocSpace objects, 10(1017KB) LOS objects, 36% free, 28MB/44MB, paused 1.536ms total 42.582ms
,W/System  ( 3513): Ignoring header User-Agent because its value was null.
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@211e67bb}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-54
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@211e67bb}
,V/KeepSync( 3934): Connecting to GoogleApiClient
,I/art     (  820): Explicit concurrent mark sweep GC freed 38271(1850KB) AllocSpace objects, 12(851KB) LOS objects, 31% free, 34MB/50MB, paused 1.503ms total 101.129ms
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1771): Handling authorization failure,
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1771): ,	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1771): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
,E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1771): 	... 7 more
V/KeepSync( 3934): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3934): IOException
E/KeepSync( 3934): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3934): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3934): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3934): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3934): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3934): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3934): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3934): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3934): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3934): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3934): 	... 10 more
W/KeepSync( 3934): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 358340, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3985): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3985): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3985): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3985): Soft error,
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3985): Sync error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source),
I/BooksSync( 3985): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 384599, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,V/GoogleAuthProtoRequest( 3094): [309] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3094): [309] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3094): [309] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3094): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3094): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3094): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3094): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1065): P2P-FIND-STOPPED 
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3232): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3232): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3232): 	at jdm.a(PG:82)
E/HttpOperation( 3232): 	at jcs.o(PG:406)
E/HttpOperation( 3232): 	at jcn.a(PG:1379)
E/HttpOperation( 3232): 	at jcs.i(PG:143)
E/HttpOperation( 3232): 	at blb.a(PG:3937)
E/HttpOperation( 3232): 	at czp.a(PG:18188)
E/HttpOperation( 3232): 	at czp.a(PG:9081)
E/HttpOperation( 3232): 	at czq.run(PG:1686)
E/HttpOperation( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3232): 	at jdj.a(PG:4091)
E/HttpOperation( 3232): 	at jdj.a(PG:1125)
E/HttpOperation( 3232): 	at jdm.a(PG:77)
E/HttpOperation( 3232): 	... 12 more
E/HttpOperation( 3232): Caused by: faj: BadAuthentication
E/HttpOperation( 3232): 	at fal.a(PG:38)
E/HttpOperation( 3232): 	at jdj.a(PG:4089)
E/HttpOperation( 3232): 	... 14 more
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3232): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3232): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3232): 	at jdm.a(PG:82)
E/HttpOperation( 3232): 	at jcs.o(PG:406)
E/HttpOperation( 3232): 	at jcn.a(PG:1379)
E/HttpOperation( 3232): 	at jcs.i(PG:143)
E/HttpOperation( 3232): 	at hec.a(PG:42)
E/HttpOperation( 3232): 	at hee.a(PG:102)
E/HttpOperation( 3232): 	at czr.a(PG:65)
E/HttpOperation( 3232): 	at kka.a(PG:108)
E/HttpOperation( 3232): 	at czp.a(PG:19176)
E/HttpOperation( 3232): 	at czp.a(PG:9081)
E/HttpOperation( 3232): 	at czq.run(PG:1686)
E/HttpOperation( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3232): 	at jdj.a(PG:4091)
E/HttpOperation( 3232): 	at jdj.a(PG:1125)
E/HttpOperation( 3232): 	at jdm.a(PG:77)
E/HttpOperation( 3232): 	... 15 more
E/HttpOperation( 3232): Caused by: faj: BadAuthentication
E/HttpOperation( 3232): 	at fal.a(PG:38)
E/HttpOperation( 3232): 	at jdj.a(PG:4089)
E/HttpOperation( 3232): 	... 17 more
,E/ExperimentLoader( 3232): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3232): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3232): 	at jdm.a(PG:82)
E/ExperimentLoader( 3232): 	at jcs.o(PG:406),
E/ExperimentLoader( 3232): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3232): 	at jcs.i(PG:143)
E/ExperimentLoader( 3232): 	at hec.a(PG:42)
E/ExperimentLoader( 3232): 	at hee.a(PG:102)
E/ExperimentLoader( 3232): 	at czr.a(PG:65)
E/ExperimentLoader( 3232): 	at kka.a(PG:108)
E/ExperimentLoader( 3232): 	at czp.a(PG:19176)
E/ExperimentLoader( 3232): 	at czp.a(PG:9081)
E/ExperimentLoader( 3232): 	at czq.run(PG:1686),
E/ExperimentLoader( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3232): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3232): ,	at jdj.a(PG:1125)
E/ExperimentLoader( 3232): 	at jdm.a(PG:77)
E/ExperimentLoader( 3232): 	... 15 more
E/ExperimentLoader( 3232): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3232): 	at fal.a(PG:38)
E/ExperimentLoader( 3232): 	,at jdj.a(PG:4089)
E/ExperimentLoader( 3232): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 601634, reason: 10074, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,V/KeepSync( 3934): Connecting to GoogleApiClient
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1771): Handling authorization failure
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1771): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1771): 	... 7 more
,V/KeepSync( 3934): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3934): IOException
E/KeepSync( 3934): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3934): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3934): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3934): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3934): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3934): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3934): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3934): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3934): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3934): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3934): 	... 10 more
W/KeepSync( 3934): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 645646, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,I/BooksSync( 3985): Starting books sync for 61035162, extras: ade
,I/art     (  820): Explicit concurrent mark sweep GC freed 38887(1752KB) AllocSpace objects, 12(474KB) LOS objects, 31% free, 34MB/50MB, paused 3.220ms total 102.500ms
,I/BooksConfig( 3985): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3985): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3985): Soft error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3985): Sync error
,E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3985): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 668086, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3094): [310] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1128): Explicit concurrent mark sweep GC freed 55804(2MB) AllocSpace objects, 20(2MB) LOS objects, 36% free, 27MB/43MB, paused 1.501ms total 43.114ms
,W/ExperimentUpdateService( 3094): [310] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3094): [310] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3094): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3094): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3094): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3094): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  820): Start proc 4226:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4226): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4226):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4226):   adb logcat -s GAv4
,W/GAv4    ( 4226): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4226): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4226): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Killing 3448:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,I/EventLogService( 1771): Opted in for usage reporting
,I/EventLogService( 1771): Aggregate from 1454969953882 (log), 1454969953777 (data)
,W/EventLogAggregator( 1771): Unknown tag: snet_gcore
W/EventLogAggregator( 1771): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1771): dumping service [account]
,D/GCM     ( 1128): Message class com.google.f.a.a.i
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3232): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3232): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3232): 	at jdm.a(PG:82)
E/HttpOperation( 3232): 	at jcs.o(PG:406)
E/HttpOperation( 3232): 	at jcn.a(PG:1379)
E/HttpOperation( 3232): 	at jcs.i(PG:143)
E/HttpOperation( 3232): 	at blb.a(PG:3937)
E/HttpOperation( 3232): 	at czp.a(PG:18188)
E/HttpOperation( 3232): 	at czp.a(PG:9081)
E/HttpOperation( 3232): 	at czq.run(PG:1686)
E/HttpOperation( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3232): 	at jdj.a(PG:4091)
E/HttpOperation( 3232): 	at jdj.a(PG:1125)
E/HttpOperation( 3232): 	at jdm.a(PG:77)
E/HttpOperation( 3232): 	... 12 more
E/HttpOperation( 3232): Caused by: faj: BadAuthentication
E/HttpOperation( 3232): 	at fal.a(PG:38)
E/HttpOperation( 3232): 	at jdj.a(PG:4089)
E/HttpOperation( 3232): 	... 14 more
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3232): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3232): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3232): 	at jdm.a(PG:82)
E/HttpOperation( 3232): 	at jcs.o(PG:406)
E/HttpOperation( 3232): 	at jcn.a(PG:1379)
E/HttpOperation( 3232): 	at jcs.i(PG:143)
E/HttpOperation( 3232): 	at hec.a(PG:42)
E/HttpOperation( 3232): 	at hee.a(PG:102)
E/HttpOperation( 3232): 	at czr.a(PG:65)
E/HttpOperation( 3232): 	at kka.a(PG:108)
E/HttpOperation( 3232): 	at czp.a(PG:19176)
E/HttpOperation( 3232): 	at czp.a(PG:9081)
E/HttpOperation( 3232): 	at czq.run(PG:1686)
E/HttpOperation( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3232): 	at jdj.a(PG:4091)
E/HttpOperation( 3232): 	at jdj.a(PG:1125)
E/HttpOperation( 3232): 	at jdm.a(PG:77)
E/HttpOperation( 3232): 	... 15 more
E/HttpOperation( 3232): Caused by: faj: BadAuthentication
E/HttpOperation( 3232): 	at fal.a(PG:38)
E/HttpOperation( 3232): 	at jdj.a(PG:4089)
E/HttpOperation( 3232): 	... 17 more
E/ExperimentLoader( 3232): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3232): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3232): 	at jdm.a(PG:82)
E/ExperimentLoader( 3232): 	at jcs.o(PG:406)
E/ExperimentLoader( 3232): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3232): 	at jcs.i(PG:143)
E/ExperimentLoader( 3232): 	at hec.a(PG:42)
E/ExperimentLoader( 3232): 	at hee.a(PG:102)
E/ExperimentLoader( 3232): 	at czr.a(PG:65)
E/ExperimentLoader( 3232): 	at kka.a(PG:108)
E/ExperimentLoader( 3232): 	at czp.a(PG:19176)
E/ExperimentLoader( 3232): 	at czp.a(PG:9081)
E/ExperimentLoader( 3232): 	at czq.run(PG:1686)
E/ExperimentLoader( 3232): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3232): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3232): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3232): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3232): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3232): 	at jdm.a(PG:77)
E/ExperimentLoader( 3232): 	... 15 more
E/ExperimentLoader( 3232): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3232): 	at fal.a(PG:38)
E/ExperimentLoader( 3232): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3232): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1101682, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,V/KeepSync( 3934): Connecting to GoogleApiClient
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1771): Handling authorization failure
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1771): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1771): 	... 7 more
,V/KeepSync( 3934): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3934): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3934): IOException
E/KeepSync( 3934): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3934): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3934): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3934): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3934): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3934): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3934): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3934): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3934): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3934): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3934): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3934): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3934): 	... 10 more
W/KeepSync( 3934): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1189979, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btm  ( 2160): Request to stop oneshot timer with non empty queue
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,I/BooksSync( 3985): Starting books sync for 61035162, extras: ade
,I/art     (  820): Explicit concurrent mark sweep GC freed 41405(1925KB) AllocSpace objects, 8(410KB) LOS objects, 31% free, 34MB/50MB, paused 1.476ms total 91.992ms
,I/BooksConfig( 3985): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3985): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3985): Soft error
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3985): Sync error,
E/BooksSync( 3985): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3985): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3985): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1204836, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/UsageStatsService(  820): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2160): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4338): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4338): CheckJNI is OFF
D/AndroidRuntime( 4338): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  820): Killing 3729:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  820): Skipping PackageSetting{1a459f2e com.example.hello/10273} due to missing metadata
I/WindowState(  820): WIN DEATH: Window{4025ea4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/BtGatt.GattService( 2160): Binder is dead - unregistering client (5)!
D/WifiService(  820): Client connection lost with reason: 4
D/BtGatt.GattService( 2160): Binder is dead - unregistering client (6)!
D/BtGatt.GattService( 2160): stopScan() - queue size =1
D/BtGatt.AdvertiseManager( 2160): message : 1
D/BtGatt.AdvertiseManager( 2160): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2160): app died - unregistering client : 6
D/BtGatt.GattService( 2160): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2160): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2160): stop scan
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2160): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.GattService( 2160): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.ScanManager( 2160): app died, unregister client - 5
D/BtGatt.GattService( 2160): Client app is not null!
D/BtGatt.GattService( 2160): unregisterClient() - clientIf=6
D/BtGatt.GattService( 2160): unregisterClient() - clientIf=5
E/BluetoothServiceJni( 2160): An exception was thrown by callback 'btgattc_multiadv_disable_cb'.
E/BluetoothServiceJni( 2160): android.os.DeadObjectException
E/BluetoothServiceJni( 2160): 	at android.os.BinderProxy.transactNative(Native Method)
E/BluetoothServiceJni( 2160): 	at android.os.BinderProxy.transact(Binder.java:496)
E/BluetoothServiceJni( 2160): 	at android.bluetooth.IBluetoothGattCallback$Stub$Proxy.onMultiAdvertiseCallback(IBluetoothGattCallback.java:874)
E/BluetoothServiceJni( 2160): 	at com.android.bluetooth.gatt.GattService.onAdvertiseInstanceDisabled(GattService.java:1233)
W/ActivityManager(  820): Force removing ActivityRecord{294aca7b u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
V/ActivityManager(  820): Display changed displayId=0
I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
W/ActivityManager(  820): Spurious death for ProcessRecord{3703a211 3729:com.test.thalitest/u0a265}, curProc for 3729: null
I/Keyboard.Facilitator( 1226): resetDictionaries() : en_US
D/BuaReceiver( 3391): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator.DecoderInitializer( 1226): run()
I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
I/Decoder ( 1226): createOrResetDecoder
D/TaskPersister(  820): removeObsoleteFile: deleting file=28_task.xml
I/art     ( 1066): Explicit concurrent mark sweep GC freed 72875(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 1.341ms total 52.524ms
I/ActivityManager(  820): Start proc 4353:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     ( 1499): Explicit concurrent mark sweep GC freed 2704(192KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 1.370ms total 103.068ms
I/ConfigService( 1128): onCreate
W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3729 uid 10265
I/art     (  820): Explicit concurrent mark sweep GC freed 12549(929KB) AllocSpace objects, 9(332KB) LOS objects, 31% free, 34MB/50MB, paused 8.048ms total 109.497ms
I/art     (  820): WaitForGcToComplete blocked for 26.617ms for cause Explicit
I/Keyboard.Facilitator( 1226): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1226): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1226): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1226): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1226): run() : Loading LM = contacts
W/LocationOracleImpl( 1499): Best location was null
I/HotwordRecognitionRnr( 1499): Starting hotword detection.
I/art     ( 1358): Explicit concurrent mark sweep GC freed 4990(364KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 694us total 29.116ms
I/MicrophoneInputStream( 1499): mic_starting com.google.android.apps.gsa.speech.audio.u@35885c2a
I/AudioFlinger(  357): AudioFlinger's thread 0xb4cd0000 ready to run
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1226): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1226): run() : Loading LM = history
I/MicrophoneInputStream( 1499): mic_started com.google.android.apps.gsa.speech.audio.u@35885c2a
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1226): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1226): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1226): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1226): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1226): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1226): run()
I/StatsUtilsManager( 1226): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1226): shouldRecordStats() = Too Soon
D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/VoicemailCleanupService( 4353): Cleaning up data for package: com.test.thalitest
I/ContactLocale( 4353): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  820): Start proc 4390:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/art     (  820): Explicit concurrent mark sweep GC freed 5524(244KB) AllocSpace objects, 1(110KB) LOS objects, 31% free, 34MB/50MB, paused 3ms total 152.836ms
I/HotwordWorker( 1499): onReady
D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@dcd18ed}
E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=50.50 rxSuccessRate=64.75 targetRoamBSSID=any RSSI=-54
I/ActivityManager(  820): Start proc 4411:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 606us total 12.767ms
E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=30.25 rxSuccessRate=137.88 targetRoamBSSID=any RSSI=-54
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 8.528ms
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 8.591ms
I/art     ( 4338): System.exit called, status: 0
I/AndroidRuntime( 4338): VM exiting with result code 0.
W/ContextImpl( 4411): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660671251
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/NetworkScheduler.SchedulerReceiver( 1128): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1128): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  820): Killing 2430:com.google.android.calendar/u0a37 (adj 15): empty #17
I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
D/Launcher.Workspace( 1358): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1358): 11683562 - stripEmptyScreens()
V/GoogleAuthProtoRequest( 3094): [311] a.<init>: mAccountName set to: thalitester@gmail.com
E/SQLiteLog( 1358): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1771): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1771): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1771): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1771): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1771): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/UpdateIcingCorporaServi( 1499): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/LocationSettingsChecker( 1771): Removing dialog suppression flag for package com.test.thalitest
W/Launcher( 1358): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@6206055 new=com.google.android.velvet.VelvetApplication@6206055
E/SQLiteLog( 1358): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 1771): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1771): Process: com.google.android.gms, PID: 1771
E/AndroidRuntime( 1771): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1771): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1771): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1771): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1771): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1771): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1771): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1771): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1771): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1771): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1771): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1771): disk I/O error (code 3850)
E/DriveAsyncService( 1771): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1771): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1771): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1771): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1771): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1771): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1771): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1771): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1771): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1771): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1771): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1771): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1771): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 1771): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1771): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1771): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1771): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1771): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1771): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1771): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1771): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1771): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1771): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1771): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1771): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1771): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1771): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1771): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1771): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1771): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1771): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1771): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1771): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1771): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1771): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1771): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1771): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1771): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1771): Sending signal. PID: 1771 SIG: 9
E/SQLiteLog( 1499): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/GLSUser ( 1128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/art     ( 1799): Explicit concurrent mark sweep GC freed 16781(986KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 935us total 35.787ms
I/ActivityManager(  820): Start proc 4445:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/DataBuffer( 1799): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3f6ed0ee)
E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
I/ActivityManager(  820): Start proc 4463:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
E/lowmemorykiller(  277): Error writing /proc/1771/oom_score_adj; errno=22
E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  820): Failure sending service ComponentInfo{com.google.android.gms/com.google.android.location.util.PreferenceService} to connection android.os.BinderProxy@183b02e8 (in com.google.android.gms)
W/ActivityManager(  820): android.os.TransactionTooLargeException
W/ActivityManager(  820): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  820): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  820): 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
W/ActivityManager(  820): 	at com.android.server.am.ActiveServices.publishServiceLocked(ActiveServices.java:885)
W/ActivityManager(  820): 	at com.android.server.am.ActivityManagerService.publishService(ActivityManagerService.java:15342)
W/ActivityManager(  820): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:978)
W/ActivityManager(  820): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  820): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager(  820): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  820): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/WifiService(  820): Client connection lost with reason: 4
W/ResourcesManager( 4445): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4445): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/OpenGLRenderer(  820): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  820): Validating map...
I/MultiDex( 4445): VM with version 2.1.0 has multidex support
I/MultiDex( 4445): install
I/MultiDex( 4445): VM has multidex support, MultiDex support library is disabled.
V/GLSActivity( 1128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  820): Start proc 4482:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
I/ActivityManager(  820): Process com.google.android.gms (pid 1771) has died
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
E/SharedPreferencesImpl( 1499): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 1499): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1499): Process: com.google.android.googlequicksearchbox:search, PID: 1499
E/AndroidRuntime( 1499): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1499): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1499): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1499): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1499): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1499): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1499): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1499): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1499): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1499): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1499): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1499): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1499): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1499): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1499): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1499): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1499): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1499): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1499): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1499): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1499): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
V/JNIHelp ( 4445): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ExperimentUpdateService( 3094): [311] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3094): [311] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3094): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3094): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3094): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3094): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3094): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3094): 	at com.a.a.k.run(SourceFile:110)
E/SQLiteDatabase( 1128): Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.
E/SQLiteDatabase( 1128): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1128): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1128): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1128): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1128): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1128): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1128): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1128): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1128): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1128): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1128): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1128): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1128): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1128): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1128): 	at com.google.android.gms.gcm.nts.n.a(SourceFile:168)
E/SQLiteDatabase( 1128): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:564)
E/SQLiteDatabase( 1128): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:54)
E/SQLiteDatabase( 1128): 	at com.google.android.gms.gcm.nts.l.a(SourceFile:271)
E/SQLiteDatabase( 1128): 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:181)
E/SQLiteDatabase( 1128): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1128): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1128): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 1128): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 1128): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 1128): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 1128): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
I/OpenGLRenderer(  820): Initialized EGL, version 1.4
D/AndroidRuntime( 1128): Shutting down VM
E/AndroidRuntime( 1128): FATAL EXCEPTION: main
E/AndroidRuntime( 1128): Process: com.google.process.gapps, PID: 1128
E/AndroidRuntime( 1128): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1128): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1128): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 1128): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 1128): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1128): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 1128): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 1128): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 1128): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 1128): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 1128): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 1128): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 1128): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 1128): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 1128): 	at com.google.android.gms.gcm.nts.n.a(SourceFile:168)
E/AndroidRuntime( 1128): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:564)
E/AndroidRuntime( 1128): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:54)
E/AndroidRuntime( 1128): 	at com.google.android.gms.gcm.nts.l.a(SourceFile:271)
E/AndroidRuntime( 1128): 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:181)
E/AndroidRuntime( 1128): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1128): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1128): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 1128): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1128): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1128): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 1128): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/OpenGLRenderer(  820): Enabling debug mode 0
E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
W/InputMethodManagerService(  820): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@18eb23eb attribute=null, token = android.os.BinderProxy@b2e3899
I/ProviderInstaller( 4445): Installed default security provider GmsCore_OpenSSL
I/OpenGLRenderer(  820): Initialized EGL, version 1.4
I/ActivityManager(  820): Start proc 4502:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
W/NativeLibraryUtils( 4445): Failed to open lock file
W/NativeLibraryUtils( 4445): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4445): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4445): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4445): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4445): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4445): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4445): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4445): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4445): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4445): 	... 3 more
I/ActivityManager(  820): Killing 3050:com.google.android.music:main/u0a66 (adj 15): empty #17
W/ResourcesManager( 4502): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4502): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 4502): VM with version 2.1.0 has multidex support
I/MultiDex( 4502): install
I/MultiDex( 4502): VM has multidex support, MultiDex support library is disabled.
I/HotwordDetector( 1499): Closing mic
I/MicrophoneInputStream( 1499): mic_close com.google.android.apps.gsa.speech.audio.u@35885c2a
I/art     ( 1128): Explicit concurrent mark sweep GC freed 55938(2MB) AllocSpace objects, 12(1134KB) LOS objects, 37% free, 27MB/43MB, paused 1.366ms total 42.875ms
E/Search.SharedPreferencesProto( 1499): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
E/SQLiteDatabase( 4502): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4502): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4502): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4502): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4502): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 4502): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 4502): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4502): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4502): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4502): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4502): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4502): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4502): 	at java.lang.Thread.run(Thread.java:818)
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
E/SQLiteDatabase( 4502): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4502): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4502): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4502): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4502): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 4502): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 4502): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4502): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4502): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4502): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4502): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4502): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4502): 	at java.lang.Thread.run(Thread.java:818)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1499): Stopping hotword detection.
I/HotwordRecognitionRnr( 1499): Hotword detection finished
V/JNIHelp ( 4502): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/GAv4    ( 4463): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4463):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4463):   adb logcat -s GAv4
W/GAv4    ( 4463): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/ProviderInstaller( 4502): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4502): Failed to open lock file
W/NativeLibraryUtils( 4502): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4502): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4502): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4502): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4502): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4502): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4502): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4502): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4502): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4502): 	... 3 more
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4463): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4463): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4463): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
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
I/ActivityManager(  820): Killing 3792:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
E/GAv4    ( 4463): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4463): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4463): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4463): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
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
E/native  ( 1226): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1226): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1226): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1226): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
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
E/native  ( 1226): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1226): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1226): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1226): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/SQLiteDatabase( 4502): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 4502): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnection.open(SQLi,teConnection.java:193)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4502): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4502): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4502): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteDatabase( 4502): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4502): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4502): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 4502): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 4502): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteDatabase( 4502): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteDatabase( 4502): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4502): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4502): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4502): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4502): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4502): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 4502): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 4502): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4502): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4502): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4502): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4502): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4502): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4502): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4502): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4502): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4502): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4502): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4502): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4502): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4502): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4502): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteOpenHelper( 4502): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteOpenHelper( 4502): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteOpenHelper( 4502): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteOpenHelper( 4502): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteOpenHelper( 4502): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteOpenHelper( 4502): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteOpenHelper( 4502): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteOpenHelper( 4502): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4502): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 4502): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4502): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4502): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 4502): Opened reminders.db in read-only mode
I/Icing   ( 4502): Storage manager: low false usage 1.98MB avail 20.74GB capacity 22.09GB
W/ResourcesManager( 4463): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4463): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  820): Start proc 4556:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/GAv4-SVC( 4502): Google Analytics 7.8.99 is starting up.
E/SQLiteDatabase( 4502): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 4502): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4502): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4502): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4502): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4502): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/SQLiteDatabase( 4502): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 4502): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 4502): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4502): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4502): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4502): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4502): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4502): 	at java.lang.Thread.run(Thread.java:818)

```
