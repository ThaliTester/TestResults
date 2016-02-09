#### Test 58380500306a2c5_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,I/CheckinService( 1771): Done disabling old GoogleServicesFramework version
D/AndroidRuntime( 3647): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3647): CheckJNI is OFF
D/AndroidRuntime( 3647): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  818): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  818): addAppToken: AppWindowToken{2dd9dec7 token=Token{12bc3806 ActivityRecord{387d42e1 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3647): Shutting down VM
V/WindowManager(  818): Adding window Window{963a460 u0 Starting com.test.thalitest} at 2 of 7 (after Window{1aba5243 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1512): Closing mic
I/MicrophoneInputStream( 1512): mic_close com.google.android.apps.gsa.speech.audio.u@1b84e521
I/ActivityManager(  818): Start proc 3662:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/GAV2    ( 3524): Thread[GAThread,5,main]: No campaign data found.
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1512): Hotword detection finished
I/HotwordRecognitionRnr( 1512): Stopping hotword detection.
I/art     (  818): Explicit concurrent mark sweep GC freed 20384(1019KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 2.186ms total 60.443ms
I/WebViewFactory( 3662): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660794131
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  818): Killing 3152:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
I/LibraryLoader( 3662): Time to load native libraries: 2 ms (timestamps 7044-7046)
I/LibraryLoader( 3662): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3662): Binding Chromium to main looper Looper (main, tid 1) {e25d7c0}
I/LibraryLoader( 3662): Expected native library version number "",actual native library version number ""
I/chromium( 3662): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3662): Initializing chromium process, singleProcess=true
W/art     ( 3662): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3662): ApplicationContext is null in ApplicationStatus
,W/chromium( 3662): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3662): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3662): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3662): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  818): Message: 20
D/BluetoothManagerService(  818): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1808aeb6:true
,W/art     ( 3662): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3662): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3662): CordovaWebView is running on device made by: motorola
,W/art     ( 3662): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3662): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3662): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3662): Validating map...
,V/WindowManager(  818): Adding window Window{1178d2c0 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{963a460 u0 Starting com.test.thalitest})
,W/chromium( 3662): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3662): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3662): Enabling debug mode 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,I/ActivityManager(  818): Displayed com.test.thalitest/.MainActivity: +543ms
,I/Keyboard.Facilitator( 1229): onFinishInput()
,W/BindingManager( 3662): Cannot call determinedVisibility() - never saw a connection for the pid: 3662
,I/ActivityManager(  818): Killing 3179:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,D/JsMessageQueue( 3662): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  818): Killing 3241:com.android.chrome/u0a40 (adj 15): empty #17
,D/jxcore_app_log( 3662): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576402048
,I/chromium( 3662): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3662): Initializing JXcore engine
W/jxcore-log( 3662): JXcore engine is ready
,W/Thread-401( 3719): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12039]" dev="sockfs" ino=12039 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-401( 3719): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-401( 3719): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10606]" dev="sockfs" ino=10606 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-401( 3719): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22105]" dev="sockfs" ino=22105 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3662): Starting JXcore engine
,W/jxcore-log( 3662): Platform android
W/jxcore-log( 3662): 
,W/jxcore-log( 3662): Process ARCH arm
W/jxcore-log( 3662): 
,I/jxcore-log( 3662): JXcore Cordova bridge is ready!
I/jxcore-log( 3662): 
W/jxcore-log( 3662): JXcore engine is started
,I/jxcore-log( 3662): Toggling radios to true
I/jxcore-log( 3662): 
,D/BluetoothAdapter( 3662): enable(): BT is already enabled..!
,D/WifiService(  818): New client listening to asynchronous messages
D/WifiService(  818): setWifiEnabled: true pid=3662, uid=10265
E/WifiService(  818): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3662): Radios toggled
I/jxcore-log( 3662): 
,I/jxcore-log( 3662): My device name is: motorola-Nexus 6
I/jxcore-log( 3662): 
,I/wpa_supplicant( 1128): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  818): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1329): Read error: ssl=0xb4886800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1329): SSL shutdown failed: ssl=0xb4886800: I/O error during system call, Broken pipe
,D/ConnectivityService(  818): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,E/WifiStateMachine(  818): Start Disconnecting Watchdog 1,
,E/WifiStateMachine(  818): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000,
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,D/ConnectivityService(  818): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  818): Disconnected - quitting
D/CSLegacyTypeTracker(  818): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  818): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  818): MasterInitialState.processMessage what=3,
D/WifiNetworkAgent(  818): NetworkAgent: NetworkAgent channel lost
,D/Tethering(  818): MasterInitialState.processMessage what=3
,D/ConnectivityService(  818): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
E/WifiStateMachine(  818): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  818): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
E/ConnectivityService(  818): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,V/MusicLeanback( 3078): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/TelephonyManager(  818): getDataEnabled: retVal=false
,E/WifiConfigStore(  818): Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  818): will read network variables netId=0
,I/ActivityManager(  818): Start proc 3727:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/WifiStateMachine(  818): CMD_AUTO_CONNECT did save config ->  nid=0
E/WifiConfigStore(  818): will read network variables netId=0
E/GpsLocationProvider(  818): No APN found to select.
,D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  818): getDataEnabled: retVal=false
,E/GpsLocationProvider(  818): No APN found to select.
,I/art     (  367): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 329us total 20.017ms
,D/SprintDMReceiver( 3727): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 331us total 13.355ms
,D/SprintDMHelper( 3727): simOperator:  IMSI: null
D/SprintDMReceiver( 3727): Not Sprint UICC, don't do anything.
,I/ActivityManager(  818): Killing 3349:com.google.android.partnersetup/u0a16 (adj 15): empty #17
I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 562us total 12.749ms
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,I/ValidateNoPeople(  818): skipping global notification
I/iu.Environment( 1771): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599967 ms
,I/iu.UploadsManager( 1771): num queued entries: 0
,I/iu.UploadsManager( 1771): num updated entries: 0
,I/iu.SyncManager( 1771): NEXT; no task
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1771): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1771): onDestroy
,I/Babel   ( 2784): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  818): Start proc 3747:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GAv4    ( 3747): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3747):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3747):   adb logcat -s GAv4
,W/GAv4    ( 3747): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3747): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3747): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3747): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3747): Time to load native libraries: 2 ms (timestamps 721-723)
,I/LibraryLoader( 3747): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3747): Binding Chromium to main looper Looper (main, tid 1) {23d1e167}
,I/LibraryLoader( 3747): Expected native library version number "",actual native library version number ""
I/chromium( 3747): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 3747): Initializing chromium process, singleProcess=true,
W/art     ( 3747): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3747): ApplicationContext is null in ApplicationStatus
,W/chromium( 3747): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3747): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3747): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3747): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3747): Requires BLUETOOTH permission
,I/NSApplication( 3747): Starting up...
,I/ActivityManager(  818): Start proc 3803:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  818): Killing 3369:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  818): Killing 3415:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,V/MusicLeanback( 3078): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3727): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3727): simOperator:  IMSI: null
,D/SprintDMReceiver( 3727): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate,
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,I/ValidateNoPeople(  818): skipping global notification
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1771): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599952 ms
,D/SystemUpdateService( 1771): onDestroy
,I/wpa_supplicant( 1128): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 1128): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1128): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1128): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  818): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Setting iface cfg
,E/WifiStateMachine(  818): Start Dhcp Watchdog 2
,E/WifiStateMachine(  818):  WifiLinkLayerStats: 
E/WifiStateMachine(  818):  my bss beacon rx: 179
E/WifiStateMachine(  818):  RSSI mgmt: -53
,E/WifiStateMachine(  818):  BE :  rx=145 tx=135 lost=0 retries=1
E/WifiStateMachine(  818):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  818):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  818):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  818):  on_time : 9627 tx_time=146 rx_time=314 scan_time=0
,D/ConnectivityService(  818): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60,
,E/native  (  818): do suspend false
,E/WifiStateMachine(  818): scanCount==0 - aborting
,I/dhcpcd  ( 3836): version 5.5.6 starting
,I/dhcpcd  ( 3836): wlan0: rebinding lease of 192.168.1.122
,I/ActivityManager(  818): Waited long enough for: ServiceRecord{4304fc6 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/dhcpcd  ( 3836): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3836): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3662): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3662): 
,D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  818): Adding iface wlan0 to network 101
,E/WifiStateMachine(  818): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  818): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  818): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  818): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  818): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  818): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  818): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  818): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  818): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  818): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  818): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  818): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3078): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3078): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  818): getDataEnabled: retVal=false
,E/GpsLocationProvider(  818): No APN found to select.
,D/SprintDMReceiver( 3727): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3727): simOperator:  IMSI: null
D/SprintDMReceiver( 3727): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 22:49:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455058174730], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455058174708]}
,D/ConnectivityService(  818): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  818): Validated
,D/ConnectivityService(  818): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  818): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/iu.Environment( 1771): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1771): num queued entries: 0
,I/iu.UploadsManager( 1771): num updated entries: 0
I/iu.SyncManager( 1771): NEXT; no task
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1771): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  818): skipping global notification
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599890 ms
,D/SystemUpdateService( 1771): onDestroy
,I/ActivityManager(  818): Killing 3553:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/Babel   ( 2784): connection state changed from DISCONNECTED to CONNECTED
,V/Herrevad( 1771): NQAS connected
,D/GCM     ( 1329): Connected
,D/GCM     ( 1329): Message class com.google.f.a.a.p
,I/jxcore-log( 3662): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3662): 
,I/jxcore-log( 3662): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
,I/jxcore-log( 3662): 
,I/jxcore-log( 3662): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
,I/jxcore-log( 3662): 
,I/jxcore-log( 3662): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3662): 
,I/jxcore-log( 3662): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3662): 
,D/ConnectivityService(  818): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network,
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3455): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3455): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3455): [1] 5.onFinished: Scheduling replication attempt 1.
,I/art     (  818): Explicit concurrent mark sweep GC freed 49677(2MB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 1.548ms total 79.088ms
,I/jxcore-log( 3662): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3662): 
,I/jxcore-log( 3662): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3662): 
,I/jxcore-log( 3662): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 3662): ,
,I/jxcore-log( 3662): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3662): 
,I/ActivityManager(  818): Killing 1417:android.process.acore/u0a5 (adj 15): empty #17
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.39 rxSuccessRate=8.61 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3662): Test app app.js loaded
I/jxcore-log( 3662): 
,I/chromium( 3662): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3662): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3662): ,	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3662): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3662): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3662): ,	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3662): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3662): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3662): 	,Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3662): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3662): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2992c436 added. We now have 1 listener(s)
I/jxcore-log( 3662): BLE advertisement is supported,
I/jxcore-log( 3662): 
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.70 rxSuccessRate=6.30 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.11 rxSuccessRate=3.96 targetRoamBSSID=any RSSI=-53
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3455): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3455): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3455): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  818): Start proc 3893:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/art     ( 1329): Explicit concurrent mark sweep GC freed 22761(1299KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.974ms total 38.749ms
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3260): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3260): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3260): 	at jdm.a(PG:82)
E/HttpOperation( 3260): 	at jcs.o(PG:406)
E/HttpOperation( 3260): 	at jcn.a(PG:1379)
E/HttpOperation( 3260): 	at jcs.i(PG:143)
E/HttpOperation( 3260): 	at blb.a(PG:3937)
E/HttpOperation( 3260): 	at czp.a(PG:18188)
E/HttpOperation( 3260): 	at czp.a(PG:9081)
E/HttpOperation( 3260): 	at czq.run(PG:1686)
E/HttpOperation( 3260): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3260): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3260): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3260): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3260): 	at jdj.a(PG:4091)
E/HttpOperation( 3260): 	at jdj.a(PG:1125)
E/HttpOperation( 3260): 	at jdm.a(PG:77)
E/HttpOperation( 3260): 	... 12 more
E/HttpOperation( 3260): Caused by: faj: BadAuthentication
E/HttpOperation( 3260): 	at fal.a(PG:38)
E/HttpOperation( 3260): 	at jdj.a(PG:4089)
E/HttpOperation( 3260): 	... 14 more
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3260): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3260): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3260): 	at jdm.a(PG:82)
E/HttpOperation( 3260): 	at jcs.o(PG:406)
E/HttpOperation( 3260): 	at jcn.a(PG:1379)
E/HttpOperation( 3260): 	at jcs.i(PG:143)
E/HttpOperation( 3260): 	at hec.a(PG:42)
E/HttpOperation( 3260): 	at hee.a(PG:102)
E/HttpOperation( 3260): 	at czr.a(PG:65)
E/HttpOperation( 3260): 	at kka.a(PG:108)
E/HttpOperation( 3260): 	at czp.a(PG:19176)
E/HttpOperation( 3260): 	at czp.a(PG:9081)
E/HttpOperation( 3260): 	at czq.run(PG:1686)
E/HttpOperation( 3260): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3260): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3260): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3260): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3260): 	at jdj.a(PG:4091)
E/HttpOperation( 3260): 	at jdj.a(PG:1125)
E/HttpOperation( 3260): 	at jdm.a(PG:77)
E/HttpOperation( 3260): 	... 15 more
E/HttpOperation( 3260): Caused by: faj: BadAuthentication
E/HttpOperation( 3260): 	at fal.a(PG:38)
E/HttpOperation( 3260): 	at jdj.a(PG:4089)
E/HttpOperation( 3260): 	... 17 more
E/ExperimentLoader( 3260): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3260): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3260): 	at jdm.a(PG:82)
E/ExperimentLoader( 3260): 	at jcs.o(PG:406)
E/ExperimentLoader( 3260): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3260): 	at jcs.i(PG:143)
E/ExperimentLoader( 3260): 	at hec.a(PG:42)
E/ExperimentLoader( 3260): 	at hee.a(PG:102)
E/ExperimentLoader( 3260): 	at czr.a(PG:65)
E/ExperimentLoader( 3260): 	at kka.a(PG:108)
E/ExperimentLoader( 3260): 	at czp.a(PG:19176)
E/ExperimentLoader( 3260): 	at czp.a(PG:9081)
E/ExperimentLoader( 3260): 	at czq.run(PG:1686)
E/ExperimentLoader( 3260): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3260): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3260): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3260): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3260): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3260): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3260): 	at jdm.a(PG:77)
E/ExperimentLoader( 3260): 	... 15 more
E/ExperimentLoader( 3260): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3260): 	at fal.a(PG:38)
E/ExperimentLoader( 3260): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3260): 	... 17 more
,V/KeepSync( 3893): Connecting to GoogleApiClient
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3893): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3893): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3893): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3893): (284) automatic index on blob_node(is_deleted)
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 76496, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  818): Start proc 3926:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3893): IOException
E/KeepSync( 3893): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3893): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3893): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3893): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3893): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3893): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3893): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3893): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3893): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3893): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3893): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3893): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3893): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3893): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3893): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3893): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3893): 	... 10 more
,W/KeepSync( 3893): Sync result 2
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 75645, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,W/GAV2    ( 3926): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3926): Created application version: 3.6.8 (30608)
,I/BooksSync( 3926): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3926): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3926): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3926): Soft error
E/BooksSync( 3926): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3926): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3926): Sync error
E/BooksSync( 3926): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3926): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3926): Finished books sync
,I/ActivityManager(  818): Killing 3524:com.google.android.gm/u0a78 (adj 15): empty #17
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 76741, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  818): Killing 3495:com.google.android.gms:car/u0a11 (adj 15): empty #18
,I/GAV2    ( 3926): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.44 rxSuccessRate=1.51 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  818): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3455): [388] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  818): Explicit concurrent mark sweep GC freed 40266(1911KB) AllocSpace objects, 12(192KB) LOS objects, 31% free, 34MB/50MB, paused 2.399ms total 81.938ms
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3455): [388] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3455): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3455): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3455): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1229): run()
I/Keyboard.Facilitator( 1229): flushDynamicLanguageModels()
,I/ConfigService( 1329): onCreate,
,I/ConfigService( 1329): onDestroy
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.58 rxSuccessRate=3.42 targetRoamBSSID=any RSSI=-53
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3455): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3455): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3455): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.21 rxSuccessRate=3.54 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  818): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  818): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  818): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (298 us)
,I/DisplayManagerService(  818): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  818): Display changed displayId=0
,I/kickstart(  869): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  869): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  869): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  869): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  818): Excessive delay in setPowerMode(): 268ms
,I/DreamManagerService(  818): Entering dreamland.
I/PowerManagerService(  818): Dozing...
,I/DreamController(  818): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  818): cancelDelayedScan -> 12
,E/native  (  818): do suspend false
,I/Keyboard.Facilitator( 1229): onFinishInput()
,E/WifiStateMachine(  818): cancelDelayedScan -> 14
,E/native  (  818): do suspend true
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AlarmManagerService(  818): Setting time of day to sec=1455058264
W/AlarmManagerService(  818): Unable to set rtc to 1455058264: Invalid argument
,I/ActivityManager(  818): Start proc 3977:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=off
,I/art     ( 1329): Explicit concurrent mark sweep GC freed 28990(1641KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.649ms total 40.255ms
,D/TimeService( 3977): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1455058264414
,D/        ( 3977): TimeServiceNative: User Time to be set is 1455058264414
D/QC-time-services( 3977): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3977): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3977): Lib:time_genoff_operation: pargs->ts_val = 1455058264414
D/QC-time-services(  371): Daemon: Connection accepted:time_genoff
D/QC-time-services(  371): Daemon:Received base = 2, unit = 1, operation = 0,value = 1455058264414
D/QC-time-services(  371): Daemon:genoff_opr: Base = 2, val = 1455058264414, operation = 0
D/QC-time-services(  371): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/27/70 19:3:23
D/QC-time-services(  371): Daemon:Value read from RTC seconds = 15361403000
D/QC-time-services(  371): Daemon:new time 1455058264414 
D/QC-time-services(  371): Daemon: delta 1439696861414 genoff 1439696861414 
D/QC-time-services(  371): Daemon:genoff_persistent_update: Writing genoff = 1439696861414 to memory
D/QC-time-services(  371): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  371): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services( 3977): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  371): Updating the TOD offset,
D/QC-time-services(  371): Daemon:genoff_persistent_update: Writing genoff = 1439696861414 to memory
D/QC-time-services(  371): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  371): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  371): Daemon:Update to modem bit set,
D/QC-time-services(  371): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  371): Daemon: Base = 2, Value being sent to MODEM = 1139093464414
E/QC-time-services( 3977): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/QC-time-services(  371): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  371): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/Finsky  ( 3455): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3455): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3455): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ActivityManager(  818): Start proc 3998:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  818): Killing 3389:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete,
,I/GAv4    ( 3998): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3998):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3998):   adb logcat -s GAv4
,W/GAv4    ( 3998): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3998): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3998): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,I/ActivityManager(  818): Killing 3078:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/kickstart(  869): STATUS: Received file 'm9kefs1'
I/kickstart(  869): STATUS: 950272 bytes transferred in 0.997304 seconds
I/kickstart(  869): STATUS: Successfully downloaded files from target 
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  869): STATUS: Sahara protocol completed
,V/KeepSync( 3893): Connecting to GoogleApiClient
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3260): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3260): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3260): 	at jdm.a(PG:82)
E/HttpOperation( 3260): 	at jcs.o(PG:406)
E/HttpOperation( 3260): 	at jcn.a(PG:1379)
E/HttpOperation( 3260): 	at jcs.i(PG:143)
E/HttpOperation( 3260): 	at blb.a(PG:3937)
E/HttpOperation( 3260): 	at czp.a(PG:18188)
E/HttpOperation( 3260): 	at czp.a(PG:9081)
E/HttpOperation( 3260): 	at czq.run(PG:1686)
E/HttpOperation( 3260): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3260): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3260): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3260): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3260): 	at jdj.a(PG:4091)
E/HttpOperation( 3260): 	at jdj.a(PG:1125)
E/HttpOperation( 3260): 	at jdm.a(PG:77)
E/HttpOperation( 3260): 	... 12 more
E/HttpOperation( 3260): Caused by: faj: BadAuthentication
E/HttpOperation( 3260): 	at fal.a(PG:38)
E/HttpOperation( 3260): 	at jdj.a(PG:4089)
E/HttpOperation( 3260): 	... 14 more
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
,V/KeepSync( 3893): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3893): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3893): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3893): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3260): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3260): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3260): 	at jdm.a(PG:82)
E/HttpOperation( 3260): 	at jcs.o(PG:406)
E/HttpOperation( 3260): 	at jcn.a(PG:1379)
E/HttpOperation( 3260): 	at jcs.i(PG:143)
E/HttpOperation( 3260): 	at hec.a(PG:42)
E/HttpOperation( 3260): 	at hee.a(PG:102)
E/HttpOperation( 3260): 	at czr.a(PG:65)
E/HttpOperation( 3260): 	at kka.a(PG:108)
E/HttpOperation( 3260): 	at czp.a(PG:19176)
E/HttpOperation( 3260): 	at czp.a(PG:9081)
E/HttpOperation( 3260): 	at czq.run(PG:1686)
E/HttpOperation( 3260): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3260): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3260): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3260): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3260): 	at jdj.a(PG:4091)
E/HttpOperation( 3260): 	at jdj.a(PG:1125)
E/HttpOperation( 3260): 	at jdm.a(PG:77)
E/HttpOperation( 3260): 	... 15 more
E/HttpOperation( 3260): Caused by: faj: BadAuthentication
E/HttpOperation( 3260): 	at fal.a(PG:38)
E/HttpOperation( 3260): 	at jdj.a(PG:4089)
E/HttpOperation( 3260): 	... 17 more
,E/ExperimentLoader( 3260): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3260): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3260): 	at jdm.a(PG:82)
E/ExperimentLoader( 3260): 	at jcs.o(PG:406)
E/ExperimentLoader( 3260): ,	at jcn.a(PG:1379)
E/ExperimentLoader( 3260): 	at jcs.i(PG:143)
E/ExperimentLoader( 3260): 	at hec.a(PG:42)
E/ExperimentLoader( 3260): 	at hee.a(PG:102)
E/ExperimentLoader( 3260): 	at czr.a(PG:65)
E/ExperimentLoader( 3260): 	at kka.a(PG:108)
E/ExperimentLoader( 3260): 	at czp.a(PG:19176)
E/ExperimentLoader( 3260): 	at czp.a(PG:9081)
E/ExperimentLoader( 3260): 	at czq.run(PG:1686)
E/ExperimentLoader( 3260): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3260): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3260): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3260): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3260): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3260): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3260): 	at jdm.a(PG:77)
E/ExperimentLoader( 3260): ,	... 15 more
E/ExperimentLoader( 3260): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3260): 	at fal.a(PG:38)
E/ExperimentLoader( 3260): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3260): 	... 17 more
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 135292, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3926): Starting books sync for 61035162, extras: ade
,I/art     (  818): Explicit concurrent mark sweep GC freed 43071(2MB) AllocSpace objects, 12(380KB) LOS objects, 31% free, 34MB/50MB, paused 1.862ms total 70.652ms
,E/KeepSync( 3893): IOException
E/KeepSync( 3893): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3893): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3893): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3893): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3893): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3893): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3893): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3893): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3893): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3893): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3893): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3893): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3893): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3893): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3893): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3893): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3893): 	... 10 more
W/KeepSync( 3893): Sync result 2
,I/BooksConfig( 3926): GmsCore Version = 7.8.99 (2134222-430),
D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 135706, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3926): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3926): Soft error
E/BooksSync( 3926): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3926): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3926): Sync error
E/BooksSync( 3926): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3926): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3926): Finished books sync
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 137201, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  818): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1329): Vacuum at: now=1455058278984 tag=VacuumService
,V/GoogleAuthProtoRequest( 3126): [310] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3126): [310] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3126): [310] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3126): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3126): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3126): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3126): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3126): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3126): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3126): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3126): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3126): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3126): 	at com.a.a.k.run(SourceFile:110)
,I/ConfigFetchService( 1771): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1771): running network task: configservice_periodic
,E/WakeLock( 1771): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1771): launchTask
,I/ConfigService( 1329): onCreate
,I/ConfigFetchService( 1771): service connected
,I/GoogleURLConnFactory( 1329): Using platform SSLCertificateSocketFactory
D/ConfigFetchService( 1771): ConfigApi connection successful.
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1329): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1329): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1329): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1329): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1329): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1329): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1329): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1329): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1329): No account for auth token provided
,W/Uploader( 1329): No account for auth token provided
,W/Uploader( 1329): No account for auth token provided
,W/Uploader( 1329): No account for auth token provided
,W/Uploader( 1329): No account for auth token provided
,W/Uploader( 1329): No account for auth token provided
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1329): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1329): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1329): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1329): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1329): No account for auth token provided
,W/Uploader( 1329): No account for auth token provided
,W/Uploader( 1329): No account for auth token provided
,W/Uploader( 1329): No account for auth token provided
,W/Uploader( 1329):  no longer exists, so no auth token.
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1329): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1329): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1329): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1329): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1329): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1329): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1329): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1329): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1329): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1329): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3455): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3455): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3455): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,V/ConfigFetchTask( 1771): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1W05-d7laKIEpHoJO5FCsckAusJUqwzZiO0Hbh8vOTy2MPBsF723lzufjQztPG5zy0vcZwmvBKU7TFToenClL55nFbZ0d0ef9vwza-2G1WNkfEvXeum2RYKUq1cm1vV_Z_JanbSOyVBDH8Cn9L9ZbBkXKQA_K3-gWeyoHHZJPQ94dvZ9VkqdsgIOMwe4rknY-XqInDsiF-ViAqRWjXn9s5_c5dei7Fq04r4qHrIOhOj7-ZBFGI,
,I/GoogleURLConnFactory( 1771): Using platform SSLCertificateSocketFactory
,I/ConfigFetchTask( 1771): updating config table for com.google.android.gms
,I/ConfigFetchService( 1771): fetch service done; releasing wakelock
,I/ConfigFetchService( 1771): stopping self
,I/ConfigFetchService( 1771): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1771): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1771): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1771): service connected
,W/ConfigFetchService( 1771): ConfigApi client is not connected. Falling back to defaultfetch interval.
,D/ConfigFetchService( 1771): ConfigApi connection successful.
,I/ConfigFetchService( 1771): stopping self
,I/ConfigService( 1329): onDestroy
,V/GoogleAuthProtoRequest( 3126): [311] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1329): Explicit concurrent mark sweep GC freed 64102(3MB) AllocSpace objects, 8(701KB) LOS objects, 36% free, 27MB/43MB, paused 1.564ms total 50.902ms
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3126): [311] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3126): [311] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3126): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3126): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3126): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3126): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3126): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3126): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3126): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3126): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3126): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3126): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1229): run()
I/Keyboard.Facilitator( 1229): flushDynamicLanguageModels()
,I/ConfigService( 1329): onCreate,
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  818): Explicit concurrent mark sweep GC freed 35549(1560KB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 34MB/50MB, paused 1.665ms total 90.465ms
,E/HttpOperation( 3260): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3260): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3260): 	at jdm.a(PG:82)
E/HttpOperation( 3260): 	at jcs.o(PG:406)
E/HttpOperation( 3260): 	at jcn.a(PG:1379)
E/HttpOperation( 3260): 	at jcs.i(PG:143)
E/HttpOperation( 3260): 	at blb.a(PG:3937)
E/HttpOperation( 3260): 	at czp.a(PG:18188)
E/HttpOperation( 3260): 	at czp.a(PG:9081)
E/HttpOperation( 3260): 	at czq.run(PG:1686)
E/HttpOperation( 3260): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3260): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3260): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3260): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3260): 	at jdj.a(PG:4091)
E/HttpOperation( 3260): 	at jdj.a(PG:1125)
E/HttpOperation( 3260): 	at jdm.a(PG:77)
E/HttpOperation( 3260): 	... 12 more
E/HttpOperation( 3260): Caused by: faj: BadAuthentication
E/HttpOperation( 3260): 	at fal.a(PG:38)
E/HttpOperation( 3260): 	at jdj.a(PG:4089)
E/HttpOperation( 3260): 	... 14 more
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3260): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3260): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3260): 	at jdm.a(PG:82)
E/HttpOperation( 3260): 	at jcs.o(PG:406)
E/HttpOperation( 3260): 	at jcn.a(PG:1379)
E/HttpOperation( 3260): 	at jcs.i(PG:143)
E/HttpOperation( 3260): 	at hec.a(PG:42)
E/HttpOperation( 3260): 	at hee.a(PG:102)
E/HttpOperation( 3260): 	at czr.a(PG:65)
E/HttpOperation( 3260): 	at kka.a(PG:108)
E/HttpOperation( 3260): 	at czp.a(PG:19176)
E/HttpOperation( 3260): 	at czp.a(PG:9081)
E/HttpOperation( 3260): 	at czq.run(PG:1686)
E/HttpOperation( 3260): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3260): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3260): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3260): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3260): 	at jdj.a(PG:4091)
E/HttpOperation( 3260): 	at jdj.a(PG:1125)
E/HttpOperation( 3260): 	at jdm.a(PG:77)
E/HttpOperation( 3260): 	... 15 more
E/HttpOperation( 3260): Caused by: faj: BadAuthentication
E/HttpOperation( 3260): 	at fal.a(PG:38)
E/HttpOperation( 3260): 	at jdj.a(PG:4089)
E/HttpOperation( 3260): 	... 17 more
,E/ExperimentLoader( 3260): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3260): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3260): 	at jdm.a(PG:82)
E/ExperimentLoader( 3260): 	at jcs.o(PG:406)
E/ExperimentLoader( 3260): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3260): 	at jcs.i(PG:143)
E/ExperimentLoader( 3260): 	at hec.a(PG:42)
E/ExperimentLoader( 3260): 	at hee.a(PG:102)
E/ExperimentLoader( 3260): 	at czr.a(PG:65)
E/ExperimentLoader( 3260): 	at kka.a(PG:108)
E/ExperimentLoader( 3260): 	at czp.a(PG:19176)
E/ExperimentLoader( 3260): 	at czp.a(PG:9081)
E/ExperimentLoader( 3260): 	at czq.run(PG:1686)
E/ExperimentLoader( 3260): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3260): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3260): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3260): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3260): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3260): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3260): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3260): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3260): 	at jdm.a(PG:77)
E/ExperimentLoader( 3260): 	... 15 more
E/ExperimentLoader( 3260): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3260): 	at fal.a(PG:38)
E/ExperimentLoader( 3260): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3260): 	... 17 more
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 226129, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1329): onDestroy
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0
,I/BooksSync( 3926): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3893): Connecting to GoogleApiClient
,I/BooksConfig( 3926): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/ClientConnectionOperation( 1771): Handling authorization failure
E/ClientConnectionOperation( 1771): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
,E/ClientConnectionOperation( 1771): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
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
V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/KeepSync( 3893): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3893): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3893): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3893): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3926): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3926): Soft error
E/BooksSync( 3926): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3926): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3926): Sync error
E/BooksSync( 3926): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3926): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3926): Finished books sync
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 228911, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3893): IOException
E/KeepSync( 3893): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3893): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3893): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3893): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3893): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3893): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3893): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3893): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3893): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3893): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3893): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3893): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3893): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3893): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3893): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3893): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3893): 	... 10 more
W/KeepSync( 3893): Sync result 2
,D/SyncManager(  818): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 226786, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,I/jxcore-log( 3662): --= Surplus to requirements =--
I/jxcore-log( 3662): 
I/jxcore-log( 3662): ****TEST TOOK:  ms ****
I/jxcore-log( 3662): 
I/jxcore-log( 3662): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3662): 
,D/AndroidRuntime( 4083): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4083): CheckJNI is OFF
,D/AndroidRuntime( 4083): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  818): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
,I/ActivityManager(  818): Killing 3662:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  818): Skipping PackageSetting{387dd53c com.example.hello/10273} due to missing metadata
,D/WifiService(  818): Client connection lost with reason: 4
I/WindowState(  818): WIN DEATH: Window{1178d2c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,E/libprocessgroup(  818): failed to kill 1 processes for processgroup 3662
W/ActivityManager(  818): Force removing ActivityRecord{387d42e1 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  818): Display changed displayId=0
,W/ActivityManager(  818): Spurious death for ProcessRecord{40ad352 3662:com.test.thalitest/u0a265}, curProc for 3662: null
I/ActivityManager(  818): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/TaskPersister(  818): removeObsoleteFile: deleting file=28_task.xml
,I/Keyboard.Facilitator( 1229): resetDictionaries() : en_US
,D/BuaReceiver( 3332): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/InputReader(  818): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1229): run()
,I/Decoder ( 1229): createOrResetDecoder
I/art     ( 1064): Explicit concurrent mark sweep GC freed 55862(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 1.686ms total 40.142ms
,I/art     ( 1512): Explicit concurrent mark sweep GC freed 2496(186KB) AllocSpace objects, 1(24KB) LOS objects, 22% free, 26MB/34MB, paused 681us total 71.534ms
,I/ActivityManager(  818): Start proc 4098:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,I/art     (  818): Explicit concurrent mark sweep GC freed 23492(1351KB) AllocSpace objects, 13(867KB) LOS objects, 31% free, 34MB/50MB, paused 2.169ms total 90.153ms
,I/art     (  818): WaitForGcToComplete blocked for 72.060ms for cause Explicit
,I/ConfigService( 1329): onCreate
,W/InputMethodManagerService(  818): Got RemoteException sending setActive(false) notification to pid 3662 uid 10265
,I/Keyboard.Facilitator( 1229): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1229): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1229): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run() : Loading LM = contacts
,W/LocationOracleImpl( 1512): Best location was null
,I/HotwordRecognitionRnr( 1512): Starting hotword detection.
,I/MicrophoneInputStream( 1512): mic_starting com.google.android.apps.gsa.speech.audio.u@1e37b698
I/art     ( 1299): Explicit concurrent mark sweep GC freed 5099(372KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 690us total 29.299ms
,I/AudioFlinger(  356): AudioFlinger's thread 0xb406e000 ready to run
,I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1512): mic_started com.google.android.apps.gsa.speech.audio.u@1e37b698
,D/JobSchedulerService(  818): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  818): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1229): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1229): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1229): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1229): run()
I/StatsUtilsManager( 1229): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1229): shouldRecordStats() = Too Soon
,D/audio_hw_primary(  356): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  356): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  356): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  356): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  356): enable_audio_route: apply and update mixer path: audio-record
,I/art     (  818): Explicit concurrent mark sweep GC freed 5457(244KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 1.214ms total 141.585ms
,D/VoicemailCleanupService( 4098): Cleaning up data for package: com.test.thalitest
,I/ContactLocale( 4098): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  818): Start proc 4135:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/HotwordWorker( 1512): onReady
,D/WifiService(  818): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@196d0304}
,E/WifiStateMachine(  818): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-54
,I/art     ( 4083): System.exit called, status: 0
I/AndroidRuntime( 4083): VM exiting with result code 0.
,I/ActivityManager(  818): Start proc 4156:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,D/Launcher.Workspace( 1299): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1299): 11683562 - stripEmptyScreens()
,E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660794131
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/ContextImpl( 4156): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1329): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1329): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,V/GoogleAuthProtoRequest( 3126): [312] a.<init>: mAccountName set to: thalitester@gmail.com
,D/PackageBroadcastService( 1771): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1771): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1771): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1771): Module APK com.google.android.play.games already loaded
,W/Launcher( 1299): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@351dd9bb new=com.google.android.velvet.VelvetApplication@351dd9bb
,I/UpdateIcingCorporaServi( 1512): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  818): Start proc 4184:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/LocationSettingsChecker( 1771): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 1771): (3850) statement aborts at 167: [DELETE FROM FileContent112 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
,E/DocListDatabase( 1771): Failed to delete from FileContent112
E/DocListDatabase( 1771): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1771): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1771): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1771): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1771): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1771): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1771): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1771): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/DocListDatabase( 1771): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/DocListDatabase( 1771): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/DocListDatabase( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 1771): 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
E/AndroidRuntime( 1771): FATAL EXCEPTION: pool-7-thread-1
E/AndroidRuntime( 1771): Process: com.google.android.gms, PID: 1771
E/AndroidRuntime( 1771): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1771): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1771): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 1771): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/AndroidRuntime( 1771): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/AndroidRuntime( 1771): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/AndroidRuntime( 1771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1771): 	at java.lang.Thread.run(Thread.java:818)
,W/FileUtils( 1771): Failed to chmod(/data/data/com.google.android.gms/databases/metrics.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,D/GOOGLEHELP_CompatibleDatabase( 1771): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1771): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1771): (3850) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
D/GOOGLEHELP_CompatibleDatabase( 1771): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1771): Sending signal. PID: 1771 SIG: 9
,I/GLSUser ( 1329): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1329): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1329): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1329): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  818): Start proc 4205:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/JavaBinder(  818): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager(  818): Failure sending service ComponentInfo{com.google.android.gms/com.google.android.location.util.PreferenceService} to connection android.os.BinderProxy@240f7cf6 (in com.google.android.gms)
W/ActivityManager(  818): android.os.TransactionTooLargeException
W/ActivityManager(  818): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  818): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  818): 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
W/ActivityManager(  818): 	at com.android.server.am.ActiveServices.publishServiceLocked(ActiveServices.java:885)
W/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.publishService(ActivityManagerService.java:15342)
W/ActivityManager(  818): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:978)
W/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  818): 	at android.os.Binder.execTransact(Binder.java:446)
,E/JavaBinder(  818): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  818): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
,W/ResourcesManager(  818): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  818): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/DropBoxManagerService(  818): Can't write: system_app_crash
E/DropBoxManagerService(  818): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  818): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  818): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  818): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  818): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  818): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  818): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  818): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  818): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  818): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  818): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  818): 	... 5 more
,I/art     (  367): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 15.798ms
V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GmsClient( 1512): service died
D/WifiService(  818): Client connection lost with reason: 4
E/AppDataSearchHelper( 1512): Could not connect to AppDataSearch for onTableChanged, error 8
W/AppDataSearchHelper( 1512): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 1512): UpdateCorporaTask done [took 94 ms] updated apps [took 94 ms] 
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 209us total 11.174ms
,D/OpenGLRenderer(  818): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  818): Validating map...
,I/ActivityManager(  818): Process com.google.android.gms (pid 1771) has died
W/ActivityManager(  818): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10970ms
W/ActivityManager(  818): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10970ms
W/ActivityManager(  818): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10970ms
W/ActivityManager(  818): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10970ms
W/ActivityManager(  818): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10970ms
W/ActivityManager(  818): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20970ms
W/ActivityManager(  818): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20970ms
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 14.033ms
W/ResourcesManager( 4205): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4205): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ExperimentUpdateService( 3126): [312] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3126): [312] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3126): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3126): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3126): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3126): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3126): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3126): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3126): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3126): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3126): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3126): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  818): Killing 3727:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/OpenGLRenderer(  818): Initialized EGL, version 1.4
,I/MultiDex( 4205): VM with version 2.1.0 has multidex support
,I/MultiDex( 4205): install
I/MultiDex( 4205): VM has multidex support, MultiDex support library is disabled.
,D/OpenGLRenderer(  818): Enabling debug mode 0
,W/InputMethodManagerService(  818): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@129b6071 attribute=null, token = android.os.BinderProxy@de89bf2
,V/JNIHelp ( 4205): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4205): Installed default security provider GmsCore_OpenSSL
,W/NativeLibraryUtils( 4205): Failed to open lock file
W/NativeLibraryUtils( 4205): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4205): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4205): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4205): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4205): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4205): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4205): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4205): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4205): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4205): 	... 3 more
,I/ActivityManager(  818): Killing 3747:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/GAv4    ( 4184): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4184):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4184):   adb logcat -s GAv4
,W/GAv4    ( 4184): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
W/GAv4    ( 4184): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4184): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4184): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4184): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4184): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4184): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4184): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4184): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4184): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4184): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4184): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 4184): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4184): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209),
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806),
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4184): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4184): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4184): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4184): 	at fdw.e(Unknown Source),
E/SQLiteDatabase( 4184): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4184): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4184): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4184): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4184): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4184): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4184): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4184): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 4184): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4184): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 4184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193),
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4184): ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4184): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4184): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4184): 	at ael.a(PG:1521)
,E/SQLiteDatabase( 4184): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4184): 	at aen.run(PG:536)
,I/ActivityManager(  818): Start proc 4239:com.google.android.gms/u0a11 for service com.google.android.gms/.analytics.service.AnalyticsService
,E/SQLiteDatabase( 4184): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4184): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4184): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4184): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4184): 	at aej.c(PG:139)
E/SQLiteDatabase( 4184): 	at aej.b(PG:398)
E/SQLiteDatabase( 4184): 	at agf.f(PG:417)
E/SQLiteDatabase( 4184): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4184): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 4184): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4184): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4184): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4184): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4184): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4184): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4184): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4184): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4184): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4184): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4184): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 4239): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4239): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 4184): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4184): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 4239): VM with version 2.1.0 has multidex support
I/MultiDex( 4239): install
I/MultiDex( 4239): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4184): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  818): Start proc 4262:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,I/ActivityManager(  818): Killing 3803:com.android.chrome/u0a40 (adj 15): empty #17
,I/ProviderInstaller( 4184): Installed default security provider GmsCore_OpenSSL
,E/SQLiteDatabase( 4184): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4184): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4184): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4184): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4184): 	at aej.c(PG:139)
E/SQLiteDatabase( 4184): 	at aej.a(PG:358)
E/SQLiteDatabase( 4184): 	at aej.a(PG:345)
E/SQLiteDatabase( 4184): 	at agf.c(PG:884)
E/SQLiteDatabase( 4184): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 4184): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4184): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4184): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 4184): Failed to query Account133 object
E/AbstractDatabaseInstance( 4184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4184): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4184): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4184): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4184): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4184): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4184): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4184): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 4184): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 4184): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AbstractDatabaseInstance( 4184): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4184): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 4184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4184): 	at java.lang.Thread.run(Thread.java:818)
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
,E/SQLiteDatabase( 4239): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4239): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4239): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4239): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4239): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4239): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4239): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 4239): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4239): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4239): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4239): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4239): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4239): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4239): 	at java.lang.Thread.run(Thread.java:818)
,E/native  ( 1229): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1229): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,V/JNIHelp ( 4239): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SQLiteDatabase( 4262): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4262): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4262): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4262): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4262): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4262): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4262): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4262): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4262): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4262): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4262): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4262): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4262): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4262): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4262): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4262): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4262): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4262): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4262): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4262): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4262): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4262): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4262): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4262): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4262): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4262): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4262): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4262): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4262): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4262): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4262): Shutting down VM
E/AndroidRuntime( 4262): FATAL EXCEPTION: main
E/AndroidRuntime( 4262): Process: com.android.documentsui, PID: 4262
E/AndroidRuntime( 4262): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4262): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4262): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4262): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4262): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4262): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4262): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4262): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4262): 	at java.lang.re,flect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4262): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4262): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4262): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4262): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4262): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4262): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4262): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4262): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4262): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4262): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4262): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4262): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4262): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4262): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4262): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4262): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4262): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4262): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4262): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4262): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4262): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4262): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4262): 	... 9 more
E/DropBoxManagerService(  818): Can't write: system_app_crash
E/DropBoxManagerService(  818): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  818): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  818): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  818): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  818): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  818): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  818): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  818): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  818): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  818): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  818): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  818): 	... 5 more
,E/native  ( 1229): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1229): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/ProviderInstaller( 4239): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  818): Start proc 4289:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/ActivityManager(  818): Killing 3286:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/OpenGLRenderer(  818): Initialized EGL, version 1.4
,W/NativeLibraryUtils( 4239): Failed to open lock file
W/NativeLibraryUtils( 4239): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4239): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4239): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4239): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4239): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4239): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4239): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4239): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4239): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4239): 	... 3 more
,E/native  ( 1229): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1229): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1229): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1229): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/ActivityManager(  818): Killing 2784:com.google.android.talk/u0a61 (adj 15): empty #17
,D/ExternalStorage( 4289): After updating volumes, found 1 active roots
,I/GAv4-SVC( 4239): Google Analytics 7.8.99 is starting up.
,D/GCM     ( 1329): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/HotwordDetector( 1512): Closing mic
I/MicrophoneInputStream( 1512): mic_close com.google.android.apps.gsa.speech.audio.u@1e37b698
,E/Search.SharedPreferencesProto( 1512): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  818): Killing 3977:com.qualcomm.timeservice/1000 (adj 15): empty #17
,E/SQLiteDatabase( 4184): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4184): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4184): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4184): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4184): 	at aej.c(PG:139)
E/SQLiteDatabase( 4184): 	at aej.a(PG:358)
E/SQLiteDatabase( 4184): 	at aej.a(PG:345)
E/SQLiteDatabase( 4184): 	at agf.d(PG:281)
E/SQLiteDatabase( 4184): 	at agf.b(PG:312)
E/SQLiteDatabase( 4184): 	at agf.a(PG:221)
E/SQLiteDatabase( 4184): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/SQLiteDatabase( 4184): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/SQLiteDatabase( 4184): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4184): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4184): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 4184): 	at android.os.Binder.execTransact(Binder.java:446)
,E/AbstractDatabaseInstance( 4184): Failed to query Account133 object
E/AbstractDatabaseInstance( 4184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4184): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4184): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4184): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4184): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4184): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4184): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4184): 	at agf.d(PG:281)
E/AbstractDatabaseInstance( 4184): 	at agf.b(PG:312)
E/AbstractDatabaseInstance( 4184): 	at agf.a(PG:221)
E/AbstractDatabaseInstance( 4184): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/AbstractDatabaseInstance( 4184): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/AbstractDatabaseInstance( 4184): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AbstractDatabaseInstance( 4184): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AbstractDatabaseInstance( 4184): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/AbstractDatabaseInstance( 4184): 	at android.os.Binder.execTransact(Binder.java:446)
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
E/DatabaseUtils( 4184): Writing exception to parcel
E/DatabaseUtils( 4184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/DatabaseUtils( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DatabaseUtils( 4184): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DatabaseUtils( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DatabaseUtils( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DatabaseUtils( 4184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/DatabaseUtils( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/DatabaseUtils( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/DatabaseUtils( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/DatabaseUtils( 4184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/DatabaseUtils( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 4184): 	at aev.getWritableDatabase(PG:238)
E/DatabaseUtils( 4184): 	at ael.a(PG:1521)
E/DatabaseUtils( 4184): 	,at hix$a.a(PG:125)
E/DatabaseUtils( 4184): 	at aej.c(PG:139)
E/DatabaseUtils( 4184): 	at aej.a(PG:358)
E/DatabaseUtils( 4184): 	at aej.a(PG:345)
E/DatabaseUtils( 4184): 	at agf.d(PG:281)
E/DatabaseUtils( 4184): 	at agf.b(PG:312)
E/DatabaseUtils( 4184): 	at agf.a(PG:221)
E/DatabaseUtils( 4184): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/DatabaseUtils( 4184): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/DatabaseUtils( 4184): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 4184): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 4184): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 4184): 	at android.os.Binder.execTransact(Binder.java:446)
W/Documents( 4262): Failed to load some roots from com.google.android.apps.docs.storage: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/Documents( 4262): Update found 6 roots in 418ms
,I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1512): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1512): Hotword detection finished
,W/GAv4    ( 4184): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4184): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4184): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4184): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 4239): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4239): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4239): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4239): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:884)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4239): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.e.k.run(SourceFile:388)
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4184): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/GAv4-SVC( 4239): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 4239): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4184): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4184): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
,W/GAv4    ( 4184): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4239): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4239): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4239): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4239): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:897)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4239): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.e.k.run(SourceFile:388)
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4-SVC( 4239): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4239): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4184): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4184): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4184): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4184): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4184): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4239): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4-SVC( 4239): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4239): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4184): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4-SVC( 4239): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4239): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4184): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/GAv4    ( 4184): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4184): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4184): Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
I/ActivityManager(  818): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
V/WindowManager(  818): addAppToken: AppWindowToken{1e5b7142 token=Token{1c34eb8d ActivityRecord{780424 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
,E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4184): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4184): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/Process ( 4184): Sending signal. PID: 4184 SIG: 9
,E/lowmemorykiller(  255): Error writing /proc/4184/oom_score_adj; errno=22
,E/JavaBinder(  818): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager(  818): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  818): android.os.TransactionTooLargeException
W/ActivityManager(  818): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  818): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  818): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  818): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  818): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ActivityManager(  818): Start proc 4320:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,W/ActivityManager(  818): Spurious death for ProcessRecord{383492ad 4320:com.google.android.apps.docs/u0a46}, curProc for 4184: null
,W/OpenGLRenderer( 1299): Incorrectly called buildLayer on View: ew, destroying layer...
,D/WifiService(  818): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@196d0304}
,D/AuthorizationBluetoothService( 1329): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
F/ActivityManager(  818): Service done with onDestroy, but executeNesting=2: ServiceRecord{c2e7282 u0 com.google.android.gms/.icing.service.IndexWorkerService}
F/ActivityManager(  818): android.util.Log$TerribleFailure: Service done with onDestroy, but executeNesting=2: ServiceRecord{c2e7282 u0 com.google.android.gms/.icing.service.IndexWorkerService}
F/ActivityManager(  818): 	at android.util.Log.wtf(Log.java:291)
F/ActivityManager(  818): 	at android.util.Slog.wtfStack(Slog.java:98)
F/ActivityManager(  818): 	at com.android.server.am.ActiveServices.serviceDoneExecutingLocked(ActiveServices.java:1877)
F/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.serviceDoneExecuting(ActivityManagerService.java:15363)
F/ActivityManager(  818): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:999)
F/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
F/ActivityManager(  818): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SQLiteDatabase( 4239): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 4239): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4239): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4239): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteDatabase( 4239): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4239): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4239): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 4239): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteDatabase( 4239): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4239): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4239): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 4239): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 4239): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4239): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4239): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4239): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4239): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4239): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHe,lper( 4239): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4239): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4239): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteOpenHelper( 4239): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteOpenHelper( 4239): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteOpenHelper( 4239): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteOpenHelper( 4239): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteOpenHelper( 4239): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteOpenHelper( 4239): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteOpenHelper( 4239): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteOpenHelper( 4239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4239): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 4239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4239): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  818): Can't write: system_server_wtf
E/DropBoxManagerService(  818): java.io.FileNotFoundException: /data/system/dropbox/drop19.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  818): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  818): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  818): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  818): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  818): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  818): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  818): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12002)
E/DropBoxManagerService(  818): 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:11815)
E/DropBoxManagerService(  818): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:11787)
E/DropBoxManagerService(  818): 	at android.os.Handler.handleCallback(Handler.java:739)
E/DropBoxManagerService(  818): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService(  818): 	at android.os.Looper.loop(Looper.java:135)
E/DropBoxManagerService(  818): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  818): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
E/DropBoxManagerService(  818): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  818): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  818): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  818): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  818): 	... 13 more
W/SQLiteOpenHelper( 4239): Opened reminders.db in read-only mode
,V/GmsCoreStatsServiceLauncher( 4239): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/Icing   ( 4239): Storage manager: low false usage 1.98MB avail 20.74GB capacity 22.09GB
,E/SQLiteDatabase( 4239): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 4239): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4239): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4239): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 4239): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 4239): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4239): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4239): 	at java.lang.Thread.run(Thread.java:818)
,E/AndroidRuntime( 4239): FATAL EXCEPTION: AsyncTask #3
E/AndroidRuntime( 4239): Process: com.google.android.gms, PID: 4239
E/AndroidRuntime( 4239): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 4239): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/AndroidRuntime( 4239): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 4239): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 4239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 4239): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 4239): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4239): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4239): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4239): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4239): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4239): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4239): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4239): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4239): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4239): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4239): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4239): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/AndroidRuntime( 4239): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 4239): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 4239): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AndroidRuntime( 4239): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4239): 	... 4 more
,E/DropBoxManagerService(  818): Can't write: system_app_crash
E/DropBoxManagerService(  818): java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  818): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  818): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  818): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  818): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  818): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  818): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  818): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  818): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  818): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  818): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  818): 	... 5 more
,W/Icing   ( 4239): Received bad json for section weights override -- ignoring.
W/Icing   ( 4239): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4239): Received bad json for section weights override -- ignoring.
W/Icing   ( 4239): Received bad json for corpus context scoring override -- ignoring.
,I/art     ( 1329): Explicit concurrent mark sweep GC freed 29417(1647KB) AllocSpace objects, 19(1906KB) LOS objects, 37% free, 26MB/42MB, paused 1.697ms total 35.781ms
,D/WearableService( 4205): callingUid 10011, callindPid: 4205
,E/MDM     ( 1799): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/Icing   ( 4239): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids for write failed: Read-only file system
,E/Icing   ( 4239): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids
E/Icing   ( 4239): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata for write failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
E/Icing   ( 4239): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring for write failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
E/Icing   ( 4239): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs for write failed: Read-only file system
E/Icing   ( 4239): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs
E/Icing   ( 4239): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.tags.h for write failed: Read-only file system
E/Icing   ( 4239): Trie initialize fail
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
E/Icing   ( 4239): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h for write failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
E/Icing   ( 4239): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage for write failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
E/Icing   ( 4239): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage for write failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
E/Icing   ( 4239): Init docstore failed
E/Icing   ( 4239): Index init failed, resetting corpora
,E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.index failed: Read-only file system
E/Icing   ( 4239): Clearing index failed
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-0 failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-24 failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-30 failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user.__unseen__i.43133bd20a9b3232 failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
E/Icing   ( 4239): Clearing docstore failed
E/Icing   ( 4239): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/compact_status failed: Read-only file system
E/Icing   ( ,4239): Deleting compact status failed
,I/art     (  818): Explicit concurrent mark sweep GC freed 25235(1438KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 34MB/50MB, paused 1.518ms total 72.674ms,
,D/GCM     ( 1329): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1329): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4239): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/LocationInitializer( 4239): Restart initialization of location
,E/MDM     ( 1799): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4239): Restart initialization of location
,I/GAv4    ( 4320): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4320):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4320):   adb logcat -s GAv4
,W/GAv4    ( 4320): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4320): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SQLiteDatabase( 1329): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1329): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1329): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1329): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1329): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1329): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1329): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1329): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1329): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1329): 	at android.content.ContextWrapper.openOrCreateDatabase(Conte,xtWrapper.java:268)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1329): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1329): Opened phenotype.db in read-only mode
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
W/GAv4    ( 4320): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4320): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/SQLiteDatabase( 4320): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4320): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4320): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4320): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4320): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4320): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4320): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4320): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4320): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4320): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4320): Opening the database failed, dropping the table and recreating it
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/SQLiteDatabase( 4320): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4320): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4320): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4320): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4320): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4320): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4320): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4320): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4320): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4320): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4320): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4320): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4320): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4320): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4320): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4320): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4320): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4320): 	at aen.run(PG:536)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database,
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
,E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): ,	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/SQLiteDatabase( 4320): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4320): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4320): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4320): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4320): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4320): 	at aej.c(PG:139)
E/SQLiteDatabase( 4320): 	at aej.b(PG:398)
E/SQLiteDatabase( 4320): 	at agf.f(PG:417)
E/SQLiteDatabase( 4320): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4320): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/AbstractDatabaseInstance( 4320): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4320): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4320): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4320): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4320): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4320): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4320): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4320): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4320): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4320): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4320): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4320): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4320): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4320): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
W/ResourcesManager( 4320): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4320): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorNotificationActivity( 4320): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
V/JNIHelp ( 4320): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4320): Installed default security provider GmsCore_OpenSSL
,D/OpenGLRenderer( 4320): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 4320): Validating map...
,V/WindowManager(  818): Adding window Window{12cd8bab u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 9 (after Window{1aba5243 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,V/WindowManager(  818): Adding window Window{28653da1 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 10 (before Window{12cd8bab u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
,W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4320): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4320): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4320): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4320): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/CAKEMIX_CRASHED( 4320): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4320): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4320): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4320): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4320): 	at aen.run(PG:536)
,E/SQLiteDatabase( 4320): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4320): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4320): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4320): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4320): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4320): 	at aej.c(PG:139)
E/SQLiteDatabase( 4320): 	at aej.a(PG:358)
E/SQLiteDatabase( 4320): 	at aej.a(PG:345)
E/SQLiteDatabase( 4320): 	at agf.c(PG:884)
E/SQLiteDatabase( 4320): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 4320): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4320): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4320): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4320): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4320): Failed to query Account133 object
E/AbstractDatabaseInstance( 4320): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDataba,seInstance( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4320): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4320): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4320): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4320): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4320): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4320): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4320): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 4320): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 4320): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AbstractDatabaseInstance( 4320): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4320): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 4320): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4320): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4320): 	at java.lang.Thread.run(Thread.java:818)
,W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4320): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4320): Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4320): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4320): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4320): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4320): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4320): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4320): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/CAKEMIX_CRASHED( 4320): java.lang.RuntimeException: An error occured while executing doInBackground()
E/CAKEMIX_CRASHED( 4320): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/CAKEMIX_CRASHED( 4320): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/CAKEMIX_CRASHED( 4320): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/CAKEMIX_CRASHED( 4320): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/CAKEMIX_CRASHED( 4320): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/CAKEMIX_CRASHED( 4320): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/CAKEMIX_CRASHED( 4320): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/CAKEMIX_CRASHED( 4320): 	at java.lang.Thread.run(Thread.java:818)
E/CAKEMIX_CRASHED( 4320): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4320): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4320): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4320): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4320): 	at aej.c(PG:139)
E/CAKEMIX_CRASHED( 4320): 	at aej.a(PG:358)
E/CAKEMIX_CRASHED( 4320): 	at aej.a(PG:345)
E/CAKEMIX_CRASHED( 4320): 	at agf.c(PG:884)
E/CAKEMIX_CRASHED( 4320): 	at aii.doInBackground(PG:1063)
E/CAKEMIX_CRASHED( 4320): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/CAKEMIX_CRASHED( 4320): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/CAKEMIX_CRASHED( 4320): 	... 4 more
,I/ActivityManager(  818): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,I/Process ( 4320): Sending signal. PID: 4320 SIG: 9
I/ActivityManager(  818): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,E/JavaBinder(  818): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager(  818): Exception thrown sending new intent to ActivityRecord{780424 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}
W/ActivityManager(  818): android.os.TransactionTooLargeException
W/ActivityManager(  818): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  818): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  818): 	at android.app.ApplicationThreadProxy.scheduleNewIntent(ApplicationThreadNative.java:830)
W/ActivityManager(  818): 	at com.android.server.am.ActivityRecord.deliverNewIntentLocked(ActivityRecord.java:665)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStackSupervisor.startActivityUncheckedLocked(ActivityStackSupervisor.java:1960)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStackSupervisor.startActivityLocked(ActivityStackSupervisor.java:1515)
W/ActivityManager(  818): 	at com.android.server.am.ActivityStackSupervisor.startActivityMayWait(ActivityStackSupervisor.java:951)
W/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.startActivityAsUser(ActivityManagerService.java:3364)
W/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.startActivity(ActivityManagerService.java:3351)
W/ActivityManager(  818): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:139)
W/ActivityManager(  818): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  818): 	at android.os.Binder.execTransact(Binder.java:446)
,I/WindowState(  818): WIN DEATH: Window{12cd8bab u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,W/InputDispatcher(  818): channel '28653da1 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  818): channel '28653da1 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,I/ActivityManager(  818): Process com.google.android.apps.docs (pid 4320) has died
,W/ActivityManager(  818): Force removing ActivityRecord{780424 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}: app died, no saved state
,I/WindowState(  818): WIN DEATH: Window{28653da1 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,W/InputDispatcher(  818): Attempted to unregister already unregistered input channel '28653da1 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
,E/SQLiteDatabase( 1329): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1329): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1329): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1329): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1329): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1329): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1329): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1329): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1329): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1329): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1329): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1329): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1329): 	at android.databa,se.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1329): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1329): Opened phenotype.db in read-only mode
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178),
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1329): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1329): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1329): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1329): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1329): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1329): 	at java.lang.Thread.run(Thread.java:818)
,I/ConfigService( 1329): onDestroy
,E/Search.SharedPreferencesProto( 1512): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,D/HeadsetStateMachine( 2159): Disconnected process message: 10, size: 0,
,E/Icing   ( 4239): Not initialized
,E/Icing   ( 4239): Not initialized,
,E/QMI_FW  (  818): xport_send: Sendto failed for port 3840
E/LocSvc_api_v02(  818): E/locClientSendReq:2446]: send_msg_sync error: -1
,E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660794131
,E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/QMI_FW  (  818): xport_send: Sendto failed for port 3840
,E/LocSvc_api_v02(  818): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  818): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
E/kickstart(  869): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
,E/kickstart(  869): ERROR: function: sahara_main:1143 Sahara protocol error
E/kickstart(  869): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_unlock
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0,

```
