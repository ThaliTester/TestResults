#### Test 58741471ee11130_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  819): Waited long enough for: ServiceRecord{2ad4518c u0 com.qualcomm.atfwd/.AtFwdService}
,--------- beginning of main
D/AndroidRuntime( 3520): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3520): CheckJNI is OFF
I/MusicLeanback( 3444): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3444): Stop autocaching.
D/AndroidRuntime( 3520): Calling main entry com.android.commands.am.Am
I/ActivityManager(  819): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  819): addAppToken: AppWindowToken{3d5f25bb token=Token{28c7324a ActivityRecord{11b26bb5 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3520): Shutting down VM
V/WindowManager(  819): Adding window Window{138e2c84 u0 Starting com.test.thalitest} at 2 of 7 (after Window{20f4b5a5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1509): Closing mic
I/MicrophoneInputStream( 1509): mic_close com.google.android.apps.gsa.speech.audio.u@2f24b002
I/ActivityManager(  819): Start proc 3542:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
E/GmsUtils( 3444): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3444): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1509): Stopping hotword detection.
I/HotwordRecognitionRnr( 1509): Hotword detection finished
I/ActivityManager(  819): Killing 3119:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
I/WebViewFactory( 3542): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1719878931
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/LibraryLoader( 3542): Time to load native libraries: 7 ms (timestamps 7693-7700)
I/LibraryLoader( 3542): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3542): Binding Chromium to main looper Looper (main, tid 1) {1071fb96}
I/LibraryLoader( 3542): Expected native library version number "",actual native library version number ""
I/chromium( 3542): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3542): Initializing chromium process, singleProcess=true
W/art     ( 3542): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3542): ApplicationContext is null in ApplicationStatus
,W/chromium( 3542): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3542): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3542): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3542): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/ActivityManager(  819): Killing 3151:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/BluetoothManagerService(  819): Message: 20
,D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@152c881c:true
,W/art     ( 3542): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3542): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3542): CordovaWebView is running on device made by: motorola
,W/art     ( 3542): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3542): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3542): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3542): Validating map...
,V/WindowManager(  819): Adding window Window{11b7ea76 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{138e2c84 u0 Starting com.test.thalitest})
,W/chromium( 3542): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  819): Explicit concurrent mark sweep GC freed 21334(1123KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.207ms total 51.980ms
,I/OpenGLRenderer( 3542): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3542): Enabling debug mode 0
,I/ActivityManager(  819): Displayed com.test.thalitest/.MainActivity: +803ms
,I/Keyboard.Facilitator( 1233): onFinishInput()
,W/BindingManager( 3542): Cannot call determinedVisibility() - never saw a connection for the pid: 3542
,D/JsMessageQueue( 3542): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3542): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576400512
,I/chromium( 3542): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 3542): Initializing JXcore engine
W/jxcore-log( 3542): JXcore engine is ready
,W/Thread-392( 3597): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9905]" dev="sockfs" ino=9905 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-392( 3597): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-392( 3597): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10084]" dev="sockfs" ino=10084 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-392( 3597): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20272]" dev="sockfs" ino=20272 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3542): Starting JXcore engine,
,W/jxcore-log( 3542): Platform android
W/jxcore-log( 3542): 
W/jxcore-log( 3542): Process ARCH arm
W/jxcore-log( 3542): 
,I/jxcore-log( 3542): JXcore Cordova bridge is ready!
I/jxcore-log( 3542): 
W/jxcore-log( 3542): JXcore engine is started
,I/jxcore-log( 3542): Toggling radios to true
I/jxcore-log( 3542): 
,D/BluetoothAdapter( 3542): enable(): BT is already enabled..!
,D/WifiService(  819): New client listening to asynchronous messages
,D/WifiService(  819): setWifiEnabled: true pid=3542, uid=10265
E/WifiService(  819): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3542): Radios toggled
I/jxcore-log( 3542): 
,I/jxcore-log( 3542): My device name is: motorola-Nexus 6
I/jxcore-log( 3542): 
,I/wpa_supplicant( 1174): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  819): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1263): Read error: ssl=0xb4887e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1263): SSL shutdown failed: ssl=0xb4887e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  819): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  819): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/ConnectivityService(  819): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Disconnected - quitting
D/CSLegacyTypeTracker(  819): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  819): MasterInitialState.processMessage what=3
D/WifiNetworkAgent(  819): NetworkAgent: NetworkAgent channel lost
D/Tethering(  819): MasterInitialState.processMessage what=3
D/ConnectivityService(  819): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  819): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  819): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
I/NetworkMonitor( 3444): type=WIFI subType= reason=null isConnected=false
E/ConnectivityService(  819): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
V/MusicLeanback( 3444): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  819): getDataEnabled: retVal=false
E/WifiConfigStore(  819): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  819): will read network variables netId=0
,I/ActivityManager(  819): Start proc 3609:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  819): CMD_AUTO_CONNECT did save config ->  nid=0
E/GpsLocationProvider(  819): No APN found to select.
,E/WifiConfigStore(  819): will read network variables netId=0
,D/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  819): getDataEnabled: retVal=false
,E/GpsLocationProvider(  819): No APN found to select.
,I/ActivityManager(  819): Start proc 3635:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  819): Killing 3186:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,D/SprintDMReceiver( 3635): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3635): simOperator:  IMSI: null,
D/SprintDMReceiver( 3635): Not Sprint UICC, don't do anything.
,I/ActivityManager(  819): Killing 2985:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/SystemUpdateService( 1772): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1772): onCreate
,D/SystemUpdateService( 1772): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1772): active receiver: enabled
,I/SystemUpdateService( 1772): showing system update notification
,I/iu.Environment( 1772): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1772): num queued entries: 0
,I/iu.UploadsManager( 1772): num updated entries: 0
,I/iu.SyncManager( 1772): NEXT; no task
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1772): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  819): skipping global notification
,V/SystemUpdateService( 1772): retry (wakeup: false) in 3599963 ms
,D/SystemUpdateService( 1772): onDestroy
,I/ActivityManager(  819): Start proc 3655:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 2952): connection state changed from UNKNOWN to DISCONNECTED
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 317us total 14.394ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 321us total 13.446ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 310us total 12.547ms
,I/GAv4    ( 3655): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3655):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3655):   adb logcat -s GAv4
,W/GAv4    ( 3655): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3655): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3655): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3655): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3655): Time to load native libraries: 3 ms (timestamps 1543-1546)
I/LibraryLoader( 3655): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3655): Binding Chromium to main looper Looper (main, tid 1) {38b399f5}
,I/LibraryLoader( 3655): Expected native library version number "",actual native library version number ""
,I/chromium( 3655): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3655): Initializing chromium process, singleProcess=true
,W/art     ( 3655): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3655): ApplicationContext is null in ApplicationStatus
,W/chromium( 3655): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3655): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 3655): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3655): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3655): Requires BLUETOOTH permission
,I/NSApplication( 3655): Starting up...
,I/ActivityManager(  819): Start proc 3711:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  819): Killing 3232:com.android.settings/1000 (adj 15): empty #17
,I/CheckinService( 1772): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  819): Start proc 3733:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  819): Killing 3253:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/wpa_supplicant( 1174): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  819): Killing 3304:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,V/MusicLeanback( 3444): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3635): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3635): simOperator:  IMSI: null
D/SprintDMReceiver( 3635): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1772): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1772): onCreate
,D/SystemUpdateService( 1772): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1772): active receiver: enabled
,I/SystemUpdateService( 1772): showing system update notification
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1772): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/art     ( 1509): WaitForGcToComplete blocked for 63.531ms for cause Background
,I/ValidateNoPeople(  819): skipping global notification
,V/SystemUpdateService( 1772): retry (wakeup: false) in 3599951 ms
,D/SystemUpdateService( 1772): onDestroy
,I/wpa_supplicant( 1174): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1174): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1174): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  819): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  819): Start Dhcp Watchdog 2
,E/WifiStateMachine(  819):  WifiLinkLayerStats: 
E/WifiStateMachine(  819):  my bss beacon rx: 164
E/WifiStateMachine(  819):  RSSI mgmt: -51
E/WifiStateMachine(  819):  BE :  rx=150 tx=132 lost=0 retries=0
E/WifiStateMachine(  819):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  on_time : 7876 tx_time=147 rx_time=322 scan_time=0
,D/ConnectivityService(  819): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  819): do suspend false
,E/WifiStateMachine(  819): scanCount==0 - aborting
,I/dhcpcd  ( 3764): version 5.5.6 starting
,I/dhcpcd  ( 3764): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3764): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3764): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  819): Adding iface wlan0 to network 101
,E/WifiStateMachine(  819): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  819): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  819): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  819): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  819): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  819): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  819): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  819): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  819):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  819): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  819): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  819): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3444): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  819): getDataEnabled: retVal=false
,V/MusicLeanback( 3444): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  819): No APN found to select.
,D/SprintDMReceiver( 3635): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3635): simOperator:  IMSI: null
D/SprintDMReceiver( 3635): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1772): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1772): onCreate
,D/SystemUpdateService( 1772): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1772): active receiver: enabled
,I/SystemUpdateService( 1772): showing system update notification
,I/iu.Environment( 1772): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1772): num queued entries: 0
I/iu.UploadsManager( 1772): num updated entries: 0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 13:05:55 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455023155295], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455023155281]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Validated
D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  819): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/iu.SyncManager( 1772): NEXT; no task
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1772): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  819): skipping global notification
,V/SystemUpdateService( 1772): retry (wakeup: false) in 3599967 ms
,D/SystemUpdateService( 1772): onDestroy
,V/Herrevad( 1772): NQAS connected
,I/Babel   ( 2952): connection state changed from DISCONNECTED to CONNECTED
,I/ActivityManager(  819): Waited long enough for: ServiceRecord{3ce26984 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,D/GCM     ( 1263): Connected
,D/GCM     ( 1263): Message class com.google.f.a.a.p
,D/ConnectivityService(  819): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3542): 
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3542): 
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3542): 
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3542): 
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3542): 
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3542): 
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3026): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3026): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3026): [1] 5.onFinished: Scheduling replication attempt 1.
,I/art     ( 1263): Explicit concurrent mark sweep GC freed 23389(1120KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.140ms total 28.440ms
,I/ActivityManager(  819): Killing 3377:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/ActivityManager(  819): Killing 3327:com.android.musicfx/u0a18 (adj 15): empty #18
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3542): 
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 3542): 
,I/jxcore-log( 3542): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3542): 
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.59 rxSuccessRate=8.69 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3542): Test app app.js loaded
I/jxcore-log( 3542): 
,I/chromium( 3542): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3542): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3542): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3542): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3542): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3542): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3542): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3542): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3542): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3542): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3542): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c495894 added. We now have 1 listener(s)
,I/jxcore-log( 3542): BLE advertisement is supported
I/jxcore-log( 3542): 
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.30 rxSuccessRate=5.34 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,D/Finsky  ( 3026): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 54794(2MB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 2.382ms total 125.210ms
,W/Finsky  ( 3026): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3026): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3026): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3026): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3026): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3026): [1] DailyHygiene.reschedule: Scheduling new run in 282 minutes (failures=4)
,D/DeviceConnectionService( 1820): client connected with version: 7571000
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.29 rxSuccessRate=4.04 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3026): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3026): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3026): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  819): Start proc 3825:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3414): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3414): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3414): 	at jdm.a(PG:82)
E/HttpOperation( 3414): 	at jcs.o(PG:406)
E/HttpOperation( 3414): 	at jcn.a(PG:1379)
E/HttpOperation( 3414): 	at jcs.i(PG:143)
E/HttpOperation( 3414): 	at blb.a(PG:3937)
E/HttpOperation( 3414): 	at czp.a(PG:18188)
E/HttpOperation( 3414): 	at czp.a(PG:9081)
E/HttpOperation( 3414): 	at czq.run(PG:1686)
E/HttpOperation( 3414): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3414): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3414): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3414): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3414): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3414): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3414): 	at jdj.a(PG:4091)
E/HttpOperation( 3414): 	at jdj.a(PG:1125)
E/HttpOperation( 3414): 	at jdm.a(PG:77)
E/HttpOperation( 3414): 	... 12 more
E/HttpOperation( 3414): Caused by: faj: BadAuthentication
E/HttpOperation( 3414): 	at fal.a(PG:38)
E/HttpOperation( 3414): 	at jdj.a(PG:4089)
E/HttpOperation( 3414): 	... 14 more
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1263): Explicit concurrent mark sweep GC freed 23044(1367KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 25MB/41MB, paused 1.400ms total 45.653ms
,E/HttpOperation( 3414): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3414): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3414): 	at jdm.a(PG:82)
E/HttpOperation( 3414): 	at jcs.o(PG:406)
E/HttpOperation( 3414): 	at jcn.a(PG:1379)
E/HttpOperation( 3414): 	at jcs.i(PG:143)
E/HttpOperation( 3414): 	at hec.a(PG:42)
E/HttpOperation( 3414): 	at hee.a(PG:102)
E/HttpOperation( 3414): 	at czr.a(PG:65)
E/HttpOperation( 3414): 	at kka.a(PG:108)
E/HttpOperation( 3414): 	at czp.a(PG:19176)
E/HttpOperation( 3414): 	at czp.a(PG:9081)
E/HttpOperation( 3414): 	at czq.run(PG:1686)
E/HttpOperation( 3414): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3414): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3414): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3414): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3414): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3414): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3414): 	at jdj.a(PG:4091)
E/HttpOperation( 3414): 	at jdj.a(PG:1125)
E/HttpOperation( 3414): 	at jdm.a(PG:77)
E/HttpOperation( 3414): 	... 15 more
E/HttpOperation( 3414): Caused by: faj: BadAuthentication
E/HttpOperation( 3414): 	at fal.a(PG:38)
E/HttpOperation( 3414): 	at jdj.a(PG:4089)
E/HttpOperation( 3414): 	... 17 more
,E/ExperimentLoader( 3414): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3414): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3414): 	at jdm.a(PG:82)
E/ExperimentLoader( 3414): 	at jcs.o(PG:406)
E/ExperimentLoader( 3414): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3414): 	at jcs.i(PG:143)
E/ExperimentLoader( 3414): 	at hec.a(PG:42)
E/ExperimentLoader( 3414): ,	at hee.a(PG:102)
E/ExperimentLoader( 3414): 	at czr.a(PG:65)
E/ExperimentLoader( 3414): 	at kka.a(PG:108)
E/ExperimentLoader( 3414): 	at czp.a(PG:19176)
E/ExperimentLoader( 3414): 	at czp.a(PG:9081)
E/ExperimentLoader( 3414): 	at czq.run(PG:1686)
E/ExperimentLoader( 3414): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3414): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3414): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3414): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3414): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3414): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3414): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3414): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3414): ,	at jdm.a(PG:77)
E/ExperimentLoader( 3414): 	... 15 more
E/ExperimentLoader( 3414): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3414): 	at fal.a(PG:38)
E/ExperimentLoader( 3414): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3414): ,	... 17 more
,V/KeepSync( 3825): Connecting to GoogleApiClient
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 79803, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  819): Start proc 3855:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1772): Handling authorization failure
E/ClientConnectionOperation( 1772): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1772): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1772): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1772): 	... 7 more
,V/KeepSync( 3825): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,W/GAV2    ( 3855): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3855): Created application version: 3.6.8 (30608)
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/BooksSync( 3855): Starting books sync for 61035162, extras: ade
,E/KeepSync( 3825): IOException
E/KeepSync( 3825): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3825): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3825): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3825): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3825): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3825): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3825): 	... 10 more
W/KeepSync( 3825): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 79337, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  819): Explicit concurrent mark sweep GC freed 31305(1444KB) AllocSpace objects, 7(112KB) LOS objects, 32% free, 33MB/49MB, paused 1.298ms total 52.936ms
,I/BooksConfig( 3855): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3855): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3855): Soft error
,E/BooksSync( 3855): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3855): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3855): Sync error
E/BooksSync( 3855): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3855): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3855): Finished books sync
,I/ActivityManager(  819): Killing 3085:com.google.android.gm/u0a78 (adj 15): empty #17
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 82085, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  819): Killing 1439:android.process.acore/u0a5 (adj 15): empty #18
,I/GAV2    ( 3855): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.83 rxSuccessRate=2.29 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3026): [289] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3026): [289] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError,
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3026): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3026): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3026): [1] 5.onFinished: Scheduling replication attempt 3.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1233): run()
,I/Keyboard.Facilitator( 1233): flushDynamicLanguageModels()
,I/ConfigService( 1263): onCreate
,I/ConfigService( 1263): onDestroy
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.74 rxSuccessRate=1.79 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3026): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3026): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3026): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.35 rxSuccessRate=2.48 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  819): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  819): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (317 us)
,I/DisplayManagerService(  819): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  819): Display changed displayId=0
,I/kickstart(  874): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  874): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  874): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  874): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  819): Excessive delay in setPowerMode(): 267ms
,I/DreamManagerService(  819): Entering dreamland.
,I/PowerManagerService(  819): Dozing...
,I/DreamController(  819): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  819): cancelDelayedScan -> 12
,E/native  (  819): do suspend false
,I/Keyboard.Facilitator( 1233): onFinishInput()
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  819): cancelDelayedScan -> 14
,E/native  (  819): do suspend true
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  874): STATUS: Received file 'm9kefs2'
I/kickstart(  874): STATUS: 950272 bytes transferred in 0.989099 seconds
,I/kickstart(  874): STATUS: Successfully downloaded files from target 
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  874): STATUS: Sahara protocol completed
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3026): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3026): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3026): [1] 5.onFinished: Scheduling replication attempt 5.
,I/BooksSync( 3855): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3855): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3414): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3414): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3414): 	at jdm.a(PG:82)
E/HttpOperation( 3414): 	at jcs.o(PG:406)
E/HttpOperation( 3414): 	at jcn.a(PG:1379)
E/HttpOperation( 3414): 	at jcs.i(PG:143)
E/HttpOperation( 3414): 	at blb.a(PG:3937)
E/HttpOperation( 3414): 	at czp.a(PG:18188)
E/HttpOperation( 3414): 	at czp.a(PG:9081)
E/HttpOperation( 3414): 	at czq.run(PG:1686)
E/HttpOperation( 3414): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3414): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3414): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3414): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3414): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3414): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3414): 	at jdj.a(PG:4091)
E/HttpOperation( 3414): 	at jdj.a(PG:1125)
E/HttpOperation( 3414): 	at jdm.a(PG:77)
E/HttpOperation( 3414): 	... 12 more
E/HttpOperation( 3414): Caused by: faj: BadAuthentication
E/HttpOperation( 3414): 	at fal.a(PG:38)
E/HttpOperation( 3414): 	at jdj.a(PG:4089)
E/HttpOperation( 3414): 	... 14 more
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3855): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3855): Soft error
E/BooksSync( 3855): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3855): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3855): Sync error
E/BooksSync( 3855): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3855): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3855): Finished books sync
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 140121, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3414): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3414): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3414): 	at jdm.a(PG:82)
E/HttpOperation( 3414): 	at jcs.o(PG:406)
E/HttpOperation( 3414): 	at jcn.a(PG:1379)
E/HttpOperation( 3414): 	at jcs.i(PG:143)
E/HttpOperation( 3414): 	at hec.a(PG:42)
E/HttpOperation( 3414): 	at hee.a(PG:102)
E/HttpOperation( 3414): 	at czr.a(PG:65)
E/HttpOperation( 3414): 	at kka.a(PG:108)
E/HttpOperation( 3414): 	at czp.a(PG:19176)
E/HttpOperation( 3414): 	at czp.a(PG:9081)
E/HttpOperation( 3414): 	at czq.run(PG:1686)
E/HttpOperation( 3414): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3414): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3414): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3414): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3414): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3414): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3414): 	at jdj.a(PG:4091)
E/HttpOperation( 3414): 	at jdj.a(PG:1125)
E/HttpOperation( 3414): 	at jdm.a(PG:77)
E/HttpOperation( 3414): 	... 15 more
E/HttpOperation( 3414): Caused by: faj: BadAuthentication
E/HttpOperation( 3414): 	at fal.a(PG:38)
E/HttpOperation( 3414): 	at jdj.a(PG:4089)
E/HttpOperation( 3414): 	... 17 more
E/ExperimentLoader( 3414): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3414): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3414): 	at jdm.a(PG:82)
E/ExperimentLoader( 3414): 	at jcs.o(PG:406)
E/ExperimentLoader( 3414): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3414): 	at jcs.i(PG:143)
E/ExperimentLoader( 3414): 	at hec.a(PG:42)
E/ExperimentLoader( 3414): 	at hee.a(PG:102)
E/ExperimentLoader( 3414): 	at czr.a(PG:65)
E/ExperimentLoader( 3414): 	at kka.a(PG:108)
E/ExperimentLoader( 3414): 	at czp.a(PG:19176)
E/ExperimentLoader( 3414): 	at czp.a(PG:9081)
E/ExperimentLoader( 3414): 	at czq.run(PG:1686)
E/ExperimentLoader( 3414): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3414): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3414): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3414): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3414): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3414): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3414): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3414): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3414): 	at jdm.a(PG:77)
E/ExperimentLoader( 3414): 	... 15 more
E/ExperimentLoader( 3414): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3414): 	at fal.a(PG:38)
E/ExperimentLoader( 3414): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3414): 	... 17 more
,I/art     (  819): Explicit concurrent mark sweep GC freed 47783(2MB) AllocSpace objects, 14(318KB) LOS objects, 31% free, 34MB/50MB, paused 1.521ms total 83.822ms
,V/KeepSync( 3825): Connecting to GoogleApiClient
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 138586, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1263): Explicit concurrent mark sweep GC freed 33112(1953KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 865us total 21.688ms
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1772): Handling authorization failure
E/ClientConnectionOperation( 1772): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1772): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1772): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1772): 	... 7 more
,V/KeepSync( 3825): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3825): IOException
E/KeepSync( 3825): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3825): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3825): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3825): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3825): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3825): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3825): 	... 10 more
W/KeepSync( 3825): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 140215, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0,
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3609): [385] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1263): Vacuum at: now=1455023269195 tag=VacuumService
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1263): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3026): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3026): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3026): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ExperimentUpdateService( 3609): [385] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3609): [385] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3609): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
,W/ExperimentUpdateService( 3609): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3609): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3609): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3609): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3609): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3609): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3609): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3609): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3609): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1263): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1263): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1263): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1263): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1263): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1263): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1263): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1263): No account for auth token provided
,W/Uploader( 1263): No account for auth token provided
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1263): Failed to get auth token: User intervention required. Notification has been pushed.
,E/Uploader( 1263): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1263): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1263): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1263): 	at com.google.android.gms.auth.p.c(SourceFile:550)
,E/Uploader( 1263): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1263): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1263): 	,at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1263): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1263): No account for auth token provided
,W/Uploader( 1263): No account for auth token provided
,W/Uploader( 1263): No account for auth token provided
,W/Uploader( 1263): No account for auth token provided
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1263): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1263): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1263): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1263): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1263): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1263): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1263): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1263): No account for auth token provided
,W/Uploader( 1263): No account for auth token provided
,W/Uploader( 1263): No account for auth token provided
,W/Uploader( 1263): No account for auth token provided
,W/Uploader( 1263):  no longer exists, so no auth token.
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1263): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1263): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1263): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1263): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1263): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1263): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1263): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1263): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GoogleAuthProtoRequest( 3609): [386] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3609): [386] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.,
,W/ExperimentUpdateService( 3609): [386] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3609): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3609): ,	at com.a.a.a.k.a(SourceFile:117),
W/ExperimentUpdateService( 3609): ,	at com.a.a.a.k.get(SourceFile:97),
W/ExperimentUpdateService( 3609): ,	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3609): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3609): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3609): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3609): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3609): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3609): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1233): run()
I/Keyboard.Facilitator( 1233): flushDynamicLanguageModels()
,I/ConfigService( 1263): onCreate
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3414): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3414): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3414): 	at jdm.a(PG:82)
E/HttpOperation( 3414): 	at jcs.o(PG:406)
E/HttpOperation( 3414): 	at jcn.a(PG:1379)
E/HttpOperation( 3414): 	at jcs.i(PG:143)
E/HttpOperation( 3414): 	at blb.a(PG:3937)
E/HttpOperation( 3414): 	at czp.a(PG:18188)
E/HttpOperation( 3414): 	,at czp.a(PG:9081)
E/HttpOperation( 3414): 	at czq.run(PG:1686)
E/HttpOperation( 3414): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3414): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3414): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3414): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3414): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3414): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3414): 	at jdj.a(PG:4091)
E/HttpOperation( 3414): 	at jdj.a(PG:1125)
E/HttpOperation( 3414): ,	at jdm.a(PG:77)
E/HttpOperation( 3414): 	... 12 more
E/HttpOperation( 3414): Caused by: faj: BadAuthentication
E/HttpOperation( 3414): 	at fal.a(PG:38)
E/HttpOperation( 3414): 	at jdj.a(PG:4089)
E/HttpOperation( 3414): 	... 14 more
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3414): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3414): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3414): 	at jdm.a(PG:82),
E/HttpOperation( 3414): 	at jcs.o(PG:406)
E/HttpOperation( 3414): 	at jcn.a(PG:1379)
E/HttpOperation( 3414): 	at jcs.i(PG:143)
E/HttpOperation( 3414): 	at hec.a(PG:42),
E/HttpOperation( 3414): 	at hee.a(PG:102)
E/HttpOperation( 3414): 	at czr.a(PG:65)
E/HttpOperation( 3414): 	at kka.a(PG:108)
E/HttpOperation( 3414): 	at czp.a(PG:19176),
E/HttpOperation( 3414): 	at czp.a(PG:9081)
,E/HttpOperation( 3414): 	at czq.run(PG:1686)
E/HttpOperation( 3414): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3414): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3414): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3414): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3414): 	,at java.lang.Thread.run(Thread.java:818),
E/HttpOperation( 3414): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3414): 	at jdj.a(PG:4091)
,E/HttpOperation( 3414): 	at jdj.a(PG:1125)
E/HttpOperation( 3414): 	at jdm.a(PG:77)
E/HttpOperation( 3414): 	,... 15 more
E/HttpOperation( 3414): Caused by: faj: BadAuthentication
E/HttpOperation( 3414): 	at fal.a(PG:38)
,E/HttpOperation( 3414): 	at jdj.a(PG:4089)
E/HttpOperation( 3414): 	... 17 more
,E/ExperimentLoader( 3414): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3414): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3414): 	at jdm.a(PG:82)
E/ExperimentLoader( 3414): 	,at jcs.o(PG:406)
E/ExperimentLoader( 3414): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3414): 	at jcs.i(PG:143)
E/ExperimentLoader( 3414): 	at hec.a(PG:42)
E/ExperimentLoader( 3414): 	at hee.a(PG:102)
E/ExperimentLoader( 3414): 	at czr.a(PG:65)
E/ExperimentLoader( 3414): 	at kka.a(PG:108)
E/ExperimentLoader( 3414): 	at czp.a(PG:19176)
E/ExperimentLoader( 3414): 	at czp.a(PG:9081)
E/ExperimentLoader( 3414): 	at czq.run(PG:1686)
E/ExperimentLoader( 3414): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3414): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3414): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3414): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3414): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3414): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3414): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3414): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3414): 	at jdm.a(PG:77)
E/ExperimentLoader( 3414): 	... 15 more
E/ExperimentLoader( 3414): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3414): 	at fal.a(PG:38)
E/ExperimentLoader( 3414): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3414): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 229083, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1263): onDestroy
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,I/BooksSync( 3855): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3825): Connecting to GoogleApiClient
,I/art     (  819): Explicit concurrent mark sweep GC freed 37868(1652KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 2.451ms total 92.863ms
,I/BooksConfig( 3855): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1772): Handling authorization failure
E/ClientConnectionOperation( 1772): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1772): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1772): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1772): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1772): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1772): 	... 7 more
,V/KeepSync( 3825): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3825): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3855): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 3855): Soft error
E/BooksSync( 3855): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3855): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3855): Sync error
E/BooksSync( 3855): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3855): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3855): Finished books sync
I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 230583, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/art     ( 1263): Explicit concurrent mark sweep GC freed 64745(3MB) AllocSpace objects, 9(907KB) LOS objects, 36% free, 27MB/43MB, paused 1.517ms total 56.320ms
,E/KeepSync( 3825): IOException
E/KeepSync( 3825): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3825): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3825): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3825): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3825): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3825): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3825): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3825): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3825): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3825): 	... 10 more
,W/KeepSync( 3825): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 231813, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3542): --= Surplus to requirements =--
I/jxcore-log( 3542): 
I/jxcore-log( 3542): ****TEST TOOK:  ms ****
I/jxcore-log( 3542): 
I/jxcore-log( 3542): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3542): 
,D/AndroidRuntime( 3964): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3964): CheckJNI is OFF
,D/AndroidRuntime( 3964): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  819): Killing 3542:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  819): Skipping PackageSetting{cb0f2f2 com.example.hello/10273} due to missing metadata
I/WindowState(  819): WIN DEATH: Window{11b7ea76 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  819): Client connection lost with reason: 4
,W/ActivityManager(  819): Force removing ActivityRecord{11b26bb5 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  819): Display changed displayId=0
,W/ActivityManager(  819): Spurious death for ProcessRecord{3e7df3a4 3542:com.test.thalitest/u0a265}, curProc for 3542: null
,I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,I/Keyboard.Facilitator( 1233): resetDictionaries() : en_US
,D/BuaReceiver( 3284): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/InputReader(  819): Reconfiguring input devices.  changes=0x00000010
,D/TaskPersister(  819): removeObsoleteFile: deleting file=28_task.xml
,I/Keyboard.Facilitator.DecoderInitializer( 1233): run()
,I/Decoder ( 1233): createOrResetDecoder
,I/art     ( 1509): Explicit concurrent mark sweep GC freed 2601(191KB) AllocSpace objects, 1(25KB) LOS objects, 22% free, 26MB/34MB, paused 688us total 52.963ms
,I/art     ( 1065): Explicit concurrent mark sweep GC freed 54641(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 974us total 49.902ms
,I/ActivityManager(  819): Start proc 3979:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,I/ConfigService( 1263): onCreate
,W/InputMethodManagerService(  819): Got RemoteException sending setActive(false) notification to pid 3542 uid 10265
,I/Keyboard.Facilitator( 1233): onFinishInput()
,I/art     (  819): Explicit concurrent mark sweep GC freed 15013(981KB) AllocSpace objects, 9(615KB) LOS objects, 31% free, 34MB/50MB, paused 1.219ms total 80.787ms
I/art     (  819): WaitForGcToComplete blocked for 20.371ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1233): run()
,W/LocationOracleImpl( 1509): Best location was null
,I/art     ( 1381): Explicit concurrent mark sweep GC freed 4998(364KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 822us total 25.682ms
,I/HotwordRecognitionRnr( 1509): Starting hotword detection.
,I/MicrophoneInputStream( 1509): mic_starting com.google.android.apps.gsa.speech.audio.u@19721ac7
,I/AudioFlinger(  357): AudioFlinger's thread 0xb406b000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1509): mic_started com.google.android.apps.gsa.speech.audio.u@19721ac7
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
D/JobSchedulerService(  819): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  819): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1233): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1233): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1233): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1233): run()
I/StatsUtilsManager( 1233): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1233): shouldRecordStats() = Too Soon
,I/WebViewFactory( 1509): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@35f24765}
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,D/VoicemailCleanupService( 3979): Cleaning up data for package: com.test.thalitest
,I/art     (  819): Explicit concurrent mark sweep GC freed 7031(338KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 1.801ms total 158.016ms
,I/HotwordWorker( 1509): onReady
,I/LibraryLoader( 1509): Time to load native libraries: 1 ms (timestamps 4781-4782)
I/LibraryLoader( 1509): Expected native library version number "",actual native library version number ""
,W/art     ( 1509): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  819): Start proc 4023:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1719878931
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ContactLocale( 3979): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/art     ( 1509): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  819): Start proc 4043:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,D/Launcher.Workspace( 1381): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1381): 11683562 - stripEmptyScreens()
,I/art     ( 3964): System.exit called, status: 0
I/AndroidRuntime( 3964): VM exiting with result code 0.
,W/ContextImpl( 4043): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1263): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1263): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,V/GoogleAuthProtoRequest( 3609): [388] a.<init>: mAccountName set to: thalitester@gmail.com
,D/PackageBroadcastService( 1772): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1772): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1772): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1772): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1772): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1772): Removing dialog suppression flag for package com.test.thalitest
,I/UpdateIcingCorporaServi( 1509): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1381): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2d86eee9 new=com.google.android.velvet.VelvetApplication@2d86eee9
,D/GOOGLEHELP_CompatibleDatabase( 1772): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1772): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1772): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1772): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1772): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1772): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1772): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/GLSUser ( 1263): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1263): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1263): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1263): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/GOOGLEHELP_CompatibleDatabase( 1772): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1772): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1772): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1772): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1772): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1772): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  819): Start proc 4083:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,V/GLSActivity( 1263): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ConfigFetchService( 1772): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1772): service connected
,I/PeopleContactsSync( 1772): CP2 sync disabled
,W/BaseAppContext( 1772): Using Auth Proxy for data requests.
,I/Icing   ( 1772): doRemovePackageData com.test.thalitest
,W/BaseAppContext( 1772): Using Auth Proxy for data requests.
,W/ExperimentUpdateService( 3609): [388] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3609): [388] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3609): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3609): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3609): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3609): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3609): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3609): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3609): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3609): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3609): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3609): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  819): Killing 2302:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/UpdateIcingCorporaServi( 1509): UpdateCorporaTask done [took 303 ms] updated apps [took 303 ms] 

```
