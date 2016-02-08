#### Test 586024278176cca_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/MusicLeanback( 3465): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3465): Stop autocaching.
E/GmsUtils( 3465): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3465): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/HeadsetStateMachine( 2396): Disconnected process message: 10, size: 0
I/GAV2    ( 3515): Thread[GAThread,5,main]: No campaign data found.
,--------- beginning of system
I/ActivityManager(  821): Killing 3197:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
D/AndroidRuntime( 3600): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3600): CheckJNI is OFF
I/ActivityManager(  821): Killing 3234:com.google.android.apps.photos/u0a71 (adj 15): empty #17
D/AndroidRuntime( 3600): Calling main entry com.android.commands.am.Am
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{3350c7a8 token=Token{1b05a3cb ActivityRecord{2abf9e9a u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  821): Adding window Window{8b969fd u0 Starting com.test.thalitest} at 2 of 7 (after Window{16e82e81 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3600): Shutting down VM
I/MicrophoneInputStream( 1505): mic_close com.google.android.apps.gsa.speech.audio.u@7bd622e
I/HotwordDetector( 1505): Closing mic
I/ActivityManager(  821): Start proc 3614:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1505): Stopping hotword detection.
I/HotwordRecognitionRnr( 1505): Hotword detection finished
I/art     (  821): Explicit concurrent mark sweep GC freed 21325(1109KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.508ms total 73.269ms
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1721517331
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3614): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  821): Killing 3032:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/LibraryLoader( 3614): Time to load native libraries: 3 ms (timestamps 8008-8011)
I/LibraryLoader( 3614): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3614): Binding Chromium to main looper Looper (main, tid 1) {31e83981}
,I/LibraryLoader( 3614): Expected native library version number "",actual native library version number ""
I/chromium( 3614): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3614): Initializing chromium process, singleProcess=true
,W/art     ( 3614): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3614): ApplicationContext is null in ApplicationStatus
,W/chromium( 3614): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3614): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3614): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3614): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c0dbb5:true
,W/art     ( 3614): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3614): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 3614): CordovaWebView is running on device made by: motorola
,W/art     ( 3614): Attempt to remove local handle scope entry from IRT, ignoring,
,W/art     ( 3614): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3614): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3614): Validating map...,
V/WindowManager(  821): Adding window Window{e300f87 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{8b969fd u0 Starting com.test.thalitest})
W/chromium( 3614): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3614): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3614): Enabling debug mode 0
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +850ms
,I/Keyboard.Facilitator( 1234): onFinishInput()
,W/BindingManager( 3614): Cannot call determinedVisibility() - never saw a connection for the pid: 3614
,D/JsMessageQueue( 3614): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3614): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576324224
,I/chromium( 3614): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3614): Initializing JXcore engine
,W/jxcore-log( 3614): JXcore engine is ready
,W/Thread-391( 3668): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9853]" dev="sockfs" ino=9853 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-391( 3668): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-391( 3668): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10019]" dev="sockfs" ino=10019 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-391( 3668): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21313]" dev="sockfs" ino=21313 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3614): Starting JXcore engine,
,W/jxcore-log( 3614): Platform android,
W/jxcore-log( 3614): 
W/jxcore-log( 3614): Process ARCH arm
W/jxcore-log( 3614): 
,I/jxcore-log( 3614): JXcore Cordova bridge is ready!
I/jxcore-log( 3614): 
,W/jxcore-log( 3614): JXcore engine is started
,I/jxcore-log( 3614): Toggling radios to true
I/jxcore-log( 3614): 
,D/BluetoothAdapter( 3614): enable(): BT is already enabled..!
,D/WifiService(  821): setWifiEnabled: true pid=3614, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  821): New client listening to asynchronous messages
,I/jxcore-log( 3614): Radios toggled
I/jxcore-log( 3614): 
,I/jxcore-log( 3614): My device name is: motorola-Nexus 6
I/jxcore-log( 3614): 
,I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1273): Read error: ssl=0xb4888000: I/O error during system call, Connection timed out
,V/NativeCrypto( 1273): SSL shutdown failed: ssl=0xb4888000: I/O error during system call, Broken pipe
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  821): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3,
E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  821): MasterInitialState.processMessage what=3
E/ConnectivityService(  821): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  821): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1505): Network connectivity changed, type is: 6
,V/MusicLeanback( 3465): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1351): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1351): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/WifiConfigStore(  821): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): will read network variables netId=0
,I/ActivityManager(  821): Start proc 3675:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
E/WifiConfigStore(  821): will read network variables netId=0
E/GpsLocationProvider(  821): No APN found to select.
,D/PhoneInterfaceManager( 1351): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1351): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
E/GpsLocationProvider(  821): No APN found to select.
,I/art     ( 1273): Explicit concurrent mark sweep GC freed 22102(1055KB) AllocSpace objects, 7(771KB) LOS objects, 37% free, 26MB/42MB, paused 725us total 22.224ms
,I/ActivityManager(  821): Start proc 3702:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  821): Killing 3319:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/SprintDMReceiver( 3702): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3702): simOperator:  IMSI: null
,D/SprintDMReceiver( 3702): Not Sprint UICC, don't do anything.
,I/ActivityManager(  821): Killing 3339:com.android.musicfx/u0a18 (adj 15): empty #17
,I/CheckinService( 1771): Done disabling old GoogleServicesFramework version
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) },
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,I/iu.Environment( 1771): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599944 ms
,I/iu.UploadsManager( 1771): num queued entries: 0
I/iu.UploadsManager( 1771): num updated entries: 0
I/iu.SyncManager( 1771): NEXT; no task
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1771): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1771): onDestroy
,I/ActivityManager(  821): Start proc 3722:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 2947): connection state changed from UNKNOWN to DISCONNECTED
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 494us total 15.698ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 215us total 9.284ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 8.875ms
,I/GAv4    ( 3722): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3722):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3722):   adb logcat -s GAv4
,W/GAv4    ( 3722): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3722): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3722): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3722): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3722): Time to load native libraries: 2 ms (timestamps 2239-2241)
I/LibraryLoader( 3722): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3722): Binding Chromium to main looper Looper (main, tid 1) {2548123c}
,I/LibraryLoader( 3722): Expected native library version number "",actual native library version number ""
,I/chromium( 3722): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3722): Initializing chromium process, singleProcess=true
,W/art     ( 3722): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3722): ApplicationContext is null in ApplicationStatus
,W/chromium( 3722): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3722): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3722): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3722): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3722): Requires BLUETOOTH permission
,I/NSApplication( 3722): Starting up...
,I/ActivityManager(  821): Start proc 3778:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  821): Killing 3382:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/wpa_supplicant( 1162): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  821): Start proc 3798:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  821): Killing 3111:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/wpa_supplicant( 1162): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1162): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 2
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 167
E/WifiStateMachine(  821):  RSSI mgmt: -55
E/WifiStateMachine(  821):  BE :  rx=153 tx=145 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=7 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 7804 tx_time=147 rx_time=316 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,I/ActivityManager(  821): Killing 3282:com.android.settings/1000 (adj 15): empty #17
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,V/MusicLeanback( 3465): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/ActivityManager(  821): Waited long enough for: ServiceRecord{2d2641ce u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,D/SprintDMReceiver( 3702): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3702): simOperator:  IMSI: null
D/SprintDMReceiver( 3702): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/dhcpcd  ( 3823): version 5.5.6 starting
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1771): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599969 ms
,D/SystemUpdateService( 1771): onDestroy
,I/dhcpcd  ( 3823): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3823): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3823): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3614): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3614): 
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
,D/ConnectivityService(  821): Adding iface wlan0 to network 101
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  821): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1351): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1,
E/PhoneInterfaceManager( 1351): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,I/NetworkMonitor( 3465): type=WIFI subType= reason=null isConnected=true
D/Tethering(  821): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1505): Network connectivity changed, type is: 2
,V/MusicLeanback( 3465): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 3702): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3702): simOperator:  IMSI: null
D/SprintDMReceiver( 3702): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1771): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1771): onCreate
,D/SystemUpdateService( 1771): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1771): active receiver: enabled
,I/SystemUpdateService( 1771): showing system update notification
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1771): retry (wakeup: false) in 3599983 ms
,I/iu.Environment( 1771): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/SystemUpdateService( 1771): onDestroy
,I/iu.UploadsManager( 1771): num queued entries: 0
I/iu.UploadsManager( 1771): num updated entries: 0
I/iu.SyncManager( 1771): NEXT; no task
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1771): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 12:36:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454934993602], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454934993582]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Validated
,D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,V/Herrevad( 1771): NQAS connected
,I/Babel   ( 2947): connection state changed from DISCONNECTED to CONNECTED
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 45818(2MB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.403ms total 85.586ms
,D/Finsky  ( 3075): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3075): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3075): [1] 5.onFinished: Scheduling replication attempt 1.
,I/jxcore-log( 3614): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3614): 
,D/GCM     ( 1273): Connected
,D/GCM     ( 1273): Message class com.google.f.a.a.p
,I/jxcore-log( 3614): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3614): 
,I/jxcore-log( 3614): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3614): 
,I/jxcore-log( 3614): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3614): 
,I/jxcore-log( 3614): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3614): 
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  821): Killing 2733:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3163:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/jxcore-log( 3614): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3614): 
,I/jxcore-log( 3614): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 3614): 
,I/jxcore-log( 3614): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3614): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.23 rxSuccessRate=11.03 targetRoamBSSID=any RSSI=-55
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3614): Test app app.js loaded,
I/jxcore-log( 3614): 
,I/chromium( 3614): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3614): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3614): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3614): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3614): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3614): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3614): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3614): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3614): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3614): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3614): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1abb5437 added. We now have 1 listener(s)
,I/jxcore-log( 3614): BLE advertisement is supported
I/jxcore-log( 3614): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.62 rxSuccessRate=9.02 targetRoamBSSID=any RSSI=-55
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,D/Finsky  ( 3075): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3075): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3075): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3075): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3075): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3075): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3075): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1839): client connected with version: 7571000
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.41 rxSuccessRate=4.00 targetRoamBSSID=any RSSI=-55
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3075): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3075): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3075): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  821): Start proc 3891:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/art     ( 1273): Explicit concurrent mark sweep GC freed 24167(1341KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 25MB/41MB, paused 1.490ms total 43.913ms
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3427): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3427): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3427): 	at jdm.a(PG:82)
E/HttpOperation( 3427): 	at jcs.o(PG:406)
E/HttpOperation( 3427): 	at jcn.a(PG:1379)
E/HttpOperation( 3427): 	at jcs.i(PG:143)
E/HttpOperation( 3427): 	at blb.a(PG:3937)
E/HttpOperation( 3427): 	at czp.a(PG:18188)
E/HttpOperation( 3427): 	at czp.a(PG:9081)
E/HttpOperation( 3427): 	at czq.run(PG:1686)
E/HttpOperation( 3427): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3427): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3427): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3427): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3427): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3427): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3427): 	at jdj.a(PG:4091)
E/HttpOperation( 3427): 	at jdj.a(PG:1125)
E/HttpOperation( 3427): 	at jdm.a(PG:77)
E/HttpOperation( 3427): 	... 12 more
E/HttpOperation( 3427): Caused by: faj: BadAuthentication
E/HttpOperation( 3427): 	at fal.a(PG:38)
E/HttpOperation( 3427): 	at jdj.a(PG:4089)
E/HttpOperation( 3427): 	... 14 more
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3427): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3427): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3427): 	at jdm.a(PG:82)
E/HttpOperation( 3427): 	at jcs.o(PG:406)
E/HttpOperation( 3427): 	at jcn.a(PG:1379)
E/HttpOperation( 3427): 	at jcs.i(PG:143)
E/HttpOperation( 3427): 	at hec.a(PG:42)
E/HttpOperation( 3427): 	at hee.a(PG:102)
E/HttpOperation( 3427): 	at czr.a(PG:65)
E/HttpOperation( 3427): 	at kka.a(PG:108)
E/HttpOperation( 3427): 	at czp.a(PG:19176)
E/HttpOperation( 3427): 	at czp.a(PG:9081)
E/HttpOperation( 3427): 	at czq.run(PG:1686)
E/HttpOperation( 3427): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3427): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3427): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3427): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3427): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3427): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3427): 	at jdj.a(PG:4091)
E/HttpOperation( 3427): 	at jdj.a(PG:1125)
E/HttpOperation( 3427): 	at jdm.a(PG:77)
E/HttpOperation( 3427): 	... 15 more
E/HttpOperation( 3427): Caused by: faj: BadAuthentication
E/HttpOperation( 3427): 	at fal.a(PG:38)
E/HttpOperation( 3427): 	at jdj.a(PG:4089)
E/HttpOperation( 3427): 	... 17 more
,E/ExperimentLoader( 3427): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3427): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3427): 	at jdm.a(PG:82)
E/ExperimentLoader( 3427): 	at jcs.o(PG:406)
E/ExperimentLoader( 3427): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3427): 	at jcs.i(PG:143)
E/ExperimentLoader( 3427): 	at hec.a(PG:42),
E/ExperimentLoader( 3427): 	at hee.a(PG:102)
E/ExperimentLoader( 3427): 	at czr.a(PG:65)
E/ExperimentLoader( 3427): 	at kka.a(PG:108)
E/ExperimentLoader( 3427): 	at czp.a(PG:19176)
E/ExperimentLoader( 3427): 	at czp.a(PG:9081)
E/ExperimentLoader( 3427): 	at czq.run(PG:1686)
E/ExperimentLoader( 3427): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/ExperimentLoader( 3427): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3427): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3427): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3427): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3427): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3427): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3427): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3427): 	at jdm.a(PG:77)
E/ExperimentLoader( 3427): 	... 15 more
E/ExperimentLoader( 3427): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3427): 	at fal.a(PG:38)
E/ExperimentLoader( 3427): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3427): 	... 17 more
,V/KeepSync( 3891): Connecting to GoogleApiClient
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 80660, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  821): Start proc 3923:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3891): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3891): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3891): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3891): (284) automatic index on blob_node(is_deleted)
,I/art     (  821): Explicit concurrent mark sweep GC freed 34447(1577KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.597ms total 98.622ms
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,W/GAV2    ( 3923): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksApp( 3923): Created application version: 3.6.8 (30608)
,E/KeepSync( 3891): IOException
E/KeepSync( 3891): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3891): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3891): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3891): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3891): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3891): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3891): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3891): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3891): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3891): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3891): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3891): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3891): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3891): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3891): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3891): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3891): 	... 10 more
,W/KeepSync( 3891): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 78975, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3923): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3923): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3923): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3923): Soft error
E/BooksSync( 3923): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3923): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3923): Sync error
E/BooksSync( 3923): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3923): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3923): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 82318, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Killing 2305:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/ActivityManager(  821): Killing 1454:android.process.acore/u0a5 (adj 15): empty #18
,I/GAV2    ( 3923): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.35 rxSuccessRate=1.46 targetRoamBSSID=any RSSI=-55
,E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3075): [289] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3075): [289] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/HeadsetStateMachine( 2396): Disconnected process message: 10, size: 0
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3075): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3075): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3075): [1] 5.onFinished: Scheduling replication attempt 3.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1234): run()
I/Keyboard.Facilitator( 1234): flushDynamicLanguageModels()
,I/ConfigService( 1273): onCreate
,I/ConfigService( 1273): onDestroy
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.83 rxSuccessRate=2.38 targetRoamBSSID=any RSSI=-55
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1273): Explicit concurrent mark sweep GC freed 24846(1435KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.366ms total 46.255ms
,D/Finsky  ( 3075): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3075): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3075): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.83 rxSuccessRate=2.26 targetRoamBSSID=any RSSI=-55
E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (211 us)
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000
,D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  821): Display changed displayId=0
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  821): Excessive delay in setPowerMode(): 284ms
,I/DreamManagerService(  821): Entering dreamland.
,I/PowerManagerService(  821): Dozing...
I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 12
,E/native  (  821): do suspend false
,I/Keyboard.Facilitator( 1234): onFinishInput()
,E/WifiStateMachine(  821): cancelDelayedScan -> 14
,E/native  (  821): do suspend true
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-55
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  871): STATUS: Received file 'm9kefs2'
I/kickstart(  871): STATUS: 950272 bytes transferred in 0.994599 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksSync( 3923): Starting books sync for 61035162, extras: ade
,D/Finsky  ( 3075): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3075): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3075): [1] 5.onFinished: Scheduling replication attempt 5.
,I/BooksConfig( 3923): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 47274(2MB) AllocSpace objects, 15(240KB) LOS objects, 31% free, 34MB/50MB, paused 3.416ms total 109.582ms
,E/HttpOperation( 3427): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3427): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3427): 	at jdm.a(PG:82)
E/HttpOperation( 3427): 	at jcs.o(PG:406)
E/HttpOperation( 3427): 	at jcn.a(PG:1379)
E/HttpOperation( 3427): 	at jcs.i(PG:143)
E/HttpOperation( 3427): 	at blb.a(PG:3937)
E/HttpOperation( 3427): 	at czp.a(PG:18188)
E/HttpOperation( 3427): 	at czp.a(PG:9081)
E/HttpOperation( 3427): 	at czq.run(PG:1686)
E/HttpOperation( 3427): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3427): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3427): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3427): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3427): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3427): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3427): 	at jdj.a(PG:4091)
E/HttpOperation( 3427): 	at jdj.a(PG:1125)
E/HttpOperation( 3427): 	at jdm.a(PG:77)
E/HttpOperation( 3427): 	... 12 more
E/HttpOperation( 3427): Caused by: faj: BadAuthentication
E/HttpOperation( 3427): 	at fal.a(PG:38)
E/HttpOperation( 3427): 	at jdj.a(PG:4089)
E/HttpOperation( 3427): 	... 14 more
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3923): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3923): Soft error
E/BooksSync( 3923): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3923): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source),
E/BooksSync( 3923): Sync error
E/BooksSync( 3923): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3923): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3923): Finished books sync
E/HttpOperation( 3427): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3427): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 3427): 	at jdm.a(PG:82)
E/HttpOperation( 3427): 	at jcs.o(PG:406)
E/HttpOperation( 3427): ,	at jcn.a(PG:1379)
E/HttpOperation( 3427): 	at jcs.i(PG:143)
E/HttpOperation( 3427): 	,at hec.a(PG:42)
E/HttpOperation( 3427): 	at hee.a(PG:102)
,E/HttpOperation( 3427): 	at czr.a(PG:65)
E/HttpOperation( 3427): 	at kka.a(PG:108)
E/HttpOperation( 3427): 	,at czp.a(PG:19176)
E/HttpOperation( 3427): 	at czp.a(PG:9081)
E/HttpOperation( 3427): 	at czq.run(PG:1686),
E/HttpOperation( 3427): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3427): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3427): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3427): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3427): 	,at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3427): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3427): 	at jdj.a(PG:4091)
E/HttpOperation( 3427): 	,at jdj.a(PG:1125)
E/HttpOperation( 3427): 	at jdm.a(PG:77)
E/HttpOperation( 3427): 	... 15 more
,E/HttpOperation( 3427): Caused by: faj: BadAuthentication
E/HttpOperation( 3427): 	at fal.a(PG:38)
E/HttpOperation( 3427): 	at jdj.a(PG:4089)
E/HttpOperation( 3427): 	,... 17 more
E/ExperimentLoader( 3427): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3427): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3427): 	,at jdm.a(PG:82)
E/ExperimentLoader( 3427): 	at jcs.o(PG:406)
E/ExperimentLoader( 3427): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3427): 	,at jcs.i(PG:143)
E/ExperimentLoader( 3427): 	at hec.a(PG:42)
E/ExperimentLoader( 3427): 	at hee.a(PG:102)
,E/ExperimentLoader( 3427): 	at czr.a(PG:65)
E/ExperimentLoader( 3427): 	at kka.a(PG:108)
E/ExperimentLoader( 3427): 	at czp.a(PG:19176),
E/ExperimentLoader( 3427): 	at czp.a(PG:9081)
E/ExperimentLoader( 3427): 	at czq.run(PG:1686)
E/ExperimentLoader( 3427): ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3427): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3427): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3427): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3427): 	at java.lang.Thread.run(Thread.java:818)
,E/ExperimentLoader( 3427): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3427): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3427): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3427): 	at jdm.a(PG:77)
E/ExperimentLoader( 3427): 	... 15 more
E/ExperimentLoader( 3427): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3427): 	at fal.a(PG:38)
E/ExperimentLoader( 3427): ,	at jdj.a(PG:4089)
E/ExperimentLoader( 3427): 	... 17 more
D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 140228, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3891): Connecting to GoogleApiClient
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 139471, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
V/KeepSync( 3891): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3891): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3891): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3891): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3891): IOException
E/KeepSync( 3891): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3891): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3891): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3891): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3891): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3891): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3891): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3891): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3891): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3891): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3891): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3891): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3891): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3891): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3891): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3891): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3891): 	... 10 more
W/KeepSync( 3891): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 140867, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-55
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2396): Disconnected process message: 10, size: 0
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3675): [385] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1273): Vacuum at: now=1454935105972 tag=VacuumService
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1273): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3675): [385] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3675): [385] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3675): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3675): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3675): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3675): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3675): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3675): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3675): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3675): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3675): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3675): 	at com.a.a.k.run(SourceFile:110)
,D/Finsky  ( 3075): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3075): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3075): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1273): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1273): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1273): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1273): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1273): No account for auth token provided
,W/Uploader( 1273): No account for auth token provided
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1273): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1273): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1273): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1273): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1273): No account for auth token provided
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1273): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1273): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1273): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1273): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1273): No account for auth token provided
,W/Uploader( 1273): No account for auth token provided
,W/Uploader( 1273): No account for auth token provided
,W/Uploader( 1273): No account for auth token provided
,W/Uploader( 1273): No account for auth token provided,
,W/Uploader( 1273): No account for auth token provided
,W/Uploader( 1273): No account for auth token provided
,W/Uploader( 1273):  no longer exists, so no auth token.
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1273): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1273): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1273): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1273): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1273): No account for auth token provided
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1273): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1273): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1273): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1273): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1273): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1273): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GoogleAuthProtoRequest( 3675): [386] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3675): [386] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3675): [386] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3675): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
,W/ExperimentUpdateService( 3675): 	at com.a.a.a.k.a(SourceFile:117),
W/ExperimentUpdateService( 3675): 	,at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3675): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3675): 	,at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3675): Caused by: com.a.a.a: User needs to (re)enter credentials.
,W/ExperimentUpdateService( 3675): 	at com.google.android.flib.a.a.a(SourceFile:167)
,W/ExperimentUpdateService( 3675): 	at com.a.a.a.g.a(SourceFile:79)
,W/ExperimentUpdateService( 3675): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3675): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1234): run()
I/Keyboard.Facilitator( 1234): flushDynamicLanguageModels()
,I/ConfigService( 1273): onCreate
,I/art     ( 1273): Explicit concurrent mark sweep GC freed 69290(3MB) AllocSpace objects, 8(745KB) LOS objects, 36% free, 27MB/43MB, paused 1.320ms total 44.659ms
,I/BooksSync( 3923): Starting books sync for 61035162, extras: ade
,I/art     (  821): Explicit concurrent mark sweep GC freed 36686(1610KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.649ms total 77.330ms
,I/ConfigService( 1273): onDestroy
,I/BooksConfig( 3923): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3923): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3923): Soft error
E/BooksSync( 3923): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3923): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3923): Sync error
E/BooksSync( 3923): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3923): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3923): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 230571, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3891): Connecting to GoogleApiClient
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3427): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3427): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3427): 	at jdm.a(PG:82)
E/HttpOperation( 3427): 	at jcs.o(PG:406)
E/HttpOperation( 3427): 	at jcn.a(PG:1379)
E/HttpOperation( 3427): 	at jcs.i(PG:143)
E/HttpOperation( 3427): 	at blb.a(PG:3937)
E/HttpOperation( 3427): 	at czp.a(PG:18188)
E/HttpOperation( 3427): 	at czp.a(PG:9081)
E/HttpOperation( 3427): 	at czq.run(PG:1686)
E/HttpOperation( 3427): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3427): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3427): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3427): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3427): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3427): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3427): 	at jdj.a(PG:4091)
E/HttpOperation( 3427): 	at jdj.a(PG:1125)
E/HttpOperation( 3427): 	at jdm.a(PG:77)
E/HttpOperation( 3427): 	... 12 more
E/HttpOperation( 3427): Caused by: faj: BadAuthentication
E/HttpOperation( 3427): 	at fal.a(PG:38)
E/HttpOperation( 3427): 	at jdj.a(PG:4089)
E/HttpOperation( 3427): 	... 14 more
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3891): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3891): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3891): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3891): (284) automatic index on blob_node(is_deleted)
I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3427): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3427): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3427): 	at jdm.a(PG:82)
E/HttpOperation( 3427): 	at jcs.o(PG:406)
E/HttpOperation( 3427): 	at jcn.a(PG:1379)
E/HttpOperation( 3427): 	at jcs.i(PG:143)
E/HttpOperation( 3427): 	at hec.a(PG:42)
E/HttpOperation( 3427): 	at hee.a(PG:102)
E/HttpOperation( 3427): 	at czr.a(PG:65)
E/HttpOperation( 3427): 	at kka.a(PG:108)
E/HttpOperation( 3427): 	at czp.a(PG:19176)
E/HttpOperation( 3427): 	at czp.a(PG:9081)
E/HttpOperation( 3427): 	at czq.run(PG:1686)
E/HttpOperation( 3427): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3427): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3427): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3427): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3427): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3427): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3427): 	at jdj.a(PG:4091)
E/HttpOperation( 3427): 	at jdj.a(PG:1125)
E/HttpOperation( 3427): 	at jdm.a(PG:77)
E/HttpOperation( 3427): 	... 15 more
E/HttpOperation( 3427): Caused by: faj: BadAuthentication
E/HttpOperation( 3427): 	at fal.a(PG:38)
E/HttpOperation( 3427): 	at jdj.a(PG:4089)
E/HttpOperation( 3427): 	... 17 more
E/ExperimentLoader( 3427): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3427): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3427): 	at jdm.a(PG:82)
E/ExperimentLoader( 3427): 	at jcs.o(PG:406)
E/ExperimentLoader( 3427): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3427): 	at jcs.i(PG:143)
E/ExperimentLoader( 3427): 	at hec.a(PG:42)
E/ExperimentLoader( 3427): 	at hee.a(PG:102)
E/ExperimentLoader( 3427): 	at czr.a(PG:65)
E/ExperimentLoader( 3427): 	at kka.a(PG:108)
E/ExperimentLoader( 3427): 	at czp.a(PG:19176)
E/ExperimentLoader( 3427): 	at czp.a(PG:9081)
E/ExperimentLoader( 3427): 	at czq.run(PG:1686)
E/ExperimentLoader( 3427): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3427): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3427): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3427): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3427): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3427): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3427): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3427): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3427): 	at jdm.a(PG:77)
E/ExperimentLoader( 3427): 	... 15 more
E/ExperimentLoader( 3427): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3427): 	at fal.a(PG:38)
E/ExperimentLoader( 3427): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3427): 	... 17 more
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3891): IOException
E/KeepSync( 3891): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3891): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3891): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3891): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3891): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3891): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3891): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3891): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3891): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3891): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3891): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3891): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3891): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3891): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3891): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3891): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3891): 	... 10 more
W/KeepSync( 3891): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 233048, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 230963, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3614): --= Surplus to requirements =--
I/jxcore-log( 3614): 
I/jxcore-log( 3614): ****TEST TOOK:  ms ****
I/jxcore-log( 3614): 
I/jxcore-log( 3614): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3614): 
,D/AndroidRuntime( 4032): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4032): CheckJNI is OFF
,D/AndroidRuntime( 4032): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg,
I/ActivityManager(  821): Killing 3614:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest,
,W/PackageSettings(  821): Skipping PackageSetting{f66dcd com.example.hello/10273} due to missing metadata
,E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3614
,W/ActivityManager(  821): Force removing ActivityRecord{2abf9e9a u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
,D/WifiService(  821): Client connection lost with reason: 4
,V/ActivityManager(  821): Display changed displayId=0
,I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,I/Keyboard.Facilitator( 1234): resetDictionaries() : en_US
,I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,D/BuaReceiver( 3302): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,D/TaskPersister(  821): removeObsoleteFile: deleting file=28_task.xml
,I/art     ( 1067): Explicit concurrent mark sweep GC freed 55403(2MB) AllocSpace objects, 1(30MB) LOS objects, 18% free, 71MB/87MB, paused 606us total 47.282ms
,I/ActivityManager(  821): Start proc 4047:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,I/Keyboard.Facilitator.DecoderInitializer( 1234): run()
I/Decoder ( 1234): createOrResetDecoder
,I/art     (  821): Explicit concurrent mark sweep GC freed 22794(1317KB) AllocSpace objects, 13(867KB) LOS objects, 31% free, 34MB/50MB, paused 2.133ms total 72.126ms
I/art     (  821): WaitForGcToComplete blocked for 16.437ms for cause Explicit
,I/art     ( 1505): Explicit concurrent mark sweep GC freed 3239(249KB) AllocSpace objects, 1(24KB) LOS objects, 22% free, 27MB/35MB, paused 5.259ms total 76.367ms
,I/ConfigService( 1273): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1234): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1234): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1234): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1234): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1234): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1234): run()
I/StatsUtilsManager( 1234): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1234): shouldRecordStats() = Too Soon
,D/VoicemailCleanupService( 4047): Cleaning up data for package: com.test.thalitest
,W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3614 uid 10265
I/Keyboard.Facilitator( 1234): onFinishInput()
,I/ActivityManager(  821): Start proc 4071:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/LocationOracleImpl( 1505): Best location was null
,I/ContactLocale( 4047): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     ( 1376): Explicit concurrent mark sweep GC freed 5087(371KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 695us total 25.243ms
,I/HotwordRecognitionRnr( 1505): Starting hotword detection.
,I/MicrophoneInputStream( 1505): mic_starting com.google.android.apps.gsa.speech.audio.u@302fe33e
,I/AudioFlinger(  357): AudioFlinger's thread 0xb407a000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1505): mic_started com.google.android.apps.gsa.speech.audio.u@302fe33e
,I/art     (  821): Explicit concurrent mark sweep GC freed 5660(274KB) AllocSpace objects, 1(110KB) LOS objects, 31% free, 34MB/50MB, paused 2.872ms total 157.105ms
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,I/ActivityManager(  821): Start proc 4104:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,D/Launcher.Workspace( 1376): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1376): 11683562 - stripEmptyScreens()
,I/HotwordWorker( 1505): onReady
D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@38c0fe48}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-55
,W/ContextImpl( 4104): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,I/art     ( 4032): System.exit called, status: 0
I/AndroidRuntime( 4032): VM exiting with result code 0.
,E/NetworkScheduler.SchedulerReceiver( 1273): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1273): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,V/GoogleAuthProtoRequest( 3675): [388] a.<init>: mAccountName set to: thalitester@gmail.com
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1771): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1771): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1771): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1771): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1771): Module APK com.google.android.play.games already loaded
,W/Launcher( 1376): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@5905580 new=com.google.android.velvet.VelvetApplication@5905580
I/LocationSettingsChecker( 1771): Removing dialog suppression flag for package com.test.thalitest
,I/UpdateIcingCorporaServi( 1505): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1721517331
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,D/GOOGLEHELP_CompatibleDatabase( 1771): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1771): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1771): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1771): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1771): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1771): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1771): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1771): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1771): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1771): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1,
D/GOOGLEHELP_CompatibleDatabase( 1771): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1771): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1771): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  821): Start proc 4135:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/ConfigFetchService( 1771): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,W/BaseAppContext( 1771): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 1771): CP2 sync disabled
,I/ConfigFetchService( 1771): service connected
,I/Icing   ( 1771): doRemovePackageData com.test.thalitest
,I/UpdateIcingCorporaServi( 1505): UpdateCorporaTask done [took 82 ms] updated apps [took 82 ms] 
,W/BaseAppContext( 1771): Using Auth Proxy for data requests.
,I/GLSUser ( 1273): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1273): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1273): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1273): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1273): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3675): [388] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3675): [388] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3675): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3675): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3675): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3675): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3675): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3675): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3675): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3675): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3675): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3675): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  821): Killing 3515:com.google.android.gm/u0a78 (adj 15): empty #17
,I/GAv4    ( 4135): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4135):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4135):   adb logcat -s GAv4
,W/GAv4    ( 4135): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4135): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4135): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 4135): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4135): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4135): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4135): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4135): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4135): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4135): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4135): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4135): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4135): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4135): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4135): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4135): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4135): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4135): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4135): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4135): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4135): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4135): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4135): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4135): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4135): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4135): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4135): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4135): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4135): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4135): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4135): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4135): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4135): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4135): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4135): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4135): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4135): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4135): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4135): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4135): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4135): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4135): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4135): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4135): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4135): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4135): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4135): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4135): 	at aen.run(PG:536)
,W/GAv4    ( 4135): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4135): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4135): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SQLiteDatabase( 4135): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4135): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4135): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4135): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4135): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4135): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4135): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4135): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4135): 	at aej.c(PG:139)
E/SQLiteDatabase( 4135): 	at aej.b(PG:398)
E/SQLiteDatabase( 4135): 	at agf.f(PG:417)
E/SQLiteDatabase( 4135): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4135): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4135): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4135): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4135): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4135): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 4135): Failed to delete from CachedSearch133,
E/AbstractDatabaseInstance( 4135): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4135): 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
,E/AbstractDatabaseInstance( 4135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4135): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463),
E/AbstractDatabaseInstance( 4135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/AbstractDatabaseInstance( 4135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
E/AbstractDatabaseInstance( 4135): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4135): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4135): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
,E/AbstractDatabaseInstance( 4135): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4135): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4135): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4135): ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4135): 	at aev.getWritableDatabase(PG:238)
,E/AbstractDatabaseInstance( 4135): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4135): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4135): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4135): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4135): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4135): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4135): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4135): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4135): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4135): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/AbstractDatabaseInstance( 4135): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4135): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4135): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4135): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4135): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4135): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4135): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4135): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/CAKEMIX_CRASHED( 4135): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4135): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4135): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4135): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4135): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4135): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4135): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4135): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4135): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4135): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4135): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4135): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4135): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4135): 	at aen.run(PG:536)
,W/ResourcesManager( 4135): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4135): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  821): Start proc 4173:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,I/ActivityManager(  821): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{c39a4ec token=Token{10265b9f ActivityRecord{199bc13e u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
,I/Process ( 4135): Sending signal. PID: 4135 SIG: 9
,I/HotwordDetector( 1505): Closing mic
,I/MicrophoneInputStream( 1505): mic_close com.google.android.apps.gsa.speech.audio.u@302fe33e
E/lowmemorykiller(  257): Error writing /proc/4135/oom_score_adj; errno=22
,E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager(  821): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  821): android.os.TransactionTooLargeException
W/ActivityManager(  821): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  821): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  821): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  821): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  821): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  821): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  821): 	at android.os.Binder.execTransact(Binder.java:446)
,D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1505): Stopping hotword detection.
I/HotwordRecognitionRnr( 1505): Hotword detection finished
,I/ActivityManager(  821): Start proc 4191:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,W/ActivityManager(  821): Spurious death for ProcessRecord{8cab66 4191:com.google.android.apps.docs/u0a46}, curProc for 4135: null
,E/Search.SharedPreferencesProto( 1505): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,W/OpenGLRenderer( 1376): Incorrectly called buildLayer on View: ew, destroying layer...
,I/ActivityManager(  821): Killing 3465:com.google.android.music:main/u0a66 (adj 15): empty #17
,E/native  ( 1234): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1234): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1234): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1234): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/SQLiteDatabase( 4173): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4173): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4173): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4173): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4173): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4173): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4173): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4173): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4173): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4173): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4173): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4173): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4173): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4173): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4173): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4173): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4173): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4173): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4173): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4173): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4173): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4173): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4173): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4173): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4173): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4173): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4173): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4173): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4173): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4173): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/AndroidRuntime( 4173): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 4173): FATAL EXCEPTION: main
E/AndroidRuntime( 4173): Process: com.android.documentsui, PID: 4173
E/AndroidRuntime( 4173): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4173): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4173): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4173): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4173): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4173): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4173): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4173): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4173): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4173): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4173): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4173): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4173): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4173): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4173): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4173): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4173): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4173): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4173): 	at, android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4173): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4173): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4173): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4173): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4173): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4173): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4173): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4173): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4173): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4173): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4173): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4173): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
,E/AndroidRuntime( 4173): 	... 9 more
,E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
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
,D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  821): Validating map...
,I/ActivityManager(  821): Start proc 4216:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,E/native  ( 1234): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1234): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1234): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1234): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/ActivityManager(  821): Killing 3702:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/Icing   ( 1771): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 34.717ms
,I/OpenGLRenderer(  821): Initialized EGL, version 1.4
,D/OpenGLRenderer(  821): Enabling debug mode 0
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 261us total 17.444ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 223us total 9.505ms
,I/ActivityManager(  821): Killing 3722:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,E/Icing   ( 1771): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1771): Could not init tag ds.tag.deleted
,D/ExternalStorage( 4216): After updating volumes, found 1 active roots
,I/GAv4    ( 4191): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4191):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4191):   adb logcat -s GAv4
,I/Icing   ( 1771): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,W/GAv4    ( 4191): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Icing   ( 1771): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1771): Writing status failed
,E/Icing   ( 1771): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,I/ActivityManager(  821): Killing 3778:com.android.chrome/u0a40 (adj 15): empty #17
,W/GAv4    ( 4191): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4191): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4191): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4191): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4191): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4191): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4191): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4191): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4191): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4191): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4191): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 4191): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4191): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.,
E/SQLiteDatabase( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4191): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4191): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4191): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4191): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4191): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4191): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4191): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4191): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4191): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4191): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4191): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 4191): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 4191): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4191): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4191): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4191): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
,E/SQLiteDatabase( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806),
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4191): 	at aev.getWritableDatabase(PG:238),
E/SQLiteDatabase( 4191): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4191): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4191): 	at aen.run(PG:536)
,E/SQLiteDatabase( 4191): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4191): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4191): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4191): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4191): 	at aej.c(PG:139)
E/SQLiteDatabase( 4191): 	at aej.b(PG:398)
E/SQLiteDatabase( 4191): 	at agf.f(PG:417)
E/SQLiteDatabase( 4191): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4191): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 4191): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4191): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4191): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4191): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4191): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4191): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4191): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4191): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4191): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4191): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4191): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4191): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4191): 	at java.lang.Thread.run(Thread.java:818)
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@38c0fe48}
,W/ResourcesManager( 4191): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4191): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1482094c}
,V/JNIHelp ( 4191): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/ErrorNotificationActivity( 4191): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
,I/ProviderInstaller( 4191): Installed default security provider GmsCore_OpenSSL
,D/OpenGLRenderer( 4191): Use EGL_SWAP_BEHAVIOR_PRESERVED: true,
,D/Atlas   ( 4191): Validating map...,
,V/WindowManager(  821): Adding window Window{122b5902 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 8 (after Window{16e82e81 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}),
,V/WindowManager(  821): Adding window Window{3272cc50 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 9 (before Window{122b5902 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}),
,W/GAv4    ( 4191): Error opening database: android.database.sqlite.SQLiteException: Database open failed,
,E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4191): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4191): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4191): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4191): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4191): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4191): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4191): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 4191): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4191): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4191): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4191): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4191): 	at aej.c(PG:139)
E/SQLiteDatabase( 4191): 	at aej.a(PG:358)
E/SQLiteDatabase( 4191): 	at aej.a(PG:345)
E/SQLiteDatabase( 4191): 	at agf.d(PG:281)
E/SQLiteDatabase( 4191): 	at agf.b(PG:312)
E/SQLiteDatabase( 4191): 	at agf.a(PG:221)
E/SQLiteDatabase( 4191): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/SQLiteDatabase( 4191): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/SQLiteDatabase( 4191): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4191): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4191): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 4191): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4191): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4191): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4191): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4191): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4191): 	at aen.run(PG:536)
,E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4191): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4191): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4191): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4191): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4191): 	at aej.c(PG:139)
E/SQLiteDatabase( 4191): 	at aej.a(PG:358)
E/SQLiteDatabase( 4191): 	at aej.a(PG:345)
E/SQLiteDatabase( 4191): 	at agf.c(PG:884)
E/SQLiteDatabase( 4191): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 4191): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4191): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4191): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4191): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4191): Failed to query Account133 object
E/AbstractDatabaseInstance( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQ,LiteDatabase.java:694)
E/AbstractDatabaseInstance( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4191): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4191): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4191): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4191): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4191): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4191): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4191): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 4191): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 4191): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AbstractDatabaseInstance( 4191): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4191): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 4191): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4191): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4191): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4191): Failed to query Account133 object
E/AbstractDatabaseInstance( 4191): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4191): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4191): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4191): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4191): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4191): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4191): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4191): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4191): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4191): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4191): 	at agf.d(PG:281)
E/AbstractDatabaseInstance( 4191): 	at agf.b(PG:312)
E/AbstractDatabaseInstance( 4191): 	at agf.a(PG:221)
E/AbstractDatabaseInstance( 4191): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/AbstractDatabaseInstance( 4191): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/AbstractDatabaseInstance( 4191): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AbstractDatabaseInstance( 4191): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AbstractDatabaseInstance( 4191): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/AbstractDatabaseInstance( 4191): 	at android.os.Binder.execTransact(Binder.java:446)
W/GAv4    ( 4191): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4191): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4191): Error opening database: android.database.sqlite.SQLiteException: Database open failed
I/ActivityManager(  821): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
I/Process ( 4191): Sending signal. PID: 4191 SIG: 9
,I/WindowState(  821): WIN DEATH: Window{122b5902 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
W/InputDispatcher(  821): channel '3272cc50 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  821): channel '3272cc50 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
I/ActivityManager(  821): Process com.google.android.apps.docs (pid 4191) has died
,I/ActivityThread( 4173): Removing dead content provider:android.content.ContentProviderProxy@225decbd
,I/WindowState(  821): WIN DEATH: Window{3272cc50 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
W/InputDispatcher(  821): Attempted to unregister already unregistered input channel '3272cc50 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
,W/ActivityManager(  821): Force removing ActivityRecord{199bc13e u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}: app died, no saved state
,W/Documents( 4173): Failed to load some roots from com.google.android.apps.docs.storage: android.os.DeadObjectException
D/Documents( 4173): Update found 6 roots in 1275ms
,I/art     (  821): Explicit concurrent mark sweep GC freed 23411(1210KB) AllocSpace objects, 5(174KB) LOS objects, 31% free, 34MB/50MB, paused 1.478ms total 70.624ms
,E/SQLiteDatabase( 1273): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1273): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1273): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1273): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1273): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1273): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1273): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1273): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1273): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1273): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1273): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1273): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1273): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1273): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1273): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1273): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1273): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1273): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1273): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1273): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1273): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1273): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1273): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1273): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1273): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1273): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1273): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
,E/SQLiteOpenHelper( 1273): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1273): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1273): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/SQLiteOpenHelper( 1273): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1273): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1273): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1273): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1273): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1273): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1273): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1273): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
E/SQLiteOpenHelper( 1273): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1273): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1273): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1273): 	,at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1273): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1273): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1273): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1273): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1273): Opened phenotype.db in read-only mode
E/SQLiteLog( 1273): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1273): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1273): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
,E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1273): ,	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1273): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1273): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1273): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1273): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1273): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1273): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1273): 	,at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1273): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1273): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1273): 	,at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1273): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1273): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1273): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1273): ,	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1273): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1273): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1273): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1273): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1273): attempt to write a readonly database (code 8)
,E/ClearcutLoggerIntentService( 1273): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1273): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
,E/ClearcutLoggerIntentService( 1273): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1273): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1273): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1273): 	at java.lang.Thread.run(Thread.java:818)
,E/Search.SharedPreferencesProto( 1505): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ConfigService( 1273): onDestroy
,E/QMI_FW  (  821): xport_send: Sendto failed for port 3840
,E/LocSvc_api_v02(  821): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1721517331
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/kickstart(  871): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
,E/kickstart(  871): ERROR: function: sahara_main:1143 Sahara protocol error
E/kickstart(  871): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,E/ThermalEngine(  365): qmi_clnt_error_cb: with error -2 called for clnt FUSION,
E/ThermalEngine(  365): modem_clnt_error_cb: with -2 called for clnt 0x6
,D/        (  357): csd_client_error_cb: error -2 cb_data 0xb547b060
D/        (  357): csd_client_error_cb: MDM reset
E/        (  357): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
E/        (  357): csd_service_deinit: Error -1 deiniting CSD
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb0
,I/Atfwd_Daemon(  374): Modem Out Of Service --> Release ATCOP service client handles, if any
,I/Atfwd_Daemon(  374): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb4
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb1
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb2
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb3
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb5
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb6
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb7
,I/ThermalEngine(  365): qmi: Instance id 157 for fusion TS
,E/        (  357): csd_service_deinit: notifier handle release rc:0
,D/        (  357): csd_service_init: qmi_client_notifier_init() successful
,W/WindowManager(  821): App freeze timeout expired.
V/ImsSenderRxr( 1351): Read packet: 15 bytes
V/ImsSenderRxr( 1351): processResponse
D/ImsSenderRxr( 1351): Response data: [12, 13, -1, -1, -1, -1, 16, 3, 24, -43, 1, 32, 0, 8, 0]
D/ImsSenderRxr( 1351):  Tag -1 3 213 0
,I/str_params(  357): key: 'all_call_states' value: ''
,I/str_params(  357): key: 'all_call_states' value: ''
,I/str_params(  357): key: 'all_call_states' value: ''

```
