#### Test 587523534d3a10e_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/ConfigService( 1264): onDestroy
,D/HeadsetStateMachine( 2186): Disconnected process message: 10, size: 0
D/AndroidRuntime( 3766): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3766): CheckJNI is OFF
I/CheckinService( 1776): Done disabling old GoogleServicesFramework version
D/AndroidRuntime( 3766): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{37b5dbe9 token=Token{31774c70 ActivityRecord{20a39eb3 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3766): Shutting down VM
I/MicrophoneInputStream( 1525): mic_close com.google.android.apps.gsa.speech.audio.u@d6c22ac
I/HotwordDetector( 1525): Closing mic
V/WindowManager(  823): Adding window Window{2a62857a u0 Starting com.test.thalitest} at 2 of 7 (after Window{1cc0d01a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  823): Start proc 3781:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1525): Hotword detection finished
I/HotwordRecognitionRnr( 1525): Stopping hotword detection.
I/ActivityManager(  823): Killing 3342:com.google.android.deskclock/u0a44 (adj 15): empty #17
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1720542483
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3781): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3781): Time to load native libraries: 2 ms (timestamps 7908-7910)
I/LibraryLoader( 3781): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3781): Binding Chromium to main looper Looper (main, tid 1) {1450a021}
,I/LibraryLoader( 3781): Expected native library version number "",actual native library version number ""
I/chromium( 3781): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3781): Initializing chromium process, singleProcess=true
,W/art     ( 3781): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3781): ApplicationContext is null in ApplicationStatus
,W/chromium( 3781): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3781): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3781): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3781): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  823): Message: 20
,D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@251d47cc:true
,W/art     ( 3781): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3781): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3781): CordovaWebView is running on device made by: motorola
,W/art     ( 3781): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3781): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3781): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3781): Validating map...
,V/WindowManager(  823): Adding window Window{2c683bfc u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2a62857a u0 Starting com.test.thalitest})
,W/chromium( 3781): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3781): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3781): Enabling debug mode 0
,I/Keyboard.Facilitator( 1235): onFinishInput()
,I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +797ms
,W/BindingManager( 3781): Cannot call determinedVisibility() - never saw a connection for the pid: 3781
,D/JsMessageQueue( 3781): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3781): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576391040
,I/chromium( 3781): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 3597): Thread[GAThread,5,main]: No campaign data found.
,W/jxcore-log( 3781): Initializing JXcore engine
W/jxcore-log( 3781): JXcore engine is ready
,W/Thread-426( 3836): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11721]" dev="sockfs" ino=11721 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-426( 3836): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-426( 3836): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10755]" dev="sockfs" ino=10755 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-426( 3836): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21419]" dev="sockfs" ino=21419 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3781): Starting JXcore engine
,W/jxcore-log( 3781): Platform android
W/jxcore-log( 3781): 
W/jxcore-log( 3781): Process ARCH arm
W/jxcore-log( 3781): 
,I/ActivityManager(  823): Killing 3071:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3250:com.android.settings/1000 (adj 15): empty #17
,I/jxcore-log( 3781): JXcore Cordova bridge is ready!
I/jxcore-log( 3781): 
W/jxcore-log( 3781): JXcore engine is started
,I/jxcore-log( 3781): Toggling radios to true
I/jxcore-log( 3781): 
,D/BluetoothAdapter( 3781): enable(): BT is already enabled..!
,D/WifiService(  823): setWifiEnabled: true pid=3781, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  823): New client listening to asynchronous messages
,I/jxcore-log( 3781): Radios toggled
I/jxcore-log( 3781): 
,I/jxcore-log( 3781): My device name is: motorola-Nexus 6
I/jxcore-log( 3781): 
,I/wpa_supplicant( 1191): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1264): Read error: ssl=0xb4886400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1264): SSL shutdown failed: ssl=0xb4886400: I/O error during system call, Broken pipe
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  823): Start Disconnecting Watchdog 1
D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): ValidatedState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/CommandListener(  353): Clearing all IP addresses on wlan0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1069): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Disconnected - quitting
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  823): MasterInitialState.processMessage what=3
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  823): MasterInitialState.processMessage what=3
,D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
,I/NetworkMonitor( 3033): type=WIFI subType= reason=null isConnected=false
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,V/MusicLeanback( 3033): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1343): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1343): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/WifiConfigStore(  823): Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  823): will read network variables netId=0
,I/ActivityManager(  823): Start proc 3848:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
E/WifiConfigStore(  823): will read network variables netId=0
,E/GpsLocationProvider(  823): No APN found to select.
,D/PhoneInterfaceManager( 1343): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1343): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/GpsLocationProvider(  823): No APN found to select.
,I/ActivityManager(  823): Start proc 3874:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  823): Killing 3267:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/SprintDMReceiver( 3874): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3874): simOperator:  IMSI: null
D/SprintDMReceiver( 3874): Not Sprint UICC, don't do anything.
,I/ActivityManager(  823): Killing 3401:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/SystemUpdateService( 1776): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1776): onCreate
,D/SystemUpdateService( 1776): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1776): active receiver: enabled
,I/SystemUpdateService( 1776): showing system update notification
,I/iu.Environment( 1776): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1776): num queued entries: 0
,I/iu.UploadsManager( 1776): num updated entries: 0
,D/ChimeraCfgMgr( 1776): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.SyncManager( 1776): NEXT; no task
,I/Kids    ( 1776): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1776): retry (wakeup: false) in 3599940 ms
,I/Babel   ( 3663): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  823): Start proc 3894:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1776): onDestroy
,I/GAv4    ( 3894): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3894):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3894):   adb logcat -s GAv4
,W/GAv4    ( 3894): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3894): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3894): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3894): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3894): Time to load native libraries: 2 ms (timestamps 1685-1687)
,I/LibraryLoader( 3894): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3894): Binding Chromium to main looper Looper (main, tid 1) {3ddbfd5c}
,I/LibraryLoader( 3894): Expected native library version number "",actual native library version number ""
,I/chromium( 3894): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3894): Initializing chromium process, singleProcess=true
,W/art     ( 3894): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3894): ApplicationContext is null in ApplicationStatus
,W/chromium( 3894): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3894): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3894): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3894): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3894): Requires BLUETOOTH permission
,I/art     (  823): Explicit concurrent mark sweep GC freed 28921(1412KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 2.141ms total 55.262ms
,I/NSApplication( 3894): Starting up...
,I/ActivityManager(  823): Start proc 3950:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  823): Killing 3421:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3470:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,V/MusicLeanback( 3033): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3874): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3874): simOperator:  IMSI: null
,D/SprintDMReceiver( 3874): Not Sprint UICC, don't do anything.
I/SystemUpdateService( 1776): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1776): onCreate
,I/wpa_supplicant( 1191): wlan0: Trying to associate with SSID 'NG7005g'
,D/SystemUpdateService( 1776): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,I/SystemUpdateService( 1776): active receiver: enabled
,I/SystemUpdateService( 1776): showing system update notification
,D/ChimeraCfgMgr( 1776): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1776): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1776): retry (wakeup: false) in 3599974 ms
,D/SystemUpdateService( 1776): onDestroy
,I/wpa_supplicant( 1191): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/art     ( 1525): WaitForGcToComplete blocked for 64.857ms for cause HomogeneousSpaceCompact
,I/wpa_supplicant( 1191): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1191): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 2
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
E/WifiStateMachine(  823):  my bss beacon rx: 174
E/WifiStateMachine(  823):  RSSI mgmt: -53
E/WifiStateMachine(  823):  BE :  rx=143 tx=132 lost=0 retries=0
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 9555 tx_time=152 rx_time=314 scan_time=0
,D/ConnectivityService(  823): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  823): do suspend false,
,E/WifiStateMachine(  823): scanCount==0 - aborting
,I/dhcpcd  ( 3982): version 5.5.6 starting
,I/dhcpcd  ( 3982): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3982): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3982): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3781): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3781): 
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
D/ConnectivityService(  823): Adding iface wlan0 to network 101
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  823): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1069): CM callback handler got msg 524290
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  823): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3033): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3033): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1343): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1343): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/GpsLocationProvider(  823): No APN found to select.
,D/SprintDMReceiver( 3874): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3874): simOperator:  IMSI: null
,D/SprintDMReceiver( 3874): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1776): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1776): onCreate
,D/SystemUpdateService( 1776): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1776): active receiver: enabled
,I/SystemUpdateService( 1776): showing system update notification
,I/iu.Environment( 1776): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1776): num queued entries: 0
I/iu.UploadsManager( 1776): num updated entries: 0
I/iu.SyncManager( 1776): NEXT; no task
,I/ValidateNoPeople(  823): skipping global notification
,D/ChimeraCfgMgr( 1776): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1776): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,V/SystemUpdateService( 1776): retry (wakeup: false) in 3599985 ms
,D/SystemUpdateService( 1776): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 14:49:20 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455029360519], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455029360504]}
,D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Validated
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1069): CM callback handler got msg 524290
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,V/Herrevad( 1776): NQAS connected
,I/Babel   ( 3663): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1264): Connected
,D/GCM     ( 1264): Message class com.google.f.a.a.p
,I/jxcore-log( 3781): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3781): 
,I/jxcore-log( 3781): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3781): 
,I/jxcore-log( 3781): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3781): 
,I/ActivityManager(  823): Waited long enough for: ServiceRecord{24f48da6 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/jxcore-log( 3781): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3781): 
,I/jxcore-log( 3781): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3781): 
,I/ActivityManager(  823): Killing 3626:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/art     ( 1264): Explicit concurrent mark sweep GC freed 30776(1670KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.071ms total 25.492ms
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3505): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3505): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3505): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  823): Killing 1436:android.process.acore/u0a5 (adj 15): empty #17
,I/jxcore-log( 3781): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3781): 
,I/jxcore-log( 3781): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 3781): 
,I/jxcore-log( 3781): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3781): 
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.84 rxSuccessRate=8.45 targetRoamBSSID=any RSSI=-53
,E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3781): Test app app.js loaded
I/jxcore-log( 3781): 
,I/chromium( 3781): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3781): load: 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3781): ,	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3781): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3781): 	,Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3781): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3781): 	Peer expiration time in milliseconds: 60000, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3781): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3781): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3781): ,	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3781): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5da3d7 added. We now have 1 listener(s)
,I/jxcore-log( 3781): BLE advertisement is supported
I/jxcore-log( 3781): 
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.42 rxSuccessRate=6.73 targetRoamBSSID=any RSSI=-53
,E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.90 rxSuccessRate=5.36 targetRoamBSSID=any RSSI=-53
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3505): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3505): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3505): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  823): Start proc 4037:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3205): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3205): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3205): 	at jdm.a(PG:82)
E/HttpOperation( 3205): 	at jcs.o(PG:406)
E/HttpOperation( 3205): 	at jcn.a(PG:1379)
E/HttpOperation( 3205): 	at jcs.i(PG:143)
E/HttpOperation( 3205): 	at blb.a(PG:3937)
E/HttpOperation( 3205): 	at czp.a(PG:18188)
E/HttpOperation( 3205): 	at czp.a(PG:9081)
E/HttpOperation( 3205): 	at czq.run(PG:1686)
E/HttpOperation( 3205): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3205): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3205): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3205): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3205): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3205): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3205): 	at jdj.a(PG:4091)
E/HttpOperation( 3205): 	at jdj.a(PG:1125)
E/HttpOperation( 3205): 	at jdm.a(PG:77)
E/HttpOperation( 3205): 	... 12 more
E/HttpOperation( 3205): Caused by: faj: BadAuthentication
E/HttpOperation( 3205): 	at fal.a(PG:38)
E/HttpOperation( 3205): 	at jdj.a(PG:4089)
E/HttpOperation( 3205): 	... 14 more
,V/KeepSync( 4037): Connecting to GoogleApiClient
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3205): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3205): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3205): 	at jdm.a(PG:82)
E/HttpOperation( 3205): 	at jcs.o(PG:406)
E/HttpOperation( 3205): 	at jcn.a(PG:1379)
E/HttpOperation( 3205): 	at jcs.i(PG:143)
E/HttpOperation( 3205): 	at hec.a(PG:42)
E/HttpOperation( 3205): 	at hee.a(PG:102)
E/HttpOperation( 3205): 	at czr.a(PG:65)
E/HttpOperation( 3205): 	at kka.a(PG:108)
E/HttpOperation( 3205): 	at czp.a(PG:19176)
E/HttpOperation( 3205): 	at czp.a(PG:9081)
E/HttpOperation( 3205): 	at czq.run(PG:1686)
E/HttpOperation( 3205): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3205): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3205): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3205): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3205): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3205): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3205): 	at jdj.a(PG:4091)
E/HttpOperation( 3205): 	at jdj.a(PG:1125)
E/HttpOperation( 3205): 	at jdm.a(PG:77)
E/HttpOperation( 3205): 	... 15 more
E/HttpOperation( 3205): Caused by: faj: BadAuthentication
E/HttpOperation( 3205): 	at fal.a(PG:38)
E/HttpOperation( 3205): 	at jdj.a(PG:4089)
E/HttpOperation( 3205): 	... 17 more
,E/ExperimentLoader( 3205): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3205): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3205): 	at jdm.a(PG:82)
E/ExperimentLoader( 3205): 	at jcs.o(PG:406)
E/ExperimentLoader( 3205): 	at jcn.a(PG:1379)
,E/ExperimentLoader( 3205): 	at jcs.i(PG:143)
E/ExperimentLoader( 3205): 	at hec.a(PG:42)
E/ExperimentLoader( 3205): 	at hee.a(PG:102)
E/ExperimentLoader( 3205): 	at czr.a(PG:65)
E/ExperimentLoader( 3205): 	at kka.a(PG:108)
E/ExperimentLoader( 3205): 	at czp.a(PG:19176)
E/ExperimentLoader( 3205): 	at czp.a(PG:9081),
E/ExperimentLoader( 3205): 	at czq.run(PG:1686)
E/ExperimentLoader( 3205): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3205): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3205): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3205): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3205): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3205): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/ExperimentLoader( 3205): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3205): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3205): 	at jdm.a(PG:77)
E/ExperimentLoader( 3205): 	... 15 more
E/ExperimentLoader( 3205): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3205): 	at fal.a(PG:38)
E/ExperimentLoader( 3205): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3205): 	,... 17 more
,I/art     (  823): Explicit concurrent mark sweep GC freed 52736(2MB) AllocSpace objects, 11(270KB) LOS objects, 32% free, 33MB/49MB, paused 1.569ms total 70.298ms
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1264): Explicit concurrent mark sweep GC freed 18013(1074KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 25MB/41MB, paused 1.155ms total 35.248ms
,E/ClientConnectionOperation( 1776): Handling authorization failure
E/ClientConnectionOperation( 1776): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1776): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1776): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1776): 	... 7 more
,V/KeepSync( 4037): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4037): (284) automatic index on blob_node(is_deleted)
D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 76798, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
E/SQLiteLog( 4037): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4037): (284) automatic index on blob_node(is_deleted)
,I/ActivityManager(  823): Start proc 4070:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4037): IOException
E/KeepSync( 4037): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4037): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4037): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4037): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4037): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4037): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4037): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4037): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4037): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4037): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4037): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4037): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4037): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4037): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4037): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4037): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4037): 	... 10 more
W/KeepSync( 4037): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 76007, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,W/GAV2    ( 4070): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4070): Created application version: 3.6.8 (30608)
,I/BooksSync( 4070): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4070): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4070): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 4070): Soft error,
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4070): Sync error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4070): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 77604, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Killing 3441:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3545:com.google.android.gms:car/u0a11 (adj 15): empty #18
,I/GAV2    ( 4070): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.76 rxSuccessRate=1.85 targetRoamBSSID=any RSSI=-53
,E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3505): [369] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3505): [369] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/HeadsetStateMachine( 2186): Disconnected process message: 10, size: 0
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3505): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3505): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3505): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2186): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1235): run()
,I/Keyboard.Facilitator( 1235): flushDynamicLanguageModels()
,I/ConfigService( 1264): onCreate
,I/ConfigService( 1264): onDestroy
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.30 rxSuccessRate=3.16 targetRoamBSSID=any RSSI=-53
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3505): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3505): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3505): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.66 rxSuccessRate=2.01 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (240 us)
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  823): Display changed displayId=0
,V/KeepSync( 4037): Connecting to GoogleApiClient
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3205): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3205): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3205): 	at jdm.a(PG:82)
E/HttpOperation( 3205): 	at jcs.o(PG:406)
E/HttpOperation( 3205): ,	at jcn.a(PG:1379)
E/HttpOperation( 3205): 	at jcs.i(PG:143)
E/HttpOperation( 3205): 	at blb.a(PG:3937)
E/HttpOperation( 3205): 	at czp.a(PG:18188)
E/HttpOperation( 3205): 	at czp.a(PG:9081)
E/HttpOperation( 3205): 	at czq.run(PG:1686)
E/HttpOperation( 3205): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3205): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3205): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3205): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3205): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3205): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3205): 	at jdj.a(PG:4091)
E/HttpOperation( 3205): 	at jdj.a(PG:1125)
E/HttpOperation( 3205): 	at jdm.a(PG:77)
E/HttpOperation( 3205): 	... 12 more
E/HttpOperation( 3205): Caused by: faj: BadAuthentication
E/HttpOperation( 3205): 	at fal.a(PG:38)
E/HttpOperation( 3205): 	at jdj.a(PG:4089)
E/HttpOperation( 3205): 	... 14 more
,E/ClientConnectionOperation( 1776): Handling authorization failure
E/ClientConnectionOperation( 1776): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1776): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1776): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1776): 	... 7 more
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3205): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3205): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3205): 	at jdm.a(PG:82)
E/HttpOperation( 3205): 	at jcs.o(PG:406)
E/HttpOperation( 3205): 	,at jcn.a(PG:1379)
E/HttpOperation( 3205): 	at jcs.i(PG:143)
E/HttpOperation( 3205): 	at hec.a(PG:42)
E/HttpOperation( 3205): 	at hee.a(PG:102)
E/HttpOperation( 3205): 	at czr.a(PG:65)
E/HttpOperation( 3205): 	at kka.a(PG:108)
E/HttpOperation( 3205): 	at czp.a(PG:19176)
E/HttpOperation( 3205): 	at czp.a(PG:9081)
E/HttpOperation( 3205): 	at czq.run(PG:1686)
E/HttpOperation( 3205): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3205): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3205): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3205): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3205): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3205): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3205): 	at jdj.a(PG:4091)
E/HttpOperation( 3205): 	at jdj.a(PG:1125)
E/HttpOperation( 3205): 	at jdm.a(PG:77)
E/HttpOperation( 3205): 	... 15 more
E/HttpOperation( 3205): Caused by: faj: BadAuthentication
E/HttpOperation( 3205): 	at fal.a(PG:38)
E/HttpOperation( 3205): 	at jdj.a(PG:4089)
E/HttpOperation( 3205): 	,... 17 more
E/ExperimentLoader( 3205): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3205): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3205): 	at jdm.a(PG:82)
E/ExperimentLoader( 3205): 	at jcs.o(PG:406)
,E/ExperimentLoader( 3205): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3205): 	at jcs.i(PG:143)
E/ExperimentLoader( 3205): 	at hec.a(PG:42)
E/ExperimentLoader( 3205): 	at hee.a(PG:102)
E/ExperimentLoader( 3205): 	at czr.a(PG:65)
E/ExperimentLoader( 3205): 	at kka.a(PG:108)
E/ExperimentLoader( 3205): 	at czp.a(PG:19176)
E/ExperimentLoader( 3205): 	at czp.a(PG:9081)
E/ExperimentLoader( 3205): 	at czq.run(PG:1686)
E/ExperimentLoader( 3205): ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3205): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3205): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3205): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3205): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3205): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3205): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3205): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3205): 	at jdm.a(PG:77)
E/ExperimentLoader( 3205): 	... 15 more
E/ExperimentLoader( 3205): Caused by: faj: BadAuthentication
,E/ExperimentLoader( 3205): 	at fal.a(PG:38)
E/ExperimentLoader( 3205): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3205): 	... 17 more
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,I/art     (  823): Explicit concurrent mark sweep GC freed 48098(2MB) AllocSpace objects, 16(256KB) LOS objects, 31% free, 34MB/50MB, paused 1.639ms total 78.909ms
,V/KeepSync( 4037): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4037): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4037): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4037): (284) automatic index on blob_node(is_deleted)
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 135749, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  823): Excessive delay in setPowerMode(): 265ms
,I/DreamManagerService(  823): Entering dreamland.
I/PowerManagerService(  823): Dozing...
,I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,I/BooksSync( 4070): Starting books sync for 61035162, extras: ade
,E/WifiStateMachine(  823): cancelDelayedScan -> 12
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/native  (  823): do suspend false
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksConfig( 4070): GmsCore Version = 7.8.99 (2134222-430)
,I/Keyboard.Facilitator( 1235): onFinishInput()
,E/KeepSync( 4037): IOException
E/KeepSync( 4037): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4037): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4037): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4037): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4037): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4037): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4037): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4037): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4037): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4037): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4037): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4037): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4037): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4037): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4037): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4037): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4037): 	... 10 more
W/KeepSync( 4037): Sync result 2
,E/WifiStateMachine(  823): cancelDelayedScan -> 14
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,E/native  (  823): do suspend true,
V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 138334, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4070): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4070): Soft error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4070): Sync error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4070): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 139231, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  871): STATUS: Received file 'm9kefs2'
I/kickstart(  871): STATUS: 950272 bytes transferred in 0.985093 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed,
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3505): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3505): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3505): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2186): Disconnected process message: 10, size: 0
,I/art     ( 1264): Explicit concurrent mark sweep GC freed 35287(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 984us total 42.173ms
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1264): Vacuum at: now=1455029472409 tag=VacuumService
,V/GoogleAuthProtoRequest( 3848): [420] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3848): [420] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
W/ExperimentUpdateService( 3848): [420] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3848): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3848): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3848): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3848): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3848): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3848): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3848): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3848): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3848): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3848): 	at com.a.a.k.run(SourceFile:110)
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1264): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 3505): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3505): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3505): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1264): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1264): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1264): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1264): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2186): Disconnected process message: 10, size: 0
,W/Uploader( 1264): No account for auth token provided
,W/Uploader( 1264): No account for auth token provided
,W/Uploader( 1264): No account for auth token provided
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1264): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1264): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1264): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1264): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1264): No account for auth token provided
,W/Uploader( 1264): No account for auth token provided
,W/Uploader( 1264): No account for auth token provided
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1264): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1264): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1264): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1264): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1264): No account for auth token provided
,W/Uploader( 1264): No account for auth token provided
,W/Uploader( 1264): No account for auth token provided
,W/Uploader( 1264): No account for auth token provided
,W/Uploader( 1264): No account for auth token provided
,W/Uploader( 1264):  no longer exists, so no auth token.
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1264): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1264): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1264): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1264): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1264): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1264): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1264): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
,E/Uploader( 1264): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1264): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1264): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1264): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1264): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/art     (  823): Explicit concurrent mark sweep GC freed 37710(1680KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.329ms total 90.336ms
,V/GoogleAuthProtoRequest( 3848): [421] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3848): [421] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3848): [421] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3848): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3848): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3848): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3848): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64),
W/ExperimentUpdateService( 3848): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3848): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3848): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3848): 	,at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3848): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3848): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1235): run()
I/Keyboard.Facilitator( 1235): flushDynamicLanguageModels()
,I/ConfigService( 1264): onCreate
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3205): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3205): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3205): 	at jdm.a(PG:82)
E/HttpOperation( 3205): 	at jcs.o(PG:406)
E/HttpOperation( 3205): 	at jcn.a(PG:1379)
E/HttpOperation( 3205): 	at jcs.i(PG:143)
E/HttpOperation( 3205): 	at blb.a(PG:3937)
E/HttpOperation( 3205): 	at czp.a(PG:18188)
E/HttpOperation( 3205): 	at czp.a(PG:9081)
E/HttpOperation( 3205): 	at czq.run(PG:1686)
E/HttpOperation( 3205): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3205): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3205): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3205): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3205): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3205): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3205): 	at jdj.a(PG:4091)
E/HttpOperation( 3205): 	at jdj.a(PG:1125)
E/HttpOperation( 3205): 	at jdm.a(PG:77)
E/HttpOperation( 3205): 	... 12 more
E/HttpOperation( 3205): Caused by: faj: BadAuthentication
E/HttpOperation( 3205): 	at fal.a(PG:38)
E/HttpOperation( 3205): 	at jdj.a(PG:4089)
E/HttpOperation( 3205): 	... 14 more
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3205): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3205): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3205): 	at jdm.a(PG:82)
E/HttpOperation( 3205): 	at jcs.o(PG:406)
E/HttpOperation( 3205): 	at jcn.a(PG:1379)
E/HttpOperation( 3205): 	at jcs.i(PG:143)
E/HttpOperation( 3205): 	at hec.a(PG:42)
E/HttpOperation( 3205): 	at hee.a(PG:102)
E/HttpOperation( 3205): 	at czr.a(PG:65)
E/HttpOperation( 3205): 	at kka.a(PG:108)
E/HttpOperation( 3205): 	at czp.a(PG:19176)
E/HttpOperation( 3205): 	at czp.a(PG:9081)
E/HttpOperation( 3205): 	at czq.run(PG:1686)
E/HttpOperation( 3205): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3205): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3205): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3205): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3205): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3205): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3205): 	at jdj.a(PG:4091)
E/HttpOperation( 3205): 	at jdj.a(PG:1125)
E/HttpOperation( 3205): 	at jdm.a(PG:77)
E/HttpOperation( 3205): 	... 15 more
E/HttpOperation( 3205): Caused by: faj: BadAuthentication
E/HttpOperation( 3205): 	at fal.a(PG:38)
E/HttpOperation( 3205): 	at jdj.a(PG:4089)
E/HttpOperation( 3205): 	... 17 more
,E/ExperimentLoader( 3205): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3205): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3205): 	at jdm.a(PG:82)
E/ExperimentLoader( 3205): 	at jcs.o(PG:406)
E/ExperimentLoader( 3205): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3205): 	at jcs.i(PG:143)
E/ExperimentLoader( 3205): 	at hec.a(PG:42)
E/ExperimentLoader( 3205): 	at hee.a(PG:102)
E/ExperimentLoader( 3205): 	at czr.a(PG:65)
E/ExperimentLoader( 3205): 	at kka.a(PG:108)
E/ExperimentLoader( 3205): 	at czp.a(PG:19176)
E/ExperimentLoader( 3205): 	at czp.a(PG:9081)
E/ExperimentLoader( 3205): 	at czq.run(PG:1686)
E/ExperimentLoader( 3205): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3205): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3205): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3205): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3205): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3205): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3205): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3205): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3205): 	at jdm.a(PG:77)
E/ExperimentLoader( 3205): 	... 15 more
E/ExperimentLoader( 3205): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3205): 	at fal.a(PG:38)
E/ExperimentLoader( 3205): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3205): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 225704, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1264): onDestroy
,D/HeadsetStateMachine( 2186): Disconnected process message: 10, size: 0
,I/BooksSync( 4070): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4070): GmsCore Version = 7.8.99 (2134222-430),
,V/KeepSync( 4037): Connecting to GoogleApiClient
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1776): Handling authorization failure
E/ClientConnectionOperation( 1776): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1776): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1776): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1776): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1776): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1776): 	... 7 more
,V/KeepSync( 4037): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4037): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4037): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4037): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4070): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4070): Soft error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4070): Sync error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4070): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 231537, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1264): Explicit concurrent mark sweep GC freed 69599(3MB) AllocSpace objects, 12(1166KB) LOS objects, 36% free, 27MB/43MB, paused 2.177ms total 53.532ms
,E/KeepSync( 4037): IOException
E/KeepSync( 4037): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4037): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4037): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4037): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4037): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4037): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4037): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4037): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4037): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4037): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4037): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4037): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4037): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4037): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4037): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4037): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4037): 	... 10 more
W/KeepSync( 4037): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 230657, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3781): --= Surplus to requirements =--
I/jxcore-log( 3781): 
I/jxcore-log( 3781): ****TEST TOOK:  ms ****
I/jxcore-log( 3781): 
I/jxcore-log( 3781): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3781): 
,D/AndroidRuntime( 4180): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4180): CheckJNI is OFF
,D/AndroidRuntime( 4180): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  823): Killing 3781:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  823): Skipping PackageSetting{1efc766d com.example.hello/10273} due to missing metadata
,E/libprocessgroup(  823): failed to kill 1 processes for processgroup 3781
W/ActivityManager(  823): Force removing ActivityRecord{20a39eb3 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
E/JavaBinder(  823): !!! FAILED BINDER TRANSACTION !!!
,D/WifiService(  823): Client connection lost with reason: 4
,W/WindowManager(  823): Failed looking up window
W/WindowManager(  823): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@11c3a4ef does not exist
W/WindowManager(  823): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
W/WindowManager(  823): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
W/WindowManager(  823): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1142)
W/WindowManager(  823): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
I/WindowState(  823): WIN DEATH: null
,V/ActivityManager(  823): Display changed displayId=0
,I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/TaskPersister(  823): removeObsoleteFile: deleting file=28_task.xml
,I/InputReader(  823): Reconfiguring input devices.  changes=0x00000010
,D/BuaReceiver( 3384): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/Keyboard.Facilitator( 1235): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1235): run()
,I/Decoder ( 1235): createOrResetDecoder
,I/ActivityManager(  823): Start proc 4196:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,W/InputMethodManagerService(  823): Got RemoteException sending setActive(false) notification to pid 3781 uid 10265
,I/Keyboard.Facilitator( 1235): onFinishInput()
,I/art     ( 1069): Explicit concurrent mark sweep GC freed 55831(2MB) AllocSpace objects, 1(30MB) LOS objects, 18% free, 71MB/87MB, paused 1.799ms total 73.882ms
,I/art     (  823): Explicit concurrent mark sweep GC freed 28540(1549KB) AllocSpace objects, 12(851KB) LOS objects, 31% free, 34MB/50MB, paused 2.298ms total 82.255ms
I/art     (  368): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 255us total 23.242ms
I/art     (  823): WaitForGcToComplete blocked for 64.578ms for cause Explicit
,I/art     ( 1525): Explicit concurrent mark sweep GC freed 2332(175KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 9.511ms total 102.044ms
I/art     ( 1525): WaitForGcToComplete blocked for 34.341ms for cause HeapTrim
,I/art     (  368): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 197us total 17.477ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 194us total 9.383ms
,I/ConfigService( 1264): onCreate
,I/art     ( 1373): Explicit concurrent mark sweep GC freed 5084(371KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 780us total 18.919ms
,D/JobSchedulerService(  823): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  823): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/LocationOracleImpl( 1525): Best location was null
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1235): run()
,I/HotwordRecognitionRnr( 1525): Starting hotword detection.
,I/MicrophoneInputStream( 1525): mic_starting com.google.android.apps.gsa.speech.audio.u@1be0588c
,I/AudioFlinger(  357): AudioFlinger's thread 0xb4d67000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1525): mic_started com.google.android.apps.gsa.speech.audio.u@1be0588c
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1235): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run() : Loading LM = contacts
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1235): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1235): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1235): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1235): run()
I/StatsUtilsManager( 1235): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1235): shouldRecordStats() = Too Soon
,D/VoicemailCleanupService( 4196): Cleaning up data for package: com.test.thalitest
,I/art     (  823): Explicit concurrent mark sweep GC freed 8628(419KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 1.708ms total 163.715ms
,I/ActivityManager(  823): Start proc 4233:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/ContactLocale( 4196): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/HotwordWorker( 1525): onReady
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@69fff80}
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
,I/ActivityManager(  823): Start proc 4252:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,D/Launcher.Workspace( 1373): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1373): 11683562 - stripEmptyScreens()
,I/art     ( 4180): System.exit called, status: 0
I/AndroidRuntime( 4180): VM exiting with result code 0.
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1720542483
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/ContextImpl( 4252): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1264): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1264): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,V/GoogleAuthProtoRequest( 3848): [424] a.<init>: mAccountName set to: thalitester@gmail.com
,D/ChimeraCfgMgr( 1776): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1776): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1776): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1776): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1776): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1776): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1776): Removing dialog suppression flag for package com.test.thalitest
I/UpdateIcingCorporaServi( 1525): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1373): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2a0036a0 new=com.google.android.velvet.VelvetApplication@2a0036a0
,D/GOOGLEHELP_CompatibleDatabase( 1776): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1776): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1776): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1776): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager(  823): Start proc 4283:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,D/GOOGLEHELP_CompatibleDatabase( 1776): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1776): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1776): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1776): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1776): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1776): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1776): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1776): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1776): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/GLSUser ( 1264): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1264): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1264): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1264): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  823): Start proc 4301:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
,V/GLSActivity( 1264): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ConfigFetchService( 1776): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,W/ResourcesManager( 4301): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4301): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/BaseAppContext( 1776): Using Auth Proxy for data requests.
,I/ConfigFetchService( 1776): service connected
I/PeopleContactsSync( 1776): CP2 sync disabled
,W/BaseAppContext( 1776): Using Auth Proxy for data requests.,
,I/Icing   ( 1776): doRemovePackageData com.test.thalitest
,W/ExperimentUpdateService( 3848): [424] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3848): [424] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3848): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3848): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3848): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3848): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3848): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3848): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3848): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3848): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3848): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3848): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  823): Killing 3597:com.google.android.gm/u0a78 (adj 15): empty #17
,I/MultiDex( 4301): VM with version 2.1.0 has multidex support
,I/MultiDex( 4301): install
,I/MultiDex( 4301): VM has multidex support, MultiDex support library is disabled.
,I/UpdateIcingCorporaServi( 1525): UpdateCorporaTask done [took 120 ms] updated apps [took 120 ms] 
,V/JNIHelp ( 4301): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4301): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  823): Killing 2498:com.google.android.calendar/u0a37 (adj 15): empty #17
,W/NativeLibraryUtils( 4301): Failed to open lock file
W/NativeLibraryUtils( 4301): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4301): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4301): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4301): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4301): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4301): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4301): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4301): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4301): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4301): 	... 3 more

```
