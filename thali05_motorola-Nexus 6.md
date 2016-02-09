#### Test 58751238ee11130_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/AndroidRuntime( 3759): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3759): CheckJNI is OFF
D/AndroidRuntime( 3759): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{3691341d token=Token{2d8cd4f4 ActivityRecord{38d7a6c7 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3759): Shutting down VM
I/MicrophoneInputStream( 1507): mic_close com.google.android.apps.gsa.speech.audio.u@31436d21
I/HotwordDetector( 1507): Closing mic
V/WindowManager(  823): Adding window Window{a2929de u0 Starting com.test.thalitest} at 2 of 7 (after Window{9484da2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  823): Start proc 3773:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1507): Hotword detection finished
I/HotwordRecognitionRnr( 1507): Stopping hotword detection.
I/art     (  823): Explicit concurrent mark sweep GC freed 21931(1085KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.208ms total 55.246ms
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660486931
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  823): Killing 3043:com.android.settings/1000 (adj 15): empty #17
,I/WebViewFactory( 3773): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3773): Time to load native libraries: 2 ms (timestamps 9255-9257)
I/LibraryLoader( 3773): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3773): Binding Chromium to main looper Looper (main, tid 1) {226fc345}
,I/LibraryLoader( 3773): Expected native library version number "",actual native library version number ""
I/chromium( 3773): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3773): Initializing chromium process, singleProcess=true
,W/art     ( 3773): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3773): ApplicationContext is null in ApplicationStatus
,W/chromium( 3773): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3773): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3773): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3773): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@168b8d90:true
,W/art     ( 3773): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3773): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3773): CordovaWebView is running on device made by: motorola
,W/art     ( 3773): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3773): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3773): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3773): Validating map...
,V/WindowManager(  823): Adding window Window{11a57ac0 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{a2929de u0 Starting com.test.thalitest})
,W/chromium( 3773): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3773): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3773): Enabling debug mode 0,
,I/Keyboard.Facilitator( 1236): onFinishInput()
,I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +884ms
,W/BindingManager( 3773): Cannot call determinedVisibility() - never saw a connection for the pid: 3773
,D/JsMessageQueue( 3773): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3773): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576394240
,I/chromium( 3773): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3773): Initializing JXcore engine
W/jxcore-log( 3773): JXcore engine is ready
,W/Thread-421( 3826): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9590]" dev="sockfs" ino=9590 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-421( 3826): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-421( 3826): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9782]" dev="sockfs" ino=9782 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-421( 3826): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22158]" dev="sockfs" ino=22158 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3773): Starting JXcore engine
,W/jxcore-log( 3773): Platform android
W/jxcore-log( 3773): 
W/jxcore-log( 3773): Process ARCH arm
W/jxcore-log( 3773): 
,I/jxcore-log( 3773): JXcore Cordova bridge is ready!,
I/jxcore-log( 3773): 
W/jxcore-log( 3773): JXcore engine is started
,I/jxcore-log( 3773): Toggling radios to true
I/jxcore-log( 3773): ,
,D/BluetoothAdapter( 3773): enable(): BT is already enabled..!
,D/WifiService(  823): setWifiEnabled: true pid=3773, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  823): New client listening to asynchronous messages
I/jxcore-log( 3773): Radios toggled
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): My device name is: motorola-Nexus 6
I/jxcore-log( 3773): 
,I/wpa_supplicant( 1189): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1376): Read error: ssl=0x9d1a1800: I/O error during system call, Connection timed out
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 1376): SSL shutdown failed: ssl=0x9d1a1800: I/O error during system call, Broken pipe
,E/WifiStateMachine(  823): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/CommandListener(  355): Clearing all IP addresses on wlan0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Disconnected - quitting
D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  823): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  823): MasterInitialState.processMessage what=3
,E/WifiConfigStore(  823): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  823): will read network variables netId=0
,D/Tethering(  823): MasterInitialState.processMessage what=3
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,D/NetworkChangeNotifierAutoDetect( 1507): Network connectivity changed, type is: 6
,V/MusicLeanback( 3067): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1302): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1302): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
,I/ActivityManager(  823): Start proc 3834:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/GpsLocationProvider(  823): No APN found to select.
,D/PhoneInterfaceManager( 1302): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1302): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/GpsLocationProvider(  823): No APN found to select.
,I/ActivityManager(  823): Start proc 3860:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  823): Killing 2556:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/SprintDMReceiver( 3860): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3860): simOperator:  IMSI: null
,D/SprintDMReceiver( 3860): Not Sprint UICC, don't do anything.
,I/ActivityManager(  823): Killing 3436:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/SystemUpdateService( 1773): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/ActivityManager(  823): Waited long enough for: ServiceRecord{29a3ac02 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,D/SystemUpdateService( 1773): onCreate
,D/SystemUpdateService( 1773): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1773): active receiver: enabled
,I/SystemUpdateService( 1773): showing system update notification
,I/iu.Environment( 1773): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1773): num queued entries: 0
,I/iu.UploadsManager( 1773): num updated entries: 0,
I/iu.SyncManager( 1773): NEXT; no task,
,I/ValidateNoPeople(  823): skipping global notification
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1773): retry (wakeup: false) in 3599960 ms
,I/Kids    ( 1773): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1773): onDestroy
,I/ActivityManager(  823): Start proc 3880:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 3654): connection state changed from UNKNOWN to DISCONNECTED
,I/GAv4    ( 3880): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3880):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3880):   adb logcat -s GAv4
,W/GAv4    ( 3880): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3880): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
W/GAv4    ( 3880): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3880): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3880): Time to load native libraries: 2 ms (timestamps 3557-3559)
I/LibraryLoader( 3880): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3880): Binding Chromium to main looper Looper (main, tid 1) {1a300f50}
,I/LibraryLoader( 3880): Expected native library version number "",actual native library version number ""
I/chromium( 3880): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3880): Initializing chromium process, singleProcess=true
,W/art     ( 3880): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3880): ApplicationContext is null in ApplicationStatus
,W/chromium( 3880): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3880): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3880): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3880): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3880): Requires BLUETOOTH permission
,I/NSApplication( 3880): Starting up...
,I/ActivityManager(  823): Start proc 3936:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  823): Killing 3492:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/wpa_supplicant( 1189): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  823): Killing 3513:com.android.musicfx/u0a18 (adj 15): empty #17
,V/MusicLeanback( 3067): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3860): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3860): simOperator:  IMSI: null
D/SprintDMReceiver( 3860): Not Sprint UICC, don't do anything.
,I/art     ( 1507): WaitForGcToComplete blocked for 5.506ms for cause DisableMovingGc
,I/ActivityManager(  823): Killing 3546:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/SystemUpdateService( 1773): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1773): onCreate
,D/SystemUpdateService( 1773): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1773): active receiver: enabled
,I/SystemUpdateService( 1773): showing system update notification,
,I/ValidateNoPeople(  823): skipping global notification
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms,
I/Kids    ( 1773): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000,
,V/SystemUpdateService( 1773): retry (wakeup: false) in 3599983 ms
,D/SystemUpdateService( 1773): onDestroy
,I/ActivityManager(  823): Killing 1435:android.process.acore/u0a5 (adj 15): empty #17
,I/wpa_supplicant( 1189): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1189): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1189): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 2
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
E/WifiStateMachine(  823):  my bss beacon rx: 184
E/WifiStateMachine(  823):  RSSI mgmt: -51
E/WifiStateMachine(  823):  BE :  rx=158 tx=143 lost=0 retries=1
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 9127 tx_time=149 rx_time=298 scan_time=0
,D/ConnectivityService(  823): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  823): do suspend false
,E/WifiStateMachine(  823): scanCount==0 - aborting,
,I/dhcpcd  ( 3966): version 5.5.6 starting
,I/dhcpcd  ( 3966): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3966): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3966): wlan0: leased 192.168.1.122 for 86400 seconds,
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  823): Adding iface wlan0 to network 101
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  823): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  823):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  823): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3067): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1507): Network connectivity changed, type is: 2
,V/MusicLeanback( 3067): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  823): Start proc 3999:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/ActivityManager(  823): Start proc 4016:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,D/PhoneInterfaceManager( 1302): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1302): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3860): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  823): No APN found to select.
,D/SprintDMHelper( 3860): simOperator:  IMSI: null
D/SprintDMReceiver( 3860): Not Sprint UICC, don't do anything.
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 14:21:09 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455027669167], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455027669148]}
,I/SystemUpdateService( 1773): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Validated
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
,D/SystemUpdateService( 1773): onCreate
,D/SystemUpdateService( 1773): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1773): active receiver: enabled
,I/iu.Environment( 1773): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1773): num queued entries: 0
I/iu.UploadsManager( 1773): num updated entries: 0
I/iu.SyncManager( 1773): NEXT; no task
,W/GAV2    ( 3999): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1773): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3773): 
,I/BooksApp( 3999): Created application version: 3.6.8 (30608)
,I/SystemUpdateService( 1773): showing system update notification
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1773): retry (wakeup: false) in 3599931 ms
,D/SystemUpdateService( 1773): onDestroy
,V/Herrevad( 1773): NQAS connected
,I/art     ( 1376): Explicit concurrent mark sweep GC freed 23656(1186KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.043ms total 26.623ms
,I/Babel   ( 3654): connection state changed from DISCONNECTED to CONNECTED
,I/BooksSync( 3999): Starting books sync for 61035162, extras: ade
,I/art     (  823): Explicit concurrent mark sweep GC freed 45969(2MB) AllocSpace objects, 6(96KB) LOS objects, 32% free, 33MB/49MB, paused 1.252ms total 80.174ms
,D/GCM     ( 1376): Connected
,D/GCM     ( 1376): Message class com.google.f.a.a.p
,I/BooksConfig( 3999): GmsCore Version = 7.8.99 (2134222-430)
V/KeepSync( 4016): Connecting to GoogleApiClient
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4016): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3999): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3999): Soft error
E/BooksSync( 3999): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3999): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3999): Sync error
E/BooksSync( 3999): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3999): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3999): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 75245, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4016): IOException
E/KeepSync( 4016): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4016): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4016): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4016): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4016): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4016): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4016): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4016): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4016): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4016): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4016): 	... 10 more
W/KeepSync( 4016): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 75919, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Killing 3625:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3773): 
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
,I/jxcore-log( 3773): 
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3582): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3582): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 3582): [1] 5.onFinished: Scheduling replication attempt 1.
,I/GAV2    ( 3999): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  823): Killing 3412:com.google.android.gm/u0a78 (adj 15): empty #17
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3773): 
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.70 rxSuccessRate=11.44 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.70 rxSuccessRate=11.44 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete,
,I/jxcore-log( 3773): Test app app.js loaded
I/jxcore-log( 3773): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	,Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c05709b added. We now have 1 listener(s)
,I/jxcore-log( 3773): BLE advertisement is supported
I/jxcore-log( 3773): 
,I/chromium( 3773): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Finsky  ( 3582): [404] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3582): [404] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.77 rxSuccessRate=3.17 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1376): Explicit concurrent mark sweep GC freed 23903(1400KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.259ms total 50.320ms
,D/Finsky  ( 3582): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3582): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3582): [1] 5.onFinished: Scheduling replication attempt 2.
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3238): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3238): 	at jdm.a(PG:82)
E/HttpOperation( 3238): 	at jcs.o(PG:406)
E/HttpOperation( 3238): 	at jcn.a(PG:1379)
E/HttpOperation( 3238): 	at jcs.i(PG:143)
E/HttpOperation( 3238): 	at blb.a(PG:3937)
E/HttpOperation( 3238): 	at czp.a(PG:18188)
E/HttpOperation( 3238): 	at czp.a(PG:9081)
E/HttpOperation( 3238): 	at czq.run(PG:1686)
E/HttpOperation( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3238): 	at jdj.a(PG:4091)
E/HttpOperation( 3238): 	at jdj.a(PG:1125)
E/HttpOperation( 3238): 	at jdm.a(PG:77)
E/HttpOperation( 3238): 	... 12 more
E/HttpOperation( 3238): Caused by: faj: BadAuthentication
E/HttpOperation( 3238): 	at fal.a(PG:38)
E/HttpOperation( 3238): 	at jdj.a(PG:4089)
E/HttpOperation( 3238): 	... 14 more
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3238): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3238): 	at jdm.a(PG:82)
E/HttpOperation( 3238): 	at jcs.o(PG:406)
E/HttpOperation( 3238): 	at jcn.a(PG:1379)
E/HttpOperation( 3238): 	at jcs.i(PG:143)
E/HttpOperation( 3238): 	at hec.a(PG:42)
E/HttpOperation( 3238): 	at hee.a(PG:102)
E/HttpOperation( 3238): 	at czr.a(PG:65)
E/HttpOperation( 3238): 	at kka.a(PG:108)
E/HttpOperation( 3238): 	at czp.a(PG:19176)
E/HttpOperation( 3238): 	at czp.a(PG:9081)
E/HttpOperation( 3238): 	at czq.run(PG:1686)
E/HttpOperation( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3238): 	at jdj.a(PG:4091)
E/HttpOperation( 3238): 	at jdj.a(PG:1125)
E/HttpOperation( 3238): 	at jdm.a(PG:77)
E/HttpOperation( 3238): 	... 15 more
E/HttpOperation( 3238): Caused by: faj: BadAuthentication
E/HttpOperation( 3238): 	at fal.a(PG:38)
E/HttpOperation( 3238): 	at jdj.a(PG:4089)
E/HttpOperation( 3238): 	... 17 more
,E/ExperimentLoader( 3238): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3238): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3238): 	at jdm.a(PG:82)
E/ExperimentLoader( 3238): 	at jcs.o(PG:406)
E/ExperimentLoader( 3238): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3238): 	at jcs.i(PG:143)
E/ExperimentLoader( 3238): 	at hec.a(PG:42)
E/ExperimentLoader( 3238): 	at hee.a(PG:102)
E/ExperimentLoader( 3238): 	at czr.a(PG:65)
E/ExperimentLoader( 3238): 	at kka.a(PG:108)
E/ExperimentLoader( 3238): 	at czp.a(PG:19176)
E/ExperimentLoader( 3238): 	at czp.a(PG:9081)
E/ExperimentLoader( 3238): 	at czq.run(PG:1686)
E/ExperimentLoader( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3238): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3238): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3238): 	at jdm.a(PG:77)
E/ExperimentLoader( 3238): 	... 15 more
E/ExperimentLoader( 3238): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3238): ,	at fal.a(PG:38)
E/ExperimentLoader( 3238): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3238): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 77044, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  823): Explicit concurrent mark sweep GC freed 40782(1871KB) AllocSpace objects, 9(144KB) LOS objects, 31% free, 34MB/50MB, paused 1.821ms total 76.744ms
,V/KeepSync( 4016): Connecting to GoogleApiClient
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4016): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4016): IOException
E/KeepSync( 4016): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4016): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4016): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4016): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4016): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4016): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4016): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4016): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4016): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4016): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4016): 	... 10 more
W/KeepSync( 4016): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 106988, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.77 rxSuccessRate=2.00 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3582): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3582): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3582): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1236): run()
I/Keyboard.Facilitator( 1236): flushDynamicLanguageModels()
,I/ConfigService( 1376): onCreate
,I/ConfigService( 1376): onDestroy
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.80 rxSuccessRate=4.04 targetRoamBSSID=any RSSI=-51
,I/BooksSync( 3999): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3999): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3999): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3999): Soft error
E/BooksSync( 3999): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3999): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3999): Sync error
E/BooksSync( 3999): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3999): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3999): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 108022, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3582): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3582): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3582): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.04 rxSuccessRate=3.18 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (397 us)
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3582): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3582): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3582): [1] 5.onFinished: Scheduling replication attempt 5.
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  823): Display changed displayId=0
,D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,I/kickstart(  878): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  878): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  878): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  878): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  823): Excessive delay in setPowerMode(): 292ms
,I/DreamManagerService(  823): Entering dreamland.
I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
I/PowerManagerService(  823): Dozing...
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  823): cancelDelayedScan -> 12
,E/native  (  823): do suspend false
,I/Keyboard.Facilitator( 1236): onFinishInput()
,E/WifiStateMachine(  823): cancelDelayedScan -> 14
,E/native  (  823): do suspend true
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off,
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off,
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  878): STATUS: Received file 'm9kefs2'
,I/kickstart(  878): STATUS: 950272 bytes transferred in 0.999564 seconds
,I/kickstart(  878): STATUS: Successfully downloaded files from target ,
I/kickstart(  878): STATUS: Wrote to /sys/power/wake_unlock,
I/kickstart(  878): STATUS: Sahara protocol completed,
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3238): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3238): 	at jdm.a(PG:82)
E/HttpOperation( 3238): 	at jcs.o(PG:406)
E/HttpOperation( 3238): 	at jcn.a(PG:1379)
E/HttpOperation( 3238): 	at jcs.i(PG:143)
E/HttpOperation( 3238): 	at blb.a(PG:3937)
E/HttpOperation( 3238): 	at czp.a(PG:18188)
E/HttpOperation( 3238): 	at czp.a(PG:9081)
E/HttpOperation( 3238): 	at czq.run(PG:1686)
E/HttpOperation( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3238): 	at jdj.a(PG:4091)
E/HttpOperation( 3238): 	at jdj.a(PG:1125)
E/HttpOperation( 3238): 	at jdm.a(PG:77)
E/HttpOperation( 3238): 	... 12 more
E/HttpOperation( 3238): Caused by: faj: BadAuthentication
E/HttpOperation( 3238): 	at fal.a(PG:38)
E/HttpOperation( 3238): 	at jdj.a(PG:4089)
E/HttpOperation( 3238): 	... 14 more
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3238): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3238): 	at jdm.a(PG:82)
E/HttpOperation( 3238): 	at jcs.o(PG:406)
E/HttpOperation( 3238): ,	at jcn.a(PG:1379)
E/HttpOperation( 3238): 	at jcs.i(PG:143)
E/HttpOperation( 3238): 	at hec.a(PG:42)
E/HttpOperation( 3238): 	at hee.a(PG:102)
E/HttpOperation( 3238): 	at czr.a(PG:65)
E/HttpOperation( 3238): 	,at kka.a(PG:108)
E/HttpOperation( 3238): 	at czp.a(PG:19176)
E/HttpOperation( 3238): 	at czp.a(PG:9081)
E/HttpOperation( 3238): 	at czq.run(PG:1686)
E/HttpOperation( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3238): 	at jdj.a(PG:4091)
E/HttpOperation( 3238): 	at jdj.a(PG:1125),
E/HttpOperation( 3238): 	at jdm.a(PG:77)
E/HttpOperation( 3238): 	... 15 more
E/HttpOperation( 3238): Caused by: faj: BadAuthentication
E/HttpOperation( 3238): 	at fal.a(PG:38)
E/HttpOperation( 3238): 	at jdj.a(PG:4089)
E/HttpOperation( 3238): 	... 17 more,
E/ExperimentLoader( 3238): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3238): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3238): 	at jdm.a(PG:82),
E/ExperimentLoader( 3238): 	at jcs.o(PG:406)
E/ExperimentLoader( 3238): 	at jcn.a(PG:1379),
E/ExperimentLoader( 3238): 	at jcs.i(PG:143)
E/ExperimentLoader( 3238): 	at hec.a(PG:42)
,E/ExperimentLoader( 3238): 	at hee.a(PG:102)
E/ExperimentLoader( 3238): 	at czr.a(PG:65)
E/ExperimentLoader( 3238): ,	at kka.a(PG:108)
E/ExperimentLoader( 3238): 	at czp.a(PG:19176)
E/ExperimentLoader( 3238): 	at czp.a(PG:9081),
E/ExperimentLoader( 3238): 	at czq.run(PG:1686)
E/ExperimentLoader( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/ExperimentLoader( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ExperimentLoader( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3238): 	,at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3238): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3238): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3238): 	at jdm.a(PG:77)
E/ExperimentLoader( 3238): 	... 15 more
E/ExperimentLoader( 3238): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3238): 	at fal.a(PG:38)
E/ExperimentLoader( 3238): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3238): 	... 17 more,
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 138028, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 51809(2MB) AllocSpace objects, 17(460KB) LOS objects, 31% free, 34MB/50MB, paused 1.741ms total 85.052ms
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1376): Vacuum at: now=1455027776537 tag=VacuumService
,I/art     ( 1376): Explicit concurrent mark sweep GC freed 38151(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 912us total 28.560ms
,V/GoogleAuthProtoRequest( 3834): [415] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3582): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3582): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3582): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3834): [415] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3834): [415] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3834): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3834): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3834): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): 	at com.google.android.flib.a.a.a(SourceFile:167)
,W/ExperimentUpdateService( 3834): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3834): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1376): Using platform SSLCertificateSocketFactory
,W/Uploader( 1376): No account for auth token provided
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1376): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1376): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1376): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1376): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1376): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1376): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1376): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1376): No account for auth token provided
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,W/Uploader( 1376): No account for auth token provided
,W/Uploader( 1376): No account for auth token provided
,W/Uploader( 1376): No account for auth token provided
,W/Uploader( 1376): No account for auth token provided,
,W/Uploader( 1376): No account for auth token provided
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1376): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1376): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1376): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1376): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1376): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1376): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1376): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1376): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1376): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1376): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1376): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1376): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1376): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1376): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1376): No account for auth token provided
,W/Uploader( 1376): No account for auth token provided
,W/Uploader( 1376): No account for auth token provided,
,W/Uploader( 1376):  no longer exists, so no auth token.
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1376): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1376): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1376): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1376): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1376): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1376): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1376): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1376): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,V/KeepSync( 4016): Connecting to GoogleApiClient
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:310),
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1773): 	... 7 more
V/KeepSync( 4016): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4016): IOException
E/KeepSync( 4016): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4016): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4016): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4016): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4016): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4016): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4016): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4016): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4016): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4016): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4016): 	... 10 more
W/KeepSync( 4016): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 167716, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3834): [416] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3834): [416] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3834): [416] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3834): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3834): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3834): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3834): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1236): run()
I/Keyboard.Facilitator( 1236): flushDynamicLanguageModels()
,I/ConfigService( 1376): onCreate
,I/BooksSync( 3999): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3999): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3999): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3999): Soft error
E/BooksSync( 3999): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3999): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3999): Sync error
E/BooksSync( 3999): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3999): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3999): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 199081, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1376): onDestroy
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,I/art     (  823): Explicit concurrent mark sweep GC freed 35973(1574KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.608ms total 85.025ms
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3238): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3238): 	at jdm.a(PG:82)
E/HttpOperation( 3238): 	at jcs.o(PG:406)
E/HttpOperation( 3238): 	at jcn.a(PG:1379)
E/HttpOperation( 3238): 	at jcs.i(PG:143)
E/HttpOperation( 3238): 	at blb.a(PG:3937)
E/HttpOperation( 3238): 	at czp.a(PG:18188)
E/HttpOperation( 3238): 	at czp.a(PG:9081)
E/HttpOperation( 3238): 	at czq.run(PG:1686)
E/HttpOperation( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3238): 	at jdj.a(PG:4091)
E/HttpOperation( 3238): 	at jdj.a(PG:1125)
E/HttpOperation( 3238): 	at jdm.a(PG:77)
E/HttpOperation( 3238): 	... 12 more
E/HttpOperation( 3238): Caused by: faj: BadAuthentication
E/HttpOperation( 3238): 	at fal.a(PG:38)
E/HttpOperation( 3238): 	at jdj.a(PG:4089)
E/HttpOperation( 3238): 	... 14 more
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3238): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3238): 	at jdm.a(PG:82)
E/HttpOperation( 3238): 	at jcs.o(PG:406)
E/HttpOperation( 3238): 	at jcn.a(PG:1379)
E/HttpOperation( 3238): 	at jcs.i(PG:143)
E/HttpOperation( 3238): 	at hec.a(PG:42)
E/HttpOperation( 3238): 	at hee.a(PG:102)
E/HttpOperation( 3238): 	at czr.a(PG:65)
E/HttpOperation( 3238): 	at kka.a(PG:108)
E/HttpOperation( 3238): 	at czp.a(PG:19176)
E/HttpOperation( 3238): 	at czp.a(PG:9081)
E/HttpOperation( 3238): 	at czq.run(PG:1686)
E/HttpOperation( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3238): 	at jdj.a(PG:4091)
E/HttpOperation( 3238): 	at jdj.a(PG:1125)
E/HttpOperation( 3238): 	at jdm.a(PG:77)
E/HttpOperation( 3238): 	... 15 more
E/HttpOperation( 3238): Caused by: faj: BadAuthentication
E/HttpOperation( 3238): 	at fal.a(PG:38)
E/HttpOperation( 3238): 	at jdj.a(PG:4089)
E/HttpOperation( 3238): 	... 17 more
,E/ExperimentLoader( 3238): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3238): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3238): 	at jdm.a(PG:82)
E/ExperimentLoader( 3238): 	at jcs.o(PG:406)
E/ExperimentLoader( 3238): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3238): 	at jcs.i(PG:143)
E/ExperimentLoader( 3238): 	at hec.a(PG:42)
E/ExperimentLoader( 3238): 	at hee.a(PG:102)
E/ExperimentLoader( 3238): 	at czr.a(PG:65)
E/ExperimentLoader( 3238): 	at kka.a(PG:108)
E/ExperimentLoader( 3238): 	at czp.a(PG:19176)
E/ExperimentLoader( 3238): 	at czp.a(PG:9081)
E/ExperimentLoader( 3238): 	at czq.run(PG:1686)
E/ExperimentLoader( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3238): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3238): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3238): 	at jdm.a(PG:77)
E/ExperimentLoader( 3238): 	... 15 more
E/ExperimentLoader( 3238): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3238): 	at fal.a(PG:38)
E/ExperimentLoader( 3238): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3238): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 228753, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3773): TAP version 13
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # multiplex can send data
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 1 String should be length:200
I/jxcore-log( 3773): 
I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # enqueue and run in order
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 2 firstPromise setTimeout
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 3 firstPromise result
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 4 firstPromise testValue
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 5 secondPromise setTimeout
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 6 secondPromise result
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 7 secondPromise testValue
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 8 thirdPromise in promise
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 9 thirdPromise result
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 10 thirdPromise testValue
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # basic
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 11 sane
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # another
,I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 12 sane
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 13 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 14 null
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 15 (unnamed assert)
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 16 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 17 should not throw
I/jxcore-log( 3773): 
I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 18 (unnamed assert)
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 19 (unnamed assert)
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 20 should not throw
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 21 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 22 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 23 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # failed to get mobile documents path
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 24 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 25 should be equal
I/jxcore-log( 3773): 
I/jxcore-log( 3773): ok 26 should be equal
I/jxcore-log( 3773): 
I/jxcore-log( 3773): ok 27 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #init should register the networkChanged event
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 28 should be equal
,I/jxcore-log( 3773): 
I/jxcore-log( 3773): # setup
,I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #startBroadcasting should throw on null device name
,I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 29 should throw
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): ,
,I/jxcore-log( 3773): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 30 should throw
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): ,
,I/jxcore-log( 3773): ok 31 should throw
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
,I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 32 should throw
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #startBroadcasting should throw on negative port
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 33 should throw
I/jxcore-log( 3773): ,
I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #startBroadcasting should throw on too large port
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 34 should throw
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 35 should be equal,
I/jxcore-log( 3773): 
I/jxcore-log( 3773): ok 36 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 37 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 38 should be equal
I/jxcore-log( 3773): ,
I/jxcore-log( 3773): ok 39 should be equal
I/jxcore-log( 3773): 
I/jxcore-log( 3773): ok 40 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 41 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 42 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 43 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 44 should be equal
I/jxcore-log( 3773): 
I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 45 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 46 should be equal
I/jxcore-log( 3773): 
I/jxcore-log( 3773): ok 47 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 48 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 49 should be equal
I/jxcore-log( 3773): 
I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 50 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 51 should be equal
I/jxcore-log( 3773): 
I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 52 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 53 should be equal
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #start should fail if called twice in a row
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): ,
,I/jxcore-log( 3773): ok 54 specific error should be received
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 55 specific error should be returned
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 56 error should be null
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 57 error should be null
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 58 error should be null
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 59 error should be null
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 60 error should be null
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 61 error should be null
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ok 62 specific error should be returned
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # setup
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): # teardown
I/jxcore-log( 3773): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9825c38 added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): setDiscoveryMode: BLE_AND_WIFI -> WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455027877979.3773
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): bind: Binding a new listener
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3773): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455027877979.3773","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): start: OK
I/io.jxcore.node.ConnectionHelper( 3773): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3773): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3773): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455027877979.3773, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3773): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3773): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3773): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455027877979.3773","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455027877979.3773","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3773): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455027877979.3773","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: OK
,I/io.jxcore.node.ConnectionHelper( 3773): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455027877979.3773, mode: WIFI
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3773): ok 63 Should be able to call startBroadcasting without error
,I/jxcore-log( 3773): 
I/io.jxcore.node.ConnectionHelper( 3773): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): stop: Stopping Bluetooth...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3773): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: OK
,I/io.jxcore.node.ConnectionHelper( 3773): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3773): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3773): Exiting thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): onServerStopped
I/io.jxcore.node.ConnectionHelper( 3773): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): stop: Stopping peer discovery...,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3773): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): stop: Stopping services,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): stop: Stopping P2P device discovery...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: NOT_INITIALIZED
I/wpa_supplicant( 1189): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onIsWifiPeerDiscoveryStartedChanged: false,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3773): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3773): release: No more listeners, de-initializing...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3773): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3773): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3773): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3773): ok 64 Should be able to call stopBroadcasting without error,
I/jxcore-log( 3773): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): 	Connection timeout in milliseconds: 15000, ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Automate Bluetooth MAC address resolution: true, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Discovery mode: WIFI, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): ,	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e2504d added. We now have 3 listener(s),
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455027878097.3773
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): bind: Binding a new listener
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): initialize: My bluetooth address is F8:CF:C5:D9:E5:61,
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3773): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455027878097.3773","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): start: OK
I/io.jxcore.node.ConnectionHelper( 3773): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3773): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455027878097.3773, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3773): bind: Binding a new listener
W/BluetoothAdapter( 3773): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3773): Waiting for incoming connections...,
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3773): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3773): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3773): createAdvertiseData: From: 1455027878097.3773 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2159): registerClient() - UUID=f65d28d1-5e89-4836-9b66-2fe84adbc60c
,D/BtGatt.GattService( 2159): onClientRegistered() - UUID=f65d28d1-5e89-4836-9b66-2fe84adbc60c, clientIf=5
,D/BluetoothLeScanner( 3773): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2159): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3773): setState: State changed from NOT_STARTED to STARTING
,D/BtGatt.ScanManager( 2159): handling starting scan
,D/BluetoothAdapterService( 2159): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3735a9a
,D/BtGatt.GattService( 2159): registerClient() - UUID=1cf36fc2-e462-4f18-aac7-15c744b70998
,D/BtGatt.GattService( 2159): onClientRegistered() - UUID=1cf36fc2-e462-4f18-aac7-15c744b70998, clientIf=6
D/BluetoothLeAdvertiser( 3773): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2159): message : 0
,D/BtGatt.AdvertiseManager( 2159): starting multi advertising
,D/BtGatt.GattService( 2159): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2159): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2159): onAdvertiseInstanceEnabled() - clientIf=6, status=0
D/BtGatt.GattService( 2159): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2159): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2159): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2159): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.GattService( 2159): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3773): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455027878097.3773","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455027878097.3773","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3773): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455027878097.3773","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: OK
I/io.jxcore.node.ConnectionHelper( 3773): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455027878097.3773, mode: BLE_AND_WIFI
I/wpa_supplicant( 1189): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3773): start
I/jxcore-log( 3773): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 3773): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3773): createAdvertiseData: From: 1455027878097.3773 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/io.jxcore.node.ConnectionHelper( 3773): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3773): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3773): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): setState: NOT_STARTED
D/BtGatt.AdvertiseManager( 2159): message : 1,
D/BtGatt.AdvertiseManager( 2159): stop advertise for client 6
D/BtGatt.GattService( 2159): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2159): Client app is not null!
D/BtGatt.GattService( 2159): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2159): registerClient() - UUID=e2483dc1-931d-4398-a08d-c2f0dae24a71,
D/BtGatt.GattService( 2159): onClientRegistered() - UUID=e2483dc1-931d-4398-a08d-c2f0dae24a71, clientIf=6
D/BluetoothLeAdvertiser( 3773): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2159): message : 0
,D/BtGatt.AdvertiseManager( 2159): starting multi advertising
,D/BtGatt.GattService( 2159): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2159): onAdvertiseDataSet() - clientIf=6, status=0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3773): start: Already running
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3773): stopProvideBluetoothMacAddressMode,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3773): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): onStartSuccess
D/BtGatt.AdvertiseManager( 2159): message : 1,
D/BtGatt.AdvertiseManager( 2159): stop advertise for client 6,
,D/BtGatt.GattService( 2159): onAdvertiseInstanceDisabled() - clientIf=6, status=0,
D/BtGatt.GattService( 2159): Client app is not null!
,D/BtGatt.GattService( 2159): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3773): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3773): updateState(): State changed from [NOT_STARTED] to [SCANNING],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onIsBlePeerDiscovererStateChanged: [SCANNING]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setState: State changed from NOT_STARTED to RUNNING,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3773): onIsAdvertiserStartedChanged: true
D/BtGatt.GattService( 2159): stopScan() - queue size =1
,D/BtGatt.GattService( 2159): unregisterClient() - clientIf=5
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3773): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3773): setState: State changed from STARTING to NOT_STARTED,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3773): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3773): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
,D/BtGatt.GattService( 2159): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2159): callback done for clientIf - 5 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3773): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 3773): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/BtGatt.ScanManager( 2159): stop scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): stop: Stopping services,
D/BtGatt.ScanManager( 2159): configureRegularScanParams() - queue=0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): restart: Restarting...
,D/BtGatt.ScanManager( 2159): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: RESTARTING
D/BtGatt.ScanManager( 2159): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3773): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3773): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3773): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): setState: NOT_STARTED
,I/wpa_supplicant( 1189): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3773): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3773): Local services cleared successfully
I/jxcore-log( 3773): ok 66 Should be able to call stopBroadcasting without error
I/jxcore-log( 3773): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3773): Service requests cleared successfully
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c12eb7c added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): setDiscoveryMode: BLE_AND_WIFI -> WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to WIFI,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to WIFI,
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455027878239.3773,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): bind: Binding a new listener
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3773): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455027878239.3773","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): start: OK
I/io.jxcore.node.ConnectionHelper( 3773): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3773): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3773): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455027878239.3773, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): bind: Binding a new listener,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3773): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3773): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3773): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455027878239.3773","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455027878239.3773","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3773): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455027878239.3773","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: OK
I/wpa_supplicant( 1189): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455027878239.3773, mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3773): start: OK
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3773): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3773): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1189): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): P2P device discovery stopped successfully
,I/jxcore-log( 3773): ok 67 Should be able to call startBroadcasting without error
I/jxcore-log( 3773): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3773): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3773): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3773): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): onServerStopped
I/io.jxcore.node.ConnectionHelper( 3773): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): stopForRestart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3773): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3773): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3773): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3773): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3773): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3773): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3773): ok 68 Should be able to call stopBroadcasting without error
I/jxcore-log( 3773): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3773): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	,Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13614368 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455027878323.3773
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): bind: Binding a new listener
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3773): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455027878323.3773","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): start: OK
I/io.jxcore.node.ConnectionHelper( 3773): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3773): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455027878323.3773, mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3773): bind: Binding a new listener
W/BluetoothAdapter( 3773): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3773): Waiting for incoming connections...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3773): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3773): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3773): createAdvertiseData: From: 1455027878323.3773 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2159): registerClient() - UUID=9cfb3f6c-6d1b-4a3a-a82a-c053fe1e050e
,D/BtGatt.GattService( 2159): onClientRegistered() - UUID=9cfb3f6c-6d1b-4a3a-a82a-c053fe1e050e, clientIf=5
D/BluetoothLeScanner( 3773): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2159): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3773): setState: State changed from NOT_STARTED to STARTING
D/BtGatt.ScanManager( 2159): handling starting scan
,D/BtGatt.GattService( 2159): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,D/BtGatt.ScanManager( 2159): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2159): registerClient() - UUID=2ba2ddf3-8ace-4fde-a8b1-aa7a56208fec
,D/BtGatt.GattService( 2159): onClientRegistered() - UUID=2ba2ddf3-8ace-4fde-a8b1-aa7a56208fec, clientIf=6
D/BtGatt.GattService( 2159): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2159): callback done for clientIf - 5 status - 0
D/BluetoothLeAdvertiser( 3773): onClientRegistered() - status=0 clientIf=6
D/BtGatt.ScanManager( 2159): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2159): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.AdvertiseManager( 2159): message : 0
,D/BtGatt.AdvertiseManager( 2159): starting multi advertising
,D/BtGatt.GattService( 2159): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2159): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3773): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455027878323.3773","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455027878323.3773","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3773): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455027878323.3773","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3773): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): onIsWifiPeerDiscoveryStartedChanged: true,
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/wpa_supplicant( 1189): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: OK
I/io.jxcore.node.ConnectionHelper( 3773): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455027878323.3773, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3773): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3773): createAdvertiseData: From: 1455027878323.3773 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/jxcore-log( 3773): ok 69 Should be able to call startBroadcasting without error
I/jxcore-log( 3773): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/io.jxcore.node.ConnectionHelper( 3773): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3773): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3773): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3773): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3773): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3773): setState: NOT_STARTED
,D/BtGatt.AdvertiseManager( 2159): message : 1
D/BtGatt.AdvertiseManager( 2159): stop advertise for client 6
,D/BtGatt.GattService( 2159): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2159): Client app is not null!
D/BtGatt.GattService( 2159): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setState: State changed from STARTING to NOT_STARTED,
,D/BtGatt.GattService( 2159): registerClient() - UUID=cf94ffd3-1321-4973-8fe5-2688e1972d3c,
,D/BtGatt.GattService( 2159): onClientRegistered() - UUID=cf94ffd3-1321-4973-8fe5-2688e1972d3c, clientIf=6,
D/BluetoothLeAdvertiser( 3773): onClientRegistered() - status=0 clientIf=6,
D/BtGatt.AdvertiseManager( 2159): message : 0
,D/BtGatt.AdvertiseManager( 2159): starting multi advertising
,D/BtGatt.GattService( 2159): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2159): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3773): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3773): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3773): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3773): setState: State changed from STARTING to RUNNING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3773): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3773): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3773): stop
,V/GoogleAuthProtoRequest( 3834): [417] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3834): [417] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3834): [417] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3834): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3834): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3834): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3834): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,V/KeepSync( 4016): Connecting to GoogleApiClient
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4016): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1376): Explicit concurrent mark sweep GC freed 70655(3MB) AllocSpace objects, 8(740KB) LOS objects, 36% free, 27MB/43MB, paused 1.564ms total 58.138ms
,E/KeepSync( 4016): IOException
E/KeepSync( 4016): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4016): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4016): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4016): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4016): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4016): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4016): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4016): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4016): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4016): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4016): 	... 10 more
W/KeepSync( 4016): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 317202, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1376): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1376): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1376): 	at com.google.android.gms.auth.p.d(SourceFile:599)
,W/GLSActivity( 1376): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1376): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1376): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1376): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3582): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3582): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3582): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3582): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3582): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3582): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3582): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3582): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2b7853c5}
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2b7853c5}
,I/BooksSync( 3999): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3999): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3999): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3999): Soft error
E/BooksSync( 3999): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3999): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3999): Sync error
E/BooksSync( 3999): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3999): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3999): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 351527, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config_util( 2159): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1189): P2P-FIND-STOPPED 
,I/art     (  823): Explicit concurrent mark sweep GC freed 32252(1466KB) AllocSpace objects, 9(709KB) LOS objects, 31% free, 34MB/50MB, paused 2.310ms total 95.115ms
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3238): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3238): 	at jdm.a(PG:82)
E/HttpOperation( 3238): 	at jcs.o(PG:406)
E/HttpOperation( 3238): 	at jcn.a(PG:1379)
E/HttpOperation( 3238): 	at jcs.i(PG:143)
E/HttpOperation( 3238): 	at blb.a(PG:3937)
E/HttpOperation( 3238): 	at czp.a(PG:18188)
E/HttpOperation( 3238): 	at czp.a(PG:9081)
E/HttpOperation( 3238): 	at czq.run(PG:1686)
E/HttpOperation( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3238): 	at jdj.a(PG:4091)
E/HttpOperation( 3238): 	at jdj.a(PG:1125)
E/HttpOperation( 3238): 	at jdm.a(PG:77)
E/HttpOperation( 3238): 	... 12 more
E/HttpOperation( 3238): Caused by: faj: BadAuthentication
E/HttpOperation( 3238): 	at fal.a(PG:38)
E/HttpOperation( 3238): 	at jdj.a(PG:4089)
E/HttpOperation( 3238): 	... 14 more
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3238): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3238): 	at jdm.a(PG:82)
E/HttpOperation( 3238): 	at jcs.o(PG:406)
E/HttpOperation( 3238): 	at jcn.a(PG:1379)
E/HttpOperation( 3238): 	at jcs.i(PG:143)
E/HttpOperation( 3238): 	at hec.a(PG:42)
E/HttpOperation( 3238): 	at hee.a(PG:102)
E/HttpOperation( 3238): 	at czr.a(PG:65)
E/HttpOperation( 3238): 	at kka.a(PG:108)
E/HttpOperation( 3238): 	at czp.a(PG:19176)
E/HttpOperation( 3238): 	at czp.a(PG:9081)
E/HttpOperation( 3238): 	at czq.run(PG:1686)
E/HttpOperation( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3238): 	at jdj.a(PG:4091)
E/HttpOperation( 3238): 	at jdj.a(PG:1125)
E/HttpOperation( 3238): 	at jdm.a(PG:77)
E/HttpOperation( 3238): 	... 15 more
E/HttpOperation( 3238): Caused by: faj: BadAuthentication
E/HttpOperation( 3238): 	at fal.a(PG:38)
E/HttpOperation( 3238): 	at jdj.a(PG:4089)
E/HttpOperation( 3238): 	... 17 more
,E/ExperimentLoader( 3238): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3238): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3238): 	at jdm.a(PG:82)
E/ExperimentLoader( 3238): 	at jcs.o(PG:406)
E/ExperimentLoader( 3238): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3238): 	at jcs.i(PG:143)
E/ExperimentLoader( 3238): 	at hec.a(PG:42)
E/ExperimentLoader( 3238): 	at hee.a(PG:102)
E/ExperimentLoader( 3238): 	at czr.a(PG:65)
E/ExperimentLoader( 3238): 	at kka.a(PG:108)
E/ExperimentLoader( 3238): 	at czp.a(PG:19176)
E/ExperimentLoader( 3238): 	at czp.a(PG:9081)
E/ExperimentLoader( 3238): 	at czq.run(PG:1686)
E/ExperimentLoader( 3238): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3238): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3238): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3238): 	at jdm.a(PG:77)
,E/ExperimentLoader( 3238): 	... 15 more
E/ExperimentLoader( 3238): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3238): 	at fal.a(PG:38)
E/ExperimentLoader( 3238): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3238): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 380598, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3834): [419] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3834): [419] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3834): [419] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3834): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3834): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3834): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3834): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,V/KeepSync( 4016): Connecting to GoogleApiClient
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:30),
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1773): 	... 7 more
,V/KeepSync( 4016): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4016): IOException
E/KeepSync( 4016): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4016): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4016): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4016): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4016): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4016): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4016): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4016): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4016): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4016): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4016): 	... 10 more
W/KeepSync( 4016): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 558314, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,I/ActivityManager(  823): Start proc 4247:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/BooksSync( 3999): Starting books sync for 61035162, extras: ade
,I/GAv4    ( 4247): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4247):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4247):   adb logcat -s GAv4
,I/BooksConfig( 3999): GmsCore Version = 7.8.99 (2134222-430)
,W/GAv4    ( 4247): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4247): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4247): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3999): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3999): Soft error
E/BooksSync( 3999): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3999): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3999): Sync error
E/BooksSync( 3999): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3999): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3999): Finished books sync
,I/ActivityManager(  823): Killing 2464:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 626895, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3238): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3238): 	at jdm.a(PG:82)
E/HttpOperation( 3238): 	at jcs.o(PG:406)
E/HttpOperation( 3238): 	at jcn.a(PG:1379)
E/HttpOperation( 3238): 	at jcs.i(PG:143)
E/HttpOperation( 3238): 	at blb.a(PG:3937)
E/HttpOperation( 3238): 	at czp.a(PG:18188)
E/HttpOperation( 3238): 	at czp.a(PG:9081)
E/HttpOperation( 3238): 	at czq.run(PG:1686)
E/HttpOperation( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3238): 	at jdj.a(PG:4091)
E/HttpOperation( 3238): 	at jdj.a(PG:1125)
E/HttpOperation( 3238): 	at jdm.a(PG:77)
E/HttpOperation( 3238): 	... 12 more
E/HttpOperation( 3238): Caused by: faj: BadAuthentication
E/HttpOperation( 3238): 	at fal.a(PG:38)
E/HttpOperation( 3238): 	at jdj.a(PG:4089)
E/HttpOperation( 3238): 	... 14 more
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3238): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3238): 	at jdm.a(PG:82)
E/HttpOperation( 3238): 	at jcs.o(PG:406)
E/HttpOperation( 3238): 	at jcn.a(PG:1379)
E/HttpOperation( 3238): 	at jcs.i(PG:143)
E/HttpOperation( 3238): 	at hec.a(PG:42)
E/HttpOperation( 3238): 	at hee.a(PG:102)
E/HttpOperation( 3238): 	at czr.a(PG:65)
E/HttpOperation( 3238): 	at kka.a(PG:108)
E/HttpOperation( 3238): 	,at czp.a(PG:19176)
E/HttpOperation( 3238): 	at czp.a(PG:9081)
E/HttpOperation( 3238): 	at czq.run(PG:1686)
E/HttpOperation( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3238): 	at jdj.a(PG:4091)
E/HttpOperation( 3238): 	at jdj.a(PG:1125)
E/HttpOperation( 3238): 	at jdm.a(PG:77)
E/HttpOperation( 3238): ,	... 15 more
E/HttpOperation( 3238): Caused by: faj: BadAuthentication
E/HttpOperation( 3238): 	at fal.a(PG:38)
E/HttpOperation( 3238): 	at jdj.a(PG:4089)
E/HttpOperation( 3238): 	... 17 more
E/ExperimentLoader( 3238): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3238): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3238): 	at jdm.a(PG:82)
E/ExperimentLoader( 3238): 	at jcs.o(PG:406)
E/ExperimentLoader( 3238): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3238): 	at jcs.i(PG:143)
E/ExperimentLoader( 3238): 	at hec.a(PG:42)
E/ExperimentLoader( 3238): 	at hee.a(PG:102)
E/ExperimentLoader( 3238): 	at czr.a(PG:65)
E/ExperimentLoader( 3238): 	at kka.a(PG:108)
E/ExperimentLoader( 3238): 	at czp.a(PG:19176)
E/ExperimentLoader( 3238): 	at czp.a(PG:9081)
E/ExperimentLoader( 3238): 	at czq.run(PG:1686)
E/ExperimentLoader( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3238): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3238): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3238): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3238): 	at jdm.a(PG:77)
E/ExperimentLoader( 3238): 	... 15 more
E/ExperimentLoader( 3238): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3238): 	at fal.a(PG:38)
E/ExperimentLoader( 3238): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3238): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 654839, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3834): [420] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1376): Explicit concurrent mark sweep GC freed 52335(2MB) AllocSpace objects, 15(1653KB) LOS objects, 36% free, 27MB/43MB, paused 1.609ms total 69.661ms
,I/art     (  823): Explicit concurrent mark sweep GC freed 35805(1621KB) AllocSpace objects, 12(474KB) LOS objects, 31% free, 34MB/50MB, paused 1.371ms total 57.911ms
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3834): [420] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3834): [420] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3834): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3834): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3834): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3834): 	at com.a.a.k.run(SourceFile:110)
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1ce6d3ab}
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1ce6d3ab}
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,V/KeepSync( 4016): Connecting to GoogleApiClient
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1773): Handling authorization failure,
E/ClientConnectionOperation( 1773): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/ClientConnectionOperation( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1773): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1773): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
,E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1773): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220),
E/ClientConnectionOperation( 1773): 	... 7 more
,V/KeepSync( 4016): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4016): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4016): IOException
E/KeepSync( 4016): com.google.android.apiary.AuthenticationException: Could not get an auth token,
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4016): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4016): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4016): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4016): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4016): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4016): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4016): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4016): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4016): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4016): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4016): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4016): 	... 10 more
,W/KeepSync( 4016): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1039769, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,I/BooksSync( 3999): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3999): GmsCore Version = 7.8.99 (2134222-430),
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3999): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3999): Soft error
,E/BooksSync( 3999): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3999): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3999): Sync error
E/BooksSync( 3999): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3999): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3999): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1125892, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,I/EventLogService( 1773): Opted in for usage reporting,
,I/EventLogService( 1773): Aggregate from 1455026745271 (log), 1455026745271 (data)
,V/GoogleAuthProtoRequest( 3834): [421] a.<init>: mAccountName set to: thalitester@gmail.com
,W/EventLogAggregator( 1773): Unknown tag: snet_gcore
W/EventLogAggregator( 1773): Unknown tag: snet_launch_service
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceDumpSys( 1773): dumping service [account]
W/ExperimentUpdateService( 3834): [421] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3834): [421] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3834): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3834): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3834): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3834): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3834): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3834): 	at com.a.a.k.run(SourceFile:110)
,D/GCM     ( 1376): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3238): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3238): 	at jdm.a(PG:82)
E/HttpOperation( 3238): 	at jcs.o(PG:406)
E/HttpOperation( 3238): 	at jcn.a(PG:1379)
E/HttpOperation( 3238): 	at jcs.i(PG:143)
E/HttpOperation( 3238): 	at blb.a(PG:3937)
E/HttpOperation( 3238): 	at czp.a(PG:18188)
E/HttpOperation( 3238): 	at czp.a(PG:9081)
E/HttpOperation( 3238): 	at czq.run(PG:1686)
E/HttpOperation( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3238): 	at jdj.a(PG:4091)
E/HttpOperation( 3238): 	at jdj.a(PG:1125)
E/HttpOperation( 3238): 	at jdm.a(PG:77)
E/HttpOperation( 3238): 	... 12 more
E/HttpOperation( 3238): Caused by: faj: BadAuthentication
E/HttpOperation( 3238): 	at fal.a(PG:38)
E/HttpOperation( 3238): 	at jdj.a(PG:4089)
E/HttpOperation( 3238): 	... 14 more
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3238): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3238): 	at jdm.a(PG:82)
E/HttpOperation( 3238): 	at jcs.o(PG:406)
E/HttpOperation( 3238): 	at jcn.a(PG:1379)
E/HttpOperation( 3238): 	at jcs.i(PG:143)
E/HttpOperation( 3238): 	at hec.a(PG:42)
E/HttpOperation( 3238): 	at hee.a(PG:102)
E/HttpOperation( 3238): 	at czr.a(PG:65)
E/HttpOperation( 3238): 	at kka.a(PG:108)
E/HttpOperation( 3238): 	at czp.a(PG:19176)
E/HttpOperation( 3238): 	at czp.a(PG:9081)
E/HttpOperation( 3238): 	at czq.run(PG:1686)
E/HttpOperation( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3238): 	at jdj.a(PG:4091)
E/HttpOperation( 3238): 	at jdj.a(PG:1125)
E/HttpOperation( 3238): 	at jdm.a(PG:77)
E/HttpOperation( 3238): 	... 15 more
E/HttpOperation( 3238): Caused by: faj: BadAuthentication
E/HttpOperation( 3238): 	at fal.a(PG:38)
E/HttpOperation( 3238): 	at jdj.a(PG:4089)
E/HttpOperation( 3238): 	... 17 more
,E/ExperimentLoader( 3238): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3238): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3238): 	at jdm.a(PG:82)
E/ExperimentLoader( 3238): 	at jcs.o(PG:406)
E/ExperimentLoader( 3238): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3238): 	at jcs.i(PG:143)
E/ExperimentLoader( 3238): 	at hec.a(PG:42)
E/ExperimentLoader( 3238): 	at hee.a(PG:102)
E/ExperimentLoader( 3238): 	at czr.a(PG:65)
E/ExperimentLoader( 3238): 	at kka.a(PG:108)
E/ExperimentLoader( 3238): 	at czp.a(PG:19176)
E/ExperimentLoader( 3238): 	at czp.a(PG:9081)
E/ExperimentLoader( 3238): 	at czq.run(PG:1686)
E/ExperimentLoader( 3238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3238): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3238): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3238): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3238): 	at jdm.a(PG:77)
E/ExperimentLoader( 3238): 	... 15 more
E/ExperimentLoader( 3238): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3238): 	at fal.a(PG:38)
E/ExperimentLoader( 3238): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3238): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1151754, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btm  ( 2159): Request to stop oneshot timer with non empty queue
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,I/art     (  823): Explicit concurrent mark sweep GC freed 42585(1993KB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 1.397ms total 89.140ms
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,I/UsageStatsService(  823): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4401): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4401): CheckJNI is OFF
D/AndroidRuntime( 4401): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  823): Killing 3773:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  823): Skipping PackageSetting{5448ed1 com.example.hello/10273} due to missing metadata
E/libprocessgroup(  823): failed to kill 1 processes for processgroup 3773
W/ActivityManager(  823): Force removing ActivityRecord{38d7a6c7 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
E/JavaBinder(  823): !!! FAILED BINDER TRANSACTION !!!
D/BtGatt.GattService( 2159): Binder is dead - unregistering client (5)!
D/BtGatt.GattService( 2159): Binder is dead - unregistering client (6)!
D/WifiService(  823): Client connection lost with reason: 4
D/BtGatt.GattService( 2159): stopScan() - queue size =1
D/BtGatt.AdvertiseManager( 2159): message : 1
D/BtGatt.AdvertiseManager( 2159): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2159): app died - unregistering client : 6
D/BtGatt.GattService( 2159): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2159): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2159): stop scan
D/BtGatt.ScanManager( 2159): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2159): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2159): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.ScanManager( 2159): app died, unregister client - 5
D/BtGatt.GattService( 2159): unregisterClient() - clientIf=6
D/BtGatt.GattService( 2159): unregisterClient() - clientIf=5
D/BtGatt.GattService( 2159): onAdvertiseInstanceDisabled() - clientIf=6, status=0
E/BtGatt.ContextMap( 2159): Context not found for ID 6
W/InputDispatcher(  823): channel '11a57ac0 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  823): channel '11a57ac0 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  823): Attempted to unregister already unregistered input channel '11a57ac0 com.test.thalitest/com.test.thalitest.MainActivity (server)'
W/WindowManager(  823): Failed looking up window
W/WindowManager(  823): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@f2f5443 does not exist
W/WindowManager(  823): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
W/WindowManager(  823): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
W/WindowManager(  823): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1142)
W/WindowManager(  823): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
I/WindowState(  823): WIN DEATH: null
V/ActivityManager(  823): Display changed displayId=0
I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
I/InputReader(  823): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1236): resetDictionaries() : en_US
D/TaskPersister(  823): removeObsoleteFile: deleting file=28_task.xml
D/BuaReceiver( 3473): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/art     ( 1507): Explicit concurrent mark sweep GC freed 3563(219KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 360us total 55.134ms
I/Keyboard.Facilitator.DecoderInitializer( 1236): run()
I/ActivityManager(  823): Start proc 4417:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     ( 1067): Explicit concurrent mark sweep GC freed 71676(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 788us total 73.238ms
I/art     (  370): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 216us total 12.299ms
I/art     (  823): Explicit concurrent mark sweep GC freed 11771(929KB) AllocSpace objects, 8(316KB) LOS objects, 31% free, 34MB/50MB, paused 1.880ms total 77.367ms
W/InputMethodManagerService(  823): Got RemoteException sending setActive(false) notification to pid 3773 uid 10265
I/Decoder ( 1236): createOrResetDecoder
I/art     (  370): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 376us total 10.730ms
I/art     (  823): WaitForGcToComplete blocked for 72.476ms for cause Explicit
I/Keyboard.Facilitator( 1236): onFinishInput()
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 192us total 11.960ms
I/ConfigService( 1376): onCreate
I/art     ( 1347): Explicit concurrent mark sweep GC freed 4985(364KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 644us total 25.356ms
W/LocationOracleImpl( 1507): Best location was null
I/HotwordRecognitionRnr( 1507): Starting hotword detection.
I/MicrophoneInputStream( 1507): mic_starting com.google.android.apps.gsa.speech.audio.u@3c63007d
D/JobSchedulerService(  823): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  823): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/AudioFlinger(  359): AudioFlinger's thread 0xb40ed000 ready to run
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1507): mic_started com.google.android.apps.gsa.speech.audio.u@3c63007d
I/art     ( 1376): Explicit concurrent mark sweep GC freed 64599(3MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 1.389ms total 49.453ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1236): run()
D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
I/Keyboard.Facilitator.MainLanguageModelLoader( 1236): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1236): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1236): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1236): run()
I/StatsUtilsManager( 1236): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1236): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 4417): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  823): Start proc 4456:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/HotwordWorker( 1507): onReady
D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@21218531}
I/art     (  823): Explicit concurrent mark sweep GC freed 6704(317KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 1.735ms total 188.180ms
I/ContactLocale( 4417): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=78.00 rxSuccessRate=91.25 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=46.00 rxSuccessRate=151.62 targetRoamBSSID=any RSSI=-51
I/ActivityManager(  823): Start proc 4475:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
D/Launcher.Workspace( 1347): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1347): 11683562 - stripEmptyScreens()
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660486931
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/art     ( 4401): System.exit called, status: 0
I/AndroidRuntime( 4401): VM exiting with result code 0.
W/ContextImpl( 4475): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1376): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1376): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  823): Killing 3393:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
I/kickstart(  878): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  878): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  878): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  878): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PackageBroadcastService( 1773): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraModuleLdr( 1773): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1773): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1773): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1773): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/UpdateIcingCorporaServi( 1507): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1347): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1b749254 new=com.google.android.velvet.VelvetApplication@1b749254
E/SQLiteLog( 1347): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 1773): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1773): Process: com.google.android.gms, PID: 1773
E/AndroidRuntime( 1773): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1773): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1773): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1773): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1773): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1773): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1773): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1773): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1773): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1773): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1773): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1773): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1773): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1773): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1773): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1773): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1773): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1507): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/ActivityManager(  823): Start proc 4505:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/ActivityManager(  823): Start proc 4522:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 1507): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 1507): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1507): Process: com.google.android.googlequicksearchbox:search, PID: 1507
E/AndroidRuntime( 1507): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1507): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1507): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1507): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1507): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1507): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1507): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1507): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1507): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1507): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1507): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1507): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1507): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1507): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1507): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1507): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1507): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1507): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1507): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1507): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1507): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ResourcesManager(  823): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  823): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/SQLiteLog( 1773): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1773): disk I/O error (code 3850)
E/DriveAsyncService( 1773): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1773): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1773): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1773): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1773): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1773): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1773): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1773): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1773): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1773): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1773): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1773): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1773): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1773): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1773): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  823): Can't write: system_app_crash
E/DropBoxManagerService(  823): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  823): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  823): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  823): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  823): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  823): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  823): 	... 5 more
D/OpenGLRenderer(  823): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  823): Validating map...
I/LocationSettingsChecker( 1773): Removing dialog suppression flag for package com.test.thalitest
E/DropBoxManagerService(  823): Can't write: system_app_crash
E/DropBoxManagerService(  823): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  823): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  823): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  823): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  823): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  823): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  823): 	... 5 more
E/SQLiteDatabase( 1773): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1773): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1773): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1773): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1773): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1773): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1773): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1773): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1773): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1773): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1773): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1773): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1773): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1773): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1773): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1773): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1773): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1773): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1773): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1773): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1773): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1773): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1773): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1773): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  823): Start proc 4545:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/SQLiteDatabase( 1773): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1773): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1773): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1773): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1773): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1773): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1773): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1773): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1773): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1773): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1773): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1773): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1773): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1773): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1773): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1773): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1773): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1773): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1773): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1773): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1773): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1773): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1773): Opened phenotype.db in read-only mode
W/SQLiteOpenHelper( 1773): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1773): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1773): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1773): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1773): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1773): Sending signal. PID: 1773 SIG: 9
E/lowmemorykiller(  255): Error writing /proc/1773/oom_score_adj; errno=22
I/OpenGLRenderer(  823): Initialized EGL, version 1.4
D/OpenGLRenderer(  823): Enabling debug mode 0
E/lowmemorykiller(  255): Error writing /proc/1773/oom_score_adj; errno=22
W/ResourcesManager( 4545): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4545): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 4545): VM with version 2.1.0 has multidex support
I/MultiDex( 4545): install
I/MultiDex( 4545): VM has multidex support, MultiDex support library is disabled.
D/WifiService(  823): Client connection lost with reason: 4
I/ActivityManager(  823): Process com.google.android.gms (pid 1773) has died
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 1000ms
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10999ms
V/JNIHelp ( 4545): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ProviderInstaller( 4545): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4545): Failed to open lock file
W/NativeLibraryUtils( 4545): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4545): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4545): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4545): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4545): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4545): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4545): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4545): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4545): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4545): 	... 3 more
I/ActivityManager(  823): Killing 3067:com.google.android.music:main/u0a66 (adj 15): empty #17
I/HotwordDetector( 1507): Closing mic
I/MicrophoneInputStream( 1507): mic_close com.google.android.apps.gsa.speech.audio.u@3c63007d
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1507): Hotword detection finished
I/HotwordRecognitionRnr( 1507): Stopping hotword detection.
E/Search.SharedPreferencesProto( 1507): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/GAv4    ( 4505): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4505):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4505):   adb logcat -s GAv4
W/GAv4    ( 4505): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4505): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4505): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4505): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4505): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4505): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4505): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4505): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4505): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4505): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4505): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4505): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4505): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4505): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4505): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4505): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4505): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4505): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4505): Opening the database failed, dropping the table and recreating it
E/SQLiteDatabase( 4505): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4505): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4505): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4505): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4505): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4505): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4505): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4505): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4505): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4505): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4505): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4505): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4505): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4505): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4505): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4505): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4505): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4505): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4505): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4505): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4505): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4505): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4505): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4505): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4505): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/ActivityManager(  823): Start proc 4581:com.google.android.gms/u0a11 for service com.google.android.gms/.analytics.service.AnalyticsService
W/ResourcesManager( 4581): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4581): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 4581): VM with version 2.1.0 has multidex support
I/MultiDex( 4581): install
I/MultiDex( 4581): VM has multidex support, MultiDex support library is disabled.
E/SQLiteDatabase( 4505): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4505): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4505): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4505): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4505): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4505): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4505): 	at aej.c(PG:139)
E/SQLiteDatabase( 4505): 	at aej.b(PG:398)
E/SQLiteDatabase( 4505): 	at agf.f(PG:417)
E/SQLiteDatabase( 4505): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4505): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4505): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4505): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4505): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4505): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4505): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4505): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4505): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4505): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4505): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4505): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4505): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4505): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4505): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4505): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4505): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 4505): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4505): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  823): Start proc 4605:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  823): Killing 3860:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
V/JNIHelp ( 4505): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/SQLiteDatabase( 4581): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4581): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4581): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4581): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4581): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 4581): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 4581): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4581): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4581): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4581): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4581): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4581): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4581): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4581): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4581): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4581): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4581): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4581): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4581): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 4581): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 4581): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4581): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4581): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4581): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4581): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4581): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4581): 	at java.lang.Thread.run(Thread.java:818)
I/ProviderInstaller( 4505): Installed default security provider GmsCore_OpenSSL
E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/SQLiteDatabase( 4505): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4505): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4505): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4505): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4505): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4505): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4505): 	at aej.c(PG:139)
E/SQLiteDatabase( 4505): 	at aej.a(PG:358)
E/SQLiteDatabase( 4505): 	at aej.a(PG:345)
E/SQLiteDatabase( 4505): 	at agf.c(PG:884)
E/SQLiteDatabase( 4505): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 4505): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4505): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4505): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4505): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4505): Failed to query Account133 object
E/AbstractDatabaseInstance( 4505): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4505): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4505): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4505): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4505): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4505): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4505): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4505): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4505): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4505): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 4505): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 4505): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AbstractDatabaseInstance( 4505): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4505): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 4505): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4505): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4505): 	at java.lang.Thread.run(Thread.java:818)
V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SharedPreferencesImpl( 4505): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
E/SQLiteDatabase( 4605): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4605): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4605): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4605): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4605): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteD,atabase( 4605): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4605): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4605): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4605): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4605): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4605): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4605): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4605): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4605): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4605): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4605): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4605): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4605): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4605): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4605): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4605): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4605): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4605): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4605): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4605): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4605): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4605): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4605): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4605): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4605): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
I/ActivityManager(  823): Killing 3880:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
D/AndroidRuntime( 4605): Shutting down VM
E/AndroidRuntime( 4605): FATAL EXCEPTION: main
E/AndroidRuntime( 4605): Process: com.android.documentsui, PID: 4605
E/AndroidRuntime( 4605): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4605): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4605): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4605): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4605): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4605): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4605): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4605): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4605): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4605): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4605): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4605): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4605): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4605): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4605): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4605): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4605): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4605): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4605): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4605): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4605): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4605): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4605): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4605): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4605): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4605): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4605): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4605): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4605): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4605): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4605): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4605): 	... 9 more
V/JNIHelp ( 4581): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ProviderInstaller( 4581): Installed default security provider GmsCore_OpenSSL
E/DropBoxManagerService(  823): Can't write: system_app_crash
E/DropBoxManagerService(  823): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  823): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  823): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  823): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  823): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  823): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  823): 	... 5 more
D/GCM     ( 1376): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  823): Start proc 4631:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider

```
