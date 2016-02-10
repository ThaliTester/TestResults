#### Test 58918757c0fcaf3_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/CheckinService( 1773): Done disabling old GoogleServicesFramework version
,I/GAV2    ( 3585): Thread[GAThread,5,main]: No campaign data found.
D/AndroidRuntime( 3757): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3757): CheckJNI is OFF
D/AndroidRuntime( 3757): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{323dfccc token=Token{d67a6ff ActivityRecord{2cef9e1e u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  821): Adding window Window{2d1576f7 u0 Starting com.test.thalitest} at 2 of 7 (after Window{3b1636df u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3757): Shutting down VM
I/HotwordDetector( 1504): Closing mic
I/MicrophoneInputStream( 1504): mic_close com.google.android.apps.gsa.speech.audio.u@1fd4f044
I/ActivityManager(  821): Start proc 3773:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1504): Stopping hotword detection.
I/HotwordRecognitionRnr( 1504): Hotword detection finished
I/ActivityManager(  821): Killing 3313:com.qualcomm.timeservice/1000 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658946835
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3773): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3773): Time to load native libraries: 1 ms (timestamps 7722-7723)
I/LibraryLoader( 3773): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3773): Binding Chromium to main looper Looper (main, tid 1) {354897ce}
I/LibraryLoader( 3773): Expected native library version number "",actual native library version number ""
I/chromium( 3773): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3773): Initializing chromium process, singleProcess=true
W/art     ( 3773): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3773): ApplicationContext is null in ApplicationStatus
W/chromium( 3773): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3773): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3773): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3773): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1192301:true
W/art     ( 3773): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3773): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3773): CordovaWebView is running on device made by: motorola
W/art     ( 3773): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3773): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  821): Killing 3333:com.google.android.deskclock/u0a44 (adj 15): empty #17
D/OpenGLRenderer( 3773): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3773): Validating map...
V/WindowManager(  821): Adding window Window{2bafce71 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2d1576f7 u0 Starting com.test.thalitest})
W/chromium( 3773): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3773): Initialized EGL, version 1.4
D/OpenGLRenderer( 3773): Enabling debug mode 0
I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +853ms
I/Keyboard.Facilitator( 1228): onFinishInput()
W/BindingManager( 3773): Cannot call determinedVisibility() - never saw a connection for the pid: 3773
I/ActivityManager(  821): Killing 3048:com.android.settings/1000 (adj 15): empty #17
D/JsMessageQueue( 3773): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3773): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576317312
,I/chromium( 3773): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3773): Initializing JXcore engine
W/jxcore-log( 3773): JXcore engine is ready
,W/Thread-422( 3828): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9508]" dev="sockfs" ino=9508 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-422( 3828): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-422( 3828): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9620]" dev="sockfs" ino=9620 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
,W/jxcore-log( 3773): Starting JXcore engine
,W/Thread-422( 3828): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21936]" dev="sockfs" ino=21936 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
,W/jxcore-log( 3773): Platform android
W/jxcore-log( 3773): 
,W/jxcore-log( 3773): Process ARCH arm
W/jxcore-log( 3773): 
,I/jxcore-log( 3773): JXcore Cordova bridge is ready!
I/jxcore-log( 3773): 
W/jxcore-log( 3773): JXcore engine is started
,I/jxcore-log( 3773): Toggling radios to true
I/jxcore-log( 3773): 
,D/BluetoothAdapter( 3773): enable(): BT is already enabled..!
,D/WifiService(  821): setWifiEnabled: true pid=3773, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  821): New client listening to asynchronous messages,
,I/jxcore-log( 3773): Radios toggled
I/jxcore-log( 3773): 
I/jxcore-log( 3773): My device name is: motorola-Nexus 6
I/jxcore-log( 3773): 
,I/wpa_supplicant( 1126): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1,
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1349): Read error: ssl=0x9cda0800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1349): SSL shutdown failed: ssl=0x9cda0800: I/O error during system call, Broken pipe
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  821): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524292
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
,D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  821): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/NetworkChangeNotifierAutoDetect( 1504): Network connectivity changed, type is: 6
I/NetworkMonitor( 3069): type=WIFI subType= reason=null isConnected=false
,V/MusicLeanback( 3069): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1287): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1287): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/WifiConfigStore(  821): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): will read network variables netId=0
,I/ActivityManager(  821): Start proc 3835:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,E/GpsLocationProvider(  821): No APN found to select.
,D/PhoneInterfaceManager( 1287): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1287): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,I/ActivityManager(  821): Start proc 3861:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  821): Killing 2565:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/SprintDMReceiver( 3861): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3861): simOperator:  IMSI: null
D/SprintDMReceiver( 3861): Not Sprint UICC, don't do anything.
,I/ActivityManager(  821): Killing 3409:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/SystemUpdateService( 1773): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1773): onCreate,
,D/SystemUpdateService( 1773): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1773): active receiver: enabled
,I/SystemUpdateService( 1773): showing system update notification
,I/iu.Environment( 1773): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1773): num queued entries: 0
,I/iu.UploadsManager( 1773): num updated entries: 0
I/iu.SyncManager( 1773): NEXT; no task
I/ValidateNoPeople(  821): skipping global notification
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1773): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000,
,V/SystemUpdateService( 1773): retry (wakeup: false) in 3599949 ms
,D/SystemUpdateService( 1773): onDestroy
,I/ActivityManager(  821): Start proc 3881:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 3652): connection state changed from UNKNOWN to DISCONNECTED
,I/GAv4    ( 3881): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3881):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3881):   adb logcat -s GAv4
,W/GAv4    ( 3881): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3881): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3881): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3881): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3881): Time to load native libraries: 2 ms (timestamps 1839-1841)
,I/LibraryLoader( 3881): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3881): Binding Chromium to main looper Looper (main, tid 1) {18b9a442}
I/LibraryLoader( 3881): Expected native library version number "",actual native library version number ""
I/chromium( 3881): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3881): Initializing chromium process, singleProcess=true
,W/art     ( 3881): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3881): ApplicationContext is null in ApplicationStatus
,W/chromium( 3881): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3881): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3881): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3881): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3881): Requires BLUETOOTH permission
,I/NSApplication( 3881): Starting up...
,I/ActivityManager(  821): Start proc 3937:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  821): Killing 3429:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3476:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/wpa_supplicant( 1126): wlan0: Trying to associate with SSID 'NG7005g'
,V/MusicLeanback( 3069): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3861): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3861): simOperator:  IMSI: null
,D/SprintDMReceiver( 3861): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1773): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1773): onCreate
,D/SystemUpdateService( 1773): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1773): active receiver: enabled
,I/SystemUpdateService( 1773): showing system update notification
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1773): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1773): retry (wakeup: false) in 3599976 ms
,D/SystemUpdateService( 1773): onDestroy
,I/wpa_supplicant( 1126): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1126): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP],
I/wpa_supplicant( 1126): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  353): Setting iface cfg
E/WifiStateMachine(  821): Start Dhcp Watchdog 2
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 167
E/WifiStateMachine(  821):  RSSI mgmt: -52
E/WifiStateMachine(  821):  BE :  rx=148 tx=139 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 9461 tx_time=203 rx_time=340 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 3967): version 5.5.6 starting
,I/dhcpcd  ( 3967): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3967): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3967): wlan0: leased 192.168.1.122 for 86400 seconds
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{b84de3a u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 101
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  821): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821):    accepting network in place of null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  821): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3069): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1504): Network connectivity changed, type is: 2
,V/MusicLeanback( 3069): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1287): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1287): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 3861): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3861): simOperator:  IMSI: null
D/SprintDMReceiver( 3861): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1773): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1773): onCreate
,D/SystemUpdateService( 1773): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1773): active receiver: enabled
,I/SystemUpdateService( 1773): showing system update notification
,I/iu.Environment( 1773): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1773): num queued entries: 0
I/iu.UploadsManager( 1773): num updated entries: 0
,I/ValidateNoPeople(  821): skipping global notification
,I/iu.SyncManager( 1773): NEXT; no task
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1773): retry (wakeup: false) in 3599979 ms
I/Kids    ( 1773): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1773): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Feb 2016 17:06:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455123996451], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455123996434]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Validated
,D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,V/Herrevad( 1773): NQAS connected
,I/Babel   ( 3652): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1349): Connected
,D/GCM     ( 1349): Message class com.google.f.a.a.p
,I/ActivityManager(  821): Killing 3612:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
,I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
,I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
,I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
,I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
,I/jxcore-log( 3773): 
,I/art     (  821): Explicit concurrent mark sweep GC freed 53111(2MB) AllocSpace objects, 10(160KB) LOS objects, 31% free, 34MB/50MB, paused 1.335ms total 99.512ms
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1349): Explicit concurrent mark sweep GC freed 27922(1495KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.038ms total 22.789ms
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3516): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3516): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3516): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  821): Killing 1423:android.process.acore/u0a5 (adj 15): empty #17
,E/libprocessgroup(  821): failed to kill 1 processes for processgroup 1423
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js,
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3773): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.34 rxSuccessRate=11.69 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3773): Test app app.js loaded
I/jxcore-log( 3773): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Advertise mode: 1, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Advertise TX power level: 1, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3773): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dfb8e3e added. We now have 1 listener(s)
,I/jxcore-log( 3773): BLE advertisement is supported
I/jxcore-log( 3773): 
,I/chromium( 3773): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.67 rxSuccessRate=6.84 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.46 rxSuccessRate=5.11 targetRoamBSSID=any RSSI=-52
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3516): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3516): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3516): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  821): Start proc 4022:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,V/KeepSync( 4022): Connecting to GoogleApiClient
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4022): GoogleApiClient failed to connect with error code: 4
,E/HttpOperation( 3239): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3239): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3239): 	at jdm.a(PG:82)
E/HttpOperation( 3239): 	at jcs.o(PG:406)
E/HttpOperation( 3239): 	at jcn.a(PG:1379)
E/HttpOperation( 3239): 	at jcs.i(PG:143)
E/HttpOperation( 3239): 	at blb.a(PG:3937)
E/HttpOperation( 3239): 	at czp.a(PG:18188)
E/HttpOperation( 3239): 	at czp.a(PG:9081)
E/HttpOperation( 3239): 	at czq.run(PG:1686)
E/HttpOperation( 3239): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3239): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3239): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3239): 	at jdj.a(PG:4091)
E/HttpOperation( 3239): 	at jdj.a(PG:1125)
E/HttpOperation( 3239): 	at jdm.a(PG:77)
E/HttpOperation( 3239): 	... 12 more
E/HttpOperation( 3239): Caused by: faj: BadAuthentication
E/HttpOperation( 3239): 	at fal.a(PG:38)
E/HttpOperation( 3239): 	at jdj.a(PG:4089)
E/HttpOperation( 3239): 	... 14 more
,E/SQLiteLog( 4022): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4022): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4022): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3239): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3239): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3239): 	at jdm.a(PG:82)
E/HttpOperation( 3239): 	at jcs.o(PG:406)
E/HttpOperation( 3239): 	at jcn.a(PG:1379)
E/HttpOperation( 3239): 	at jcs.i(PG:143)
E/HttpOperation( 3239): 	at hec.a(PG:42)
E/HttpOperation( 3239): 	at hee.a(PG:102)
E/HttpOperation( 3239): 	at czr.a(PG:65)
E/HttpOperation( 3239): 	at kka.a(PG:108)
,E/HttpOperation( 3239): 	at czp.a(PG:19176)
E/HttpOperation( 3239): 	at czp.a(PG:9081)
E/HttpOperation( 3239): 	at czq.run(PG:1686)
E/HttpOperation( 3239): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3239): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3239): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3239): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3239): 	at jdj.a(PG:4091)
E/HttpOperation( 3239): 	at jdj.a(PG:1125)
E/HttpOperation( 3239): ,	at jdm.a(PG:77)
E/HttpOperation( 3239): 	... 15 more
E/HttpOperation( 3239): Caused by: faj: BadAuthentication
E/HttpOperation( 3239): 	at fal.a(PG:38)
E/HttpOperation( 3239): 	at jdj.a(PG:4089)
E/HttpOperation( 3239): 	,... 17 more
E/ExperimentLoader( 3239): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3239): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3239): 	at jdm.a(PG:82)
E/ExperimentLoader( 3239): 	at jcs.o(PG:406)
E/ExperimentLoader( 3239): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3239): 	at jcs.i(PG:143)
E/ExperimentLoader( 3239): 	at hec.a(PG:42)
E/ExperimentLoader( 3239): 	at hee.a(PG:102)
E/ExperimentLoader( 3239): 	at czr.a(PG:65)
E/ExperimentLoader( 3239): 	at kka.a(PG:108)
E/ExperimentLoader( 3239): 	at czp.a(PG:19176)
E/ExperimentLoader( 3239): 	at czp.a(PG:9081)
,E/ExperimentLoader( 3239): 	at czq.run(PG:1686)
E/ExperimentLoader( 3239): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3239): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3239): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3239): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3239): 	at jdj.a(PG:4091),
E/ExperimentLoader( 3239): 	,at jdj.a(PG:1125)
E/ExperimentLoader( 3239): 	at jdm.a(PG:77)
E/ExperimentLoader( 3239): ,	... 15 more
E/ExperimentLoader( 3239): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3239): 	at fal.a(PG:38),
E/ExperimentLoader( 3239): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3239): 	... 17 more
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4022): IOException
E/KeepSync( 4022): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4022): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4022): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4022): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4022): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4022): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4022): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4022): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4022): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4022): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4022): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4022): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4022): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4022): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4022): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4022): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4022): 	... 10 more
W/KeepSync( 4022): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 74764, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Start proc 4055:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 75977, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1349): Explicit concurrent mark sweep GC freed 19923(1137KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.436ms total 62.295ms
,W/GAV2    ( 4055): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4055): Created application version: 3.6.8 (30608)
,I/BooksSync( 4055): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4055): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  821): Explicit concurrent mark sweep GC freed 36691(1731KB) AllocSpace objects, 7(112KB) LOS objects, 32% free, 33MB/49MB, paused 2.301ms total 93.901ms
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 4055): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4055): Soft error
E/BooksSync( 4055): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4055): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4055): Sync error,
E/BooksSync( 4055): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4055): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4055): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 77248, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/ActivityManager(  821): Killing 3585:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3556:com.google.android.gms:car/u0a11 (adj 15): empty #18
,E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3556
,I/GAV2    ( 4055): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.20 rxSuccessRate=2.91 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3516): [369] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3516): [369] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3516): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3516): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3516): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1228): run()
I/Keyboard.Facilitator( 1228): flushDynamicLanguageModels()
,I/ConfigService( 1349): onCreate
,I/ConfigService( 1349): onDestroy
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.42 rxSuccessRate=2.57 targetRoamBSSID=any RSSI=-52
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3516): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3516): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3516): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.32 rxSuccessRate=3.28 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (340 us)
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  278): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  821): Display changed displayId=0
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  278): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  821): Excessive delay in setPowerMode(): 268ms
,I/DreamManagerService(  821): Entering dreamland.
I/PowerManagerService(  821): Dozing...
,I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 12
,E/native  (  821): do suspend false
,I/Keyboard.Facilitator( 1228): onFinishInput()
,E/WifiStateMachine(  821): cancelDelayedScan -> 14
,E/native  (  821): do suspend true
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,V/KeepSync( 4022): Connecting to GoogleApiClient
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/HttpOperation( 3239): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 3239): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3239): 	at jdm.a(PG:82)
E/HttpOperation( 3239): 	at jcs.o(PG:406)
E/HttpOperation( 3239): 	at jcn.a(PG:1379)
E/HttpOperation( 3239): 	at jcs.i(PG:143)
E/HttpOperation( 3239): 	at blb.a(PG:3937)
E/HttpOperation( 3239): 	at czp.a(PG:18188)
E/HttpOperation( 3239): 	at czp.a(PG:9081)
E/HttpOperation( 3239): 	at czq.run(PG:1686)
E/HttpOperation( 3239): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/HttpOperation( 3239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3239): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3239): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3239): 	at jdj.a(PG:4091)
E/HttpOperation( 3239): 	at jdj.a(PG:1125)
E/HttpOperation( 3239): 	at jdm.a(PG:77)
E/HttpOperation( 3239): 	... 12 more
E/HttpOperation( 3239): Caused by: faj: BadAuthentication
E/HttpOperation( 3239): 	,at fal.a(PG:38)
E/HttpOperation( 3239): 	at jdj.a(PG:4089)
E/HttpOperation( 3239): 	... 14 more
V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4022): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4022): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4022): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4022): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3239): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3239): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3239): 	at jdm.a(PG:82)
E/HttpOperation( 3239): 	at jcs.o(PG:406)
E/HttpOperation( 3239): 	at jcn.a(PG:1379)
E/HttpOperation( 3239): 	at jcs.i(PG:143)
E/HttpOperation( 3239): 	at hec.a(PG:42)
E/HttpOperation( 3239): 	at hee.a(PG:102)
E/HttpOperation( 3239): 	at czr.a(PG:65)
E/HttpOperation( 3239): 	at kka.a(PG:108)
E/HttpOperation( 3239): 	at czp.a(PG:19176)
E/HttpOperation( 3239): 	at czp.a(PG:9081)
E/HttpOperation( 3239): 	at czq.run(PG:1686)
E/HttpOperation( 3239): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3239): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3239): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3239): 	at jdj.a(PG:4091)
E/HttpOperation( 3239): 	at jdj.a(PG:1125)
E/HttpOperation( 3239): 	at jdm.a(PG:77)
E/HttpOperation( 3239): 	... 15 more
E/HttpOperation( 3239): Caused by: faj: BadAuthentication
E/HttpOperation( 3239): 	at fal.a(PG:38)
E/HttpOperation( 3239): 	at jdj.a(PG:4089)
E/HttpOperation( 3239): 	... 17 more
E/ExperimentLoader( 3239): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3239): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3239): 	at jdm.a(PG:82)
E/ExperimentLoader( 3239): 	at jcs.o(PG:406)
E/ExperimentLoader( 3239): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3239): 	at jcs.i(PG:143)
E/ExperimentLoader( 3239): 	at hec.a(PG:42)
E/ExperimentLoader( 3239): 	at hee.a(PG:102)
E/ExperimentLoader( 3239): 	at czr.a(PG:65)
,E/ExperimentLoader( 3239): 	at kka.a(PG:108)
E/ExperimentLoader( 3239): 	at czp.a(PG:19176)
E/ExperimentLoader( 3239): 	at czp.a(PG:9081)
E/ExperimentLoader( 3239): 	at czq.run(PG:1686)
E/ExperimentLoader( 3239): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3239): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3239): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3239): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3239): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3239): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3239): 	at jdm.a(PG:77)
E/ExperimentLoader( 3239): 	... 15 more
E/ExperimentLoader( 3239): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3239): 	at fal.a(PG:38)
E/ExperimentLoader( 3239): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3239): 	... 17 more
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4022): IOException
E/KeepSync( 4022): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4022): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4022): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4022): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4022): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4022): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4022): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4022): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4022): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4022): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4022): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4022): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4022): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4022): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4022): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4022): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4022): 	... 10 more
,W/KeepSync( 4022): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 135142, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 134861, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksSync( 4055): Starting books sync for 61035162, extras: ade
,D/Finsky  ( 3516): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3516): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3516): [1] 5.onFinished: Scheduling replication attempt 5.
,I/art     (  821): Explicit concurrent mark sweep GC freed 49479(2MB) AllocSpace objects, 17(366KB) LOS objects, 31% free, 34MB/50MB, paused 1.863ms total 72.990ms
,I/BooksConfig( 4055): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/kickstart(  872): STATUS: Received file 'm9kefs2'
I/kickstart(  872): STATUS: 950272 bytes transferred in 0.991598 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4055): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4055): Soft error
E/BooksSync( 4055): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4055): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4055): Sync error
E/BooksSync( 4055): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4055): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4055): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 136570, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1349): Explicit concurrent mark sweep GC freed 37173(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.421ms total 37.128ms
,V/GoogleAuthProtoRequest( 3835): [415] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1349): Vacuum at: now=1455124107157 tag=VacuumService
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1349): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,W/Uploader( 1349): No account for auth token provided
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ExperimentUpdateService( 3835): [415] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3835): [415] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3835): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3835): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3835): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3835): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3835): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3835): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3835): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3835): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3835): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3835): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3516): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3516): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3516): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1349): No account for auth token provided
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1349): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1349): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1349): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1349): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1349): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1349): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1349): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1349): No account for auth token provided
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1349): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1349): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1349): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1349): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1349): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1349): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1349): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1349): No account for auth token provided
,W/Uploader( 1349): No account for auth token provided
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1349): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1349): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1349): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1349): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1349): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1349): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1349): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1349): No account for auth token provided
,W/Uploader( 1349): No account for auth token provided
,W/Uploader( 1349): No account for auth token provided
,W/Uploader( 1349): No account for auth token provided
,W/Uploader( 1349): No account for auth token provided
,W/Uploader( 1349):  no longer exists, so no auth token.,
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1349): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1349): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1349): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1349): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1349): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1349): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1349): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1349): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GoogleAuthProtoRequest( 3835): [416] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3835): [416] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3835): [416] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3835): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3835): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3835): ,	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3835): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3835): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3835): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3835): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3835): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3835): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3835): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1228): run()
I/Keyboard.Facilitator( 1228): flushDynamicLanguageModels()
,I/ConfigService( 1349): onCreate
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3239): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3239): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3239): 	at jdm.a(PG:82)
E/HttpOperation( 3239): 	at jcs.o(PG:406)
E/HttpOperation( 3239): 	at jcn.a(PG:1379)
E/HttpOperation( 3239): 	at jcs.i(PG:143)
E/HttpOperation( 3239): 	at blb.a(PG:3937)
E/HttpOperation( 3239): 	at czp.a(PG:18188)
E/HttpOperation( 3239): 	at czp.a(PG:9081)
E/HttpOperation( 3239): 	at czq.run(PG:1686)
E/HttpOperation( 3239): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3239): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3239): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3239): 	at jdj.a(PG:4091)
E/HttpOperation( 3239): 	at jdj.a(PG:1125)
E/HttpOperation( 3239): 	at jdm.a(PG:77)
E/HttpOperation( 3239): ,	... 12 more
E/HttpOperation( 3239): Caused by: faj: BadAuthentication
E/HttpOperation( 3239): 	at fal.a(PG:38)
E/HttpOperation( 3239): 	at jdj.a(PG:4089)
E/HttpOperation( 3239): 	... 14 more,
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3239): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3239): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3239): 	at jdm.a(PG:82)
E/HttpOperation( 3239): 	at jcs.o(PG:406)
E/HttpOperation( 3239): 	at jcn.a(PG:1379)
E/HttpOperation( 3239): 	at jcs.i(PG:143)
E/HttpOperation( 3239): 	at hec.a(PG:42)
E/HttpOperation( 3239): 	at hee.a(PG:102)
E/HttpOperation( 3239): 	at czr.a(PG:65)
E/HttpOperation( 3239): 	at kka.a(PG:108)
E/HttpOperation( 3239): 	at czp.a(PG:19176)
E/HttpOperation( 3239): 	at czp.a(PG:9081)
E/HttpOperation( 3239): 	at czq.run(PG:1686)
E/HttpOperation( 3239): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3239): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3239): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3239): 	at jdj.a(PG:4091)
E/HttpOperation( 3239): 	at jdj.a(PG:1125)
E/HttpOperation( 3239): 	at jdm.a(PG:77)
E/HttpOperation( 3239): 	... 15 more
E/HttpOperation( 3239): Caused by: faj: BadAuthentication
E/HttpOperation( 3239): 	at fal.a(PG:38)
E/HttpOperation( 3239): 	at jdj.a(PG:4089)
E/HttpOperation( 3239): 	... 17 more
,E/ExperimentLoader( 3239): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3239): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3239): 	at jdm.a(PG:82)
E/ExperimentLoader( 3239): 	at jcs.o(PG:406)
E/ExperimentLoader( 3239): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3239): 	at jcs.i(PG:143)
E/ExperimentLoader( 3239): 	at hec.a(PG:42)
E/ExperimentLoader( 3239): 	at hee.a(PG:102)
E/ExperimentLoader( 3239): 	at czr.a(PG:65)
E/ExperimentLoader( 3239): 	at kka.a(PG:108)
E/ExperimentLoader( 3239): 	at czp.a(PG:19176)
E/ExperimentLoader( 3239): 	at czp.a(PG:9081)
E/ExperimentLoader( 3239): 	at czq.run(PG:1686)
E/ExperimentLoader( 3239): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3239): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3239): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3239): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3239): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3239): 	at jdm.a(PG:77)
E/ExperimentLoader( 3239): 	... 15 more
E/ExperimentLoader( 3239): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3239): 	at fal.a(PG:38)
E/ExperimentLoader( 3239): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3239): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 225031, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1349): onDestroy
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/BooksSync( 4055): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4022): Connecting to GoogleApiClient
,I/BooksConfig( 4055): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     (  821): Explicit concurrent mark sweep GC freed 38024(1662KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.542ms total 67.112ms,
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4022): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4022): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4022): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4022): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4055): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4055): Soft error
E/BooksSync( 4055): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4055): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4055): Sync error
E/BooksSync( 4055): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4055): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4055): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 226889, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4022): IOException
E/KeepSync( 4022): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4022): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4022): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4022): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4022): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4022): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4022): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4022): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4022): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4022): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4022): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4022): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4022): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4022): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4022): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4022): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4022): 	... 10 more
W/KeepSync( 4022): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 225669, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3773): --= Surplus to requirements =--
I/jxcore-log( 3773): 
,I/jxcore-log( 3773): ****TEST TOOK:  ms ****
I/jxcore-log( 3773): 
I/jxcore-log( 3773): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3773): 
,D/AndroidRuntime( 4159): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4159): CheckJNI is OFF,
,D/AndroidRuntime( 4159): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3773:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  821): Skipping PackageSetting{268f809b com.example.hello/10273} due to missing metadata
,I/WindowState(  821): WIN DEATH: Window{2bafce71 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  821): Client connection lost with reason: 4
,W/ActivityManager(  821): Force removing ActivityRecord{2cef9e1e u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  821): Display changed displayId=0
,W/ActivityManager(  821): Spurious death for ProcessRecord{289f85e2 3773:com.test.thalitest/u0a265}, curProc for 3773: null
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/TaskPersister(  821): removeObsoleteFile: deleting file=28_task.xml
,I/Keyboard.Facilitator( 1228): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1228): run()
,D/BuaReceiver( 3392): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
I/Decoder ( 1228): createOrResetDecoder
,I/ActivityManager(  821): Start proc 4175:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,I/art     ( 1062): Explicit concurrent mark sweep GC freed 55300(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 1.161ms total 59.605ms
,I/ConfigService( 1349): onCreate
,I/art     (  821): Explicit concurrent mark sweep GC freed 13126(905KB) AllocSpace objects, 9(615KB) LOS objects, 31% free, 34MB/50MB, paused 3.771ms total 86.733ms
,I/art     (  821): WaitForGcToComplete blocked for 87.443ms for cause Explicit
,W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3773 uid 10265
,I/art     ( 1504): Explicit concurrent mark sweep GC freed 2524(183KB) AllocSpace objects, 1(25KB) LOS objects, 36% free, 27MB/43MB, paused 892us total 100.745ms
I/Keyboard.Facilitator( 1228): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1228): run()
,W/LocationOracleImpl( 1504): Best location was null
,I/art     ( 1325): Explicit concurrent mark sweep GC freed 5066(370KB) AllocSpace objects, 11(1298KB) LOS objects, 31% free, 35MB/51MB, paused 1.423ms total 25.959ms
,I/HotwordRecognitionRnr( 1504): Starting hotword detection.
I/MicrophoneInputStream( 1504): mic_starting com.google.android.apps.gsa.speech.audio.u@1874dd14
,I/AudioFlinger(  357): AudioFlinger's thread 0xb4d50000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1504): mic_started com.google.android.apps.gsa.speech.audio.u@1874dd14
,D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1228): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1228): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1228): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1228): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1228): run()
I/StatsUtilsManager( 1228): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1228): shouldRecordStats() = Too Soon
,D/VoicemailCleanupService( 4175): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  821): Start proc 4212:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 253us total 10.794ms
,I/art     (  821): Explicit concurrent mark sweep GC freed 7306(341KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 1.636ms total 149.868ms
D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@97b7ab9}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 9.640ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 356us total 9.045ms
,I/HotwordWorker( 1504): onReady
,I/ActivityManager(  821): Start proc 4231:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/ContactLocale( 4175): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658946835
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,D/Launcher.Workspace( 1325): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1325): 11683562 - stripEmptyScreens()
I/art     ( 4159): System.exit called, status: 0
I/AndroidRuntime( 4159): VM exiting with result code 0.
,W/ContextImpl( 4231): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1349): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1349): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,V/GoogleAuthProtoRequest( 3835): [417] a.<init>: mAccountName set to: thalitester@gmail.com
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1773): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1773): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1773): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1773): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1773): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1773): Removing dialog suppression flag for package com.test.thalitest
,I/UpdateIcingCorporaServi( 1504): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1325): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@68bd2a6 new=com.google.android.velvet.VelvetApplication@68bd2a6
,D/GOOGLEHELP_CompatibleDatabase( 1773): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1773): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1773): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1773): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager(  821): Start proc 4264:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/art     ( 1349): Explicit concurrent mark sweep GC freed 64199(3MB) AllocSpace objects, 12(989KB) LOS objects, 36% free, 27MB/43MB, paused 986us total 49.760ms
D/GOOGLEHELP_CompatibleDatabase( 1773): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1773): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1773): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1773): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1773): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1773): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1773): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1773): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1773): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ConfigFetchService( 1773): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1773): service connected
,I/PeopleContactsSync( 1773): CP2 sync disabled
,I/Icing   ( 1773): doRemovePackageData com.test.thalitest
,W/BaseAppContext( 1773): Using Auth Proxy for data requests.
,W/BaseAppContext( 1773): Using Auth Proxy for data requests.
,I/GLSUser ( 1349): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1349): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1349): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1349): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/UpdateIcingCorporaServi( 1504): UpdateCorporaTask done [took 91 ms] updated apps [took 91 ms] 
,V/GLSActivity( 1349): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3835): [417] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3835): [417] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3835): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3835): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3835): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3835): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3835): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3835): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3835): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3835): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3835): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3835): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  821): Killing 2494:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/GAv4    ( 4264): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4264):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4264):   adb logcat -s GAv4
,W/GAv4    ( 4264): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4264): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4264): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
,E/SharedPreferencesImpl( 4264): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4264): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4264): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 4264): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30

```
