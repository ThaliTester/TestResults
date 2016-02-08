#### Test 581356550b07fff_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/CheckinService( 1770): Done disabling old GoogleServicesFramework version
,I/GAV2    ( 3564): Thread[GAThread,5,main]: No campaign data found.
D/AndroidRuntime( 3740): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3740): CheckJNI is OFF
D/AndroidRuntime( 3740): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{5f1e4bf token=Token{1e93ade ActivityRecord{4f3aa19 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3740): Shutting down VM
V/WindowManager(  822): Adding window Window{31c2d078 u0 Starting com.test.thalitest} at 2 of 7 (after Window{2a23158e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1505): Closing mic
I/MicrophoneInputStream( 1505): mic_close com.google.android.apps.gsa.speech.audio.u@2caf6534
I/ActivityManager(  822): Start proc 3756:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1505): Stopping hotword detection.
I/HotwordRecognitionRnr( 1505): Hotword detection finished
I/ActivityManager(  822): Killing 3309:com.google.android.deskclock/u0a44 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660384531
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3756): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3756): Time to load native libraries: 4 ms (timestamps 7552-7556)
,I/LibraryLoader( 3756): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3756): Binding Chromium to main looper Looper (main, tid 1) {21901653}
I/LibraryLoader( 3756): Expected native library version number "",actual native library version number ""
,I/chromium( 3756): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3756): Initializing chromium process, singleProcess=true,
W/art     ( 3756): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3756): ApplicationContext is null in ApplicationStatus
,W/chromium( 3756): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3756): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3756): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3756): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/BluetoothManagerService(  822): Message: 20
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7b21e9a:true
,W/art     ( 3756): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3756): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3756): CordovaWebView is running on device made by: motorola
,W/art     ( 3756): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3756): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3756): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3756): Validating map...
,V/WindowManager(  822): Adding window Window{109f624a u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{31c2d078 u0 Starting com.test.thalitest})
,W/chromium( 3756): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3756): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3756): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +680ms
,I/Keyboard.Facilitator( 1228): onFinishInput()
,W/BindingManager( 3756): Cannot call determinedVisibility() - never saw a connection for the pid: 3756
,D/JsMessageQueue( 3756): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  822): Killing 3082:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,D/jxcore_app_log( 3756): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576390144
,I/chromium( 3756): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  822): Killing 3024:com.android.settings/1000 (adj 15): empty #17
,W/jxcore-log( 3756): Initializing JXcore engine
W/jxcore-log( 3756): JXcore engine is ready
,W/Thread-421( 3809): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10653]" dev="sockfs" ino=10653 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-421( 3809): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
W/Thread-421( 3809): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9790]" dev="sockfs" ino=9790 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-421( 3809): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23687]" dev="sockfs" ino=23687 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3756): Starting JXcore engine,
,W/jxcore-log( 3756): Platform android,
W/jxcore-log( 3756): 
W/jxcore-log( 3756): Process ARCH arm,
W/jxcore-log( 3756): 
,I/jxcore-log( 3756): JXcore Cordova bridge is ready!,
I/jxcore-log( 3756): 
,W/jxcore-log( 3756): JXcore engine is started
,I/jxcore-log( 3756): Toggling radios to true
I/jxcore-log( 3756): 
,D/BluetoothAdapter( 3756): enable(): BT is already enabled..!,
,D/WifiService(  822): New client listening to asynchronous messages
D/WifiService(  822): setWifiEnabled: true pid=3756, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3756): Radios toggled
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): My device name is: motorola-Nexus 6
I/jxcore-log( 3756): ,
,I/wpa_supplicant( 1122): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1270): Read error: ssl=0xb4888e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1270): SSL shutdown failed: ssl=0xb4888e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost,
E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting,
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  822): MasterInitialState.processMessage what=3
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  822): MasterInitialState.processMessage what=3
I/NetworkMonitor( 3043): type=WIFI subType= reason=null isConnected=false
,E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,V/MusicLeanback( 3043): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1333): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1333): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): will read network variables netId=0
,I/ActivityManager(  822): Start proc 3818:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
E/GpsLocationProvider(  822): No APN found to select.
,E/WifiConfigStore(  822): will read network variables netId=0
,D/PhoneInterfaceManager( 1333): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1333): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,I/ActivityManager(  822): Start proc 3844:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  822): Killing 2552:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/SprintDMReceiver( 3844): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3844): simOperator:  IMSI: null
,D/SprintDMReceiver( 3844): Not Sprint UICC, don't do anything.
,I/ActivityManager(  822): Killing 3388:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/SystemUpdateService( 1770): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1770): onCreate
,D/SystemUpdateService( 1770): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1770): active receiver: enabled
,I/SystemUpdateService( 1770): showing system update notification
I/iu.Environment( 1770): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1770): num queued entries: 0,
I/iu.UploadsManager( 1770): num updated entries: 0
I/iu.SyncManager( 1770): NEXT; no task
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1770): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/Babel   ( 3631): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1770): retry (wakeup: false) in 3599931 ms
,I/ActivityManager(  822): Start proc 3864:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1770): onDestroy
,I/GAv4    ( 3864): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3864):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3864):   adb logcat -s GAv4
,W/GAv4    ( 3864): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3864): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3864): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3864): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3864): Time to load native libraries: 4 ms (timestamps 1544-1548)
I/LibraryLoader( 3864): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3864): Binding Chromium to main looper Looper (main, tid 1) {f9f4776}
,I/LibraryLoader( 3864): Expected native library version number "",actual native library version number ""
,I/chromium( 3864): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3864): Initializing chromium process, singleProcess=true
,W/art     ( 3864): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3864): ApplicationContext is null in ApplicationStatus
,W/chromium( 3864): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3864): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3864): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3864): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3864): Requires BLUETOOTH permission
,I/NSApplication( 3864): Starting up...
,I/ActivityManager(  822): Start proc 3920:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  822): Killing 3408:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3455:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/wpa_supplicant( 1122): wlan0: Trying to associate with SSID 'NG7005g'
,V/MusicLeanback( 3043): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,D/SprintDMReceiver( 3844): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3844): simOperator:  IMSI: null
D/SprintDMReceiver( 3844): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1770): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1770): onCreate
,D/SystemUpdateService( 1770): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1770): active receiver: enabled
,I/SystemUpdateService( 1770): showing system update notification
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 1770): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1770): retry (wakeup: false) in 3599953 ms
,D/SystemUpdateService( 1770): onDestroy
,I/wpa_supplicant( 1122): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1122): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1122): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 157
E/WifiStateMachine(  822):  RSSI mgmt: -53
E/WifiStateMachine(  822):  BE :  rx=137 tx=127 lost=0 retries=1
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 8784 tx_time=203 rx_time=403 scan_time=0
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/dhcpcd  ( 3953): version 5.5.6 starting
,I/dhcpcd  ( 3953): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{dae456d u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/dhcpcd  ( 3953): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/ActivityManager(  822): Killing 1431:android.process.acore/u0a5 (adj 15): empty #17
,I/dhcpcd  ( 3953): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3756): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3756): 
,I/ActivityManager(  822): Killing 3593:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 101
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
,D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101],
,D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3043): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1333): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1333): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
V/MusicLeanback( 3043): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMReceiver( 3844): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3844): simOperator:  IMSI: null
D/SprintDMReceiver( 3844): Not Sprint UICC, don't do anything.
I/SystemUpdateService( 1770): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1770): onCreate
,D/SystemUpdateService( 1770): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1770): active receiver: enabled
,I/SystemUpdateService( 1770): showing system update notification
,I/iu.Environment( 1770): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1770): num queued entries: 0
,I/iu.UploadsManager( 1770): num updated entries: 0
I/iu.SyncManager( 1770): NEXT; no task
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  822): skipping global notification
I/Kids    ( 1770): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,V/SystemUpdateService( 1770): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1770): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 16:52:16 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454950336919], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454950336900]}
,D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
,I/art     (  822): Explicit concurrent mark sweep GC freed 51542(2MB) AllocSpace objects, 11(270KB) LOS objects, 32% free, 33MB/49MB, paused 1.471ms total 75.463ms
,I/Babel   ( 3631): connection state changed from DISCONNECTED to CONNECTED
,V/Herrevad( 1770): NQAS connected
,I/jxcore-log( 3756): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3756): 
,I/ActivityManager(  822): Start proc 3999:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1270): Connected
,D/GCM     ( 1270): Message class com.google.f.a.a.p
,E/HttpOperation( 3218): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3218): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3218): 	at jdm.a(PG:82)
E/HttpOperation( 3218): 	at jcs.o(PG:406)
E/HttpOperation( 3218): 	at jcn.a(PG:1379)
E/HttpOperation( 3218): 	at jcs.i(PG:143)
E/HttpOperation( 3218): 	at blb.a(PG:3937)
E/HttpOperation( 3218): 	at czp.a(PG:18188)
E/HttpOperation( 3218): 	at czp.a(PG:9081)
E/HttpOperation( 3218): 	at czq.run(PG:1686)
E/HttpOperation( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3218): 	at jdj.a(PG:4091)
E/HttpOperation( 3218): 	at jdj.a(PG:1125)
E/HttpOperation( 3218): 	at jdm.a(PG:77)
E/HttpOperation( 3218): 	... 12 more
E/HttpOperation( 3218): Caused by: faj: BadAuthentication
E/HttpOperation( 3218): 	at fal.a(PG:38)
E/HttpOperation( 3218): 	at jdj.a(PG:4089)
E/HttpOperation( 3218): 	... 14 more
,I/jxcore-log( 3756): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3756): 
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3218): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3218): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3218): 	at jdm.a(PG:82)
E/HttpOperation( 3218): 	at jcs.o(PG:406)
E/HttpOperation( 3218): 	at jcn.a(PG:1379)
E/HttpOperation( 3218): 	at jcs.i(PG:143)
E/HttpOperation( 3218): 	at hec.a(PG:42)
E/HttpOperation( 3218): 	at hee.a(PG:102)
E/HttpOperation( 3218): 	at czr.a(PG:65)
E/HttpOperation( 3218): 	at kka.a(PG:108)
E/HttpOperation( 3218): 	at czp.a(PG:19176)
E/HttpOperation( 3218): 	at czp.a(PG:9081)
E/HttpOperation( 3218): 	at czq.run(PG:1686)
E/HttpOperation( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3218): 	at jdj.a(PG:4091)
E/HttpOperation( 3218): 	at jdj.a(PG:1125)
E/HttpOperation( 3218): 	at jdm.a(PG:77)
E/HttpOperation( 3218): 	... 15 more
E/HttpOperation( 3218): Caused by: faj: BadAuthentication
E/HttpOperation( 3218): 	at fal.a(PG:38)
E/HttpOperation( 3218): 	at jdj.a(PG:4089)
E/HttpOperation( 3218): 	... 17 more
E/ExperimentLoader( 3218): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3218): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3218): 	at jdm.a(PG:82)
E/ExperimentLoader( 3218): 	at jcs.o(PG:406)
E/ExperimentLoader( 3218): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3218): 	at jcs.i(PG:143)
E/ExperimentLoader( 3218): 	at hec.a(PG:42)
E/ExperimentLoader( 3218): 	at hee.a(PG:102)
E/ExperimentLoader( 3218): 	at czr.a(PG:65)
E/ExperimentLoader( 3218): 	at kka.a(PG:108)
E/ExperimentLoader( 3218): 	at czp.a(PG:19176)
E/ExperimentLoader( 3218): 	at czp.a(PG:9081)
E/ExperimentLoader( 3218): 	at czq.run(PG:1686)
E/ExperimentLoader( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3218): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3218): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3218): 	at jdm.a(PG:77)
E/ExperimentLoader( 3218): 	... 15 more
E/ExperimentLoader( 3218): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3218): 	at fal.a(PG:38)
E/ExperimentLoader( 3218): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3218): 	... 17 more
,I/art     ( 1270): Explicit concurrent mark sweep GC freed 33321(1879KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 894us total 24.954ms
,I/jxcore-log( 3756): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3756): 
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 74795, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3756): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3756): 
,V/KeepSync( 3999): Connecting to GoogleApiClient
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3999): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3999): IOException
E/KeepSync( 3999): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3999): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3999): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3999): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3999): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3999): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3999): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3999): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3999): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3999): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3999): 	... 10 more
W/KeepSync( 3999): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 75118, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3495): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3495): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3495): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  822): Killing 3535:com.google.android.gms:car/u0a11 (adj 15): empty #17
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.66 rxSuccessRate=8.02 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3756): Test app app.js loaded
I/jxcore-log( 3756): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10e8d23 added. We now have 1 listener(s)
,I/chromium( 3756): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3756): BLE advertisement is supported
I/jxcore-log( 3756): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.83 rxSuccessRate=6.51 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.05 rxSuccessRate=4.97 targetRoamBSSID=any RSSI=-52
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3495): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3495): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3495): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  822): Start proc 4039:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/GAV2    ( 4039): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4039): Created application version: 3.6.8 (30608)
,I/BooksSync( 4039): Starting books sync for 61035162, extras: ade
,I/art     ( 1270): Explicit concurrent mark sweep GC freed 17517(981KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 26MB/42MB, paused 1.555ms total 50.408ms
,I/art     (  822): Explicit concurrent mark sweep GC freed 38890(1787KB) AllocSpace objects, 7(112KB) LOS objects, 32% free, 33MB/49MB, paused 1.486ms total 57.415ms
,I/BooksConfig( 4039): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4039): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4039): Soft error
E/BooksSync( 4039): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 4039): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4039): Sync error
E/BooksSync( 4039): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4039): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4039): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 76860, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 3564:com.google.android.gm/u0a78 (adj 15): empty #17
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3218): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3218): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3218): 	at jdm.a(PG:82)
E/HttpOperation( 3218): 	at jcs.o(PG:406)
E/HttpOperation( 3218): 	at jcn.a(PG:1379)
E/HttpOperation( 3218): 	at jcs.i(PG:143)
E/HttpOperation( 3218): 	at blb.a(PG:3937)
E/HttpOperation( 3218): 	at czp.a(PG:18188)
E/HttpOperation( 3218): 	at czp.a(PG:9081)
E/HttpOperation( 3218): 	at czq.run(PG:1686)
E/HttpOperation( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/HttpOperation( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3218): 	at jdj.a(PG:4091)
E/HttpOperation( 3218): 	at jdj.a(PG:1125)
E/HttpOperation( 3218): 	at jdm.a(PG:77)
E/HttpOperation( 3218): 	... 12 more
E/HttpOperation( 3218): Caused by: faj: BadAuthentication
E/HttpOperation( 3218): 	at fal.a(PG:38)
E/HttpOperation( 3218): 	at jdj.a(PG:4089)
E/HttpOperation( 3218): 	... 14 more
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3218): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3218): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3218): 	at jdm.a(PG:82)
E/HttpOperation( 3218): 	at jcs.o(PG:406)
E/HttpOperation( 3218): 	at jcn.a(PG:1379)
E/HttpOperation( 3218): 	at jcs.i(PG:143)
E/HttpOperation( 3218): 	at hec.a(PG:42)
E/HttpOperation( 3218): 	at hee.a(PG:102)
E/HttpOperation( 3218): 	at czr.a(PG:65)
E/HttpOperation( 3218): 	at kka.a(PG:108)
E/HttpOperation( 3218): 	at czp.a(PG:19176)
E/HttpOperation( 3218): 	at czp.a(PG:9081)
E/HttpOperation( 3218): 	at czq.run(PG:1686)
E/HttpOperation( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3218): 	at jdj.a(PG:4091)
E/HttpOperation( 3218): 	at jdj.a(PG:1125)
E/HttpOperation( 3218): 	at jdm.a(PG:77)
E/HttpOperation( 3218): 	... 15 more
E/HttpOperation( 3218): Caused by: faj: BadAuthentication
E/HttpOperation( 3218): 	at fal.a(PG:38)
E/HttpOperation( 3218): 	at jdj.a(PG:4089)
E/HttpOperation( 3218): 	... 17 more
,E/ExperimentLoader( 3218): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3218): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3218): 	at jdm.a(PG:82)
E/ExperimentLoader( 3218): 	at jcs.o(PG:406)
E/ExperimentLoader( 3218): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3218): 	at jcs.i(PG:143)
E/ExperimentLoader( 3218): 	at hec.a(PG:42)
E/ExperimentLoader( 3218): 	at hee.a(PG:102)
E/ExperimentLoader( 3218): 	at czr.a(PG:65)
E/ExperimentLoader( 3218): 	at kka.a(PG:108)
E/ExperimentLoader( 3218): 	at czp.a(PG:19176)
E/ExperimentLoader( 3218): 	at czp.a(PG:9081)
E/ExperimentLoader( 3218): 	at czq.run(PG:1686)
E/ExperimentLoader( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/ExperimentLoader( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3218): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3218): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3218): 	at jdm.a(PG:77)
E/ExperimentLoader( 3218): 	... 15 more
E/ExperimentLoader( 3218): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3218): 	at fal.a(PG:38),
E/ExperimentLoader( 3218): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3218): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 105690, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GAV2    ( 4039): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.38 rxSuccessRate=1.62 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3495): [369] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3495): [369] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3495): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3495): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3495): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1228): run()
I/Keyboard.Facilitator( 1228): flushDynamicLanguageModels()
,I/ConfigService( 1270): onCreate
,I/ConfigService( 1270): onDestroy
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.33 rxSuccessRate=3.01 targetRoamBSSID=any RSSI=-52
,V/KeepSync( 3999): Connecting to GoogleApiClient
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3999): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3999): IOException
E/KeepSync( 3999): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3999): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3999): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3999): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3999): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3999): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3999): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3999): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3999): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3999): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3999): 	... 10 more
W/KeepSync( 3999): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 108109, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3495): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3495): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3495): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.17 rxSuccessRate=3.44 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (501 us)
,D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6082000
I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  822): Display changed displayId=0
,I/kickstart(  874): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  874): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  874): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0,
D/SurfaceControl(  822): Excessive delay in setPowerMode(): 277ms
,I/DreamManagerService(  822): Entering dreamland.
,I/PowerManagerService(  822): Dozing...
,I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1228): onFinishInput()
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): cancelDelayedScan -> 14
,E/native  (  822): do suspend true
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/kickstart(  874): STATUS: Received file 'm9kefs1'
I/kickstart(  874): STATUS: 950272 bytes transferred in 0.998487 seconds
I/kickstart(  874): STATUS: Successfully downloaded files from target 
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  874): STATUS: Sahara protocol completed
,I/art     (  822): Explicit concurrent mark sweep GC freed 49135(2MB) AllocSpace objects, 17(366KB) LOS objects, 31% free, 34MB/50MB, paused 2.714ms total 79.506ms
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3495): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3495): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3495): [1] 5.onFinished: Scheduling replication attempt 5.
,I/BooksSync( 4039): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4039): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4039): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4039): Soft error
E/BooksSync( 4039): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4039): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4039): Sync error
E/BooksSync( 4039): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 4039): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4039): Finished books sync,
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 137244, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1270): Vacuum at: now=1454950446902 tag=VacuumService
,V/GoogleAuthProtoRequest( 3818): [415] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1270): Explicit concurrent mark sweep GC freed 40050(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.322ms total 37.897ms
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1270): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Uploader( 1270): No account for auth token provided
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3495): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3495): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3495): [1] 5.onFinished: Giving up after 6 failures.
,W/ExperimentUpdateService( 3818): [415] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3818): [415] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3818): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3818): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3818): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3818): 	at com.a.a.k.run(SourceFile:110)
,W/Uploader( 1270): No account for auth token provided
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1270): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1270): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1270): 	at com.google.android.gms.auth.p.e(SourceFile:1268),
E/Uploader( 1270): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1270): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1270): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1270): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1270): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1270): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1270): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1270): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1270): No account for auth token provided
,W/Uploader( 1270): No account for auth token provided
,W/Uploader( 1270): No account for auth token provided
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1270): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1270): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1270): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1270): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1270): No account for auth token provided
,W/Uploader( 1270): No account for auth token provided
,W/Uploader( 1270): No account for auth token provided
,W/Uploader( 1270): No account for auth token provided
,W/Uploader( 1270): No account for auth token provided
,W/Uploader( 1270):  no longer exists, so no auth token.
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1270): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1270): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1270): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1270): 	at com.google.android.gms.gcm.am.run(SourceFile:135),
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1270): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1270): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1270): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1270): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1270): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1270): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3218): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3218): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3218): 	at jdm.a(PG:82)
,E/HttpOperation( 3218): 	at jcs.o(PG:406)
E/HttpOperation( 3218): 	,at jcn.a(PG:1379)
E/HttpOperation( 3218): 	,at jcs.i(PG:143)
E/HttpOperation( 3218): 	at blb.a(PG:3937)
E/HttpOperation( 3218): 	at czp.a(PG:18188)
,E/HttpOperation( 3218): 	at czp.a(PG:9081)
E/HttpOperation( 3218): 	at czq.run(PG:1686),
E/HttpOperation( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/HttpOperation( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3218): 	at jdj.a(PG:4091)
E/HttpOperation( 3218): 	at jdj.a(PG:1125)
E/HttpOperation( 3218): 	at jdm.a(PG:77)
E/HttpOperation( 3218): 	... 12 more
E/HttpOperation( 3218): Caused by: faj: BadAuthentication
E/HttpOperation( 3218): 	at fal.a(PG:38)
E/HttpOperation( 3218): 	at jdj.a(PG:4089)
E/HttpOperation( 3218): 	... 14 more
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3218): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3218): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3218): 	at jdm.a(PG:82)
E/HttpOperation( 3218): 	at jcs.o(PG:406)
E/HttpOperation( 3218): 	at jcn.a(PG:1379)
E/HttpOperation( 3218): 	at jcs.i(PG:143)
E/HttpOperation( 3218): 	at hec.a(PG:42)
E/HttpOperation( 3218): 	at hee.a(PG:102)
E/HttpOperation( 3218): 	at czr.a(PG:65)
E/HttpOperation( 3218): 	at kka.a(PG:108)
E/HttpOperation( 3218): 	at czp.a(PG:19176)
E/HttpOperation( 3218): 	at czp.a(PG:9081)
E/HttpOperation( 3218): 	at czq.run(PG:1686)
E/HttpOperation( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3218): 	at jdj.a(PG:4091)
E/HttpOperation( 3218): 	at jdj.a(PG:1125)
E/HttpOperation( 3218): 	at jdm.a(PG:77)
E/HttpOperation( 3218): 	... 15 more
E/HttpOperation( 3218): Caused by: faj: BadAuthentication
E/HttpOperation( 3218): 	at fal.a(PG:38)
E/HttpOperation( 3218): 	at jdj.a(PG:4089)
E/HttpOperation( 3218): 	... 17 more
,E/ExperimentLoader( 3218): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3218): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3218): 	at jdm.a(PG:82)
E/ExperimentLoader( 3218): 	at jcs.o(PG:406),
E/ExperimentLoader( 3218): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3218): 	at jcs.i(PG:143)
E/ExperimentLoader( 3218): 	at hec.a(PG:42)
E/ExperimentLoader( 3218): 	at hee.a(PG:102)
E/ExperimentLoader( 3218): 	at czr.a(PG:65)
E/ExperimentLoader( 3218): 	at kka.a(PG:108)
E/ExperimentLoader( 3218): 	at czp.a(PG:19176)
E/ExperimentLoader( 3218): 	at czp.a(PG:9081)
E/ExperimentLoader( 3218): 	at czq.run(PG:1686)
E/ExperimentLoader( 3218): ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error,
E/ExperimentLoader( 3218): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3218): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3218): 	at jdm.a(PG:77)
E/ExperimentLoader( 3218): 	... 15 more
E/ExperimentLoader( 3218): Caused by: faj: BadAuthentication,
E/ExperimentLoader( 3218): 	at fal.a(PG:38)
E/ExperimentLoader( 3218): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3218): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 166965, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3818): [416] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3818): [416] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3818): [416] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3818): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3818): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3818): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3818): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1228): run()
I/Keyboard.Facilitator( 1228): flushDynamicLanguageModels()
,I/ConfigService( 1270): onCreate
,I/art     (  822): Explicit concurrent mark sweep GC freed 36110(1569KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 2.369ms total 80.677ms
,V/KeepSync( 3999): Connecting to GoogleApiClient,
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1770): Handling authorization failure
,E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
,E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	,at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3999): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3999): IOException
E/KeepSync( 3999): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3999): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3999): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3999): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3999): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3999): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3999): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3999): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3999): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3999): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3999): 	... 10 more
W/KeepSync( 3999): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 200379, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/ConfigService( 1270): onDestroy
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,I/BooksSync( 4039): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4039): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4039): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4039): Soft error
E/BooksSync( 4039): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4039): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4039): Sync error
E/BooksSync( 4039): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4039): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4039): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 228366, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3818): [417] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3818): [417] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3818): [417] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3818): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3818): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3818): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3818): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,I/jxcore-log( 3756): TAP version 13
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # multiplex can send data
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 1 String should be length:200
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # enqueue and run in order
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 2 firstPromise setTimeout
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 3 firstPromise result
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 4 firstPromise testValue
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 5 secondPromise setTimeout
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 6 secondPromise result
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 7 secondPromise testValue
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 8 thirdPromise in promise
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 9 thirdPromise result
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 10 thirdPromise testValue
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # basic
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 11 sane
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # another
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 12 sane
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 13 should be equal
I/jxcore-log( 3756): ,
,I/jxcore-log( 3756): ok 14 null
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 15 (unnamed assert)
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 16 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 17 should not throw
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
,I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 18 (unnamed assert)
I/jxcore-log( 3756): ,
I/jxcore-log( 3756): ok 19 (unnamed assert)
I/jxcore-log( 3756): 
I/jxcore-log( 3756): ok 20 should not throw
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 21 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 22 should be equal
I/jxcore-log( 3756): 
I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown,
I/jxcore-log( 3756): ,
,I/jxcore-log( 3756): ok 23 should be equal,
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # failed to get mobile documents path
,I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown,
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 24 should be equal,
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #init should register the peerAvailabilityChanged event,
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown,
,I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 25 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 26 should be equal
I/jxcore-log( 3756): 
I/jxcore-log( 3756): ok 27 should be equal
I/jxcore-log( 3756): 
I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #init should register the networkChanged event
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 28 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup,
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #startBroadcasting should throw on null device name
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 29 should throw
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 30 should throw
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 31 should throw
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 32 should throw
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #startBroadcasting should throw on negative port
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 33 should throw
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #startBroadcasting should throw on too large port
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 34 should throw
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 35 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 36 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 37 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 38 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 39 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 40 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 41 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 42 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 43 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 44 should be equal
I/jxcore-log( 3756): 
I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 45 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 46 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 47 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3756): ,
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 48 should be equal
I/jxcore-log( 3756): 
I/jxcore-log( 3756): ok 49 should be equal,
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 50 should be equal,
I/jxcore-log( 3756): 
I/jxcore-log( 3756): ok 51 should be equal,
I/jxcore-log( 3756): 
I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 52 should be equal
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): ok 53 should be equal
I/jxcore-log( 3756): 
I/jxcore-log( 3756): # setup
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3756): 
,I/jxcore-log( 3756): # teardown
I/jxcore-log( 3756): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3756): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3756): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3756): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3756): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e44f220 added. We now have 2 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): setDiscoveryMode: BLE_AND_WIFI -> WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3756): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454950573632.3756
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3756): bind: Binding a new listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3756): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3756): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454950573632.3756","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3756): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3756): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3756): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3756): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3756): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3756): start: OK
I/io.jxcore.node.ConnectionHelper( 3756): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454950573632.3756, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3756): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3756): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3756): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3756): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454950573632.3756","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3756): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454950573632.3756","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3756): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454950573632.3756","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3756): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3756): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3756): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3756): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454950573632.3756, mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3756): start: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3756): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3756): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3756): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3756): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3756): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3756): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3756): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3756): 
I/io.jxcore.node.ConnectionHelper( 3756): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3756): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3756): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3756): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3756): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3756): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3756): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3756): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3756): onServerStopped
I/io.jxcore.node.ConnectionHelper( 3756): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3756): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3756): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3756): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3756): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3756): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3756): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3756): clear,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): setState: NOT_STARTED,
I/io.jxcore.node.ConnectionHelper( 3756): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3756): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 3756): 
,I/wpa_supplicant( 1122): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3756): Local services cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3756): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3756): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3756): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3756): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Advertise TX power level: 1, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): 	Scan mode: 1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3756): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e514895 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3756): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3756): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3756): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454950573721.3756
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3756): bind: Binding a new listener
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3756): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3756): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454950573721.3756","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3756): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3756): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3756): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3756): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3756): start: OK
I/io.jxcore.node.ConnectionHelper( 3756): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3756): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3756): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3756): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454950573721.3756, mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3756): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3756): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3756): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3756): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3756): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3756): createAdvertiseData: From: 1454950573721.3756 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3756): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2148): registerClient() - UUID=71da86fc-3f0e-4698-9efe-6fa96fc42002
,D/BtGatt.GattService( 2148): onClientRegistered() - UUID=71da86fc-3f0e-4698-9efe-6fa96fc42002, clientIf=5
,D/BluetoothLeScanner( 3756): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2148): start scan with filters
D/BtGatt.ScanManager( 2148): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3756): setState: State changed from NOT_STARTED to STARTING
,D/BluetoothAdapterService( 2148): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@858fb90
,D/BtGatt.GattService( 2148): registerClient() - UUID=2c24c97b-3139-4aae-bb84-414e63e28530
,D/BtGatt.GattService( 2148): onClientRegistered() - UUID=2c24c97b-3139-4aae-bb84-414e63e28530, clientIf=6
D/BluetoothLeAdvertiser( 3756): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2148): message : 0
,D/BtGatt.GattService( 2148): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2148): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2148): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
D/BtGatt.ScanManager( 2148): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2148): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2148): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/BtGatt.AdvertiseManager( 2148): starting multi advertising
,D/BtGatt.GattService( 2148): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2148): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3756): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3756): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454950573721.3756","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3756): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454950573721.3756","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3756): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454950573721.3756","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3756): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3756): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3756): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): start: OK
,I/io.jxcore.node.ConnectionHelper( 3756): start: OK
I/wpa_supplicant( 1122): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454950573721.3756, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3756): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3756): createAdvertiseData: From: 1454950573721.3756 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3756): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/jxcore-log( 3756): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 3756): 
,I/io.jxcore.node.ConnectionHelper( 3756): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3756): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3756): Shutting down...
D/BtGatt.AdvertiseManager( 2148): message : 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3756): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3756): shutdown
D/BtGatt.AdvertiseManager( 2148): stop advertise for client 6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3756): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3756): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3756): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3756): onServerStopped
,D/BtGatt.GattService( 2148): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2148): Client app is not null!
D/BtGatt.GattService( 2148): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3756): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3756): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2148): registerClient() - UUID=43b96b4c-6395-4cac-81bd-fde61c58a4d2
,D/BtGatt.GattService( 2148): onClientRegistered() - UUID=43b96b4c-6395-4cac-81bd-fde61c58a4d2, clientIf=6
D/BluetoothLeAdvertiser( 3756): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2148): message : 0
,D/BtGatt.AdvertiseManager( 2148): starting multi advertising,
,D/BtGatt.GattService( 2148): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2148): onAdvertiseDataSet() - clientIf=6, status=0,
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3756): setState: State changed from NOT_STARTED to STARTING,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3756): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3756): start: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3756): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3756): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3756): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3756): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3756): stop
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3756): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3756): onIsAdvertiserStartedChanged: true
,D/btif_config_util( 2148): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/art     ( 1270): Explicit concurrent mark sweep GC freed 71284(3MB) AllocSpace objects, 11(962KB) LOS objects, 36% free, 28MB/44MB, paused 1.887ms total 68.666ms
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3218): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3218): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3218): 	at jdm.a(PG:82)
E/HttpOperation( 3218): 	at jcs.o(PG:406)
E/HttpOperation( 3218): 	at jcn.a(PG:1379)
E/HttpOperation( 3218): 	at jcs.i(PG:143)
E/HttpOperation( 3218): 	at blb.a(PG:3937)
E/HttpOperation( 3218): 	at czp.a(PG:18188)
E/HttpOperation( 3218): 	at czp.a(PG:9081)
E/HttpOperation( 3218): 	at czq.run(PG:1686)
E/HttpOperation( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3218): 	at jdj.a(PG:4091)
E/HttpOperation( 3218): 	at jdj.a(PG:1125)
E/HttpOperation( 3218): 	at jdm.a(PG:77)
E/HttpOperation( 3218): 	... 12 more
E/HttpOperation( 3218): Caused by: faj: BadAuthentication
E/HttpOperation( 3218): 	at fal.a(PG:38)
E/HttpOperation( 3218): 	at jdj.a(PG:4089)
E/HttpOperation( 3218): 	... 14 more
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3218): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3218): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3218): 	at jdm.a(PG:82)
E/HttpOperation( 3218): 	at jcs.o(PG:406)
E/HttpOperation( 3218): 	at jcn.a(PG:1379)
E/HttpOperation( 3218): 	at jcs.i(PG:143)
E/HttpOperation( 3218): 	at hec.a(PG:42)
E/HttpOperation( 3218): 	at hee.a(PG:102)
E/HttpOperation( 3218): 	at czr.a(PG:65)
E/HttpOperation( 3218): 	at kka.a(PG:108)
E/HttpOperation( 3218): 	at czp.a(PG:19176)
E/HttpOperation( 3218): 	at czp.a(PG:9081)
E/HttpOperation( 3218): 	at czq.run(PG:1686)
E/HttpOperation( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3218): 	at jdj.a(PG:4091)
E/HttpOperation( 3218): 	at jdj.a(PG:1125)
E/HttpOperation( 3218): 	at jdm.a(PG:77)
E/HttpOperation( 3218): 	... 15 more
E/HttpOperation( 3218): Caused by: faj: BadAuthentication
E/HttpOperation( 3218): 	at fal.a(PG:38)
E/HttpOperation( 3218): 	at jdj.a(PG:4089)
E/HttpOperation( 3218): 	... 17 more
E/ExperimentLoader( 3218): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3218): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3218): 	at jdm.a(PG:82)
E/ExperimentLoader( 3218): 	at jcs.o(PG:406)
E/ExperimentLoader( 3218): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3218): 	at jcs.i(PG:143)
E/ExperimentLoader( 3218): 	at hec.a(PG:42)
E/ExperimentLoader( 3218): 	at hee.a(PG:102)
E/ExperimentLoader( 3218): 	at czr.a(PG:65)
E/ExperimentLoader( 3218): 	at kka.a(PG:108)
E/ExperimentLoader( 3218): 	at czp.a(PG:19176)
E/ExperimentLoader( 3218): 	at czp.a(PG:9081)
E/ExperimentLoader( 3218): 	at czq.run(PG:1686)
E/ExperimentLoader( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3218): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3218): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3218): 	at jdm.a(PG:77)
E/ExperimentLoader( 3218): 	... 15 more
E/ExperimentLoader( 3218): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3218): 	at fal.a(PG:38)
E/ExperimentLoader( 3218): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3218): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 316613, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1270): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1270): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1270): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1270): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1270): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1270): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1270): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3495): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3495): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3495): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3495): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3495): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3495): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3495): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3495): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@339cb5b}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@339cb5b}
,V/KeepSync( 3999): Connecting to GoogleApiClient
,I/art     (  822): Explicit concurrent mark sweep GC freed 33755(1508KB) AllocSpace objects, 10(725KB) LOS objects, 31% free, 34MB/50MB, paused 1.422ms total 89.462ms
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3999): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3999): IOException
E/KeepSync( 3999): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3999): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3999): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3999): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3999): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3999): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3999): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3999): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3999): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3999): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3999): 	... 10 more
,W/KeepSync( 3999): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 355021, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 4039): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4039): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4039): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4039): Soft error
E/BooksSync( 4039): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4039): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4039): Sync error
E/BooksSync( 4039): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4039): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4039): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 381385, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3818): [418] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3818): [418] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3818): [418] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3818): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3818): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3818): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3818): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1122): P2P-FIND-STOPPED 
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,I/ActivityManager(  822): Start proc 4216:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4216): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4216):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4216):   adb logcat -s GAv4
,W/GAv4    ( 4216): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4216): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4216): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3218): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3218): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3218): 	at jdm.a(PG:82)
E/HttpOperation( 3218): 	at jcs.o(PG:406)
E/HttpOperation( 3218): 	at jcn.a(PG:1379)
E/HttpOperation( 3218): 	at jcs.i(PG:143)
E/HttpOperation( 3218): 	at blb.a(PG:3937)
E/HttpOperation( 3218): 	at czp.a(PG:18188)
E/HttpOperation( 3218): 	at czp.a(PG:9081)
E/HttpOperation( 3218): 	at czq.run(PG:1686)
E/HttpOperation( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3218): 	at jdj.a(PG:4091)
E/HttpOperation( 3218): 	at jdj.a(PG:1125)
E/HttpOperation( 3218): 	at jdm.a(PG:77)
E/HttpOperation( 3218): 	... 12 more
E/HttpOperation( 3218): Caused by: faj: BadAuthentication
E/HttpOperation( 3218): 	at fal.a(PG:38)
E/HttpOperation( 3218): 	at jdj.a(PG:4089)
E/HttpOperation( 3218): 	... 14 more
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3218): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3218): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3218): 	at jdm.a(PG:82)
E/HttpOperation( 3218): 	at jcs.o(PG:406)
E/HttpOperation( 3218): 	at jcn.a(PG:1379)
E/HttpOperation( 3218): 	at jcs.i(PG:143)
E/HttpOperation( 3218): 	at hec.a(PG:42)
E/HttpOperation( 3218): 	at hee.a(PG:102)
E/HttpOperation( 3218): 	at czr.a(PG:65)
E/HttpOperation( 3218): 	at kka.a(PG:108)
E/HttpOperation( 3218): 	at czp.a(PG:19176)
E/HttpOperation( 3218): 	at czp.a(PG:9081)
E/HttpOperation( 3218): 	at czq.run(PG:1686)
E/HttpOperation( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3218): 	at jdj.a(PG:4091)
E/HttpOperation( 3218): 	at jdj.a(PG:1125)
E/HttpOperation( 3218): 	at jdm.a(PG:77)
E/HttpOperation( 3218): 	... 15 more
E/HttpOperation( 3218): Caused by: faj: BadAuthentication
E/HttpOperation( 3218): 	at fal.a(PG:38)
E/HttpOperation( 3218): 	at jdj.a(PG:4089)
E/HttpOperation( 3218): 	... 17 more
,E/ExperimentLoader( 3218): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3218): java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3218): 	at jdm.a(PG:82),
E/ExperimentLoader( 3218): 	at jcs.o(PG:406)
E/ExperimentLoader( 3218): ,	at jcn.a(PG:1379)
E/ExperimentLoader( 3218): 	,at jcs.i(PG:143)
,E/ExperimentLoader( 3218): 	at hec.a(PG:42)
,E/ExperimentLoader( 3218): 	,at hee.a(PG:102)
E/ExperimentLoader( 3218): ,	at czr.a(PG:65)
,E/ExperimentLoader( 3218): 	at kka.a(PG:108)
E/ExperimentLoader( 3218): ,	at czp.a(PG:19176)
,E/ExperimentLoader( 3218): 	at czp.a(PG:9081)
E/ExperimentLoader( 3218): ,	at czq.run(PG:1686)
E/ExperimentLoader( 3218): ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
,E/ExperimentLoader( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/ExperimentLoader( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3218): 	at java.lang.Thread.run(Thread.java:818),
E/ExperimentLoader( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3218): ,	at jdj.a(PG:4091)
E/ExperimentLoader( 3218): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3218): 	at jdm.a(PG:77)
E/ExperimentLoader( 3218): 	... 15 more
E/ExperimentLoader( 3218): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3218): 	at fal.a(PG:38)
E/ExperimentLoader( 3218): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3218): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 559033, reason: Periodic, SyncResult: stats [ numIoExceptions: 1],
I/ActivityManager(  822): Killing 2466:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,V/KeepSync( 3999): Connecting to GoogleApiClient
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3999): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3999): IOException
E/KeepSync( 3999): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3999): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3999): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3999): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3999): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3999): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3999): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3999): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3999): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3999): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3999): 	... 10 more
W/KeepSync( 3999): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 636116, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,I/art     (  822): Explicit concurrent mark sweep GC freed 38400(1728KB) AllocSpace objects, 12(474KB) LOS objects, 31% free, 34MB/50MB, paused 2.392ms total 65.700ms
,I/BooksSync( 4039): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4039): GmsCore Version = 7.8.99 (2134222-430)
,I/art     ( 1270): Explicit concurrent mark sweep GC freed 55755(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.443ms total 39.075ms
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4039): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 4039): Soft error
E/BooksSync( 4039): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4039): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4039): Sync error
E/BooksSync( 4039): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4039): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4039): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 658749, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x22
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x88
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x77
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x96
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x88
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x18
E/bt_h4   ( 2148): H4: Unable to acquire buffer for incoming HCI message.
,E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x97
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x19
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x26
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0xc6
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x88
,E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x18
E/bt_h4   ( 2148): H4: Unable to acquire buffer for incoming HCI message.
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3818): [419] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3818): [419] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3818): [419] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3818): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3818): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3818): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3818): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3818): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3818): 	at com.a.a.k.run(SourceFile:110)
,E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x0
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0xdc
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x97
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x19
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x26
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0xc6
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x88
,E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x18,
,E/bt_h4   ( 2148): H4: Unable to acquire buffer for incoming HCI message.,
,E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x1
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x6
,E/bt_h4   ( 2148): H4: Unable to acquire buffer for incoming HCI message.
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x19
,E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x26
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0xc6
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x88
,E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x8
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x7
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0xff
,E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x88
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0xc6
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x26
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x19
,E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x97
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0xdc
E/bt_h4   ( 2148): [h4] Unknown HCI message type drop this byte 0x9f
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/GCM     ( 1270): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3218): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3218): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3218): 	at jdm.a(PG:82)
E/HttpOperation( 3218): 	at jcs.o(PG:406)
E/HttpOperation( 3218): 	at jcn.a(PG:1379)
E/HttpOperation( 3218): 	at jcs.i(PG:143)
E/HttpOperation( 3218): 	at blb.a(PG:3937)
E/HttpOperation( 3218): 	at czp.a(PG:18188)
E/HttpOperation( 3218): 	at czp.a(PG:9081)
E/HttpOperation( 3218): 	at czq.run(PG:1686)
E/HttpOperation( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3218): 	at jdj.a(PG:4091)
E/HttpOperation( 3218): 	at jdj.a(PG:1125)
E/HttpOperation( 3218): 	at jdm.a(PG:77)
E/HttpOperation( 3218): 	... 12 more
E/HttpOperation( 3218): Caused by: faj: BadAuthentication
E/HttpOperation( 3218): 	at fal.a(PG:38)
E/HttpOperation( 3218): 	at jdj.a(PG:4089)
E/HttpOperation( 3218): 	... 14 more
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3218): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3218): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3218): 	at jdm.a(PG:82)
E/HttpOperation( 3218): 	at jcs.o(PG:406)
E/HttpOperation( 3218): 	at jcn.a(PG:1379)
E/HttpOperation( 3218): 	at jcs.i(PG:143)
E/HttpOperation( 3218): 	at hec.a(PG:42)
E/HttpOperation( 3218): 	at hee.a(PG:102)
E/HttpOperation( 3218): 	at czr.a(PG:65)
E/HttpOperation( 3218): 	at kka.a(PG:108)
E/HttpOperation( 3218): 	at czp.a(PG:19176)
E/HttpOperation( 3218): 	at czp.a(PG:9081)
E/HttpOperation( 3218): 	at czq.run(PG:1686)
E/HttpOperation( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3218): 	at jdj.a(PG:4091)
E/HttpOperation( 3218): 	at jdj.a(PG:1125)
E/HttpOperation( 3218): 	at jdm.a(PG:77)
E/HttpOperation( 3218): 	... 15 more
E/HttpOperation( 3218): Caused by: faj: BadAuthentication
E/HttpOperation( 3218): 	at fal.a(PG:38)
E/HttpOperation( 3218): 	at jdj.a(PG:4089)
E/HttpOperation( 3218): 	... 17 more
E/ExperimentLoader( 3218): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3218): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3218): 	at jdm.a(PG:82)
E/ExperimentLoader( 3218): 	at jcs.o(PG:406)
E/ExperimentLoader( 3218): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3218): 	at jcs.i(PG:143)
E/ExperimentLoader( 3218): 	at hec.a(PG:42)
E/ExperimentLoader( 3218): 	at hee.a(PG:102)
E/ExperimentLoader( 3218): 	at czr.a(PG:65)
E/ExperimentLoader( 3218): 	at kka.a(PG:108)
E/ExperimentLoader( 3218): 	at czp.a(PG:19176)
E/ExperimentLoader( 3218): 	at czp.a(PG:9081)
E/ExperimentLoader( 3218): 	at czq.run(PG:1686)
E/ExperimentLoader( 3218): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3218): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3218): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3218): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3218): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3218): 	at jdm.a(PG:77)
E/ExperimentLoader( 3218): 	... 15 more
E/ExperimentLoader( 3218): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3218): 	at fal.a(PG:38)
E/ExperimentLoader( 3218): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3218): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1043395, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,V/KeepSync( 3999): Connecting to GoogleApiClient
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3999): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3999): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3999): IOException
E/KeepSync( 3999): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3999): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3999): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3999): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3999): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3999): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3999): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3999): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3999): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3999): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3999): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3999): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3999): 	... 10 more
W/KeepSync( 3999): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1154570, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 4039): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4039): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1270): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1270): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1270): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1270): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1270): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 4039): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4039): Soft error
E/BooksSync( 4039): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4039): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4039): Sync error
E/BooksSync( 4039): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4039): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4039): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1169715, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,I/art     (  822): Explicit concurrent mark sweep GC freed 42659(1904KB) AllocSpace objects, 8(410KB) LOS objects, 31% free, 34MB/50MB, paused 1.243ms total 76.967ms
,W/bt-btm  ( 2148): Request to stop oneshot timer with non empty queue
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2148): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4385): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4385): CheckJNI is OFF
D/AndroidRuntime( 4385): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 3756:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  822): Skipping PackageSetting{670693f com.example.hello/10273} due to missing metadata
D/BtGatt.GattService( 2148): Binder is dead - unregistering client (5)!
D/BtGatt.GattService( 2148): Binder is dead - unregistering client (6)!
I/WindowState(  822): WIN DEATH: Window{109f624a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  822): Client connection lost with reason: 4
D/BtGatt.GattService( 2148): stopScan() - queue size =1
D/BtGatt.AdvertiseManager( 2148): message : 1
D/BtGatt.AdvertiseManager( 2148): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2148): app died - unregistering client : 6
D/BtGatt.GattService( 2148): unregisterClient() - clientIf=6
E/libprocessgroup(  822): failed to kill 1 processes for processgroup 3756
W/ActivityManager(  822): Force removing ActivityRecord{4f3aa19 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
D/BtGatt.GattService( 2148): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2148): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2148): stop scan
D/BtGatt.ScanManager( 2148): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2148): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2148): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.ScanManager( 2148): app died, unregister client - 5
D/BtGatt.GattService( 2148): onAdvertiseInstanceDisabled() - clientIf=255, status=0
E/BtGatt.ContextMap( 2148): Context not found for ID 255
D/BtGatt.GattService( 2148): unregisterClient() - clientIf=5
V/ActivityManager(  822): Display changed displayId=0
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
D/TaskPersister(  822): removeObsoleteFile: deleting file=28_task.xml
W/ActivityManager(  822): Spurious death for ProcessRecord{534e4ed 3756:com.test.thalitest/u0a265}, curProc for 3756: null
I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1228): resetDictionaries() : en_US
D/BuaReceiver( 3371): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator.DecoderInitializer( 1228): run()
I/Decoder ( 1228): createOrResetDecoder
I/art     ( 1059): Explicit concurrent mark sweep GC freed 71565(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 900us total 50.523ms
I/art     (  822): Explicit concurrent mark sweep GC freed 10615(859KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 5.407ms total 89.514ms
I/art     (  822): WaitForGcToComplete blocked for 89.203ms for cause Explicit
I/ActivityManager(  822): Start proc 4401:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 263us total 12.962ms
I/art     ( 1505): Explicit concurrent mark sweep GC freed 1583(134KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 345us total 111.415ms
W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3756 uid 10265
I/ConfigService( 1270): onCreate
I/Keyboard.Facilitator( 1228): onFinishInput()
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 213us total 9.982ms
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 8.665ms
W/LocationOracleImpl( 1505): Best location was null
I/art     ( 1371): Explicit concurrent mark sweep GC freed 4986(364KB) AllocSpace objects, 11(1298KB) LOS objects, 31% free, 35MB/51MB, paused 725us total 21.717ms
D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/Keyboard.Facilitator.MainLanguageModelLoader( 1228): run()
I/HotwordRecognitionRnr( 1505): Starting hotword detection.
I/MicrophoneInputStream( 1505): mic_starting com.google.android.apps.gsa.speech.audio.u@ff12cac
I/AudioFlinger(  358): AudioFlinger's thread 0xb4d57000 ready to run
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1505): mic_started com.google.android.apps.gsa.speech.audio.u@ff12cac
D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
I/Keyboard.Facilitator.MainLanguageModelLoader( 1228): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run() : Loading LM = contacts
I/art     ( 1270): Explicit concurrent mark sweep GC freed 60623(2MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 875us total 27.623ms
D/VoicemailCleanupService( 4401): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  822): Start proc 4438:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1228): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1228): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1228): run()
I/StatsUtilsManager( 1228): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1228): shouldRecordStats() = Too Soon
I/HotwordWorker( 1505): onReady
D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2ebb2c3e}
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=69.25 rxSuccessRate=92.75 targetRoamBSSID=any RSSI=-52
I/art     (  822): Explicit concurrent mark sweep GC freed 7345(343KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 1.672ms total 201.684ms
I/ContactLocale( 4401): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  822): Start proc 4459:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=38.12 rxSuccessRate=128.38 targetRoamBSSID=any RSSI=-52
D/Launcher.Workspace( 1371): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1371): 11683562 - stripEmptyScreens()
W/ContextImpl( 4459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1270): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1270): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660384531
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
D/PackageBroadcastService( 1770): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1770): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1770): Clearing selected account for com.test.thalitest
I/ActivityManager(  822): Killing 3428:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1770): Module APK com.google.android.play.games already loaded
I/art     ( 4385): System.exit called, status: 0
I/AndroidRuntime( 4385): VM exiting with result code 0.
I/kickstart(  874): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  874): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  874): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
I/LocationSettingsChecker( 1770): Removing dialog suppression flag for package com.test.thalitest
I/UpdateIcingCorporaServi( 1505): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1371): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3de9bb9a new=com.google.android.velvet.VelvetApplication@3de9bb9a
D/GOOGLEHELP_CompatibleDatabase( 1770): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1770): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1770): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1770): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
I/ActivityManager(  822): Start proc 4490:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/SQLiteLog( 1770): (3850) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] disk I/O error
D/GOOGLEHELP_CompatibleDatabase( 1770): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
--------- beginning of crash
E/AndroidRuntime( 1770): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1770): Process: com.google.android.gms, PID: 1770
E/AndroidRuntime( 1770): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1770): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1770): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1770): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1770): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1770): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1770): 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
E/AndroidRuntime( 1770): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
E/AndroidRuntime( 1770): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1770): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1770): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1770): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1770): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1770): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1770): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1770): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1770): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1770): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1770): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1770): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1770): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1770): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1770): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1770): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1770): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1770): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1770): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1770): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1770): Opened phenotype.db in read-only mode
E/SQLiteLog( 1505): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 4401): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
E/AndroidRuntime( 4401): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4401): Process: android.process.acore, PID: 4401
E/AndroidRuntime( 4401): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4401): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4401): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4401): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4401): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4401): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4401): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 4401): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 4401): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4401): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4401): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4401): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  822): Start proc 4507:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
W/ResourcesManager(  822): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  822): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/DropBoxManagerService(  822): Can't write: system_app_crash
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
D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  822): Validating map...
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
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
W/ResourcesManager( 4490): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4490): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  822): Start proc 4527:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
I/MultiDex( 4490): VM with version 2.1.0 has multidex support
E/SharedPreferencesImpl( 1505): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 1505): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1505): Process: com.google.android.googlequicksearchbox:search, PID: 1505
E/AndroidRuntime( 1505): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1505): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1505): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1505): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1505): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1505): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1505): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1505): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1505): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1505): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1505): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1505): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1505): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1505): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1505): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1505): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1505): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1505): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1505): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1505): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1505): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4490): install
I/MultiDex( 4490): VM has multidex support, MultiDex support library is disabled.
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
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
I/ConfigFetchService( 1770): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1770): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
I/OpenGLRenderer(  822): Initialized EGL, version 1.4
W/BaseAppContext( 1770): Using Auth Proxy for data requests.
D/OpenGLRenderer(  822): Enabling debug mode 0
V/JNIHelp ( 4490): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/BaseAppContext( 1770): Using Auth Proxy for data requests.
I/ConfigFetchService( 1770): service connected
I/PeopleContactsSync( 1770): CP2 sync disabled
I/Icing   ( 1770): doRemovePackageData com.test.thalitest
E/SQLiteDatabase( 1770): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1770): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1770): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1770): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1770): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1770): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1770): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1770): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1770): Runtime exception while performing operation
E/ClearPendingStateOp( 1770): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1770): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1770): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1770): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1770): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1770): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1770): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1770): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1770): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1770): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1770): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1770): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1770): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1770): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1770): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1770): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  822): Can't write: system_app_wtf
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
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
I/ProviderInstaller( 4490): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4490): Failed to open lock file
W/NativeLibraryUtils( 4490): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4490): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4490): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4490): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4490): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4490): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4490): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4490): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4490): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4490): 	... 3 more
I/ActivityManager(  822): Killing 3043:com.google.android.music:main/u0a66 (adj 15): empty #17
I/ActivityManager(  822): Killing 3844:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
I/HotwordDetector( 1505): Closing mic
I/MicrophoneInputStream( 1505): mic_close com.google.android.apps.gsa.speech.audio.u@ff12cac
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1505): Hotword detection finished
I/HotwordRecognitionRnr( 1505): Stopping hotword detection.
D/GFEEDBACK_SendErrorReportOperation( 1770): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 1770): Error saving report: java.io.IOException: failed to create reports directory
E/Search.SharedPreferencesProto( 1505): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/GAv4    ( 4507): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4507):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4507):   adb logcat -s GAv4
W/GAv4    ( 4507): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4507): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4507): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4507): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4507): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4507): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4507): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4507): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4507): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4507): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4507): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4507): 	at aen.run(PG:536)
E/SQLiteDatabase( 4507): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4507): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4507): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4507): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4507): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4507): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4507): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4507): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4507): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4507): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4507): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4507): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4507): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4507): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4507): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4507): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4507): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4507): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4507): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4507): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4507): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4507): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4507): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4507): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4507): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4507): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4507): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4507): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4507): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4507): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4507): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4507): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4507): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4507): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 4507): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4507): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4507): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4507): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4507): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4507): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4507): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4507): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4507): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4507): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4507): 	at aej.c(PG:139)
E/SQLiteDatabase( 4507): 	at aej.b(PG:398)
E/SQLiteDatabase( 4507): 	at agf.f(PG:417)
E/SQLiteDatabase( 4507): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4507): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4507): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4507): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4507): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4507): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4507): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4507): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4507): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4507): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4507): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4507): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4507): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4507): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4507): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4507): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4507): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4507): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4507): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4507): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4507): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4507): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4507): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4507): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4507): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4507): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4507): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4507): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4507): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 4507): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4507): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4507): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4507): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4507): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4507): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4507): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4507): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4507): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4507): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4507): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4507): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4507): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4507): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4507): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4507): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4507): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4507): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4507): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4507): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4507): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4507): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4507): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4507): 	at aen.run(PG:536)
W/ResourcesManager( 4507): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4507): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  822): Start proc 4575:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  822): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{147c0112 token=Token{2861989d ActivityRecord{185fb74 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4507): Sending signal. PID: 4507 SIG: 9
E/lowmemorykiller(  254): Error writing /proc/4507/oom_score_adj; errno=22
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
I/ActivityManager(  822): Start proc 4594:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
E/native  ( 1228): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1228): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
W/ActivityManager(  822): Spurious death for ProcessRecord{1ef10d4f 4594:com.google.android.apps.docs/u0a46}, curProc for 4507: null
W/OpenGLRenderer( 1371): Incorrectly called buildLayer on View: ew, destroying layer...
E/native  ( 1228): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1228): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1228): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1228): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1228): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1228): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/SQLiteDatabase( 4575): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4575): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4575): 	at android,.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4575): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4575): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4575): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4575): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4575): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4575): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4575): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4575): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4575): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4575): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4575): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4575): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4575): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4575): Shutting down VM
E/AndroidRuntime( 4575): FATAL EXCEPTION: main
E/AndroidRuntime( 4575): Process: com.android.documentsui, PID: 4575
E/AndroidRuntime( 4575): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4575): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4575): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4575): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4575): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4575): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4575): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4575): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4575): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4575): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4575): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4575): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4575): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4575): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4575): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4575): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4575): 	... 9 more
I/ActivityManager(  822): Killing 3864:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
I/ActivityManager(  822): Start proc 4614:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
E/kickstart(  874): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  874): WARNING: function: sahara_start:892 Retrying memory read request

```
