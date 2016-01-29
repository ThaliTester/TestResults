#### Test 5761781115ba656_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  820): Waited long enough for: ServiceRecord{3926785b u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,--------- beginning of main
D/AndroidRuntime( 3838): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3838): CheckJNI is OFF
D/AndroidRuntime( 3838): Calling main entry com.android.commands.am.Am
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{2cd38723 token=Token{b441852 ActivityRecord{3fea84dd u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3838): Shutting down VM
V/WindowManager(  820): Adding window Window{1816a24c u0 Starting com.test.thalitest} at 2 of 7 (after Window{27fddcb7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/MicrophoneInputStream( 1521): mic_close com.google.android.apps.gsa.speech.audio.u@2611ba35
I/HotwordDetector( 1521): Closing mic
I/ActivityManager(  820): Start proc 3852:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1521): Hotword detection finished
I/HotwordRecognitionRnr( 1521): Stopping hotword detection.
I/ActivityManager(  820): Killing 3483:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660507411
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  820): Killing 3371:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,I/WebViewFactory( 3852): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3852): Time to load native libraries: 2 ms (timestamps 5571-5573)
I/LibraryLoader( 3852): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3852): Binding Chromium to main looper Looper (main, tid 1) {3035f324}
I/LibraryLoader( 3852): Expected native library version number "",actual native library version number ""
I/chromium( 3852): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3852): Initializing chromium process, singleProcess=true
W/art     ( 3852): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3852): ApplicationContext is null in ApplicationStatus
W/chromium( 3852): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3852): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3852): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3852): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a447f13:true
W/art     ( 3852): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3852): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3852): CordovaWebView is running on device made by: motorola
W/art     ( 3852): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3852): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3852): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3852): Validating map...
V/WindowManager(  820): Adding window Window{430cfe u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1816a24c u0 Starting com.test.thalitest})
W/chromium( 3852): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3852): Initialized EGL, version 1.4
D/OpenGLRenderer( 3852): Enabling debug mode 0
I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +834ms
I/Keyboard.Facilitator( 1217): onFinishInput()
W/BindingManager( 3852): Cannot call determinedVisibility() - never saw a connection for the pid: 3852
D/JsMessageQueue( 3852): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3852): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576327424
I/chromium( 3852): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3852): Initializing JXcore engine
W/jxcore-log( 3852): JXcore engine is ready
,W/Thread-437( 3905): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10439]" dev="sockfs" ino=10439 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-437( 3905): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-437( 3905): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10622]" dev="sockfs" ino=10622 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-437( 3905): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23815]" dev="sockfs" ino=23815 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3852): Starting JXcore engine
,W/jxcore-log( 3852): Platform android
W/jxcore-log( 3852): 
W/jxcore-log( 3852): Process ARCH arm
W/jxcore-log( 3852): 
,I/jxcore-log( 3852): JXcore Cordova bridge is ready!
I/jxcore-log( 3852): 
W/jxcore-log( 3852): JXcore engine is started
,I/jxcore-log( 3852): Toggling radios to true
I/jxcore-log( 3852): 
,D/BluetoothAdapter( 3852): enable(): BT is already enabled..!,
,D/WifiService(  820): setWifiEnabled: true pid=3852, uid=10265
,E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  820): New client listening to asynchronous messages
,I/jxcore-log( 3852): Radios toggled
I/jxcore-log( 3852): 
,I/jxcore-log( 3852): My device name is: motorola-Nexus 6
,I/jxcore-log( 3852): 
,I/wpa_supplicant( 1141): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1,
E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state,
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  353): Clearing all IP addresses on wlan0,
,V/NativeCrypto( 1499): Read error: ssl=0xb4888800: I/O error during system call, Connection timed out
V/NativeCrypto( 1499): SSL shutdown failed: ssl=0xb4888800: I/O error during system call, Broken pipe
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  820): Start Disconnecting Watchdog 1,
E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
D/CommandListener(  353): Clearing all IP addresses on wlan0
D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PhoneInterfaceManager( 1262): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1262): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3044): type=WIFI subType= reason=null isConnected=false
,D/NetworkChangeNotifierAutoDetect( 1521): Network connectivity changed, type is: 6
D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
V/MusicLeanback( 3044): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  820): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): will read network variables netId=0
,I/ActivityManager(  820): Start proc 3914:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/GpsLocationProvider(  820): No APN found to select.
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,D/PhoneInterfaceManager( 1262): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1262): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
E/WifiConfigStore(  820): will read network variables netId=0
D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,I/art     ( 1499): Explicit concurrent mark sweep GC freed 27745(1502KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 817us total 21.073ms
,I/ActivityManager(  820): Start proc 3942:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  820): Killing 3544:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/art     (  820): Explicit concurrent mark sweep GC freed 34549(1625KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 2.764ms total 90.794ms
,D/SprintDMReceiver( 3942): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3942): simOperator:  IMSI: null
D/SprintDMReceiver( 3942): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1777): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1777): onCreate
,D/SystemUpdateService( 1777): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1777): active receiver: enabled
,I/SystemUpdateService( 1777): showing system update notification
,I/iu.Environment( 1777): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1777): num queued entries: 0
,I/iu.UploadsManager( 1777): num updated entries: 0
I/iu.SyncManager( 1777): NEXT; no task
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1777): retry (wakeup: false) in 3599982 ms
,I/Babel   ( 3724): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  820): Start proc 3962:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1777): onDestroy
,I/ActivityManager(  820): Killing 3565:com.android.musicfx/u0a18 (adj 15): empty #17
,I/GAv4    ( 3962): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3962):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3962):   adb logcat -s GAv4
,W/GAv4    ( 3962): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3962): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3962): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3962): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3962): Time to load native libraries: 2 ms (timestamps 9534-9536)
,I/LibraryLoader( 3962): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3962): Binding Chromium to main looper Looper (main, tid 1) {3355509b}
,I/LibraryLoader( 3962): Expected native library version number "",actual native library version number ""
,I/chromium( 3962): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3962): Initializing chromium process, singleProcess=true
,W/art     ( 3962): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3962): ApplicationContext is null in ApplicationStatus
,W/chromium( 3962): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3962): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3962): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3962): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/NSApplication( 3962): Starting up...
W/AudioManagerAndroid( 3962): Requires BLUETOOTH permission
,I/ActivityManager(  820): Start proc 4018:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  820): Killing 3594:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/ActivityManager(  820): Killing 1336:android.process.acore/u0a5 (adj 15): empty #17
,I/wpa_supplicant( 1141): wlan0: Trying to associate with SSID 'NG7005g'
,V/MusicLeanback( 3044): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3942): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3942): simOperator:  IMSI: null
D/SprintDMReceiver( 3942): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1777): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1777): onCreate
,D/SystemUpdateService( 1777): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1777): active receiver: enabled
,I/SystemUpdateService( 1777): showing system update notification
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1777): retry (wakeup: false) in 3599975 ms
,D/SystemUpdateService( 1777): onDestroy
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3632): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3632): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3632): [1] 5.onFinished: Scheduling replication attempt 1.
,I/wpa_supplicant( 1141): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1141): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1141): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 2
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
,E/WifiStateMachine(  820):  my bss beacon rx: 214
E/WifiStateMachine(  820):  RSSI mgmt: -49
E/WifiStateMachine(  820):  BE :  rx=190 tx=164 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=3 tx=0 lost=0 retries=0
,E/WifiStateMachine(  820):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 9154 tx_time=139 rx_time=512 scan_time=0
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/dhcpcd  ( 4050): version 5.5.6 starting
,I/dhcpcd  ( 4050): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 4050): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 4050): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3852): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3852): 
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 101
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=10.69 rxSuccessRate=12.44 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
D/ConnectivityService(  820): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820):    accepting network in place of null
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101],
,D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true,
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3044): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3044): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/NetworkChangeNotifierAutoDetect( 1521): Network connectivity changed, type is: 2
,D/PhoneInterfaceManager( 1262): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1262): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
D/SprintDMReceiver( 3942): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3942): simOperator:  IMSI: null
D/SprintDMReceiver( 3942): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1777): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1777): onCreate
,D/SystemUpdateService( 1777): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1777): active receiver: enabled
,I/SystemUpdateService( 1777): showing system update notification
,I/ActivityManager(  820): Start proc 4084:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 304us total 10.158ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 9.239ms
,I/ValidateNoPeople(  820): skipping global notification
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 9.417ms
,V/SystemUpdateService( 1777): retry (wakeup: false) in 3599955 ms
,I/ActivityManager(  820): Start proc 4103:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,D/SystemUpdateService( 1777): onDestroy
,I/iu.Environment( 1777): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1777): num queued entries: 0
,I/iu.UploadsManager( 1777): num updated entries: 0
D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.SyncManager( 1777): NEXT; no task
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4103): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/Kids    ( 1777): [AccountUtils] Account not ready
W/Kids    ( 1777): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1777): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1777): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1777): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1777): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1777): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1777): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1777): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1777): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1777): 	at java.lang.Thread.run(Thread.java:818)
,I/BooksApp( 4103): Created application version: 3.6.8 (30608)
,I/Babel   ( 3724): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1499): Connected
,D/ConnectivityService(  820): reportInetCondition: type=1 ok, revalidate
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  820): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/GCM     ( 1499): Message class com.google.f.a.a.p
,D/ConnectivityService(  820): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,I/BooksSync( 4103): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4084): Connecting to GoogleApiClient
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 36299(1753KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 1.751ms total 72.586ms
,I/art     ( 1499): Explicit concurrent mark sweep GC freed 13524(693KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 26MB/42MB, paused 1.282ms total 23.487ms
,E/ClientConnectionOperation( 1777): Handling authorization failure
E/ClientConnectionOperation( 1777): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1777): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1777): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1777): 	... 7 more
,V/KeepSync( 4084): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4084): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4084): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4084): (284) automatic index on blob_node(is_deleted)
,I/BooksConfig( 4103): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4084): IOException
E/KeepSync( 4084): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4084): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4084): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4084): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4084): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4084): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4084): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4084): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4084): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4084): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4084): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4084): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4084): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4084): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4084): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4084): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4084): 	... 10 more
W/KeepSync( 4084): Sync result 2
,E/BooksAccountManager( 4103): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4103): Soft error
E/BooksSync( 4103): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4103): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4103): Sync error
E/BooksSync( 4103): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4103): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4103): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 73196, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/jxcore-log( 3852): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3852): 
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 74960, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3852): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3852): 
I/jxcore-log( 3852): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3852): 
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3852): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3852): 
,E/HttpOperation( 3694): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3694): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3694): 	at jdm.a(PG:82)
E/HttpOperation( 3694): 	at jcs.o(PG:406)
E/HttpOperation( 3694): 	at jcn.a(PG:1379)
E/HttpOperation( 3694): 	at jcs.i(PG:143)
E/HttpOperation( 3694): 	at blb.a(PG:3937)
E/HttpOperation( 3694): 	at czp.a(PG:18188)
E/HttpOperation( 3694): 	at czp.a(PG:9081)
E/HttpOperation( 3694): 	at czq.run(PG:1686)
E/HttpOperation( 3694): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3694): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3694): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3694): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3694): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3694): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3694): 	at jdj.a(PG:4091)
E/HttpOperation( 3694): 	at jdj.a(PG:1125)
E/HttpOperation( 3694): 	at jdm.a(PG:77)
E/HttpOperation( 3694): 	... 12 more
E/HttpOperation( 3694): Caused by: faj: BadAuthentication
E/HttpOperation( 3694): 	at fal.a(PG:38)
E/HttpOperation( 3694): 	at jdj.a(PG:4089)
E/HttpOperation( 3694): 	... 14 more
,I/jxcore-log( 3852): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js,
I/jxcore-log( 3852): 
,I/jxcore-log( 3852): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3852): ,
,I/jxcore-log( 3852): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3852): 
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3694): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3694): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3694): 	at jdm.a(PG:82)
E/HttpOperation( 3694): 	at jcs.o(PG:406)
E/HttpOperation( 3694): 	at jcn.a(PG:1379)
E/HttpOperation( 3694): 	at jcs.i(PG:143)
E/HttpOperation( 3694): 	at hec.a(PG:42)
E/HttpOperation( 3694): 	at hee.a(PG:102)
E/HttpOperation( 3694): 	at czr.a(PG:65)
E/HttpOperation( 3694): 	at kka.a(PG:108)
E/HttpOperation( 3694): 	at czp.a(PG:19176)
E/HttpOperation( 3694): 	at czp.a(PG:9081)
E/HttpOperation( 3694): 	at czq.run(PG:1686)
E/HttpOperation( 3694): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3694): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3694): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3694): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3694): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3694): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3694): 	at jdj.a(PG:4091)
E/HttpOperation( 3694): 	at jdj.a(PG:1125)
E/HttpOperation( 3694): 	at jdm.a(PG:77)
E/HttpOperation( 3694): 	... 15 more
E/HttpOperation( 3694): Caused by: faj: BadAuthentication
E/HttpOperation( 3694): 	at fal.a(PG:38)
E/HttpOperation( 3694): 	at jdj.a(PG:4089)
E/HttpOperation( 3694): 	... 17 more
,E/ExperimentLoader( 3694): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3694): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3694): 	at jdm.a(PG:82)
E/ExperimentLoader( 3694): 	at jcs.o(PG:406)
E/ExperimentLoader( 3694): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3694): 	at jcs.i(PG:143)
E/ExperimentLoader( 3694): 	at hec.a(PG:42)
E/ExperimentLoader( 3694): 	,at hee.a(PG:102)
E/ExperimentLoader( 3694): 	at czr.a(PG:65)
E/ExperimentLoader( 3694): 	at kka.a(PG:108)
E/ExperimentLoader( 3694): 	at czp.a(PG:19176)
E/ExperimentLoader( 3694): 	at czp.a(PG:9081)
E/ExperimentLoader( 3694): 	at czq.run(PG:1686)
E/ExperimentLoader( 3694): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3694): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3694): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3694): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3694): 	at java.lang.Thread.run(Thread.java:818)
,E/ExperimentLoader( 3694): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3694): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3694): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3694): 	at jdm.a(PG:77)
E/ExperimentLoader( 3694): 	... 15 more
E/ExperimentLoader( 3694): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3694): 	at fal.a(PG:38)
E/ExperimentLoader( 3694): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3694): 	... 17 more
,I/ActivityManager(  820): Killing 3673:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 76683, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  820): Killing 3458:com.google.android.gm/u0a78 (adj 15): empty #17
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=-2ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 08:28:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454056112172], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454056112154]}
,D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Validated
,D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
,V/Herrevad( 1777): NQAS connected
,I/GAV2    ( 4103): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3852): Test app app.js loaded
I/jxcore-log( 3852): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3852): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3852): BLE advertisement is supported
I/jxcore-log( 3852): 
,I/chromium( 3852): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=7.92 rxSuccessRate=9.86 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,D/Finsky  ( 3632): [417] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3632): [417] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3632): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3632): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3632): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.25 rxSuccessRate=6.81 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.35 rxSuccessRate=3.17 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/HeadsetStateMachine( 2218): Disconnected process message: 10, size: 0
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3632): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3632): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3632): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2218): Disconnected process message: 10, size: 0
,I/BooksSync( 4103): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4103): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     (  820): Explicit concurrent mark sweep GC freed 47821(2MB) AllocSpace objects, 14(318KB) LOS objects, 31% free, 34MB/50MB, paused 1.562ms total 80.740ms
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3694): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3694): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3694): 	at jdm.a(PG:82)
E/HttpOperation( 3694): 	at jcs.o(PG:406)
E/HttpOperation( 3694): 	at jcn.a(PG:1379)
E/HttpOperation( 3694): 	at jcs.i(PG:143)
E/HttpOperation( 3694): 	at blb.a(PG:3937)
E/HttpOperation( 3694): 	at czp.a(PG:18188)
E/HttpOperation( 3694): 	at czp.a(PG:9081)
E/HttpOperation( 3694): 	at czq.run(PG:1686)
E/HttpOperation( 3694): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3694): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3694): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3694): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3694): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3694): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3694): 	at jdj.a(PG:4091)
E/HttpOperation( 3694): 	at jdj.a(PG:1125)
E/HttpOperation( 3694): 	at jdm.a(PG:77)
E/HttpOperation( 3694): 	... 12 more
E/HttpOperation( 3694): Caused by: faj: BadAuthentication
E/HttpOperation( 3694): 	at fal.a(PG:38)
E/HttpOperation( 3694): 	at jdj.a(PG:4089)
E/HttpOperation( 3694): 	... 14 more
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3694): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3694): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3694): 	at jdm.a(PG:82)
E/HttpOperation( 3694): 	at jcs.o(PG:406)
E/HttpOperation( 3694): 	at jcn.a(PG:1379)
E/HttpOperation( 3694): 	at jcs.i(PG:143)
E/HttpOperation( 3694): 	at hec.a(PG:42)
E/HttpOperation( 3694): 	at hee.a(PG:102)
E/HttpOperation( 3694): 	at czr.a(PG:65)
E/HttpOperation( 3694): 	at kka.a(PG:108)
E/HttpOperation( 3694): 	at czp.a(PG:19176)
E/HttpOperation( 3694): 	at czp.a(PG:9081)
E/HttpOperation( 3694): 	at czq.run(PG:1686)
E/HttpOperation( 3694): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3694): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3694): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3694): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3694): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3694): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3694): 	at jdj.a(PG:4091)
E/HttpOperation( 3694): 	at jdj.a(PG:1125)
E/HttpOperation( 3694): 	at jdm.a(PG:77)
E/HttpOperation( 3694): 	... 15 more
E/HttpOperation( 3694): Caused by: faj: BadAuthentication
E/HttpOperation( 3694): 	at fal.a(PG:38)
E/HttpOperation( 3694): 	at jdj.a(PG:4089)
E/HttpOperation( 3694): 	... 17 more
E/ExperimentLoader( 3694): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3694): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3694): 	at jdm.a(PG:82)
E/ExperimentLoader( 3694): 	at jcs.o(PG:406)
E/ExperimentLoader( 3694): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3694): 	at jcs.i(PG:143)
E/ExperimentLoader( 3694): 	at hec.a(PG:42)
E/ExperimentLoader( 3694): 	at hee.a(PG:102)
E/ExperimentLoader( 3694): 	at czr.a(PG:65)
E/ExperimentLoader( 3694): ,	at kka.a(PG:108)
E/ExperimentLoader( 3694): 	at czp.a(PG:19176)
E/ExperimentLoader( 3694): 	at czp.a(PG:9081)
E/ExperimentLoader( 3694): 	at czq.run(PG:1686)
E/ExperimentLoader( 3694): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3694): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3694): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3694): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3694): 	at java.lang.Thread.run(Thread.java:818)
,E/ExperimentLoader( 3694): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3694): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3694): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3694): 	at jdm.a(PG:77)
E/ExperimentLoader( 3694): 	... 15 more,
E/ExperimentLoader( 3694): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3694): 	at fal.a(PG:38)
E/ExperimentLoader( 3694): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3694): 	... 17 more
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1499): Explicit concurrent mark sweep GC freed 33823(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.368ms total 30.072ms
,E/BooksAccountManager( 4103): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4103): Soft error
E/BooksSync( 4103): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4103): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4103): Sync error
E/BooksSync( 4103): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4103): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4103): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 113950, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 115450, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 4084): Connecting to GoogleApiClient
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1777): Handling authorization failure
E/ClientConnectionOperation( 1777): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1777): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1777): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1777): 	... 7 more
,V/KeepSync( 4084): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4084): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4084): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4084): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4084): IOException
E/KeepSync( 4084): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4084): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4084): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4084): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4084): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4084): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4084): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4084): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4084): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4084): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4084): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4084): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4084): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4084): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4084): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4084): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4084): 	... 10 more
W/KeepSync( 4084): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 116187, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1217): run()
I/Keyboard.Facilitator( 1217): flushDynamicLanguageModels()
,I/ConfigService( 1499): onCreate
,I/ConfigService( 1499): onDestroy
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.90 rxSuccessRate=2.38 targetRoamBSSID=any RSSI=-49
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3632): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3632): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3632): [1] 5.onFinished: Scheduling replication attempt 4.
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.77 rxSuccessRate=2.98 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (156 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000
V/ActivityManager(  820): Display changed displayId=0
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2,
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0,
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  820): Excessive delay in setPowerMode(): 264ms
,I/DreamManagerService(  820): Entering dreamland.,
I/PowerManagerService(  820): Dozing...
,I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 12
,E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1217): onFinishInput()
,E/WifiStateMachine(  820): cancelDelayedScan -> 14
,E/native  (  820): do suspend true
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off,
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  871): STATUS: Received file 'm9kefs2',
I/kickstart(  871): STATUS: 950272 bytes transferred in 1.051781 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed,
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3632): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3632): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3632): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ActivityManager(  820): Start proc 4200:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4200): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4200):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4200):   adb logcat -s GAv4
,W/GAv4    ( 4200): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4200): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4200): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Killing 2496:com.google.android.calendar/u0a37 (adj 15): empty #17
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2218): Disconnected process message: 10, size: 0
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3914): [430] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1499): Vacuum at: now=1454056210851 tag=VacuumService
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3914): [430] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3914): [430] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3914): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3914): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3914): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3914): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3914): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3914): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3914): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3914): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3914): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3914): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1499): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1499): No account for auth token provided
,D/Finsky  ( 3632): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3632): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3632): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1499): No account for auth token provided
,W/Uploader( 1499): No account for auth token provided
,I/art     (  820): Explicit concurrent mark sweep GC freed 45374(2MB) AllocSpace objects, 13(396KB) LOS objects, 31% free, 34MB/50MB, paused 1.355ms total 76.961ms
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1499): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1499): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1499): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1499): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1499): No account for auth token provided
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1499): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1499): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1499): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1499): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1499): No account for auth token provided
,D/HeadsetStateMachine( 2218): Disconnected process message: 10, size: 0
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1499): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1499): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1499): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1499): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1499): No account for auth token provided
,W/Uploader( 1499): No account for auth token provided
,W/Uploader( 1499): No account for auth token provided
,W/Uploader( 1499): No account for auth token provided
,W/Uploader( 1499): No account for auth token provided
,W/Uploader( 1499):  no longer exists, so no auth token.
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1499): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1499): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1499): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1499): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1499): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1499): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1499): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1499): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1499): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1499): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1499): 	at com.google.android.gms.gcm.am.run(SourceFile:135),
,I/BooksSync( 4103): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4103): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4103): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4103): Soft error
E/BooksSync( 4103): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4103): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4103): Sync error
E/BooksSync( 4103): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4103): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4103): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 194271, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3914): [431] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3914): [431] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3914): [431] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3914): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3914): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3914): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3914): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3914): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3914): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3914): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3914): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3914): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3914): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1217): run()
I/Keyboard.Facilitator( 1217): flushDynamicLanguageModels()
,I/ConfigService( 1499): onCreate
,I/art     ( 1499): Explicit concurrent mark sweep GC freed 69922(3MB) AllocSpace objects, 11(974KB) LOS objects, 36% free, 27MB/43MB, paused 1.863ms total 59.376ms
,V/KeepSync( 4084): Connecting to GoogleApiClient
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1777): Handling authorization failure
,E/ClientConnectionOperation( 1777): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1777): 	,at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1777): ,	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1777): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1777): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1777): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1777): ,	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1777): 	,at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
,E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1777),: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1777): 	... 7 more
,V/KeepSync( 4084): GoogleApiClient failed to connect with error code: 4
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/SQLiteLog( 4084): (284) automatic index on blob_node(is_deleted),
V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 4084): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4084): (284) automatic index on blob_node(is_deleted)
E/HttpOperation( 3694): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3694): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3694): 	at jdm.a(PG:82)
E/HttpOperation( 3694): 	at jcs.o(PG:406)
E/HttpOperation( 3694): 	at jcn.a(PG:1379)
E/HttpOperation( 3694): 	at jcs.i(PG:143)
E/HttpOperation( 3694): 	at blb.a(PG:3937)
E/HttpOperation( 3694): 	at czp.a(PG:18188)
E/HttpOperation( 3694): 	at czp.a(PG:9081)
E/HttpOperation( 3694): 	at czq.run(PG:1686)
E/HttpOperation( 3694): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3694): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3694): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3694): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3694): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3694): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3694): 	at jdj.a(PG:4091)
E/HttpOperation( 3694): 	at jdj.a(PG:1125)
E/HttpOperation( 3694): 	at jdm.a(PG:77)
E/HttpOperation( 3694): 	... 12 more
E/HttpOperation( 3694): Caused by: faj: BadAuthentication
E/HttpOperation( 3694): 	at fal.a(PG:38)
E/HttpOperation( 3694): 	at jdj.a(PG:4089)
E/HttpOperation( 3694): 	... 14 more
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3694): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3694): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3694): 	at jdm.a(PG:82)
E/HttpOperation( 3694): 	at jcs.o(PG:406)
E/HttpOperation( 3694): 	at jcn.a(PG:1379)
E/HttpOperation( 3694): 	at jcs.i(PG:143)
E/HttpOperation( 3694): 	at hec.a(PG:42)
E/HttpOperation( 3694): 	at hee.a(PG:102)
E/HttpOperation( 3694): 	at czr.a(PG:65)
E/HttpOperation( 3694): 	at kka.a(PG:108)
E/HttpOperation( 3694): 	at czp.a(PG:19176)
E/HttpOperation( 3694): 	at czp.a(PG:9081)
E/HttpOperation( 3694): 	at czq.run(PG:1686)
E/HttpOperation( 3694): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3694): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3694): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3694): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3694): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3694): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3694): 	at jdj.a(PG:4091)
E/HttpOperation( 3694): 	at jdj.a(PG:1125)
E/HttpOperation( 3694): 	at jdm.a(PG:77)
E/HttpOperation( 3694): 	... 15 more
E/HttpOperation( 3694): Caused by: faj: BadAuthentication
E/HttpOperation( 3694): 	at fal.a(PG:38)
E/HttpOperation( 3694): 	at jdj.a(PG:4089)
E/HttpOperation( 3694): 	... 17 more
E/ExperimentLoader( 3694): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3694): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3694): 	at jdm.a(PG:82)
E/ExperimentLoader( 3694): 	at jcs.o(PG:406)
E/ExperimentLoader( 3694): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3694): 	at jcs.i(PG:143)
E/ExperimentLoader( 3694): 	at hec.a(PG:42)
E/ExperimentLoader( 3694): 	at hee.a(PG:102)
E/ExperimentLoader( 3694): 	at czr.a(PG:65)
E/ExperimentLoader( 3694): 	at kka.a(PG:108)
E/ExperimentLoader( 3694): 	at czp.a(PG:19176)
E/ExperimentLoader( 3694): 	at czp.a(PG:9081)
E/ExperimentLoader( 3694): 	at czq.run(PG:1686)
E/ExperimentLoader( 3694): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3694): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3694): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3694): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3694): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3694): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3694): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3694): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3694): 	at jdm.a(PG:77)
E/ExperimentLoader( 3694): 	... 15 more
E/ExperimentLoader( 3694): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3694): 	at fal.a(PG:38)
E/ExperimentLoader( 3694): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3694): 	... 17 more
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4084): IOException
E/KeepSync( 4084): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4084): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4084): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4084): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4084): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4084): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4084): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4084): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4084): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4084): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4084): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4084): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4084): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4084): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4084): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4084): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4084): 	... 10 more
W/KeepSync( 4084): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 199066, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 196706, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1499): onDestroy
,D/HeadsetStateMachine( 2218): Disconnected process message: 10, size: 0
,I/jxcore-log( 3852): --= Surplus to requirements =--
I/jxcore-log( 3852): 
I/jxcore-log( 3852): ****TEST TOOK:  ms ****
I/jxcore-log( 3852): 
,I/jxcore-log( 3852): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3852): 
,D/AndroidRuntime( 4267): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4267): CheckJNI is OFF
,D/AndroidRuntime( 4267): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
,I/ActivityManager(  820): Killing 3852:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest,
,I/WindowState(  820): WIN DEATH: Window{430cfe u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  820): Client connection lost with reason: 4
,W/PackageSettings(  820): Skipping PackageSetting{178319e0 com.example.hello/10273} due to missing metadata
,W/ActivityManager(  820): Force removing ActivityRecord{3fea84dd u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  820): Display changed displayId=0
,W/ActivityManager(  820): Spurious death for ProcessRecord{2b0f96e0 3852:com.test.thalitest/u0a265}, curProc for 3852: null
,I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,I/Keyboard.Facilitator( 1217): resetDictionaries() : en_US
D/TaskPersister(  820): removeObsoleteFile: deleting file=28_task.xml
D/BuaReceiver( 3524): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1217): run()
,I/art     ( 1062): Explicit concurrent mark sweep GC freed 57199(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 1.127ms total 43.296ms
,I/Decoder ( 1217): createOrResetDecoder
,I/art     ( 1521): Explicit concurrent mark sweep GC freed 1863(150KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 6.464ms total 71.284ms
,I/ActivityManager(  820): Start proc 4283:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,I/ConfigService( 1499): onCreate
,W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3852 uid 10265
,I/art     (  820): Explicit concurrent mark sweep GC freed 36316(1904KB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 1.802ms total 103.373ms
,I/Keyboard.Facilitator( 1217): onFinishInput()
,I/art     (  820): WaitForGcToComplete blocked for 87.230ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1217): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1217): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1217): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1217): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1217): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1217): run()
I/StatsUtilsManager( 1217): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1217): shouldRecordStats() = Too Soon
,W/LocationOracleImpl( 1521): Best location was null
,I/art     ( 1281): Explicit concurrent mark sweep GC freed 5085(371KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 880us total 25.860ms
,D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/HotwordRecognitionRnr( 1521): Starting hotword detection.
,I/MicrophoneInputStream( 1521): mic_starting com.google.android.apps.gsa.speech.audio.u@2c0b73f8
,I/AudioFlinger(  357): AudioFlinger's thread 0xb4d31000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1521): mic_started com.google.android.apps.gsa.speech.audio.u@2c0b73f8
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,D/VoicemailCleanupService( 4283): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  820): Start proc 4321:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/ContactLocale( 4283): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/HotwordWorker( 1521): onReady
,I/art     (  820): Explicit concurrent mark sweep GC freed 8828(420KB) AllocSpace objects, 7(771KB) LOS objects, 32% free, 33MB/49MB, paused 6.757ms total 140.296ms
,I/art     ( 1817): Explicit concurrent mark sweep GC freed 16094(950KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 874us total 28.941ms
,E/DataBuffer( 1817): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3fbef5a0)
,I/ActivityManager(  820): Start proc 4340:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,D/Launcher.Workspace( 1281): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1281): 11683562 - stripEmptyScreens()
D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2d89ba92}
E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
,W/ContextImpl( 4340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660507411
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/NetworkScheduler.SchedulerReceiver( 1499): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1499): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,V/GoogleAuthProtoRequest( 3914): [433] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 4267): System.exit called, status: 0
I/AndroidRuntime( 4267): VM exiting with result code 0.
,D/PackageBroadcastService( 1777): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1777): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1777): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1777): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1777): Removing dialog suppression flag for package com.test.thalitest
,I/UpdateIcingCorporaServi( 1521): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1281): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1003ceaf new=com.google.android.velvet.VelvetApplication@1003ceaf
,D/GOOGLEHELP_CompatibleDatabase( 1777): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1777): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1777): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1777): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1777): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1777): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1777): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  820): Start proc 4370:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,D/GOOGLEHELP_CompatibleDatabase( 1777): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1777): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1777): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1777): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1777): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1777): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ConfigFetchService( 1777): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,I/ConfigFetchService( 1777): service connected
,I/PeopleContactsSync( 1777): CP2 sync disabled
I/Icing   ( 1777): doRemovePackageData com.test.thalitest
,I/GLSUser ( 1499): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1499): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1499): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1499): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1499): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3914): [433] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3914): [433] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3914): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3914): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3914): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3914): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3914): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3914): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3914): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3914): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3914): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3914): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  820): Killing 3418:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/UpdateIcingCorporaServi( 1521): UpdateCorporaTask done [took 341 ms] updated apps [took 341 ms] 
,I/GAv4    ( 4370): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4370):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4370):   adb logcat -s GAv4
,W/GAv4    ( 4370): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4370): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4370): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 4370): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4370): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4370): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4370): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4370): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4370): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4370): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4370): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4370): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4370): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4370): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4370): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4370): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4370): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4370): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4370): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4370): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4370): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabas,e.java:694)
E/SQLiteDatabase( 4370): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4370): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4370): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4370): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4370): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4370): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4370): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4370): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4370): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4370): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4370): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4370): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4370): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4370): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4370): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4370): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4370): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4370): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4370): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4370): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4370): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4370): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4370): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4370): 	at aen.run(PG:536)
,W/GAv4    ( 4370): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4370): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4370): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
W/GAv4    ( 4370): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4370): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4370): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/ResourcesManager( 4370): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4370): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4370): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4370): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4370): Error opening database: android.database.sqlite.SQLiteException: Database open failed
I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0

```
