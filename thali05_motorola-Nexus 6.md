#### Test 583805004251330_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/AndroidRuntime( 3789): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3789): CheckJNI is OFF
D/AndroidRuntime( 3789): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{1dd7cc10 token=Token{327dd8d3 ActivityRecord{8a2e2c2 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  820): Adding window Window{218ab6c5 u0 Starting com.test.thalitest} at 2 of 7 (after Window{cc7b8e0 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3789): Shutting down VM
I/HotwordDetector( 1542): Closing mic
I/MicrophoneInputStream( 1542): mic_close com.google.android.apps.gsa.speech.audio.u@2f975b45
I/ActivityManager(  820): Start proc 3805:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1542): Hotword detection finished
I/HotwordRecognitionRnr( 1542): Stopping hotword detection.
I/ActivityManager(  820): Killing 3353:com.google.android.deskclock/u0a44 (adj 15): empty #17
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660466451
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3805): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3805): Time to load native libraries: 2 ms (timestamps 8558-8560)
I/LibraryLoader( 3805): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3805): Binding Chromium to main looper Looper (main, tid 1) {38361299}
I/LibraryLoader( 3805): Expected native library version number "",actual native library version number ""
I/chromium( 3805): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3805): Initializing chromium process, singleProcess=true
W/art     ( 3805): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3805): ApplicationContext is null in ApplicationStatus
W/chromium( 3805): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3805): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3805): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3805): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
I/ActivityManager(  820): Killing 3106:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@845f97d:true
W/art     ( 3805): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3805): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3805): CordovaWebView is running on device made by: motorola
W/art     ( 3805): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3805): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3805): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3805): Validating map...
V/WindowManager(  820): Adding window Window{2327f10f u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{218ab6c5 u0 Starting com.test.thalitest})
W/chromium( 3805): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3805): Initialized EGL, version 1.4
I/ActivityManager(  820): Killing 3050:com.android.settings/1000 (adj 15): empty #17
D/OpenGLRenderer( 3805): Enabling debug mode 0
I/Keyboard.Facilitator( 1261): onFinishInput()
W/BindingManager( 3805): Cannot call determinedVisibility() - never saw a connection for the pid: 3805
D/JsMessageQueue( 3805): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +1s64ms
D/jxcore_app_log( 3805): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576317312
,I/chromium( 3805): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3805): Initializing JXcore engine
W/jxcore-log( 3805): JXcore engine is ready
,W/Thread-427( 3859): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9590]" dev="sockfs" ino=9590 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-427( 3859): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
W/Thread-427( 3859): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9672]" dev="sockfs" ino=9672 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-427( 3859): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23579]" dev="sockfs" ino=23579 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3805): Starting JXcore engine
,W/jxcore-log( 3805): Platform android
W/jxcore-log( 3805): 
W/jxcore-log( 3805): Process ARCH arm
W/jxcore-log( 3805): 
,I/jxcore-log( 3805): JXcore Cordova bridge is ready!
I/jxcore-log( 3805): 
W/jxcore-log( 3805): JXcore engine is started
,I/jxcore-log( 3805): Toggling radios to true
I/jxcore-log( 3805): 
,D/BluetoothAdapter( 3805): enable(): BT is already enabled..!,
,D/WifiService(  820): setWifiEnabled: true pid=3805, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  820): New client listening to asynchronous messages
,I/jxcore-log( 3805): Radios toggled
,I/jxcore-log( 3805): 
I/jxcore-log( 3805): My device name is: motorola-Nexus 6
,I/jxcore-log( 3805): 
,I/wpa_supplicant( 1092): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1210): Read error: ssl=0xaec37400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1210): SSL shutdown failed: ssl=0xaec37400: I/O error during system call, Broken pipe,
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  820): Start Disconnecting Watchdog 1
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
,D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1072): CM callback handler got msg 524292
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/NetworkMonitor( 3074): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1542): Network connectivity changed, type is: 6
,E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,V/MusicLeanback( 3074): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1332): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1332): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/WifiConfigStore(  820): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): will read network variables netId=0
,I/ActivityManager(  820): Start proc 3867:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
E/GpsLocationProvider(  820): No APN found to select.
,E/WifiConfigStore(  820): will read network variables netId=0
,D/PhoneInterfaceManager( 1332): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1332): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,I/ActivityManager(  820): Start proc 3893:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  820): Killing 2575:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/SprintDMReceiver( 3893): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3893): simOperator:  IMSI: null
,D/SprintDMReceiver( 3893): Not Sprint UICC, don't do anything.
,I/ActivityManager(  820): Killing 3459:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1783): onCreate,
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,I/iu.Environment( 1783): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1783): num queued entries: 0
I/iu.UploadsManager( 1783): num updated entries: 0
I/iu.SyncManager( 1783): NEXT; no task
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599958 ms
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1783): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1783): onDestroy
,I/Babel   ( 3679): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  820): Start proc 3913:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GAv4    ( 3913): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3913):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3913):   adb logcat -s GAv4
,W/GAv4    ( 3913): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3913): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3913): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3913): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3913): Time to load native libraries: 1 ms (timestamps 2711-2712)
I/LibraryLoader( 3913): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3913): Binding Chromium to main looper Looper (main, tid 1) {d230134}
,I/LibraryLoader( 3913): Expected native library version number "",actual native library version number ""
,I/chromium( 3913): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3913): Initializing chromium process, singleProcess=true
,W/art     ( 3913): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3913): ApplicationContext is null in ApplicationStatus
,W/chromium( 3913): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3913): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3913): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3913): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/NSApplication( 3913): Starting up...
,W/AudioManagerAndroid( 3913): Requires BLUETOOTH permission
,I/ActivityManager(  820): Start proc 3970:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  820): Killing 3517:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/art     (  820): Explicit concurrent mark sweep GC freed 30042(1498KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 1.581ms total 92.930ms
,I/ActivityManager(  820): Killing 3537:com.android.musicfx/u0a18 (adj 15): empty #17
,V/MusicLeanback( 3074): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/wpa_supplicant( 1092): wlan0: Trying to associate with SSID 'NG7005g',
,D/SprintDMReceiver( 3893): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3893): simOperator:  IMSI: null
D/SprintDMReceiver( 3893): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1783): onCreate
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1783): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599957 ms
,D/SystemUpdateService( 1783): onDestroy
,I/wpa_supplicant( 1092): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1092): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1092): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
E/WifiStateMachine(  820): Start Dhcp Watchdog 2
E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 166
E/WifiStateMachine(  820):  RSSI mgmt: -54
E/WifiStateMachine(  820):  BE :  rx=155 tx=146 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 9062 tx_time=199 rx_time=400 scan_time=0
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/dhcpcd  ( 3999): version 5.5.6 starting
,I/dhcpcd  ( 3999): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  820): Killing 3265:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3572:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,I/ActivityManager(  820): Waited long enough for: ServiceRecord{dedd3ef u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/dhcpcd  ( 3999): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3999): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 101
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  820): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820):    accepting network in place of null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101],
,D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1072): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3074): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1542): Network connectivity changed, type is: 2
,V/MusicLeanback( 3074): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3893): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3893): simOperator:  IMSI: null
D/SprintDMReceiver( 3893): Not Sprint UICC, don't do anything.
,I/ActivityManager(  820): Start proc 4032:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 16:06:00 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455033960572], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455033960552]}
,I/ActivityManager(  820): Start proc 4049:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1072): CM callback handler got msg 524290
,D/SystemUpdateService( 1783): onCreate
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/PhoneInterfaceManager( 1332): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1332): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,E/GpsLocationProvider(  820): No APN found to select.
,I/ValidateNoPeople(  820): skipping global notification
,I/iu.Environment( 1783): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1783): num queued entries: 0
I/iu.UploadsManager( 1783): num updated entries: 0
I/iu.SyncManager( 1783): NEXT; no task
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599965 ms
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1783): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/SystemUpdateService( 1783): onDestroy
,W/GAV2    ( 4032): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4032): Created application version: 3.6.8 (30608)
,V/Herrevad( 1783): NQAS connected
,I/art     ( 1210): Explicit concurrent mark sweep GC freed 28373(1533KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.076ms total 21.296ms
,I/Babel   ( 3679): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3805): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3805): 
,I/BooksSync( 4032): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4049): Connecting to GoogleApiClient
,D/GCM     ( 1210): Connected
,D/GCM     ( 1210): Message class com.google.f.a.a.p
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 4049): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,I/BooksConfig( 4032): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4049): IOException
E/KeepSync( 4049): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4049): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4049): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4049): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4049): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4049): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4049): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4049): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4049): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4049): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4049): 	... 10 more
W/KeepSync( 4049): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 75239, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,E/BooksAccountManager( 4032): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4032): Soft error
E/BooksSync( 4032): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4032): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4032): Sync error
E/BooksSync( 4032): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4032): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4032): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 74826, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  820): Explicit concurrent mark sweep GC freed 42014(1951KB) AllocSpace objects, 7(112KB) LOS objects, 31% free, 34MB/50MB, paused 1.911ms total 50.629ms
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3242): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at blb.a(PG:3937)
E/HttpOperation( 3242): 	at czp.a(PG:18188)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 12 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): 	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 14 more
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3242): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at hec.a(PG:42)
E/HttpOperation( 3242): 	at hee.a(PG:102)
E/HttpOperation( 3242): 	at czr.a(PG:65)
E/HttpOperation( 3242): 	at kka.a(PG:108)
E/HttpOperation( 3242): 	at czp.a(PG:19176)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 15 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): 	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 17 more
E/ExperimentLoader( 3242): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3242): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3242): 	at jdm.a(PG:82)
E/ExperimentLoader( 3242): 	at jcs.o(PG:406)
E/ExperimentLoader( 3242): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3242): 	at jcs.i(PG:143)
E/ExperimentLoader( 3242): 	at hec.a(PG:42)
E/ExperimentLoader( 3242): 	at hee.a(PG:102)
E/ExperimentLoader( 3242): 	at czr.a(PG:65)
E/ExperimentLoader( 3242): 	at kka.a(PG:108)
E/ExperimentLoader( 3242): 	at czp.a(PG:19176)
E/ExperimentLoader( 3242): 	at czp.a(PG:9081)
E/ExperimentLoader( 3242): 	at czq.run(PG:1686)
E/ExperimentLoader( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3242): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3242): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3242): 	at jdm.a(PG:77)
E/ExperimentLoader( 3242): 	... 15 more
E/ExperimentLoader( 3242): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3242): 	at fal.a(PG:38)
E/ExperimentLoader( 3242): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3242): 	... 17 more
,I/ActivityManager(  820): Killing 3648:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 76089, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3805): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
,I/jxcore-log( 3805): 
,I/jxcore-log( 3805): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
,I/jxcore-log( 3805): 
,I/jxcore-log( 3805): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3805): 
,I/art     ( 1210): Explicit concurrent mark sweep GC freed 22129(1337KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.551ms total 58.825ms
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3608): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3608): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3608): [1] 5.onFinished: Scheduling replication attempt 1.
,I/GAV2    ( 4032): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  820): Killing 3435:com.google.android.gm/u0a78 (adj 15): empty #17
,I/jxcore-log( 3805): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3805): 
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.39 rxSuccessRate=8.80 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3805): Test app app.js loaded
I/jxcore-log( 3805): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@196a61d7 added. We now have 1 listener(s)
,I/chromium( 3805): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3805): BLE advertisement is supported
I/jxcore-log( 3805): 
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.39 rxSuccessRate=8.80 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,D/Finsky  ( 3608): [384] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3608): [384] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.29 rxSuccessRate=4.49 targetRoamBSSID=any RSSI=-53
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3608): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3608): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3608): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.54 rxSuccessRate=2.11 targetRoamBSSID=any RSSI=-53
,E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3608): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3608): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3608): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1261): run()
I/Keyboard.Facilitator( 1261): flushDynamicLanguageModels()
,I/ConfigService( 1210): onCreate
,I/ConfigService( 1210): onDestroy
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.41 rxSuccessRate=2.47 targetRoamBSSID=any RSSI=-53
,I/BooksSync( 4032): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4032): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3242): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at blb.a(PG:3937)
E/HttpOperation( 3242): 	at czp.a(PG:18188)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 12 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): 	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 14 more
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3242): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at hec.a(PG:42)
E/HttpOperation( 3242): 	at hee.a(PG:102)
E/HttpOperation( 3242): 	at czr.a(PG:65)
E/HttpOperation( 3242): 	at kka.a(PG:108)
E/HttpOperation( 3242): 	at czp.a(PG:19176)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 15 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): 	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 17 more
,E/ExperimentLoader( 3242): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3242): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3242): 	at jdm.a(PG:82)
E/ExperimentLoader( 3242): 	at jcs.o(PG:406)
,E/ExperimentLoader( 3242): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3242): 	at jcs.i(PG:143),
E/ExperimentLoader( 3242): ,	at hec.a(PG:42)
E/ExperimentLoader( 3242): 	at hee.a(PG:102)
E/ExperimentLoader( 3242): 	at czr.a(PG:65)
E/ExperimentLoader( 3242): 	at kka.a(PG:108)
E/ExperimentLoader( 3242): 	at czp.a(PG:19176)
E/ExperimentLoader( 3242): 	at czp.a(PG:9081)
E/ExperimentLoader( 3242): 	at czq.run(PG:1686)
E/ExperimentLoader( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3242): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3242): 	,at jdj.a(PG:1125)
E/ExperimentLoader( 3242): 	at jdm.a(PG:77)
E/ExperimentLoader( 3242): 	... 15 more
E/ExperimentLoader( 3242): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3242): 	at fal.a(PG:38)
E/ExperimentLoader( 3242): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3242): 	... 17 more
,E/BooksAccountManager( 4032): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4032): Soft error,
E/BooksSync( 4032): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4032): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4032): Sync error
E/BooksSync( 4032): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4032): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4032): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 108027, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 4049): Connecting to GoogleApiClient
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 106920, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  820): Explicit concurrent mark sweep GC freed 49717(2MB) AllocSpace objects, 15(428KB) LOS objects, 31% free, 34MB/50MB, paused 2.063ms total 75.001ms
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 4049): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4049): IOException
E/KeepSync( 4049): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4049): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4049): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4049): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4049): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4049): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4049): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4049): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4049): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4049): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4049): 	... 10 more
W/KeepSync( 4049): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 108758, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3608): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3608): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3608): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.83 rxSuccessRate=2.37 targetRoamBSSID=any RSSI=-53
,E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (332 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  820): Display changed displayId=0
,D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6082000
,D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
,I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2,
I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  820): Excessive delay in setPowerMode(): 275ms
,I/DreamManagerService(  820): Entering dreamland.
,I/PowerManagerService(  820): Dozing...
,I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 12
,E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1261): onFinishInput()
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): cancelDelayedScan -> 14
E/native  (  820): do suspend true
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  870): STATUS: Received file 'm9kefs2'
I/kickstart(  870): STATUS: 950272 bytes transferred in 0.985544 seconds
,I/kickstart(  870): STATUS: Successfully downloaded files from target 
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  870): STATUS: Sahara protocol completed
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3608): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3608): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3608): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3867): [420] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1210): Explicit concurrent mark sweep GC freed 37959(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.874ms total 48.627ms
,I/VacuumService( 1210): Vacuum at: now=1455034070575 tag=VacuumService
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1210): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 3608): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3608): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3608): [1] 5.onFinished: Giving up after 6 failures.
,W/ExperimentUpdateService( 3867): [420] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/Uploader( 1210): No account for auth token provided
,W/ExperimentUpdateService( 3867): [420] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3867): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3867): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3867): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3867): 	at com.a.a.k.run(SourceFile:110)
,W/Uploader( 1210): No account for auth token provided
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1210): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1210): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1210): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1210): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1210): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1210): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1210): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1210): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1210): No account for auth token provided
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1210): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1210): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1210): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1210): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1210): No account for auth token provided
,W/Uploader( 1210): No account for auth token provided
,W/Uploader( 1210): No account for auth token provided
,W/Uploader( 1210): No account for auth token provided
,W/Uploader( 1210): No account for auth token provided
,W/Uploader( 1210): No account for auth token provided
,W/Uploader( 1210):  no longer exists, so no auth token.
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1210): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1210): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1210): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1210): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1210): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1210): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1210): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1210): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1210): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1210): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/art     (  820): Explicit concurrent mark sweep GC freed 44108(2MB) AllocSpace objects, 10(254KB) LOS objects, 31% free, 34MB/50MB, paused 2.288ms total 73.845ms
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3242): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at blb.a(PG:3937)
E/HttpOperation( 3242): 	at czp.a(PG:18188)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 12 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): 	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 14 more
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3242): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at hec.a(PG:42)
E/HttpOperation( 3242): 	at hee.a(PG:102)
E/HttpOperation( 3242): 	at czr.a(PG:65)
E/HttpOperation( 3242): 	at kka.a(PG:108)
E/HttpOperation( 3242): 	at czp.a(PG:19176)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 15 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): 	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 17 more
,E/ExperimentLoader( 3242): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3242): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3242): 	at jdm.a(PG:82)
E/ExperimentLoader( 3242): ,	at jcs.o(PG:406)
E/ExperimentLoader( 3242): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3242): 	at jcs.i(PG:143)
E/ExperimentLoader( 3242): 	,at hec.a(PG:42)
E/ExperimentLoader( 3242): 	at hee.a(PG:102)
E/ExperimentLoader( 3242): 	at czr.a(PG:65)
E/ExperimentLoader( 3242): 	at kka.a(PG:108)
E/ExperimentLoader( 3242): 	at czp.a(PG:19176)
E/ExperimentLoader( 3242): 	at czp.a(PG:9081),
E/ExperimentLoader( 3242): 	at czq.run(PG:1686)
E/ExperimentLoader( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ExperimentLoader( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3242): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3242): 	,at jdj.a(PG:1125)
E/ExperimentLoader( 3242): 	at jdm.a(PG:77)
E/ExperimentLoader( 3242): 	... 15 more
E/ExperimentLoader( 3242): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3242): 	,at fal.a(PG:38)
E/ExperimentLoader( 3242): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3242): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 196970, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3867): [421] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3867): [421] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3867): [421] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3867): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3867): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3867): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3867): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1261): run()
I/Keyboard.Facilitator( 1261): flushDynamicLanguageModels()
,I/ConfigService( 1210): onCreate
,I/BooksSync( 4032): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4049): Connecting to GoogleApiClient
,I/BooksConfig( 4032): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 4049): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4032): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4032): Soft error
E/BooksSync( 4032): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4032): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4032): Sync error
E/BooksSync( 4032): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4032): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4032): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 199745, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4049): IOException
E/KeepSync( 4049): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4049): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4049): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4049): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4049): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4049): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4049): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4049): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4049): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4049): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4049): 	... 10 more
W/KeepSync( 4049): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 201626, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1210): onDestroy
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/jxcore-log( 3805): TAP version 13
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # multiplex can send data
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 1 String should be length:200
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
,I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # enqueue and run in order
,I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
,I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 2 firstPromise setTimeout
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 3 firstPromise result
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 4 firstPromise testValue
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 5 secondPromise setTimeout
I/jxcore-log( 3805): 
I/jxcore-log( 3805): ok 6 secondPromise result
I/jxcore-log( 3805): 
I/jxcore-log( 3805): ok 7 secondPromise testValue
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 8 thirdPromise in promise
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 9 thirdPromise result
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 10 thirdPromise testValue
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # basic
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 11 sane
I/jxcore-log( 3805): ,
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # another
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 12 sane
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 13 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 14 null
,I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 15 (unnamed assert)
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 16 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 17 should not throw
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 18 (unnamed assert)
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 19 (unnamed assert)
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 20 should not throw,
I/jxcore-log( 3805): ,
,I/jxcore-log( 3805): ok 21 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 22 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 23 should be equal
I/jxcore-log( 3805): ,
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # failed to get mobile documents path
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 24 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 25 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 26 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 27 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #init should register the networkChanged event
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 28 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #startBroadcasting should throw on null device name
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 29 should throw
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 30 should throw
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 31 should throw
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 32 should throw
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #startBroadcasting should throw on negative port
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 33 should throw
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #startBroadcasting should throw on too large port,
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 34 should throw
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 35 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 36 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 37 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 38 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 39 should be equal
I/jxcore-log( 3805): 
I/jxcore-log( 3805): ok 40 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 41 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 42 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 43 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 44 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 45 should be equal
I/jxcore-log( 3805): ,
I/jxcore-log( 3805): ok 46 should be equal
I/jxcore-log( 3805): 
I/jxcore-log( 3805): ok 47 should be equal
I/jxcore-log( 3805): 
I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 48 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 49 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 50 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 51 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 52 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 53 should be equal
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #start should fail if called twice in a row
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 54 specific error should be received
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 55 specific error should be returned
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 56 error should be null
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 57 error should be null
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 58 error should be null
I/jxcore-log( 3805): 
I/jxcore-log( 3805): ok 59 error should be null
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 3805): ,
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 60 error should be null
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 61 error should be null
,I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup,
,I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): ok 62 specific error should be returned
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # setup
I/jxcore-log( 3805): 
,I/jxcore-log( 3805): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3805): ,
,I/jxcore-log( 3805): # teardown
I/jxcore-log( 3805): ,
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): ,	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f655ac4 added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455034165606.3805
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): bind: Binding a new listener,
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3805): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165606.3805","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): start: OK
,I/io.jxcore.node.ConnectionHelper( 3805): start: Using peer discovery mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3805): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455034165606.3805, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3805): bind: Binding a new listener
,W/BluetoothAdapter( 3805): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3805): Waiting for incoming connections...
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3805): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165606.3805","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165606.3805","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3805): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165606.3805","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: OK
I/io.jxcore.node.ConnectionHelper( 3805): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455034165606.3805, mode: WIFI
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3805): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 3805): 
I/io.jxcore.node.ConnectionHelper( 3805): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3805): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3805): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): onServerStopped
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3805): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3805): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 3805): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3805): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): release: No more listeners, de-initializing...
I/io.jxcore.node.ConnectionHelper( 3805): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3805): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3805): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3805): Local services cleared successfully
I/wpa_supplicant( 1092): P2P-FIND-STOPPED 
I/jxcore-log( 3805): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 3805): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): 	,Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Advertise mode: 1, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b9c57a9 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3805): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455034165703.3805
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3805): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165703.3805","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3805): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): start: OK,
I/io.jxcore.node.ConnectionHelper( 3805): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3805): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455034165703.3805, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3805): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3805): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3805): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3805): createAdvertiseData: From: 1455034165703.3805 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2168): registerClient() - UUID=e02b733e-85e1-4287-9955-18748965ea75
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=e02b733e-85e1-4287-9955-18748965ea75, clientIf=5
,D/BluetoothLeScanner( 3805): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2168): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3805): setState: State changed from NOT_STARTED to STARTING
D/BtGatt.ScanManager( 2168): handling starting scan
,D/BluetoothAdapterService( 2168): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2406b95e
,D/BtGatt.GattService( 2168): registerClient() - UUID=ac7b1fae-4bb2-44e9-8efe-a2976e60c5ac,
D/BtGatt.GattService( 2168): onClientRegistered() - UUID=ac7b1fae-4bb2-44e9-8efe-a2976e60c5ac, clientIf=6
D/BluetoothLeAdvertiser( 3805): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2168): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2168): callback done for clientIf - 5 status - 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3805): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165703.3805","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165703.3805","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3805): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165703.3805","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455034165703.3805, mode: BLE_AND_WIFI
I/wpa_supplicant( 1092): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/io.jxcore.node.ConnectionHelper( 3805): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3805): createAdvertiseData: From: 1455034165703.3805 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/jxcore-log( 3805): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 3805): 
D/BtGatt.AdvertiseManager( 2168): message : 1
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 6
I/io.jxcore.node.ConnectionHelper( 3805): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3805): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3805): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): setState: NOT_STARTED
D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2168): Client app is not null!
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2168): registerClient() - UUID=85be419d-6d1b-43dc-82a7-90dba97516b7
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=85be419d-6d1b-43dc-82a7-90dba97516b7, clientIf=6
D/BluetoothLeAdvertiser( 3805): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3805): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setState: State changed from STARTING to RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3805): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3805): stopProvideBluetoothMacAddressMode
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3805): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3805): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): onStartSuccess
I/wpa_supplicant( 1092): P2P-FIND-STOPPED 
,D/BtGatt.AdvertiseManager( 2168): message : 1,
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 6
,D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2168): Client app is not null!
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onIsBlePeerDiscovererStateChanged: [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): onIsAdvertiserStartedChanged: true
D/BtGatt.GattService( 2168): stopScan() - queue size =1
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3805): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3805): setState: State changed from STARTING to NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3805): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3805): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3805): onDiscoveryManagerStateChanged: NOT_STARTED
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2168): callback done for clientIf - 5 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3805): Local services cleared successfully
D/BtGatt.ScanManager( 2168): stop scan
I/jxcore-log( 3805): ok 66 Should be able to call stopBroadcasting without error
I/jxcore-log( 3805): 
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3805): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@223e448 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455034165882.3805
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): bind: Binding a new listener
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3805): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165882.3805","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3805): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): start: OK
I/io.jxcore.node.ConnectionHelper( 3805): start: Using peer discovery mode: WIFI
,W/BluetoothAdapter( 3805): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3805): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455034165882.3805, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3805): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3805): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165882.3805","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165882.3805","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3805): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165882.3805","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onIsWifiPeerDiscoveryStartedChanged: true,
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455034165882.3805, mode: WIFI,
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/wpa_supplicant( 1092): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): start: Already running, call stopListening() first to restart,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3805): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3805): Local service added successfully,
,I/io.jxcore.node.ConnectionHelper( 3805): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: STARTED,
I/wpa_supplicant( 1092): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 3805): ok 67 Should be able to call startBroadcasting without error,
I/jxcore-log( 3805): 
I/io.jxcore.node.ConnectionHelper( 3805): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3805): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3805): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3805): onConnectionManagerStateChanged: NOT_STARTED,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3805): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): stop: Stopping services,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3805): release: No more listeners, de-initializing...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3805): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3805): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3805): onDiscoveryManagerStateChanged: NOT_STARTED,
I/jxcore-log( 3805): ok 68 Should be able to call stopBroadcasting without error
I/jxcore-log( 3805): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3805): 	Maximum number of connection attempt retries: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3805): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b6fcf4 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3805): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455034165950.3805
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3805): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165950.3805","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): startListeningForIncomingConnections: Starting...,
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): start: OK
I/io.jxcore.node.ConnectionHelper( 3805): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3805): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455034165950.3805, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3805): bind: Binding a new listener
W/BluetoothAdapter( 3805): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3805): Waiting for incoming connections...
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3805): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3805): createAdvertiseData: From: 1455034165950.3805 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2168): registerClient() - UUID=5d0d0728-0d63-4500-a5fa-b4a1e771e5a3
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=5d0d0728-0d63-4500-a5fa-b4a1e771e5a3, clientIf=5
D/BluetoothLeScanner( 3805): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2168): start scan with filters
,D/BtGatt.ScanManager( 2168): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3805): setState: State changed from NOT_STARTED to STARTING
,D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2168): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2168): registerClient() - UUID=d6474df5-73cd-428e-82e3-5dcff6545a5a
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=d6474df5-73cd-428e-82e3-5dcff6545a5a, clientIf=6
D/BluetoothLeAdvertiser( 3805): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2168): callback done for clientIf - 5 status - 0
D/BtGatt.AdvertiseManager( 2168): message : 0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3805): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165950.3805","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165950.3805","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3805): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455034165950.3805","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3805): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455034165950.3805, mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3805): start: OK
I/wpa_supplicant( 1092): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3805): createAdvertiseData: From: 1455034165950.3805 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.AdvertiseManager( 2168): message : 1,
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 6
,I/jxcore-log( 3805): ok 69 Should be able to call startBroadcasting without error
I/jxcore-log( 3805): 
,D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2168): Client app is not null!
I/io.jxcore.node.ConnectionHelper( 3805): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): stopListeningForIncomingConnections: Stopping...,
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3805): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3805): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3805): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3805): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3805): setState: NOT_STARTED
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setState: State changed from STARTING to NOT_STARTED
D/BtGatt.GattService( 2168): registerClient() - UUID=d37ce2ce-53a6-4fc8-93da-03fdf3cacfc6
D/BtGatt.GattService( 2168): onClientRegistered() - UUID=d37ce2ce-53a6-4fc8-93da-03fdf3cacfc6, clientIf=6
D/BluetoothLeAdvertiser( 3805): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2168): message : 0
D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3805): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3805): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3805): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3805): setState: State changed from STARTING to RUNNING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3805): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3805): stop
,V/GoogleAuthProtoRequest( 3867): [422] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3867): [422] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3867): [422] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3867): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3867): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3867): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3867): 	at com.a.a.k.run(SourceFile:110)
,I/wpa_supplicant( 1092): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3242): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at blb.a(PG:3937)
E/HttpOperation( 3242): 	at czp.a(PG:18188)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 12 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): 	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 14 more
,I/art     ( 1210): Explicit concurrent mark sweep GC freed 64514(3MB) AllocSpace objects, 7(698KB) LOS objects, 36% free, 27MB/43MB, paused 1.426ms total 60.336ms
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3242): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at hec.a(PG:42)
E/HttpOperation( 3242): 	at hee.a(PG:102)
E/HttpOperation( 3242): 	at czr.a(PG:65)
E/HttpOperation( 3242): 	at kka.a(PG:108)
E/HttpOperation( 3242): 	,at czp.a(PG:19176)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	,at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): ,	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 15 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): 	,at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 17 more
E/ExperimentLoader( 3242): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3242): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3242): 	,at jdm.a(PG:82)
E/ExperimentLoader( 3242): 	at jcs.o(PG:406)
E/ExperimentLoader( 3242): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3242): 	at jcs.i(PG:143)
E/ExperimentLoader( 3242): 	at hec.a(PG:42)
,E/ExperimentLoader( 3242): 	at hee.a(PG:102)
E/ExperimentLoader( 3242): 	at czr.a(PG:65)
E/ExperimentLoader( 3242): 	at kka.a(PG:108)
E/ExperimentLoader( 3242): 	at czp.a(PG:19176),
E/ExperimentLoader( 3242): 	at czp.a(PG:9081)
E/ExperimentLoader( 3242): 	at czq.run(PG:1686)
E/ExperimentLoader( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3242): ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3242): 	,at jdj.a(PG:4091)
E/ExperimentLoader( 3242): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3242): 	at jdm.a(PG:77)
E/ExperimentLoader( 3242): 	... 15 more
E/ExperimentLoader( 3242): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3242): ,	at fal.a(PG:38)
E/ExperimentLoader( 3242): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3242): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 319124, reason: Periodic, SyncResult: stats [ numIoExceptions: 1],
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@29677451}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@29677451}
,I/art     (  820): Explicit concurrent mark sweep GC freed 36350(1684KB) AllocSpace objects, 11(741KB) LOS objects, 31% free, 34MB/50MB, paused 2.553ms total 105.216ms
,D/btif_config_util( 2168): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1210): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,W/GLSActivity( 1210): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1210): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1210): ,	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1210): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1210): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1210): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3608): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3608): ,	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3608): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3608): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3608): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3608): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/BooksSync( 4032): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4032): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 4049): Connecting to GoogleApiClient
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 4049): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,E/BooksAccountManager( 4032): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4032): Soft error
E/BooksSync( 4032): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4032): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4032): Sync error
E/BooksSync( 4032): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4032): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4032): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 354761, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 4049): IOException
E/KeepSync( 4049): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4049): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4049): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4049): 	,at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4049): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4049): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4049): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4049): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4049): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4049): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4049): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4049): 	,... 10 more
W/KeepSync( 4049): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 357835, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/EventLogService( 1783): Opted in for usage reporting
I/EventLogService( 1783): Aggregate from 1455032475842 (log), 1455032475842 (data)
,W/EventLogAggregator( 1783): Unknown tag: snet_gcore
W/EventLogAggregator( 1783): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1783): dumping service [account]
,I/wpa_supplicant( 1092): P2P-FIND-STOPPED 
,V/GoogleAuthProtoRequest( 3867): [423] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3867): [423] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3867): [423] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3867): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3867): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3867): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3867): 	at com.a.a.k.run(SourceFile:110)
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1092): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3242): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at blb.a(PG:3937)
E/HttpOperation( 3242): 	at czp.a(PG:18188)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 12 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): 	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 14 more
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3242): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at hec.a(PG:42)
E/HttpOperation( 3242): 	at hee.a(PG:102)
E/HttpOperation( 3242): 	at czr.a(PG:65)
E/HttpOperation( 3242): 	at kka.a(PG:108)
E/HttpOperation( 3242): 	at czp.a(PG:19176)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 15 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): 	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 17 more
,E/ExperimentLoader( 3242): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3242): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3242): 	at jdm.a(PG:82)
E/ExperimentLoader( 3242): 	at jcs.o(PG:406)
E/ExperimentLoader( 3242): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3242): 	at jcs.i(PG:143)
E/ExperimentLoader( 3242): 	at hec.a(PG:42)
E/ExperimentLoader( 3242): 	at hee.a(PG:102)
E/ExperimentLoader( 3242): 	at czr.a(PG:65)
E/ExperimentLoader( 3242): 	at kka.a(PG:108)
E/ExperimentLoader( 3242): 	at czp.a(PG:19176)
E/ExperimentLoader( 3242): 	at czp.a(PG:9081)
E/ExperimentLoader( 3242): 	at czq.run(PG:1686)
E/ExperimentLoader( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3242): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3242): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3242): 	at jdm.a(PG:77)
E/ExperimentLoader( 3242): 	... 15 more
E/ExperimentLoader( 3242): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3242): 	at fal.a(PG:38)
E/ExperimentLoader( 3242): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3242): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 563135, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/ActivityManager(  820): Start proc 4279:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 357us total 16.696ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 360us total 14.920ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 241us total 15.012ms
,I/GAv4    ( 4279): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4279):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4279):   adb logcat -s GAv4
,W/GAv4    ( 4279): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4279): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4279): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Killing 2500:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/art     (  820): Explicit concurrent mark sweep GC freed 35749(1655KB) AllocSpace objects, 8(316KB) LOS objects, 31% free, 34MB/50MB, paused 1.562ms total 80.504ms
,I/BooksSync( 4032): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4032): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4032): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4032): Soft error
E/BooksSync( 4032): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4032): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4032): Sync error
E/BooksSync( 4032): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4032): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4032): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 634585, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,V/KeepSync( 4049): Connecting to GoogleApiClient
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 4049): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1210): Explicit concurrent mark sweep GC freed 52445(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.478ms total 67.359ms
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4049): IOException
E/KeepSync( 4049): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4049): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4049): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4049): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4049): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4049): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4049): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4049): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4049): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4049): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4049): 	... 10 more
,W/KeepSync( 4049): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 640712, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3867): [424] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3867): [424] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.,
W/ExperimentUpdateService( 3867): [424] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3867): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64),
W/ExperimentUpdateService( 3867): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3867): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3867): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3867): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3867): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/GCM     ( 1210): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3242): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at blb.a(PG:3937)
E/HttpOperation( 3242): 	at czp.a(PG:18188)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 12 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): 	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 14 more
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3242): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at hec.a(PG:42)
E/HttpOperation( 3242): 	at hee.a(PG:102)
E/HttpOperation( 3242): 	at czr.a(PG:65)
E/HttpOperation( 3242): 	at kka.a(PG:108)
E/HttpOperation( 3242): 	at czp.a(PG:19176)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 15 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): 	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 17 more
,E/ExperimentLoader( 3242): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3242): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3242): ,	at jdm.a(PG:82)
E/ExperimentLoader( 3242): 	at jcs.o(PG:406)
E/ExperimentLoader( 3242): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3242): 	at jcs.i(PG:143)
E/ExperimentLoader( 3242): ,	at hec.a(PG:42)
E/ExperimentLoader( 3242): 	at hee.a(PG:102)
,E/ExperimentLoader( 3242): 	at czr.a(PG:65)
E/ExperimentLoader( 3242): 	at kka.a(PG:108)
E/ExperimentLoader( 3242): 	,at czp.a(PG:19176)
E/ExperimentLoader( 3242): 	at czp.a(PG:9081)
E/ExperimentLoader( 3242): 	at czq.run(PG:1686)
E/ExperimentLoader( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
,E/ExperimentLoader( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3242): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3242): 	at jdj.a(PG:4091)
,E/ExperimentLoader( 3242): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3242): 	at jdm.a(PG:77)
E/ExperimentLoader( 3242): 	,... 15 more
E/ExperimentLoader( 3242): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3242): 	at fal.a(PG:38)
E/ExperimentLoader( 3242): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3242): ,	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1050317, reason: Periodic, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/BooksSync( 4032): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4032): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 42958(1938KB) AllocSpace objects, 10(442KB) LOS objects, 31% free, 34MB/50MB, paused 2.495ms total 103.286ms
,E/BooksAccountManager( 4032): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4032): Soft error
E/BooksSync( 4032): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4032): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4032): Sync error
E/BooksSync( 4032): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4032): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4032): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1144539, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btm  ( 2168): Request to stop oneshot timer with non empty queue
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,V/KeepSync( 4049): Connecting to GoogleApiClient
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 4049): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4049): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1210): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1210): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1210): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1210): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1210): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4049): IOException
E/KeepSync( 4049): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4049): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4049): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4049): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4049): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4049): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4049): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4049): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4049): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4049): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4049): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4049): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4049): 	... 10 more
,W/KeepSync( 4049): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1186665, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/UsageStatsService(  820): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4433): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4433): CheckJNI is OFF
D/AndroidRuntime( 4433): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  820): Killing 3805:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  820): Skipping PackageSetting{2ebd9a65 com.example.hello/10273} due to missing metadata
E/libprocessgroup(  820): failed to kill 1 processes for processgroup 3805
W/ActivityManager(  820): Force removing ActivityRecord{8a2e2c2 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
D/BtGatt.GattService( 2168): Binder is dead - unregistering client (5)!
D/BtGatt.GattService( 2168): Binder is dead - unregistering client (6)!
D/WifiService(  820): Client connection lost with reason: 4
D/BtGatt.GattService( 2168): stopScan() - queue size =1
D/BtGatt.AdvertiseManager( 2168): message : 1
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2168): app died - unregistering client : 6
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2168): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2168): stop scan
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.ScanManager( 2168): app died, unregister client - 5
D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2168): Client app is not null!
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
E/BluetoothServiceJni( 2168): An exception was thrown by callback 'btgattc_multiadv_disable_cb'.
E/BluetoothServiceJni( 2168): android.os.DeadObjectException
E/BluetoothServiceJni( 2168): 	at android.os.BinderProxy.transactNative(Native Method)
E/BluetoothServiceJni( 2168): 	at android.os.BinderProxy.transact(Binder.java:496)
E/BluetoothServiceJni( 2168): 	at android.bluetooth.IBluetoothGattCallback$Stub$Proxy.onMultiAdvertiseCallback(IBluetoothGattCallback.java:874)
E/BluetoothServiceJni( 2168): 	at com.android.bluetooth.gatt.GattService.onAdvertiseInstanceDisabled(GattService.java:1233)
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
V/ActivityManager(  820): Display changed displayId=0
I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
I/Keyboard.Facilitator( 1261): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1261): run()
D/BuaReceiver( 3498): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
D/TaskPersister(  820): removeObsoleteFile: deleting file=28_task.xml
I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
I/Decoder ( 1261): createOrResetDecoder
I/art     ( 1072): Explicit concurrent mark sweep GC freed 71408(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 1.725ms total 48.088ms
I/art     (  820): Explicit concurrent mark sweep GC freed 22693(1353KB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.638ms total 74.634ms
I/art     (  820): WaitForGcToComplete blocked for 16.690ms for cause Explicit
I/art     ( 1542): Explicit concurrent mark sweep GC freed 2398(173KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 381us total 86.760ms
I/ActivityManager(  820): Start proc 4449:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3805 uid 10265
I/Keyboard.Facilitator( 1261): onFinishInput()
I/ConfigService( 1210): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1261): run()
W/LocationOracleImpl( 1542): Best location was null
I/art     ( 1360): Explicit concurrent mark sweep GC freed 4997(364KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 713us total 23.889ms
I/HotwordRecognitionRnr( 1542): Starting hotword detection.
I/MicrophoneInputStream( 1542): mic_starting com.google.android.apps.gsa.speech.audio.u@3ef4fc60
I/AudioFlinger(  357): AudioFlinger's thread 0xb4057000 ready to run
D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1542): mic_started com.google.android.apps.gsa.speech.audio.u@3ef4fc60
D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
I/Keyboard.Facilitator.MainLanguageModelLoader( 1261): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1261): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1261): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1261): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1261): run()
I/StatsUtilsManager( 1261): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1261): shouldRecordStats() = Too Soon
I/art     ( 1210): Explicit concurrent mark sweep GC freed 62090(2MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 1.038ms total 31.565ms
D/Launcher.Workspace( 1360): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1360): 11683562 - stripEmptyScreens()
I/ContactLocale( 4449): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/HotwordWorker( 1542): onReady
D/VoicemailCleanupService( 4449): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  820): Start proc 4491:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/art     (  820): Explicit concurrent mark sweep GC freed 8140(384KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 2.934ms total 197.206ms
I/ActivityManager(  820): Start proc 4510:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@23bdaf07}
E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=77.50 rxSuccessRate=94.75 targetRoamBSSID=any RSSI=-53
I/art     ( 4433): System.exit called, status: 0
I/AndroidRuntime( 4433): VM exiting with result code 0.
W/ContextImpl( 4510): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660466451
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/NetworkScheduler.SchedulerReceiver( 1210): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1210): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/art     ( 1809): Explicit concurrent mark sweep GC freed 16917(1005KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.895ms total 44.647ms
E/DataBuffer( 1809): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d5ff08f)
D/PackageBroadcastService( 1783): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1783): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1783): Clearing selected account for com.test.thalitest
I/ActivityManager(  820): Killing 3416:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1783): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1783): Removing dialog suppression flag for package com.test.thalitest
W/Launcher( 1360): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1c705af8 new=com.google.android.velvet.VelvetApplication@1c705af8
I/UpdateIcingCorporaServi( 1542): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=44.75 rxSuccessRate=183.88 targetRoamBSSID=any RSSI=-53
D/GOOGLEHELP_CompatibleDatabase( 1783): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1783): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1783): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1783): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
D/GOOGLEHELP_CompatibleDatabase( 1783): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1783): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
I/ActivityManager(  820): Start proc 4540:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
D/GOOGLEHELP_CompatibleDatabase( 1783): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1783): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1783): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1783): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1783): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1783): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1783): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  820): Start proc 4557:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/SQLiteLog( 1542): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AppDataSearchHelper( 1542): Exception thrown from onTableChanged
E/AppDataSearchHelper( 1542): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1542): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 1542): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 1542): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 1542): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 1542): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 1542): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 1542): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AppDataSearchHelper( 1542): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 1542): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 1542): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 1542): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 1542): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 1542): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 1542): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 1542): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 1542): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 1542): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 1542): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1542): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 1542): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 1542): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 1542): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 1542): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 1542): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 1542): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 1542): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 1542): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 1542): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 1542): 	... 16 more
W/AppDataSearchHelper( 1542): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 1542): UpdateCorporaTask done [took 83 ms] updated apps [took 82 ms] 
I/ConfigFetchService( 1783): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1783): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
I/ConfigFetchService( 1783): service connected
I/PeopleContactsSync( 1783): CP2 sync disabled
I/Icing   ( 1783): doRemovePackageData com.test.thalitest
W/ResourcesManager( 4557): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4557): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/BaseAppContext( 1783): Using Auth Proxy for data requests.
W/BaseAppContext( 1783): Using Auth Proxy for data requests.
I/MultiDex( 4557): VM with version 2.1.0 has multidex support
I/MultiDex( 4557): install
I/MultiDex( 4557): VM has multidex support, MultiDex support library is disabled.
E/SQLiteDatabase( 1783): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1783): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1783): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1783): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1783): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1783): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1783): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1783): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1783): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1783): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1783): Runtime exception while performing operation
E/ClearPendingStateOp( 1783): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1783): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1783): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1783): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1783): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1783): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1783): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1783): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1783): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1783): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1783): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1783): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1783): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1783): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1783): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1783): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1783): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1783): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1783): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1783): 	at java.lang.Thread.run(Thread.java:818)
V/JNIHelp ( 4557): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/DropBoxManagerService(  820): Can't write: system_app_wtf
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
I/ProviderInstaller( 4557): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4557): Failed to open lock file
W/NativeLibraryUtils( 4557): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4557): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4557): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4557): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4557): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4557): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4557): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4557): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4557): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4557): 	... 3 more
I/ActivityManager(  820): Killing 3074:com.google.android.music:main/u0a66 (adj 15): empty #17
I/GAv4    ( 4540): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4540):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4540):   adb logcat -s GAv4
W/GAv4    ( 4540): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4540): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4540): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
W/GAv4    ( 4540): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4540): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4540): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4540): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4540): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4540): 	at aen.run(PG:536)
E/SQLiteDatabase( 4540): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4540): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4540): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4540): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4540): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4540): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4540): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4540): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4540): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4540): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4540): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4540): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4540): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4540): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4540): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4540): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4540): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4540): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4540): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4540): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4540): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4540): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4540): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4540): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4540): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4540): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4540): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4540): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4540): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4540): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4540): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4540): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4540): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4540): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4540): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4540): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4540): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 4540): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4540): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4540): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4540): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4540): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4540): 	at aej.c(PG:139)
E/SQLiteDatabase( 4540): 	at aej.b(PG:398)
E/SQLiteDatabase( 4540): 	at agf.f(PG:417)
E/SQLiteDatabase( 4540): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4540): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4540): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4540): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4540): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4540): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 4540): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4540): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4540): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4540): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4540): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4540): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4540): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4540): 	at aen.run(PG:536)
E/AbstractDatabaseInstance( 4540): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4540): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4540): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4540): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4540): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4540): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4540): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4540): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4540): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4540): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4540): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4540): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4540): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4540): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 4540): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4540): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  820): Start proc 4597:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  820): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{1e2ce1df token=Token{23ab787e ActivityRecord{2dc7da39 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4540): Sending signal. PID: 4540 SIG: 9
E/lowmemorykiller(  256): Error writing /proc/4540/oom_score_adj; errno=22
E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
I/HotwordDetector( 1542): Closing mic
I/MicrophoneInputStream( 1542): mic_close com.google.android.apps.gsa.speech.audio.u@3ef4fc60
W/ActivityManager(  820): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  820): android.os.TransactionTooLargeException
W/ActivityManager(  820): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  820): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  820): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  820): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  820): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  820): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  820): 	at android.os.Binder.execTransact(Binder.java:446)
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1542): Hotword detection finished
I/HotwordRecognitionRnr( 1542): Stopping hotword detection.
I/ActivityManager(  820): Start proc 4614:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  820): Spurious death for ProcessRecord{7436de8 4614:com.google.android.apps.docs/u0a46}, curProc for 4540: null
E/Search.SharedPreferencesProto( 1542): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
W/OpenGLRenderer( 1360): Incorrectly called buildLayer on View: ew, destroying layer...
E/native  ( 1261): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1261): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/ActivityManager(  820): Killing 3893:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
E/SQLiteDatabase( 4597): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4597): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4597): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4597): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4597): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4597): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4597): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4597): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4597): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4597): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4597): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4597): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4597): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4597): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4597): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4597): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4597): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4597): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4597): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4597): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4597): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 4597): FATAL EXCEPTION: main
E/AndroidRuntime( 4597): Process: com.android.documentsui, PID: 4597
E/AndroidRuntime( 4597): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4597): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4597): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4597): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4597): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4597): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4597): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4597): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4597): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4597): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4597): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4597): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4597): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4597): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4597): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4597): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4597): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4597): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4597): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4597): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4597): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4597): 	... 9 more
I/ActivityManager(  820): Killing 3913:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
E/native  ( 1261): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1261): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/kickstart(  870): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  870): WARNING: function: sahara_start:892 Retrying memory read request
I/ActivityManager(  820): Start proc 4637:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
I/ActivityManager(  820): Killing 3970:com.android.chrome/u0a40 (adj 15): empty #17
D/GCM     ( 1210): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
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
D/ExternalStorage( 4637): After updating volumes, found 1 active roots
D/OpenGLRenderer(  820): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  820): Validating map...
D/AuthorizationBluetoothService( 1210): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/native  ( 1261): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1261): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1261): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1261): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
V/GmsCoreStatsServiceLauncher( 1783): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  820): Killing 3724:com.google.android.apps.photos/u0a71 (adj 15): empty #17
I/OpenGLRenderer(  820): Initialized EGL, version 1.4
D/OpenGLRenderer(  820): Enabling debug mode 0
I/GAv4    ( 4614): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4614):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4614):   adb logcat -s GAv4
W/GAv4    ( 4614): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/WearableService( 4557): callingUid 10011, callindPid: 4557
W/GAv4    ( 4614): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4614): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4614): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/LocationInitializer( 1783): Restart initialization of location
W/GAv4    ( 4614): AnalyticsService not registered in the ap,p manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.

```
