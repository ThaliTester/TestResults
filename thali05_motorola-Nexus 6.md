#### Test 5841644866d9c0e_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  819): Killing 3315:com.qualcomm.timeservice/1000 (adj 15): empty #17
I/ActivityManager(  819): Killing 3335:com.google.android.deskclock/u0a44 (adj 15): empty #17
,--------- beginning of main
D/AndroidRuntime( 3747): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3747): CheckJNI is OFF
D/AndroidRuntime( 3747): Calling main entry com.android.commands.am.Am
I/ActivityManager(  819): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  819): addAppToken: AppWindowToken{8ea181d token=Token{7eac8f4 ActivityRecord{32e4eac7 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
I/MicrophoneInputStream( 1516): mic_close com.google.android.apps.gsa.speech.audio.u@12fdd709
V/WindowManager(  819): Adding window Window{1e12428c u0 Starting com.test.thalitest} at 2 of 7 (after Window{1432b765 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1516): Closing mic
D/AndroidRuntime( 3747): Shutting down VM
I/ActivityManager(  819): Start proc 3761:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1516): Stopping hotword detection.
I/HotwordRecognitionRnr( 1516): Hotword detection finished
I/ActivityManager(  819): Killing 3108:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660007699
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3761): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3761): Time to load native libraries: 6 ms (timestamps 9538-9544)
,I/LibraryLoader( 3761): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3761): Binding Chromium to main looper Looper (main, tid 1) {1b541f5c}
,I/LibraryLoader( 3761): Expected native library version number "",actual native library version number ""
,I/chromium( 3761): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 3761): Initializing chromium process, singleProcess=true
,W/art     ( 3761): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3761): ApplicationContext is null in ApplicationStatus
,W/chromium( 3761): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3761): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 3761): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3761): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  819): Message: 20
D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28ed1a8e:true
,W/art     ( 3761): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3761): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 3761): CordovaWebView is running on device made by: motorola
,W/art     ( 3761): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3761): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3761): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3761): Validating map...
V/WindowManager(  819): Adding window Window{2b1b433e u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1e12428c u0 Starting com.test.thalitest})
W/chromium( 3761): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3761): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3761): Enabling debug mode 0
,I/ActivityManager(  819): Displayed com.test.thalitest/.MainActivity: +846ms
,I/Keyboard.Facilitator( 1233): onFinishInput()
,W/BindingManager( 3761): Cannot call determinedVisibility() - never saw a connection for the pid: 3761
,D/JsMessageQueue( 3761): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3761): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576397312
,I/chromium( 3761): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3761): Initializing JXcore engine
W/jxcore-log( 3761): JXcore engine is ready
,W/Thread-417( 3814): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11515]" dev="sockfs" ino=11515 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
W/Thread-417( 3814): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-417( 3814): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11747]" dev="sockfs" ino=11747 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-417( 3814): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[24040]" dev="sockfs" ino=24040 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3761): Starting JXcore engine,
,W/jxcore-log( 3761): Platform android,
,W/jxcore-log( 3761): 
W/jxcore-log( 3761): Process ARCH arm
W/jxcore-log( 3761): 
,I/jxcore-log( 3761): JXcore Cordova bridge is ready!
I/jxcore-log( 3761): 
W/jxcore-log( 3761): JXcore engine is started
,I/jxcore-log( 3761): Toggling radios to true
I/jxcore-log( 3761): 
,D/BluetoothAdapter( 3761): enable(): BT is already enabled..!
,D/WifiService(  819): setWifiEnabled: true pid=3761, uid=10265
E/WifiService(  819): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  819): New client listening to asynchronous messages
,I/jxcore-log( 3761): Radios toggled
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): My device name is: motorola-Nexus 6
I/jxcore-log( 3761): 
,I/wpa_supplicant( 1135): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  819): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1260): Read error: ssl=0x9d14a800: I/O error during system call, Connection timed out,
,V/NativeCrypto( 1260): SSL shutdown failed: ssl=0x9d14a800: I/O error during system call, Broken pipe
,D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
E/WifiStateMachine(  819): Start Disconnecting Watchdog 1
E/WifiStateMachine(  819): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/WifiNetworkAgent(  819): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  819): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  819): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  819): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  819): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  819): MasterInitialState.processMessage what=3
D/ConnectivityService(  819): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  819): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1516): Network connectivity changed, type is: 6
,D/PhoneInterfaceManager( 1342): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1342): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false,
,E/WifiConfigStore(  819): Setting BSSID for "NG7005g"WPA_PSK to any
,V/MusicLeanback( 3072): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/WifiConfigStore(  819): will read network variables netId=0
,E/WifiStateMachine(  819): CMD_AUTO_CONNECT did save config ->  nid=0
D/TelephonyManager(  819): getDataEnabled: retVal=false
,E/WifiConfigStore(  819): will read network variables netId=0
,E/GpsLocationProvider(  819): No APN found to select.
,I/ActivityManager(  819): Start proc 3823:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,D/PhoneInterfaceManager( 1342): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1342): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  819): getDataEnabled: retVal=false
,E/GpsLocationProvider(  819): No APN found to select.
,I/ActivityManager(  819): Start proc 3849:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  819): Killing 3050:com.android.settings/1000 (adj 15): empty #17
,D/SprintDMReceiver( 3849): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3849): simOperator:  IMSI: null,
D/SprintDMReceiver( 3849): Not Sprint UICC, don't do anything.
,I/ActivityManager(  819): Killing 2573:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1774): num queued entries: 0
,I/iu.UploadsManager( 1774): num updated entries: 0
,I/iu.SyncManager( 1774): NEXT; no task
,I/ValidateNoPeople(  819): skipping global notification
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599962 ms
I/Kids    ( 1774): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/Babel   ( 3635): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  819): Start proc 3869:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1774): onDestroy
,I/GAv4    ( 3869): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3869):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3869):   adb logcat -s GAv4
,W/GAv4    ( 3869): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3869): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3869): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3869): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3869): Time to load native libraries: 1 ms (timestamps 3577-3578)
I/LibraryLoader( 3869): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3869): Binding Chromium to main looper Looper (main, tid 1) {69d8cf0}
I/LibraryLoader( 3869): Expected native library version number "",actual native library version number ""
I/chromium( 3869): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3869): Initializing chromium process, singleProcess=true
W/art     ( 3869): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3869): ApplicationContext is null in ApplicationStatus
,W/chromium( 3869): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3869): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3869): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3869): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,W/AudioManagerAndroid( 3869): Requires BLUETOOTH permission
,I/NSApplication( 3869): Starting up...
,I/ActivityManager(  819): Start proc 3925:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  819): Killing 3477:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  819): Waited long enough for: ServiceRecord{316a84e4 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/ActivityManager(  819): Killing 3499:com.android.musicfx/u0a18 (adj 15): empty #17
,V/MusicLeanback( 3072): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3849): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3849): simOperator:  IMSI: null,
D/SprintDMReceiver( 3849): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) },
,D/SystemUpdateService( 1774): onCreate,
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/ActivityManager(  819): Killing 3531:com.google.android.apps.docs/u0a46 (adj 15): empty #17
I/SystemUpdateService( 1774): showing system update notification
,I/wpa_supplicant( 1135): wlan0: Trying to associate with SSID 'NG7005g'
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1774): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  819): skipping global notification
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599750 ms
,D/SystemUpdateService( 1774): onDestroy
,I/ActivityManager(  819): Killing 1417:android.process.acore/u0a5 (adj 15): empty #17
,I/wpa_supplicant( 1135): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1135): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1135): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  819): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} },
E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
E/WifiStateMachine(  819): Start Dhcp Watchdog 2
,E/WifiStateMachine(  819):  WifiLinkLayerStats: 
E/WifiStateMachine(  819):  my bss beacon rx: 175
E/WifiStateMachine(  819):  RSSI mgmt: -51
E/WifiStateMachine(  819):  BE :  rx=181 tx=149 lost=0 retries=0
E/WifiStateMachine(  819):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  on_time : 8665 tx_time=208 rx_time=454 scan_time=0
,D/ConnectivityService(  819): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  819): do suspend false
,E/WifiStateMachine(  819): scanCount==0 - aborting
,I/dhcpcd  ( 3954): version 5.5.6 starting
,I/dhcpcd  ( 3954): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3954): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3954): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3761): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3761): 
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
,D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  819): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
,D/CSLegacyTypeTracker(  819): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  819): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1342): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1342): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  819): getDataEnabled: retVal=false
,I/NetworkMonitor( 3072): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1516): Network connectivity changed, type is: 2
,E/GpsLocationProvider(  819): No APN found to select.
V/MusicLeanback( 3072): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3849): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3849): simOperator:  IMSI: null
D/SprintDMReceiver( 3849): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1774): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1774): onCreate,
,I/ActivityManager(  819): Start proc 3986:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,D/SystemUpdateService( 1774): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1774): active receiver: enabled
,I/SystemUpdateService( 1774): showing system update notification
,I/ActivityManager(  819): Start proc 4004:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 12:09:25 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455019765605], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455019765586]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Validated
D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  819): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/iu.Environment( 1774): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1774): num queued entries: 0
,I/ValidateNoPeople(  819): skipping global notification
,I/iu.UploadsManager( 1774): num updated entries: 0
,V/SystemUpdateService( 1774): retry (wakeup: false) in 3599921 ms
,I/iu.SyncManager( 1774): NEXT; no task
,I/art     (  819): Explicit concurrent mark sweep GC freed 48701(2MB) AllocSpace objects, 11(270KB) LOS objects, 32% free, 33MB/49MB, paused 1.367ms total 53.632ms
,D/SystemUpdateService( 1774): onDestroy
,D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1774): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,W/GAV2    ( 4004): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/Herrevad( 1774): NQAS connected
,I/art     ( 1260): Explicit concurrent mark sweep GC freed 28372(1523KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 856us total 30.213ms
,I/BooksApp( 4004): Created application version: 3.6.8 (30608)
,I/Babel   ( 3635): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1260): Connected
,D/GCM     ( 1260): Message class com.google.f.a.a.p
,I/BooksSync( 4004): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3986): Connecting to GoogleApiClient
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3986): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,I/BooksConfig( 4004): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3761): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3761): 
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/BooksAccountManager( 4004): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4004): Soft error
E/BooksSync( 4004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4004): Sync error
E/BooksSync( 4004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4004): Finished books sync
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 74851, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3986): IOException
E/KeepSync( 3986): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3986): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3986): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3986): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3986): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3986): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3986): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3986): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3986): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3986): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3986): 	... 10 more
W/KeepSync( 3986): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 74287, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3761): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3761): 
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/jxcore-log( 3761): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3761): 
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/jxcore-log( 3761): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3761): 
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
E/ExperimentLoader( 3242): 	,at hec.a(PG:42)
E/ExperimentLoader( 3242): 	at hee.a(PG:102)
E/ExperimentLoader( 3242): 	at czr.a(PG:65)
E/ExperimentLoader( 3242): 	at kka.a(PG:108)
E/ExperimentLoader( 3242): 	at czp.a(PG:19176)
E/ExperimentLoader( 3242): 	at czp.a(PG:9081)
E/ExperimentLoader( 3242): 	at czq.run(PG:1686)
E/ExperimentLoader( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3242): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3242): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3242): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3242): 	at jdm.a(PG:77)
E/ExperimentLoader( 3242): 	... 15 more
,E/ExperimentLoader( 3242): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3242): 	at fal.a(PG:38)
E/ExperimentLoader( 3242): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3242): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 76311, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  819): Killing 3609:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/ConnectivityService(  819): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
,D/Finsky  ( 3569): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 3569): [1] 5.onFinished: Scheduling replication attempt 1.
,I/art     ( 1260): Explicit concurrent mark sweep GC freed 21610(1252KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.385ms total 31.434ms
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.86 rxSuccessRate=9.83 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,I/GAV2    ( 4004): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  819): Killing 3417:com.google.android.gm/u0a78 (adj 15): empty #17
,I/jxcore-log( 3761): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3761): 
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.86 rxSuccessRate=9.83 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3761): Test app app.js loaded
I/jxcore-log( 3761): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c4f2c16 added. We now have 1 listener(s)
,I/chromium( 3761): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,I/jxcore-log( 3761): BLE advertisement is supported,
I/jxcore-log( 3761): 
,D/Finsky  ( 3569): [374] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 34741(1575KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.351ms total 85.495ms
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3569): [374] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.34 rxSuccessRate=5.46 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3569): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3569): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.54 rxSuccessRate=11.53 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3569): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3569): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1233): run()
I/Keyboard.Facilitator( 1233): flushDynamicLanguageModels()
,I/ConfigService( 1260): onCreate
,I/BooksSync( 4004): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3986): Connecting to GoogleApiClient
,I/BooksConfig( 4004): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
,E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	,at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication,
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): ,	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): ,	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	,at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774),: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
V/KeepSync( 3986): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4004): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4004): Soft error
E/BooksSync( 4004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4004): Sync error
E/BooksSync( 4004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4004): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 108924, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3986): IOException
E/KeepSync( 3986): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3986): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3986): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3986): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3986): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3986): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3986): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3986): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3986): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3986): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3986): 	... 10 more
W/KeepSync( 3986): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 108591, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
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
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
E/ExperimentLoader( 3242): 	,at kka.a(PG:108)
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
E/ExperimentLoader( 3242): ,	at jdj.a(PG:1125)
E/ExperimentLoader( 3242): 	at jdm.a(PG:77)
E/ExperimentLoader( 3242): 	... 15 more
E/ExperimentLoader( 3242): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3242): 	at fal.a(PG:38)
E/ExperimentLoader( 3242): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3242): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 110419, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1260): onDestroy
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.41 rxSuccessRate=4.83 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3569): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3569): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.83 rxSuccessRate=5.64 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  819): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  819): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (313 us),
,D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6082000
I/DisplayManagerService(  819): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  819): Display changed displayId=0,
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  819): Excessive delay in setPowerMode(): 262ms
,I/DreamManagerService(  819): Entering dreamland.,
,I/DreamController(  819): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,I/PowerManagerService(  819): Dozing...
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  819): cancelDelayedScan -> 12
,E/native  (  819): do suspend false
,I/art     (  819): Explicit concurrent mark sweep GC freed 53414(2MB) AllocSpace objects, 23(556KB) LOS objects, 31% free, 34MB/50MB, paused 2.490ms total 80.810ms
,I/Keyboard.Facilitator( 1233): onFinishInput()
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  819): cancelDelayedScan -> 14
,E/native  (  819): do suspend true
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3569): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3569): [1] 5.onFinished: Scheduling replication attempt 5.
,I/kickstart(  870): STATUS: Received file 'm9kefs2'
I/kickstart(  870): STATUS: 950272 bytes transferred in 0.977032 seconds
I/kickstart(  870): STATUS: Successfully downloaded files from target 
,I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  870): STATUS: Sahara protocol completed
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3823): [410] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1260): Explicit concurrent mark sweep GC freed 37323(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.040ms total 39.969ms
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1260): Vacuum at: now=1455019873501 tag=VacuumService
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Finsky  ( 3569): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3569): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3569): [1] 5.onFinished: Giving up after 6 failures.
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3823): [410] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3823): [410] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3823): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3823): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3823): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3823): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1260): Using platform SSLCertificateSocketFactory
,W/Uploader( 1260): No account for auth token provided
,W/Uploader( 1260): No account for auth token provided
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1260): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1260): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1260): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1260): ,	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1260): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1260): No account for auth token provided
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1260): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1260): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1260): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1260): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1260): No account for auth token provided
,W/Uploader( 1260): No account for auth token provided,
,W/Uploader( 1260): No account for auth token provided
,W/Uploader( 1260): No account for auth token provided
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1260): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1260): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1260): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1260): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1260): No account for auth token provided
,W/Uploader( 1260): No account for auth token provided
,W/Uploader( 1260):  no longer exists, so no auth token.
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1260): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1260): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1260): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1260): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1260): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1260): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1260): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1260): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1260): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1260): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/KeepSync( 3986): Connecting to GoogleApiClient
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure,
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	,at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3986): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3986): IOException
E/KeepSync( 3986): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3986): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3986): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3986): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3986): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3986): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3986): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3986): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3986): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3986): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3986): 	... 10 more
W/KeepSync( 3986): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 194741, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,V/GoogleAuthProtoRequest( 3823): [411] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3823): [411] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3823): [411] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3823): 	,at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3823): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3823): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3823): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3823): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1233): run()
I/Keyboard.Facilitator( 1233): flushDynamicLanguageModels()
,I/ConfigService( 1260): onCreate
,I/art     (  819): Explicit concurrent mark sweep GC freed 38176(1667KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 2.008ms total 94.480ms
,I/BooksSync( 4004): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4004): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3242): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	at jcs.i(PG:143)
E/HttpOperation( 3242): 	at blb.a(PG:3937),
E/HttpOperation( 3242): 	at czp.a(PG:18188)
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 12 more,
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	at fal.a(PG:38)
E/HttpOperation( 3242): ,	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 14 more
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
E/BooksAccountManager( 4004): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4004): Soft error
E/BooksSync( 4004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4004): Sync error
E/BooksSync( 4004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4004): Finished books sync
D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 195327, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 198054, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1260): onDestroy
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,I/jxcore-log( 3761): TAP version 13
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # multiplex can send data
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 1 String should be length:200
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # enqueue and run in order
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 2 firstPromise setTimeout
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 3 firstPromise result
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 4 firstPromise testValue
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 5 secondPromise setTimeout
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 6 secondPromise result
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 7 secondPromise testValue
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 8 thirdPromise in promise
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 9 thirdPromise result
,I/jxcore-log( 3761): 
I/jxcore-log( 3761): ok 10 thirdPromise testValue
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup,
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # basic
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 11 sane
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # another,
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 12 sane
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 13 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 14 null
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 15 (unnamed assert)
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 16 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 17 should not throw
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 18 (unnamed assert)
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 19 (unnamed assert)
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 20 should not throw
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 21 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 22 should be equal
I/jxcore-log( 3761): 
I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 23 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # failed to get mobile documents path
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 24 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 25 should be equal
I/jxcore-log( 3761): 
I/jxcore-log( 3761): ok 26 should be equal
I/jxcore-log( 3761): 
I/jxcore-log( 3761): ok 27 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #init should register the networkChanged event
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 28 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #startBroadcasting should throw on null device name
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 29 should throw
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 30 should throw
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3761): ,
,I/jxcore-log( 3761): # teardown,
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 31 should throw,
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup,
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #startBroadcasting should throw on NaN port,
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 32 should throw
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #startBroadcasting should throw on negative port
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 33 should throw
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #startBroadcasting should throw on too large port
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 34 should throw
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 35 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 36 should be equal
I/jxcore-log( 3761): 
I/jxcore-log( 3761): ok 37 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 38 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 39 should be equal
I/jxcore-log( 3761): 
I/jxcore-log( 3761): ok 40 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 41 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 42 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 43 should be equal
I/jxcore-log( 3761): 
I/jxcore-log( 3761): ok 44 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 45 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 46 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 47 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 48 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 49 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # should call Mobile("Disconnect") without an error
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 50 should be equal
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 51 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # should call Mobile("Disconnect") and handle an error
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 52 should be equal
,I/jxcore-log( 3761): 
I/jxcore-log( 3761): ok 53 should be equal
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup,
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #start should fail if called twice in a row,
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown,
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 54 specific error should be received
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 55 specific error should be returned
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 56 error should be null
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 57 error should be null
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
,I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 58 error should be null
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 59 error should be null
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): ,
,I/jxcore-log( 3761): ok 60 error should be null
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 61 error should be null
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): ok 62 specific error should be returned
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # setup
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3761): 
,I/jxcore-log( 3761): # teardown
I/jxcore-log( 3761): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): load: ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c28a997 added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): setDiscoveryMode: BLE_AND_WIFI -> WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to WIFI,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to WIFI,
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019968710.3761
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): bind: Binding a new listener
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3761): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019968710.3761","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): start: OK
I/io.jxcore.node.ConnectionHelper( 3761): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3761): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3761): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019968710.3761, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3761): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3761): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019968710.3761","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019968710.3761","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455019968710.3761","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: OK
I/io.jxcore.node.ConnectionHelper( 3761): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019968710.3761, mode: WIFI
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3761): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 3761): 
,I/io.jxcore.node.ConnectionHelper( 3761): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): stopListeningForIncomingConnections: Stopping...,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): onServerStopped
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopForRestart,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3761): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3761): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 3761): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3761): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3761): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): setState: NOT_STARTED
I/wpa_supplicant( 1135): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3761): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3761): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 3761): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Insecure RFCOMM socket port number: -1, 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180477f0 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3761): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019968807.3761
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): bind: Binding a new listener
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3761): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019968807.3761","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): start: OK
I/io.jxcore.node.ConnectionHelper( 3761): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3761): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019968807.3761, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3761): bind: Binding a new listener
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3761): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3761): createAdvertiseData: From: 1455019968807.3761 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2178): registerClient() - UUID=ef07d986-c071-451b-ba53-b033f3c24476
,D/BtGatt.GattService( 2178): onClientRegistered() - UUID=ef07d986-c071-451b-ba53-b033f3c24476, clientIf=5
,D/BluetoothLeScanner( 3761): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2178): start scan with filters
D/BtGatt.ScanManager( 2178): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): setState: State changed from NOT_STARTED to STARTING
,D/BluetoothAdapterService( 2178): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34724b3a
,D/BtGatt.GattService( 2178): registerClient() - UUID=b2ccde34-d849-4728-b426-d45772f5c8c3
,D/BtGatt.GattService( 2178): onClientRegistered() - UUID=b2ccde34-d849-4728-b426-d45772f5c8c3, clientIf=6
,D/BluetoothLeAdvertiser( 3761): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2178): message : 0,
D/BtGatt.GattService( 2178): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2178): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2178): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2178): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.AdvertiseManager( 2178): starting multi advertising
,D/BtGatt.GattService( 2178): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2178): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3761): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019968807.3761","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019968807.3761","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455019968807.3761","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: OK
I/io.jxcore.node.ConnectionHelper( 3761): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019968807.3761, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3761): createAdvertiseData: From: 1455019968807.3761 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/wpa_supplicant( 1135): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3761): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 3761): 
I/io.jxcore.node.ConnectionHelper( 3761): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): shutdown
D/BtGatt.AdvertiseManager( 2178): message : 1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): onServerStopped
D/BtGatt.AdvertiseManager( 2178): stop advertise for client 6
,D/BtGatt.GattService( 2178): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2178): Client app is not null!
D/BtGatt.GattService( 2178): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2178): registerClient() - UUID=c45a5860-637e-4a53-ad46-29c97566fddd
,D/BtGatt.GattService( 2178): onClientRegistered() - UUID=c45a5860-637e-4a53-ad46-29c97566fddd, clientIf=6
D/BluetoothLeAdvertiser( 3761): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2178): message : 0
,D/BtGatt.AdvertiseManager( 2178): starting multi advertising
,D/BtGatt.GattService( 2178): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2178): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from NOT_STARTED to STARTING,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: Already running, call stopListening() first to restart,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
I/io.jxcore.node.ConnectionHelper( 3761): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3761): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3761): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): stop
I/wpa_supplicant( 1135): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 2178): message : 1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery stopped successfully
D/BtGatt.AdvertiseManager( 2178): stop advertise for client 6
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: RESTARTING
,D/BtGatt.GattService( 2178): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2178): Client app is not null!
D/BtGatt.GattService( 2178): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): stop: Stopped,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsBlePeerDiscovererStateChanged: [SCANNING]
,D/BtGatt.GattService( 2178): stopScan() - queue size =1
,D/BtGatt.GattService( 2178): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): stop: Stopped,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): updateState(): State changed from [SCANNING] to [NOT_STARTED]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsBlePeerDiscovererStateChanged: [NOT_STARTED]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopBlePeerDiscoverer: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): stop: Stopping services
D/BtGatt.GattService( 2178): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2178): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2178): stop scan
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3761): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3761): clear
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3761): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3761): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3761): ok 66 Should be able to call stopBroadcasting without error
I/jxcore-log( 3761): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Discovery mode: BLE_AND_WIFI, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e568aab added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019968952.3761
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): bind: Binding a new listener
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3761): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019968952.3761","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): start: OK
I/io.jxcore.node.ConnectionHelper( 3761): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3761): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3761): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019968952.3761, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3761): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3761): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019968952.3761","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019968952.3761","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455019968952.3761","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: OK
I/wpa_supplicant( 1135): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3761): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019968952.3761, mode: WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3761): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/wpa_supplicant( 1135): P2P-FIND-STOPPED 
I/jxcore-log( 3761): ok 67 Should be able to call startBroadcasting without error
I/jxcore-log( 3761): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3761): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3761): onConnectionManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3761): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3761): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3761): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3761): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 3761): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3761): ok 68 Should be able to call stopBroadcasting without error
I/jxcore-log( 3761): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f12687 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019969021.3761
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): bind: Binding a new listener
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3761): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019969021.3761","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): start: OK
I/io.jxcore.node.ConnectionHelper( 3761): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3761): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3761): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019969021.3761, mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3761): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3761): createAdvertiseData: From: 1455019969021.3761 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2178): registerClient() - UUID=a0063e77-08a4-4a96-af51-7e352bfc3dbb
,D/BtGatt.GattService( 2178): onClientRegistered() - UUID=a0063e77-08a4-4a96-af51-7e352bfc3dbb, clientIf=5
D/BluetoothLeScanner( 3761): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2178): start scan with filters
D/BtGatt.ScanManager( 2178): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): setState: State changed from NOT_STARTED to STARTING
,D/BtGatt.GattService( 2178): registerClient() - UUID=18345776-4f43-4ccd-8603-42009a52eb6e,
D/BtGatt.GattService( 2178): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2178): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2178): onClientRegistered() - UUID=18345776-4f43-4ccd-8603-42009a52eb6e, clientIf=6
,D/BluetoothLeAdvertiser( 3761): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2178): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2178): callback done for clientIf - 5 status - 0
,D/BtGatt.AdvertiseManager( 2178): message : 0
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/BtGatt.AdvertiseManager( 2178): starting multi advertising
,D/BtGatt.GattService( 2178): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2178): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3761): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019969021.3761","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019969021.3761","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455019969021.3761","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): setState: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 1135): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019969021.3761, mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3761): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3761): createAdvertiseData: From: 1455019969021.3761 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BtGatt.AdvertiseManager( 2178): message : 1
D/BtGatt.AdvertiseManager( 2178): stop advertise for client 6
,I/jxcore-log( 3761): ok 69 Should be able to call startBroadcasting without error
I/jxcore-log( 3761): 
,D/BtGatt.GattService( 2178): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2178): Client app is not null!
I/io.jxcore.node.ConnectionHelper( 3761): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): stopListeningForIncomingConnections: Stopping...
D/BtGatt.GattService( 2178): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from STARTING to NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): setState: NOT_STARTED
,D/BtGatt.GattService( 2178): registerClient() - UUID=77e9fa17-69f6-493b-bd91-b93e862bcc6e,
D/BtGatt.GattService( 2178): onClientRegistered() - UUID=77e9fa17-69f6-493b-bd91-b93e862bcc6e, clientIf=6
D/BluetoothLeAdvertiser( 3761): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2178): message : 0
,D/BtGatt.AdvertiseManager( 2178): starting multi advertising
,D/BtGatt.GattService( 2178): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2178): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): onStartSuccess
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3761): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): stop,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3761): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3761): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): onStartSuccess
I/wpa_supplicant( 1135): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 2178): message : 1
D/BtGatt.AdvertiseManager( 2178): stop advertise for client 6
D/BtGatt.GattService( 2178): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2178): Client app is not null!
D/BtGatt.GattService( 2178): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsBlePeerDiscovererStateChanged: [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): onIsAdvertiserStartedChanged: true
D/BtGatt.GattService( 2178): stopScan() - queue size =1
,D/BtGatt.GattService( 2178): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopBlePeerDiscoverer: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: RESTARTING
D/BtGatt.GattService( 2178): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2178): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2178): stop scan
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3761): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3761): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3761): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3761): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3761): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 3761): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23c976d9 added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): setDiscoveryMode: BLE_AND_WIFI -> WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to WIFI,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019969146.3761
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): bind: Binding a new listener
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3761): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019969146.3761","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3761): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): start: OK
I/io.jxcore.node.ConnectionHelper( 3761): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3761): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019969146.3761, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3761): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3761): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019969146.3761","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019969146.3761","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455019969146.3761","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsWifiPeerDiscoveryStartedChanged: true,
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: OK,
I/io.jxcore.node.ConnectionHelper( 3761): start: OK
I/wpa_supplicant( 1135): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019969146.3761, mode: WIFI
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3761): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 3761): 
I/io.jxcore.node.ConnectionHelper( 3761): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3761): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3761): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3761): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: NOT_INITIALIZED
I/wpa_supplicant( 1135): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3761): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3761): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3761): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3761): Service requests cleared successfully
,I/jxcore-log( 3761): ok 72 Should be able to call stopBroadcasting without error
I/jxcore-log( 3761): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3761): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fd1a795 added. We now have 7 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3761): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019969196.3761
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): bind: Binding a new listener
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3761): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019969196.3761","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3761): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): start: OK
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/io.jxcore.node.ConnectionHelper( 3761): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3761): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019969196.3761, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): bind: Binding a new listener,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3761): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3761): createAdvertiseData: From: 1455019969196.3761 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2178): registerClient() - UUID=706d1e51-87b1-4faa-bfd3-487fd80bd15c
,D/BtGatt.GattService( 2178): onClientRegistered() - UUID=706d1e51-87b1-4faa-bfd3-487fd80bd15c, clientIf=5
,D/BluetoothLeScanner( 3761): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2178): start scan with filters
D/BtGatt.ScanManager( 2178): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): setState: State changed from NOT_STARTED to STARTING,
,D/BtGatt.GattService( 2178): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2178): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2178): registerClient() - UUID=9f96c2a3-eb9f-4542-b1c2-c85c75b2c3e4
D/BtGatt.GattService( 2178): onClientRegistered() - UUID=9f96c2a3-eb9f-4542-b1c2-c85c75b2c3e4, clientIf=6
D/BluetoothLeAdvertiser( 3761): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2178): message : 0
D/BtGatt.GattService( 2178): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2178): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.AdvertiseManager( 2178): starting multi advertising
,D/BtGatt.GattService( 2178): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2178): onAdvertiseDataSet() - clientIf=6, status=0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from NOT_STARTED to STARTING,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3761): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019969196.3761","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1455019969196.3761","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3761): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1455019969196.3761","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3761): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1455019969196.3761, mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3761): start: OK
I/wpa_supplicant( 1135): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3761): createAdvertiseData: From: 1455019969196.3761 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BtGatt.AdvertiseManager( 2178): message : 1
D/BtGatt.AdvertiseManager( 2178): stop advertise for client 6
I/jxcore-log( 3761): ok 73 Should be able to call startBroadcasting without error
I/jxcore-log( 3761): 
D/BtGatt.GattService( 2178): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2178): Client app is not null!
I/io.jxcore.node.ConnectionHelper( 3761): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): stop: Stopping Bluetooth...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3761): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3761): setState: NOT_STARTED
D/BtGatt.GattService( 2178): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3761): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3761): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from STARTING to NOT_STARTED
D/BtGatt.GattService( 2178): registerClient() - UUID=cb4b1c83-c9ca-45ee-aaf5-bf7e065d5c4e
D/BtGatt.GattService( 2178): onClientRegistered() - UUID=cb4b1c83-c9ca-45ee-aaf5-bf7e065d5c4e, clientIf=6
D/BluetoothLeAdvertiser( 3761): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2178): message : 0
D/BtGatt.AdvertiseManager( 2178): starting multi advertising
,D/BtGatt.GattService( 2178): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2178): onAdvertiseDataSet() - clientIf=6, status=0,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3761): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3761): start: Already running, call stopListening() first to restart,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3761): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3761): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3761): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3761): onIsAdvertiserStartedChanged: true
,V/GoogleAuthProtoRequest( 3823): [412] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3823): [412] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3823): [412] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3823): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3823): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3823): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3823): 	at com.a.a.k.run(SourceFile:110)
,I/wpa_supplicant( 1135): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 1135): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,V/KeepSync( 3986): Connecting to GoogleApiClient
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3986): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1260): Explicit concurrent mark sweep GC freed 69764(3MB) AllocSpace objects, 7(698KB) LOS objects, 36% free, 27MB/43MB, paused 2.308ms total 50.192ms
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3986): IOException
E/KeepSync( 3986): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3986): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3986): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3986): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3986): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3986): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3986): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3986): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3986): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3986): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3986): 	... 10 more
W/KeepSync( 3986): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 319015, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1260): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1260): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1260): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1260): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1260): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1260): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1260): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3569): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 3569): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3569): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3569): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3569): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3569): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3569): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3569): Ignoring header User-Agent because its value was null.
,I/wpa_supplicant( 1135): P2P-DEVICE-LOST p2p_dev_addr=de:4a:3e:0f:89:ad
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3fa38a3b}
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3fa38a3b}
,I/BooksSync( 4004): Starting books sync for 61035162, extras: ade
,I/art     (  819): Explicit concurrent mark sweep GC freed 35637(1683KB) AllocSpace objects, 10(725KB) LOS objects, 31% free, 34MB/50MB, paused 2.902ms total 90.642ms
,I/BooksConfig( 4004): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4004): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4004): Soft error
E/BooksSync( 4004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4004): Sync error
E/BooksSync( 4004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4004): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 350292, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 355075, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 1135): P2P-FIND-STOPPED 
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/ActivityManager(  819): Start proc 4192:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4192): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4192):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4192):   adb logcat -s GAv4
,W/GAv4    ( 4192): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4192): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4192): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  819): Killing 2497:com.google.android.calendar/u0a37 (adj 15): empty #17
,V/GoogleAuthProtoRequest( 3823): [413] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3823): [413] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3823): [413] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3823): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3823): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3823): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3823): 	at com.a.a.k.run(SourceFile:110)
,I/wpa_supplicant( 1135): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,V/KeepSync( 3986): Connecting to GoogleApiClient
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3986): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3986): IOException
E/KeepSync( 3986): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3986): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3986): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3986): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3986): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3986): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3986): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3986): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3986): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3986): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3986): 	... 10 more
W/KeepSync( 3986): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 567110, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,I/BooksSync( 4004): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4004): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4004): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4004): Soft error
E/BooksSync( 4004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4004): Sync error
E/BooksSync( 4004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4004): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 629842, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  819): Explicit concurrent mark sweep GC freed 37003(1657KB) AllocSpace objects, 10(442KB) LOS objects, 31% free, 34MB/50MB, paused 3.252ms total 112.984ms
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1260): Explicit concurrent mark sweep GC freed 55110(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.081ms total 27.792ms
,E/HttpOperation( 3242): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3242): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3242): 	at jdm.a(PG:82)
E/HttpOperation( 3242): 	at jcs.o(PG:406)
E/HttpOperation( 3242): 	at jcn.a(PG:1379)
E/HttpOperation( 3242): 	,at jcs.i(PG:143)
E/HttpOperation( 3242): 	at hec.a(PG:42)
E/HttpOperation( 3242): 	at hee.a(PG:102)
E/HttpOperation( 3242): 	at czr.a(PG:65)
E/HttpOperation( 3242): 	at kka.a(PG:108)
E/HttpOperation( 3242): 	at czp.a(PG:19176),
E/HttpOperation( 3242): 	at czp.a(PG:9081)
E/HttpOperation( 3242): 	at czq.run(PG:1686)
E/HttpOperation( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3242): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3242): 	at jdj.a(PG:4091)
E/HttpOperation( 3242): 	,at jdj.a(PG:1125)
E/HttpOperation( 3242): 	at jdm.a(PG:77)
E/HttpOperation( 3242): 	... 15 more
E/HttpOperation( 3242): Caused by: faj: BadAuthentication
E/HttpOperation( 3242): 	,at fal.a(PG:38)
E/HttpOperation( 3242): 	at jdj.a(PG:4089)
E/HttpOperation( 3242): 	... 17 more
E/ExperimentLoader( 3242): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3242): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3242): 	at jdm.a(PG:82)
E/ExperimentLoader( 3242): 	at jcs.o(PG:406)
E/ExperimentLoader( 3242): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3242): ,	at jcs.i(PG:143)
E/ExperimentLoader( 3242): 	at hec.a(PG:42)
E/ExperimentLoader( 3242): 	at hee.a(PG:102)
E/ExperimentLoader( 3242): 	at czr.a(PG:65)
E/ExperimentLoader( 3242): ,	at kka.a(PG:108)
E/ExperimentLoader( 3242): 	at czp.a(PG:19176)
E/ExperimentLoader( 3242): 	at czp.a(PG:9081)
E/ExperimentLoader( 3242): 	at czq.run(PG:1686)
,E/ExperimentLoader( 3242): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3242): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3242): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ExperimentLoader( 3242): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3242): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3242): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3242): 	at jdj.a(PG:1125)
,E/ExperimentLoader( 3242): 	at jdm.a(PG:77)
E/ExperimentLoader( 3242): 	... 15 more
E/ExperimentLoader( 3242): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3242): 	at fal.a(PG:38)
E/ExperimentLoader( 3242): 	,at jdj.a(PG:4089)
E/ExperimentLoader( 3242): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 639315, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/btif_config_util( 2178): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0,
,V/GoogleAuthProtoRequest( 3823): [414] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3823): [414] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3823): [414] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3823): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3823): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3823): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3823): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3823): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3823): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/GCM     ( 1260): Message class com.google.f.a.a.i
,I/GoogleURLConnFactory( 1774): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/KeepSync( 3986): Connecting to GoogleApiClient
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/GLSActivity( 1260): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1260): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1260): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1260): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1260): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1260): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1260): 	at android.os.Binder.execTransact(Binder.java:446)
,W/SubscribedFeeds( 1774): Hard error
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 1062904, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  819): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 1094414, reason: Periodic
,E/ClientConnectionOperation( 1774): Handling authorization failure
E/ClientConnectionOperation( 1774): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1774): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1774): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1774): 	... 7 more
,V/KeepSync( 3986): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3986): (284) automatic index on blob_node(is_deleted)
,I/PeopleSync( 1774): onPerformSync() [5005f081]
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleDatabaseHelper( 1774): cleanUpNonGplusAccounts done.
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3986): IOException
E/KeepSync( 3986): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3986): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3986): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3986): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3986): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3986): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3986): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3986): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3986): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3986): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3986): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3986): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3986): 	... 10 more
W/KeepSync( 3986): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1062783, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  819): Start proc 4345:com.google.android.calendar/u0a37 for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService
,I/PeopleSync( 1774): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1774): Starting sync, feed=null [5005f081]
,E/SQLiteLog( 4345): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,W/BaseAppContext( 1774): Using Auth Proxy for data requests.
,W/BaseAppContext( 1774): Using Auth Proxy for data requests.
,W/BaseAppContext( 1774): Using Auth Proxy for data requests.
,I/PeopleSync( 1774): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/AnalyticsLogBase( 4345): PlayLogger.onLoggerConnected
,I/AnalyticsLogBase( 4345): PlayLogger.onLoggerConnected
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleSync( 1774): Sync finished, successful=false, took 71ms
,I/PeopleSync( 1774): Cannot authenticate [5005f081]
I/PeopleSync( 1774): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 1774): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 1774): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 1774): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 1774): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 1774): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 1774): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 1774): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 1774): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 1774): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 1774): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 1774): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 1774): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 1774): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 1774): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 1774): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/art     (  819): Explicit concurrent mark sweep GC freed 38727(1925KB) AllocSpace objects, 22(635KB) LOS objects, 31% free, 34MB/50MB, paused 1.791ms total 69.701ms
,I/art     ( 1260): Explicit concurrent mark sweep GC freed 46049(2MB) AllocSpace objects, 13(1434KB) LOS objects, 37% free, 26MB/42MB, paused 1.334ms total 38.773ms
,I/PeopleSync( 1774): ***Sync finished***, duration: 512 [5005f081]
,W/ResourcesManager( 4345): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4345): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 1062990, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  819): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 1096393, reason: Periodic
,V/JNIHelp ( 4345): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     ( 1797): Explicit concurrent mark sweep GC freed 17736(998KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.042ms total 26.631ms
,E/DataBuffer( 1797): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2aa8e61e)
,I/ProviderInstaller( 4345): Installed default security provider GmsCore_OpenSSL
,I/GCoreUlr( 1797): Uploading GCM registration ID for account#2#
W/AbstractGoogleClient( 4345): Application name is not set. Call Builder#setApplicationName.
,W/BaseAppContext( 1797): Using Auth Proxy for data requests.
,I/GLSUser ( 1797): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1797): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/GCoreUlr( 1797): 
,E/GCoreUlr( 1797): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1797): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1797): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1797): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1797): 	,at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1797): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1797): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1797): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1797): ,	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1797): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1797): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1797): 	at com.google.android.location.reporting.c.g.a(SourceFile:111),
E/GCoreUlr( 1797): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1797): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1797): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1797): 	,at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 1062999, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  819): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 1095154, reason: Periodic
,I/ActivityManager(  819): Start proc 4380:com.google.android.gm/u0a78 for service com.google.android.gm/.provider.MailSyncAdapterService
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 347us total 25.517ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 349us total 17.524ms
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 340us total 15.223ms
,E/CalendarSyncAdapter( 4345): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 4345): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 4345): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 4345): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 4345): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 4345): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 4345): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 4345): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 4345): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2382)
E/CalendarSyncAdapter( 4345): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1850)
E/CalendarSyncAdapter( 4345): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:1733)
E/CalendarSyncAdapter( 4345): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:503)
E/CalendarSyncAdapter( 4345): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:392)
E/CalendarSyncAdapter( 4345): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 4345): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 4345): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 4345): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 4345): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 4345): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 4345): 	... 12 more
,I/Gmail   ( 4380): getAccountsCursor
D/ActivityThread( 4380): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 1062994, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  819): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 1097043, reason: Periodic
,I/ActivityManager(  819): Start proc 4403:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,W/GAV2    ( 4380): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/[@@    ] SyncAdapterProxy( 1260): Delagator disabled, using the (deprecated) GData sync adapter
,W/ActivityManager(  819): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 4380): Observing account changes for notifications
,W/Gmail   ( 4380): Sync started for account: account:61035162
,I/ContactLocale( 4403): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/Gmail   ( 4380): getAccountsCursor
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 4380): (283) recovered 33 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4380): notifyAccountChanged
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/Gmail   ( 4380): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4380): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4380): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4380): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/GLSActivity( 1260): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1260): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1260): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1260): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1260): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1260): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1260): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 1260): innerSync failed
D/ContactsSyncAdapter( 1260): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1260): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1260): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1260): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1260): 	at com.google.android.syncadapters.contacts.delegation.SyncAdapterProxy.onPerformLoggedSync(SyncAdapterProxy.java:123)
D/ContactsSyncAdapter( 1260): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1260): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1260): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1260): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
D/ContactsSyncAdapter( 1260): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1260): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
D/ContactsSyncAdapter( 1260): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1260): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ActivityManager(  819): Killing 3398:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/Gmail   ( 4380): notifyAccountChanged
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 1063008, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  819): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 1095952, reason: Periodic
,I/Gmail   ( 4380): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4353, normalSync: true
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4380): getAccountsCursor
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1260): Explicit concurrent mark sweep GC freed 20163(1064KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.603ms total 56.597ms
,I/art     (  819): Explicit concurrent mark sweep GC freed 21205(890KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 1.188ms total 73.500ms
,I/Gmail   ( 4380): getAccountsCursor
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 4380): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4380): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 4380): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,E/ReminderSync( 1774): AuthError [T SyncAdapterThread-1:id=249:priority=5:group=main],
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 1063013, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1],
D/SyncManager(  819): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 1097948, reason: Periodic
,I/ProviderInstaller( 4380): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SyncAdapterService( 3869): Ignoring sync request for non-current account
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1260): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1260): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1260): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1260): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1260): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1260): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1260): 	at android.os.Binder.execTransact(Binder.java:446)
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DelayedSyncController( 3925): Delaying sync.
,W/GLSActivity( 1260): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1260): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1260): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1260): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1260): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1260): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1260): 	at android.os.Binder.execTransact(Binder.java:446)
,I/Gmail   ( 4380): notifyAccountChanged
,I/Gmail   ( 4380): getAccountsCursor
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1774): Using Auth Proxy for data requests.
,W/BaseAppContext( 1774): Using Auth Proxy for data requests.
,W/BaseAppContext( 1774): Using Auth Proxy for data requests.
,W/BaseAppContext( 1774): Using Auth Proxy for data requests.
,I/Gmail   ( 4380): notifyAccountChanged
,W/Gmail   ( 4380): Sync complete for account: account:61035162
I/Gmail   ( 4380): getAccountsCursor
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 1063003, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  819): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 1097292, reason: Periodic
,I/ActivityManager(  819): Killing 3072:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/art     ( 1774): Explicit concurrent mark sweep GC freed 7818(593KB) AllocSpace objects, 4(64KB) LOS objects, 35% free, 29MB/45MB, paused 1.469ms total 47.872ms
,I/ActivityManager(  819): Start proc 4455:com.google.android.music:main/u0a66 for service com.google.android.music/.sync.SyncAdapterService
,W/BaseAppContext( 1774): Using Auth Proxy for data requests.
,W/BaseAppContext( 1774): Using Auth Proxy for data requests.
,W/BaseAppContext( 1774): Using Auth Proxy for data requests.
,I/MusicStore( 4455): Database version: 120
,I/ActivityManager(  819): Start proc 4476:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,W/ResourcesManager( 4455): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4455): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4455): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/ProviderInstaller( 4455): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4455): GMSCore installation verified
,I/ConfigStore( 4455): Config Database version: 1
,I/MediaRouter( 4455): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 4455): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 4455): Using platform SSLCertificateSocketFactory
,I/MusicLifecycle( 4455): Sync started
I/NetworkMonitor( 4455): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 4455): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 4455): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/ActivityManager(  819): Start proc 4503:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,I/GoogleURLConnFactory( 4455): Using platform SSLCertificateSocketFactory
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 4476): Sync request not initiated by GCP app. Dropping
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  819): Killing 3849:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  819): Killing 3684:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,W/GLSActivity( 1260): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1260): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1260): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1260): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1260): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1260): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1260): 	at android.os.Binder.execTransact(Binder.java:446)
,I/MusicLifecycle( 4455): Sync ended
W/MusicSyncAdapter( 4455): Sync failed due to an authentication issue.
,E/Auth.Api.Credentials( 1774): [CredentialSyncAdapter] Unknown sync event.
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 1063032, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  819): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 1097325, reason: Periodic
,I/art     (  819): Explicit concurrent mark sweep GC freed 23367(960KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 3.767ms total 96.645ms
,I/MusicLeanback( 4455): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 4455): Stop autocaching.
,I/art     ( 1260): Explicit concurrent mark sweep GC freed 12871(736KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 958us total 22.330ms
,I/ActivityManager(  819): Start proc 4534:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,W/ResourcesManager( 4534): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4534): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 4534): VM with version 2.1.0 has multidex support
I/MultiDex( 4534): install
I/MultiDex( 4534): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4534): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4534): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1260): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1260): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1774): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,D/WearableService( 4534): callingUid 10011, callindPid: 4534
,D/LocationInitializer( 1774): Restart initialization of location
,E/MDM     ( 1797): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 4455): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 4455): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  819): Killing 3635:com.google.android.talk/u0a61 (adj 15): empty #17
,I/GAV2    ( 4345): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 4380): Thread[GAThread,5,main]: No campaign data found.
,I/MusicLeanback( 4455): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 4455): Stop autocaching.
,E/GmsUtils( 4455): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 4455): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,I/ActivityManager(  819): Killing 1516:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  819): Client connection lost with reason: 4
,I/ActivityManager(  819): Killing 3569:com.android.vending/u0a19 (adj 15): empty #17
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0,
,I/BooksSync( 4004): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4004): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4004): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4004): Soft error
E/BooksSync( 4004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4004): Sync error
E/BooksSync( 4004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4004): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1131256, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2178): Request to stop oneshot timer with non empty queue
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/GLSUser ( 1260): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1260): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1260): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1260): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1180335, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,I/UsageStatsService(  819): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2178): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4615): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4615): CheckJNI is OFF
D/AndroidRuntime( 4615): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  819): Killing 3761:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  819): Skipping PackageSetting{2d33e7f1 com.example.hello/10273} due to missing metadata
I/WindowState(  819): WIN DEATH: Window{2b1b433e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  819): Client connection lost with reason: 4
D/BtGatt.GattService( 2178): Binder is dead - unregistering client (5)!
D/BtGatt.GattService( 2178): Binder is dead - unregistering client (6)!
D/BtGatt.AdvertiseManager( 2178): message : 1
E/libprocessgroup(  819): failed to kill 1 processes for processgroup 3761
D/BtGatt.GattService( 2178): stopScan() - queue size =1
D/BtGatt.AdvertiseManager( 2178): stop advertise for client 6
W/ActivityManager(  819): Force removing ActivityRecord{32e4eac7 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
D/BtGatt.AdvertiseManager( 2178): app died - unregistering client : 6
D/BtGatt.GattService( 2178): unregisterClient() - clientIf=6
D/BtGatt.GattService( 2178): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2178): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2178): stop scan
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2178): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.ScanManager( 2178): app died, unregister client - 5
D/BtGatt.GattService( 2178): onAdvertiseInstanceDisabled() - clientIf=255, status=0
E/BtGatt.ContextMap( 2178): Context not found for ID 255
D/BtGatt.GattService( 2178): unregisterClient() - clientIf=5
V/ActivityManager(  819): Display changed displayId=0
W/ActivityManager(  819): Spurious death for ProcessRecord{23702c19 3761:com.test.thalitest/u0a265}, curProc for 3761: null
I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
I/Keyboard.Facilitator( 1233): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1233): run()
I/Decoder ( 1233): createOrResetDecoder
I/InputReader(  819): Reconfiguring input devices.  changes=0x00000010
D/TaskPersister(  819): removeObsoleteFile: deleting file=28_task.xml
D/BuaReceiver( 3458): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/art     ( 1065): Explicit concurrent mark sweep GC freed 73166(2MB) AllocSpace objects, 1(30MB) LOS objects, 18% free, 72MB/88MB, paused 736us total 41.175ms
D/VoicemailCleanupService( 4403): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  819): Start proc 4632:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/art     (  819): Explicit concurrent mark sweep GC freed 33463(1836KB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.244ms total 91.283ms
I/art     (  819): WaitForGcToComplete blocked for 86.650ms for cause Explicit
I/ActivityManager(  819): Start proc 4649:com.google.android.googlequicksearchbox:search/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService
W/InputMethodManagerService(  819): Got RemoteException sending setActive(false) notification to pid 3761 uid 10265
I/Keyboard.Facilitator( 1233): onFinishInput()
I/ConfigService( 1260): onCreate
I/art     ( 1373): Explicit concurrent mark sweep GC freed 5083(371KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 697us total 18.827ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1233): run()
D/JobSchedulerService(  819): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  819): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/Keyboard.Facilitator.MainLanguageModelLoader( 1233): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Loading LM = contacts
I/ActivityManager(  819): Start proc 4671:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/ActivityManager(  819): Killing 4192:com.google.android.deskclock/u0a44 (adj 15): empty #17
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1233): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1233): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1233): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1233): run()
I/StatsUtilsManager( 1233): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1233): shouldRecordStats() = Too Soon
I/art     (  819): Explicit concurrent mark sweep GC freed 6774(390KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 3.410ms total 112.043ms
I/art     ( 4615): System.exit called, status: 0
I/AndroidRuntime( 4615): VM exiting with result code 0.
W/ContextImpl( 4671): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1260): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1260): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  819): Killing 3823:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
D/Launcher.Workspace( 1373): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1373): 11683562 - stripEmptyScreens()
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1774): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1774): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1774): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1774): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1774): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1373): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
E/SQLiteLog( 1774): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/ActivityManager(  819): Start proc 4705:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
I/LocationSettingsChecker( 1774): Removing dialog suppression flag for package com.test.thalitest
--------- beginning of crash
E/AndroidRuntime( 1774): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1774): Process: com.google.android.gms, PID: 1774
E/AndroidRuntime( 1774): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1774): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1774): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1774): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1774): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1774): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1774): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1774): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1774): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1774): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1774): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1774): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1774): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1774): disk I/O error (code 3850)
E/DriveAsyncService( 1774): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1774): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1774): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1774): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1774): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1774): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1774): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1774): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1774): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1774): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1774): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1774): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1774): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager(  819): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  819): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/DropBoxManagerService(  819): Can't write: system_app_crash
E/DropBoxManagerService(  819): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  819): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  819): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  819): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  819): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  819): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  819): 	... 5 more
E/SQLiteDatabase( 1774): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1774): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1774): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1774): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1774): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1774): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1774): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1774): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1774): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1774): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1774): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1774): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1774): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1774): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1774): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1774): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1774): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1774): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1774): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1774): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1774): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1774): Sending signal. PID: 1774 SIG: 9
D/OpenGLRenderer(  819): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  819): Validating map...
I/OpenGLRenderer(  819): Initialized EGL, version 1.4
D/OpenGLRenderer(  819): Enabling debug mode 0
D/AndroidRuntime( 4649): Shutting down VM
D/WifiService(  819): Client connection lost with reason: 4
I/ActivityManager(  819): Start proc 4746:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
I/ActivityManager(  819): Process com.google.android.gms (pid 1774) has died
W/ActivityManager(  819): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  819): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  819): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  819): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  819): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
W/ActivityManager(  819): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 21000ms
E/SharedPreferencesImpl( 4649): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 4649): FATAL EXCEPTION: main
E/AndroidRuntime( 4649): Process: com.google.android.googlequicksearchbox:search, PID: 4649
E/AndroidRuntime( 4649): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 4649): 	at com.google.android.search.core.bh$2.onFailure(SearchController.java:381)
E/AndroidRuntime( 4649): 	at com.google.android.apps.gsa.shared.util.c.a.r$1.run(TaskRunnerImpl.java:329)
E/AndroidRuntime( 4649): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 4649): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4649): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4649): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4649): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4649): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4649): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4649): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4649): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 4649): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime( 4649): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime( 4649): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime( 4649): 	at com.google.android.apps.gsa.shared.util.c.d$1.call(LazyListenableFuture.java:46)
E/AndroidRuntime( 4649): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4649): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4649): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4649): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4649): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 4649): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 4649): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime( 4649): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime( 4649): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 4649): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 4649): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 4649): 	... 5 more
E/AndroidRuntime( 4649): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 4649): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime( 4649): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime( 4649): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime( 4649): 	... 9 more
E/AndroidRuntime( 4649): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 4649): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime( 4649): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime( 4649): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime( 4649): 	... 11 more
E/DropBoxManagerService(  819): Can't write: system_app_crash
E/DropBoxManagerService(  819): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  819): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  819): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  819): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  819): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  819): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  819): 	... 5 more
I/ActivityManager(  819): Start proc 4765:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 212us total 13.933ms
I/art     (  368): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 9.449ms
W/InputMethodManagerService(  819): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@321082c3 attribute=null, token = android.os.BinderProxy@30d0b85c
W/Launcher( 1373): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@10b2fdf4 new=com.google.android.velvet.VelvetApplication@10b2fdf4
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 218us total 9.113ms
E/SQLiteLog( 1373): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
W/ResourcesManager( 4765): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4765): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/OpenGLRenderer(  819): Initialized EGL, version 1.4

```
