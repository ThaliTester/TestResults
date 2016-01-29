#### Test 56818254e6f5c3b_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 3601): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3601): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3601): [1] 5.onFinished: Scheduling replication attempt 1.
D/AndroidRuntime( 3764): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3764): CheckJNI is OFF
D/AndroidRuntime( 3764): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{27781f56 token=Token{2cc5f571 ActivityRecord{b893718 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  822): Adding window Window{25303e73 u0 Starting com.test.thalitest} at 2 of 7 (after Window{1847c093 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1542): Closing mic
I/MicrophoneInputStream( 1542): mic_close com.google.android.apps.gsa.speech.audio.u@333901f1
D/AndroidRuntime( 3764): Shutting down VM
I/ActivityManager(  822): Start proc 3779:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/ActivityManager(  822): Killing 3451:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
I/HotwordRecognitionRnr( 1542): Hotword detection finished
I/HotwordRecognitionRnr( 1542): Stopping hotword detection.
I/ActivityManager(  822): Killing 3127:com.google.android.apps.gcs/u0a89 (adj 15): empty #18
,I/WebViewFactory( 3779): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3779): Time to load native libraries: 2 ms (timestamps 9915-9917)
I/LibraryLoader( 3779): Expected native library version number "",actual native library version number ""
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660740883
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,V/WebViewChromiumFactoryProvider( 3779): Binding Chromium to main looper Looper (main, tid 1) {28a76fd0}
I/LibraryLoader( 3779): Expected native library version number "",actual native library version number ""
I/chromium( 3779): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3779): Initializing chromium process, singleProcess=true
W/art     ( 3779): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3779): ApplicationContext is null in ApplicationStatus
,W/chromium( 3779): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3779): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3779): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3779): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f25aa63:true
,W/art     ( 3779): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3779): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3779): CordovaWebView is running on device made by: motorola
,W/art     ( 3779): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3779): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3779): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3779): Validating map...
,V/WindowManager(  822): Adding window Window{1005f253 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{25303e73 u0 Starting com.test.thalitest})
,W/chromium( 3779): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3779): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3779): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +884ms
,I/Keyboard.Facilitator( 1265): onFinishInput()
,W/BindingManager( 3779): Cannot call determinedVisibility() - never saw a connection for the pid: 3779
,D/JsMessageQueue( 3779): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3779): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576324608
,I/chromium( 3779): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3779): Initializing JXcore engine
W/jxcore-log( 3779): JXcore engine is ready
,W/Thread-422( 3834): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10822]" dev="sockfs" ino=10822 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-422( 3834): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/jxcore-log( 3779): Starting JXcore engine,
,W/Thread-422( 3834): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9804]" dev="sockfs" ino=9804 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
W/Thread-422( 3834): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23811]" dev="sockfs" ino=23811 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3779): Platform android
W/jxcore-log( 3779): ,
W/jxcore-log( 3779): Process ARCH arm
W/jxcore-log( 3779): 
,I/jxcore-log( 3779): JXcore Cordova bridge is ready!
I/jxcore-log( 3779): 
W/jxcore-log( 3779): JXcore engine is started
,I/jxcore-log( 3779): Toggling radios to true
I/jxcore-log( 3779): 
,D/BluetoothAdapter( 3779): enable(): BT is already enabled..!
,D/WifiService(  822): New client listening to asynchronous messages
D/WifiService(  822): setWifiEnabled: true pid=3779, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3779): Radios toggled
I/jxcore-log( 3779): 
I/jxcore-log( 3779): My device name is: motorola-Nexus 6
I/jxcore-log( 3779): 
,I/wpa_supplicant( 1095): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1225): Read error: ssl=0xb4886000: I/O error during system call, Connection timed out
,V/NativeCrypto( 1225): SSL shutdown failed: ssl=0xb4886000: I/O error during system call, Broken pipe
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1075): CM callback handler got msg 524292
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/Tethering(  822): MasterInitialState.processMessage what=3
,E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent,
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/PhoneInterfaceManager( 1385): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1385): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,V/MusicLeanback( 3080): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): will read network variables netId=0
,I/ActivityManager(  822): Start proc 3843:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
E/GpsLocationProvider(  822): No APN found to select.
,E/WifiConfigStore(  822): will read network variables netId=0
,D/PhoneInterfaceManager( 1385): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1385): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,I/ActivityManager(  822): Start proc 3869:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  822): Killing 3511:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/SprintDMReceiver( 3869): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3869): simOperator:  IMSI: null
,D/SprintDMReceiver( 3869): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1783): onCreate
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,I/iu.Environment( 1783): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ValidateNoPeople(  822): skipping global notification
,I/iu.UploadsManager( 1783): num queued entries: 0
I/iu.UploadsManager( 1783): num updated entries: 0
I/iu.SyncManager( 1783): NEXT; no task
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599975 ms
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1783): onDestroy
,I/Babel   ( 3667): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  822): Start proc 3889:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/ActivityManager(  822): Killing 3533:com.android.musicfx/u0a18 (adj 15): empty #17
,I/GAv4    ( 3889): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3889):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3889):   adb logcat -s GAv4
,W/GAv4    ( 3889): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3889): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3889): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1225): Explicit concurrent mark sweep GC freed 28924(1578KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.105ms total 33.109ms
,I/WebViewFactory( 3889): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3889): Time to load native libraries: 3 ms (timestamps 3678-3681)
I/LibraryLoader( 3889): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3889): Binding Chromium to main looper Looper (main, tid 1) {16061ab7}
,I/LibraryLoader( 3889): Expected native library version number "",actual native library version number ""
,I/chromium( 3889): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3889): Initializing chromium process, singleProcess=true
,W/art     ( 3889): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 3889): ApplicationContext is null in ApplicationStatus
,W/chromium( 3889): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3889): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3889): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3889): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/NSApplication( 3889): Starting up...
,W/AudioManagerAndroid( 3889): Requires BLUETOOTH permission
,I/ActivityManager(  822): Start proc 3946:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  822): Killing 3562:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/art     (  822): Explicit concurrent mark sweep GC freed 33919(1651KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.873ms total 80.402ms
,I/ActivityManager(  822): Killing 2530:android.process.acore/u0a5 (adj 15): empty #17
,V/MusicLeanback( 3080): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3869): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3869): simOperator:  IMSI: null
D/SprintDMReceiver( 3869): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1783): onCreate
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599973 ms
,D/SystemUpdateService( 1783): onDestroy
,I/wpa_supplicant( 1095): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 1095): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1095): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1095): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 234
E/WifiStateMachine(  822):  RSSI mgmt: -49
E/WifiStateMachine(  822):  BE :  rx=158 tx=126 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=6 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 9312 tx_time=151 rx_time=394 scan_time=0
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/dhcpcd  ( 3977): version 5.5.6 starting
,I/dhcpcd  ( 3977): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3977): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3977): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 101,
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822):    accepting network in place of null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1075): CM callback handler got msg 524290
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3080): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3080): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  822): Start proc 4008:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 16:40:57 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454085657311], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454085657287]}
,I/ActivityManager(  822): Start proc 4025:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1075): CM callback handler got msg 524290
,D/PhoneInterfaceManager( 1385): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1385): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3869): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMHelper( 3869): simOperator:  IMSI: null
D/SprintDMReceiver( 3869): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1783): onCreate
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1783): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1783): num queued entries: 0
I/iu.UploadsManager( 1783): num updated entries: 0
I/SystemUpdateService( 1783): active receiver: enabled
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.SyncManager( 1783): NEXT; no task
,I/SystemUpdateService( 1783): showing system update notification
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/GAV2    ( 4025): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ValidateNoPeople(  822): skipping global notification
,I/BooksApp( 4025): Created application version: 3.6.8 (30608)
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599949 ms
,D/SystemUpdateService( 1783): onDestroy
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1783): [AccountUtils] Account not ready
W/Kids    ( 1783): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1783): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1783): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1783): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1783): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1783): 	at java.lang.Thread.run(Thread.java:818)
,V/Herrevad( 1783): NQAS connected
,I/Babel   ( 3667): connection state changed from DISCONNECTED to CONNECTED
,I/BooksSync( 4025): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4008): Connecting to GoogleApiClient
,D/GCM     ( 1225): Connected
,D/GCM     ( 1225): Message class com.google.f.a.a.p
,I/BooksConfig( 4025): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4008): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4008): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4008): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4008): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4025): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4025): Soft error
E/BooksSync( 4025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4025): Sync error
E/BooksSync( 4025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4025): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 77123, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1225): Explicit concurrent mark sweep GC freed 18042(977KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 843us total 20.094ms
,I/art     (  822): Explicit concurrent mark sweep GC freed 39679(1879KB) AllocSpace objects, 7(206KB) LOS objects, 31% free, 34MB/50MB, paused 1.394ms total 53.452ms
,E/KeepSync( 4008): IOException
E/KeepSync( 4008): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4008): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4008): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4008): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4008): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4008): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4008): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4008): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4008): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4008): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4008): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4008): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4008): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4008): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4008): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4008): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4008): 	... 10 more
W/KeepSync( 4008): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 76839, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3267): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3267): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3267): 	at jdm.a(PG:82)
E/HttpOperation( 3267): 	at jcs.o(PG:406)
E/HttpOperation( 3267): 	at jcn.a(PG:1379)
E/HttpOperation( 3267): 	at jcs.i(PG:143)
E/HttpOperation( 3267): 	at blb.a(PG:3937)
E/HttpOperation( 3267): 	at czp.a(PG:18188)
E/HttpOperation( 3267): 	at czp.a(PG:9081)
E/HttpOperation( 3267): 	at czq.run(PG:1686)
E/HttpOperation( 3267): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3267): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3267): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3267): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3267): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3267): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3267): 	at jdj.a(PG:4091)
E/HttpOperation( 3267): 	at jdj.a(PG:1125)
E/HttpOperation( 3267): 	at jdm.a(PG:77)
E/HttpOperation( 3267): 	... 12 more
E/HttpOperation( 3267): Caused by: faj: BadAuthentication
E/HttpOperation( 3267): 	at fal.a(PG:38)
E/HttpOperation( 3267): 	at jdj.a(PG:4089)
E/HttpOperation( 3267): 	... 14 more
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3267): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3267): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3267): 	at jdm.a(PG:82)
E/HttpOperation( 3267): 	at jcs.o(PG:406)
E/HttpOperation( 3267): 	at jcn.a(PG:1379)
E/HttpOperation( 3267): 	at jcs.i(PG:143)
E/HttpOperation( 3267): 	at hec.a(PG:42)
E/HttpOperation( 3267): 	at hee.a(PG:102)
E/HttpOperation( 3267): 	at czr.a(PG:65)
E/HttpOperation( 3267): 	at kka.a(PG:108)
E/HttpOperation( 3267): 	at czp.a(PG:19176)
E/HttpOperation( 3267): 	at czp.a(PG:9081)
E/HttpOperation( 3267): 	at czq.run(PG:1686)
E/HttpOperation( 3267): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3267): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3267): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3267): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3267): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3267): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3267): 	at jdj.a(PG:4091)
E/HttpOperation( 3267): 	at jdj.a(PG:1125)
E/HttpOperation( 3267): 	at jdm.a(PG:77)
E/HttpOperation( 3267): 	... 15 more
E/HttpOperation( 3267): Caused by: faj: BadAuthentication
E/HttpOperation( 3267): 	at fal.a(PG:38)
E/HttpOperation( 3267): 	at jdj.a(PG:4089)
E/HttpOperation( 3267): 	... 17 more
E/ExperimentLoader( 3267): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3267): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3267): 	at jdm.a(PG:82)
E/ExperimentLoader( 3267): 	at jcs.o(PG:406)
E/ExperimentLoader( 3267): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3267): 	at jcs.i(PG:143)
E/ExperimentLoader( 3267): 	at hec.a(PG:42)
E/ExperimentLoader( 3267): 	at hee.a(PG:102)
E/ExperimentLoader( 3267): 	at czr.a(PG:65)
E/ExperimentLoader( 3267): 	at kka.a(PG:108)
E/ExperimentLoader( 3267): 	at czp.a(PG:19176)
E/ExperimentLoader( 3267): 	at czp.a(PG:9081)
E/ExperimentLoader( 3267): 	at czq.run(PG:1686)
E/ExperimentLoader( 3267): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3267): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3267): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3267): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3267): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3267): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3267): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3267): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3267): 	at jdm.a(PG:77)
E/ExperimentLoader( 3267): 	... 15 more
E/ExperimentLoader( 3267): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3267): 	at fal.a(PG:38)
E/ExperimentLoader( 3267): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3267): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 77491, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 3641:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3779): 
,I/GAV2    ( 4025): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  822): Killing 3426:com.google.android.gm/u0a78 (adj 15): empty #17
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.69 rxSuccessRate=10.34 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3779): Test app app.js loaded
I/jxcore-log( 3779): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3779): BLE advertisement is supported
I/jxcore-log( 3779): 
,I/chromium( 3779): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.69 rxSuccessRate=10.34 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,D/Finsky  ( 3601): [384] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3601): [384] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3601): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3601): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3601): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.67 rxSuccessRate=4.15 targetRoamBSSID=any RSSI=-49
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3601): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3601): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3601): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.66 rxSuccessRate=2.28 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/BooksSync( 4025): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4008): Connecting to GoogleApiClient
,I/BooksConfig( 4025): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4008): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4008): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4008): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4008): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4025): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4025): Soft error
E/BooksSync( 4025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4025): Sync error
E/BooksSync( 4025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4025): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 117211, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4008): IOException
E/KeepSync( 4008): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4008): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4008): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4008): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4008): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4008): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4008): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4008): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4008): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4008): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4008): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4008): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4008): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4008): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4008): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4008): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4008): 	... 10 more
W/KeepSync( 4008): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 117592, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3267): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3267): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3267): 	at jdm.a(PG:82)
E/HttpOperation( 3267): 	at jcs.o(PG:406)
E/HttpOperation( 3267): 	at jcn.a(PG:1379)
E/HttpOperation( 3267): 	at jcs.i(PG:143)
E/HttpOperation( 3267): 	at blb.a(PG:3937)
E/HttpOperation( 3267): 	at czp.a(PG:18188)
E/HttpOperation( 3267): 	at czp.a(PG:9081)
E/HttpOperation( 3267): 	at czq.run(PG:1686)
E/HttpOperation( 3267): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3267): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3267): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3267): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3267): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3267): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3267): 	at jdj.a(PG:4091)
E/HttpOperation( 3267): 	at jdj.a(PG:1125)
E/HttpOperation( 3267): 	at jdm.a(PG:77)
E/HttpOperation( 3267): 	... 12 more
E/HttpOperation( 3267): Caused by: faj: BadAuthentication
E/HttpOperation( 3267): 	at fal.a(PG:38)
E/HttpOperation( 3267): 	at jdj.a(PG:4089)
E/HttpOperation( 3267): 	... 14 more
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3267): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3267): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3267): 	at jdm.a(PG:82)
E/HttpOperation( 3267): 	at jcs.o(PG:406)
E/HttpOperation( 3267): 	at jcn.a(PG:1379)
E/HttpOperation( 3267): 	at jcs.i(PG:143)
E/HttpOperation( 3267): 	at hec.a(PG:42)
E/HttpOperation( 3267): 	at hee.a(PG:102)
E/HttpOperation( 3267): 	at czr.a(PG:65)
E/HttpOperation( 3267): 	at kka.a(PG:108)
E/HttpOperation( 3267): 	at czp.a(PG:19176)
E/HttpOperation( 3267): 	at czp.a(PG:9081)
E/HttpOperation( 3267): 	at czq.run(PG:1686)
E/HttpOperation( 3267): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3267): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3267): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3267): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3267): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3267): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3267): 	at jdj.a(PG:4091)
E/HttpOperation( 3267): 	at jdj.a(PG:1125)
E/HttpOperation( 3267): 	at jdm.a(PG:77)
E/HttpOperation( 3267): 	... 15 more
E/HttpOperation( 3267): Caused by: faj: BadAuthentication
E/HttpOperation( 3267): 	at fal.a(PG:38)
E/HttpOperation( 3267): 	at jdj.a(PG:4089)
E/HttpOperation( 3267): 	... 17 more
,E/ExperimentLoader( 3267): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3267): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3267): 	at jdm.a(PG:82)
E/ExperimentLoader( 3267): 	at jcs.o(PG:406)
E/ExperimentLoader( 3267): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3267): 	at jcs.i(PG:143)
E/ExperimentLoader( 3267): 	at hec.a(PG:42)
E/ExperimentLoader( 3267): 	at hee.a(PG:102)
E/ExperimentLoader( 3267): 	at czr.a(PG:65)
E/ExperimentLoader( 3267): 	at kka.a(PG:108)
E/ExperimentLoader( 3267): ,	at czp.a(PG:19176)
E/ExperimentLoader( 3267): 	at czp.a(PG:9081)
E/ExperimentLoader( 3267): 	at czq.run(PG:1686)
E/ExperimentLoader( 3267): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3267): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3267): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3267): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3267): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3267): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3267): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3267): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3267): 	at jdm.a(PG:77)
E/ExperimentLoader( 3267): 	... 15 more
E/ExperimentLoader( 3267): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3267): 	at fal.a(PG:38)
E/ExperimentLoader( 3267): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3267): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 117836, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1265): run()
I/Keyboard.Facilitator( 1265): flushDynamicLanguageModels()
,I/art     (  822): Explicit concurrent mark sweep GC freed 51269(2MB) AllocSpace objects, 17(460KB) LOS objects, 31% free, 34MB/50MB, paused 1.584ms total 74.636ms
,I/ConfigService( 1225): onCreate,
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1225): Explicit concurrent mark sweep GC freed 33712(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.642ms total 53.912ms
,D/Finsky  ( 3601): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3601): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3601): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ConfigService( 1225): onDestroy
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.35 rxSuccessRate=2.40 targetRoamBSSID=any RSSI=-49
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (217 us)
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  822): Display changed displayId=0
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 280ms
,I/DreamManagerService(  822): Entering dreamland.
,I/PowerManagerService(  822): Dozing...
,I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 11
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1265): onFinishInput()
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): cancelDelayedScan -> 13
E/native  (  822): do suspend true
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
D/Finsky  ( 3601): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3601): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3601): [1] 5.onFinished: Scheduling replication attempt 5.
,I/kickstart(  872): STATUS: Received file 'm9kefs2'
I/kickstart(  872): STATUS: 950272 bytes transferred in 0.985056 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed,
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1225): Vacuum at: now=1454085750140 tag=VacuumService
,V/GoogleAuthProtoRequest( 3843): [416] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GoogleURLConnFactory( 1225): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ExperimentUpdateService( 3843): [416] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ExperimentUpdateService( 3843): [416] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3843): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3843): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3843): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3843): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3843): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3843): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3843): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3843): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3843): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3843): 	at com.a.a.k.run(SourceFile:110)
,E/Uploader( 1225): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1225): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1225): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1225): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1225): No account for auth token provided
,W/Uploader( 1225): No account for auth token provided
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1225): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1225): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1225): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1225): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1225): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1225): No account for auth token provided
,W/Uploader( 1225): No account for auth token provided
,W/Uploader( 1225): No account for auth token provided
,W/Uploader( 1225): No account for auth token provided
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1225): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1225): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1225): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1225): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1225): No account for auth token provided
,W/Uploader( 1225): No account for auth token provided
,W/Uploader( 1225): No account for auth token provided
,W/Uploader( 1225): No account for auth token provided
,W/Uploader( 1225): No account for auth token provided
,W/Uploader( 1225): No account for auth token provided
,W/Uploader( 1225):  no longer exists, so no auth token.
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1225): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1225): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1225): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1225): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1225): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1225): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1225): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1225): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1225): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1225): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/Finsky  ( 3601): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3601): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3601): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/BooksSync( 4025): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4025): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  822): Explicit concurrent mark sweep GC freed 40282(1882KB) AllocSpace objects, 7(394KB) LOS objects, 31% free, 34MB/50MB, paused 2.394ms total 92.643ms
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4025): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4025): Soft error
E/BooksSync( 4025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4025): Sync error
E/BooksSync( 4025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4025): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 195972, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3843): [417] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3843): [417] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3843): [417] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3843): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3843): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3843): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3843): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3843): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3843): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3843): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3843): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3843): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3843): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1265): run()
I/Keyboard.Facilitator( 1265): flushDynamicLanguageModels()
,I/ConfigService( 1225): onCreate
,V/KeepSync( 4008): Connecting to GoogleApiClient
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4008): GoogleApiClient failed to connect with error code: 4
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SQLiteLog( 4008): (284) automatic index on blob_node(is_deleted)
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 4008): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4008): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 3267): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3267): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3267): 	at jdm.a(PG:82)
E/HttpOperation( 3267): 	at jcs.o(PG:406)
E/HttpOperation( 3267): 	at jcn.a(PG:1379)
E/HttpOperation( 3267): 	at jcs.i(PG:143)
E/HttpOperation( 3267): 	at blb.a(PG:3937)
E/HttpOperation( 3267): 	at czp.a(PG:18188)
E/HttpOperation( 3267): 	at czp.a(PG:9081)
E/HttpOperation( 3267): 	at czq.run(PG:1686)
E/HttpOperation( 3267): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3267): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3267): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3267): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3267): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3267): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3267): 	at jdj.a(PG:4091)
E/HttpOperation( 3267): 	at jdj.a(PG:1125)
E/HttpOperation( 3267): 	at jdm.a(PG:77)
E/HttpOperation( 3267): 	... 12 more
E/HttpOperation( 3267): Caused by: faj: BadAuthentication
E/HttpOperation( 3267): 	at fal.a(PG:38)
E/HttpOperation( 3267): 	at jdj.a(PG:4089)
E/HttpOperation( 3267): 	... 14 more
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1225): Explicit concurrent mark sweep GC freed 72052(4MB) AllocSpace objects, 10(946KB) LOS objects, 36% free, 27MB/43MB, paused 1.643ms total 57.098ms
,E/HttpOperation( 3267): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3267): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3267): 	at jdm.a(PG:82)
E/HttpOperation( 3267): 	at jcs.o(PG:406)
E/HttpOperation( 3267): 	at jcn.a(PG:1379)
E/HttpOperation( 3267): 	at jcs.i(PG:143)
E/HttpOperation( 3267): 	at hec.a(PG:42)
E/HttpOperation( 3267): 	at hee.a(PG:102)
E/HttpOperation( 3267): 	at czr.a(PG:65)
E/HttpOperation( 3267): 	at kka.a(PG:108)
E/HttpOperation( 3267): 	at czp.a(PG:19176)
E/HttpOperation( 3267): 	at czp.a(PG:9081)
E/HttpOperation( 3267): 	at czq.run(PG:1686)
E/HttpOperation( 3267): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3267): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3267): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3267): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3267): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3267): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3267): 	at jdj.a(PG:4091)
E/HttpOperation( 3267): 	at jdj.a(PG:1125)
E/HttpOperation( 3267): 	at jdm.a(PG:77)
E/HttpOperation( 3267): 	... 15 more
E/HttpOperation( 3267): Caused by: faj: BadAuthentication
E/HttpOperation( 3267): 	at fal.a(PG:38)
E/HttpOperation( 3267): 	at jdj.a(PG:4089)
E/HttpOperation( 3267): 	... 17 more
E/ExperimentLoader( 3267): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3267): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3267): 	at jdm.a(PG:82)
E/ExperimentLoader( 3267): 	at jcs.o(PG:406)
E/ExperimentLoader( 3267): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3267): 	at jcs.i(PG:143)
E/ExperimentLoader( 3267): 	at hec.a(PG:42)
E/ExperimentLoader( 3267): 	at hee.a(PG:102)
E/ExperimentLoader( 3267): 	at czr.a(PG:65)
E/ExperimentLoader( 3267): 	at kka.a(PG:108)
E/ExperimentLoader( 3267): 	at czp.a(PG:19176)
E/ExperimentLoader( 3267): 	at czp.a(PG:9081)
E/ExperimentLoader( 3267): 	at czq.run(PG:1686)
E/ExperimentLoader( 3267): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3267): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3267): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3267): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3267): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3267): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3267): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3267): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3267): 	at jdm.a(PG:77)
E/ExperimentLoader( 3267): 	... 15 more
E/ExperimentLoader( 3267): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3267): 	at fal.a(PG:38)
E/ExperimentLoader( 3267): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3267): 	... 17 more
,E/KeepSync( 4008): IOException
E/KeepSync( 4008): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4008): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4008): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4008): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4008): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4008): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4008): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4008): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4008): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4008): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4008): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4008): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4008): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4008): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4008): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4008): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4008): 	... 10 more
W/KeepSync( 4008): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 196619, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 197081, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1225): onDestroy
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2168): Disconnected process message: 10, size: 0
,I/jxcore-log( 3779): TAP version 13
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # multiplex can send data
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 1 String should be length:200
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # enqueue and run in order
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 2 firstPromise setTimeout
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 3 firstPromise result
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 4 firstPromise testValue
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 5 secondPromise setTimeout
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 6 secondPromise result
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 7 secondPromise testValue
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 8 thirdPromise in promise
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 9 thirdPromise result
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 10 thirdPromise testValue
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # basic
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 11 sane
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # another
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown,
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 12 sane
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 13 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 14 null
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 15 (unnamed assert)
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 16 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 17 should not throw
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 18 (unnamed assert)
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 19 (unnamed assert)
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 20 should not throw
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 21 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 22 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 23 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # failed to get mobile documents path
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 24 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 25 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 26 should be equal
I/jxcore-log( 3779): 
I/jxcore-log( 3779): ok 27 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #init should register the networkChanged event
I/jxcore-log( 3779): ,
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 28 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startBroadcasting should throw on null device name
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 29 should throw
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 30 should throw
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 31 should throw
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 32 should throw
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startBroadcasting should throw on negative port
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 33 should throw
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startBroadcasting should throw on too large port
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 34 should throw
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 35 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 36 should be equal
I/jxcore-log( 3779): 
I/jxcore-log( 3779): ok 37 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 38 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 39 should be equal
I/jxcore-log( 3779): 
I/jxcore-log( 3779): ok 40 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 41 should be equal
,I/jxcore-log( 3779): 
I/jxcore-log( 3779): ok 42 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): ,
,I/jxcore-log( 3779): ok 43 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 44 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 45 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 46 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 47 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 48 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 49 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 50 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 51 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 52 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 53 should be equal
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866212.3779
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener,
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866212.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI,
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866212.3779
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085866212.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=ea7946f3-1a3e-4953-b05c-70bc50dd31e2,
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=ea7946f3-1a3e-4953-b05c-70bc50dd31e2, clientIf=5
,D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2168): message : 0,
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=9c41cff7-afa5-4fec-a124-72366c93b72b
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=9c41cff7-afa5-4fec-a124-72366c93b72b, clientIf=6
,D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2168): start scan with filters
,D/BtGatt.ScanManager( 2168): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothAdapterService( 2168): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e3c2bc9
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866212.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866212.3779","ra":"F8:CF:C5:D9:E5:61"}
,D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866212.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp",
,D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866212.3779
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/jxcore-log( 3779): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3779): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3779): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/BtGatt.AdvertiseManager( 2168): message : 1
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
,D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): Client app is not null!
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2168): stopScan() - queue size =1
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully
I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
D/BtGatt.ScanManager( 2168): stop scan
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
,I/jxcore-log( 3779): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866407.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866407.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866407.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085866407.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=37228276-d964-4587-b3ff-11742deaf251
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=37228276-d964-4587-b3ff-11742deaf251, clientIf=5
,D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=b9e1985f-e89a-48b8-af1b-7175b022e765
D/BtGatt.GattService( 2168): onClientRegistered() - UUID=b9e1985f-e89a-48b8-af1b-7175b022e765, clientIf=6
D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2168): start scan with filters
,D/BtGatt.ScanManager( 2168): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866407.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866407.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866407.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866407.3779
,I/wpa_supplicant( 1095): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
I/jxcore-log( 3779): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 3779): 
I/io.jxcore.node.ConnectionHelper( 3779): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
D/BtGatt.AdvertiseManager( 2168): message : 1
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2168): Client app is not null!
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2168): stopScan() - queue size =1
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): stop scan
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log( 3779): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866473.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866473.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866473.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085866473.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=724e2372-b566-4d09-ba63-b1edc08c8416
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=724e2372-b566-4d09-ba63-b1edc08c8416, clientIf=5
D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=e15ac9aa-2c87-4598-b105-6ac4e80544dc
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=e15ac9aa-2c87-4598-b105-6ac4e80544dc, clientIf=6
D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2168): start scan with filters
D/BtGatt.ScanManager( 2168): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866473.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866473.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866473.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866473.3779
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/wpa_supplicant( 1095): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
I/jxcore-log( 3779): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 3779): 
,I/io.jxcore.node.ConnectionHelper( 3779): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
,D/BtGatt.AdvertiseManager( 2168): message : 1
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
,D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2168): Client app is not null!
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2168): stopScan() - queue size =1
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3779): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
D/BtGatt.ScanManager( 2168): stop scan
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866534.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866534.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866534.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085866534.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=725ebcb1-2bc4-4bb1-bc0c-4e813577f668
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=725ebcb1-2bc4-4bb1-bc0c-4e813577f668, clientIf=5
D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=5850b699-cb26-40a9-afec-80d799f2c26a
D/BtGatt.GattService( 2168): onClientRegistered() - UUID=5850b699-cb26-40a9-afec-80d799f2c26a, clientIf=6
D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2168): start scan with filters
D/BtGatt.ScanManager( 2168): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866534.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866534.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866534.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 1095): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866534.3779
I/io.jxcore.node.ConnectionHelper( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/jxcore-log( 3779): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 3779): 
,I/io.jxcore.node.ConnectionHelper( 3779): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 2168): message : 1
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
,D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): Client app is not null!
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2168): stopScan() - queue size =1
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2168): stop scan
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
,I/jxcore-log( 3779): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866599.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866599.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866599.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085866599.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=4b24096f-5bf2-48f0-96c1-fad755e972d5
D/BtGatt.GattService( 2168): onClientRegistered() - UUID=4b24096f-5bf2-48f0-96c1-fad755e972d5, clientIf=5
,D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=49ead1cf-a659-4d2f-9055-89462e82df4e
D/BtGatt.GattService( 2168): onClientRegistered() - UUID=49ead1cf-a659-4d2f-9055-89462e82df4e, clientIf=6
,D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2168): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 2168): handling starting scan
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866599.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866599.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866599.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866599.3779
,I/wpa_supplicant( 1095): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
I/jxcore-log( 3779): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 3779): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3779): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
,I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
D/BtGatt.AdvertiseManager( 2168): message : 1
,D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2168): Client app is not null!
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2168): stopScan() - queue size =1
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): stop scan
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully
I/jxcore-log( 3779): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866670.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866670.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866670.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085866670.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=496c8ddf-5fff-4bc5-8d96-bc2516db7493,
D/BtGatt.GattService( 2168): onClientRegistered() - UUID=496c8ddf-5fff-4bc5-8d96-bc2516db7493, clientIf=5
D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising,
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=516face4-a7b6-4598-a63e-39950784f938
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=516face4-a7b6-4598-a63e-39950784f938, clientIf=6
D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2168): start scan with filters
,D/BtGatt.ScanManager( 2168): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866670.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866670.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866670.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3779): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866670.3779,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully
I/jxcore-log( 3779): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 3779): 
,I/wpa_supplicant( 1095): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3779): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
D/BtGatt.AdvertiseManager( 2168): message : 1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2168): Client app is not null!
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2168): stopScan() - queue size =1
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
,D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): stop scan
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3779): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866753.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866753.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866753.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085866753.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=8efbf648-7e9b-430b-a28c-60c40bb8a3cf
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=8efbf648-7e9b-430b-a28c-60c40bb8a3cf, clientIf=5
D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=f0faf4f9-b4c9-47f7-9ad0-d20ba08bd074
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=f0faf4f9-b4c9-47f7-9ad0-d20ba08bd074, clientIf=6
D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2168): start scan with filters
,D/BtGatt.ScanManager( 2168): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866753.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866753.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866753.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true,
I/wpa_supplicant( 1095): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866753.3779
I/io.jxcore.node.ConnectionHelper( 3779): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
I/jxcore-log( 3779): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 3779): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3779): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
,D/BtGatt.AdvertiseManager( 2168): message : 1
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
,D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): Client app is not null!
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2168): stopScan() - queue size =1
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...
,D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): stop scan
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3779): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866841.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866841.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866841.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085866841.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=78920270-cbb8-41ba-9855-f93b1ef78d70
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=78920270-cbb8-41ba-9855-f93b1ef78d70, clientIf=5
D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=9609a3e9-7e62-4b5a-90ec-2360e6516d12
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=9609a3e9-7e62-4b5a-90ec-2360e6516d12, clientIf=6
D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2168): start scan with filters
,D/BtGatt.ScanManager( 2168): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866841.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866841.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866841.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
I/wpa_supplicant( 1095): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866841.3779
,I/io.jxcore.node.ConnectionHelper( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...,
I/jxcore-log( 3779): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3779): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3779): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
,D/BtGatt.AdvertiseManager( 2168): message : 1
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
,D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2168): Client app is not null!
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2168): stopScan() - queue size =1
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
D/BtGatt.ScanManager( 2168): stop scan
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1,
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3779): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866917.3779
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866917.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866917.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085866917.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=f6ec538b-3fb5-4903-96b7-642ff4213fa7
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=f6ec538b-3fb5-4903-96b7-642ff4213fa7, clientIf=5
D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising,
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=4906cf1e-73cb-4398-8f28-5e0a57d2767a,
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=4906cf1e-73cb-4398-8f28-5e0a57d2767a, clientIf=6
D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6,
D/BtGatt.GattService( 2168): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 2168): handling starting scan
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866917.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866917.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866917.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...
,I/wpa_supplicant( 1095): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866917.3779
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
I/jxcore-log( 3779): ok 70 Should be able to call startBroadcasting without error
,I/jxcore-log( 3779): 
I/io.jxcore.node.ConnectionHelper( 3779): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
,I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 2168): message : 1
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
,D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): Client app is not null!
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2168): stopScan() - queue size =1
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully
,D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): stop scan
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log( 3779): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866990.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866990.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866990.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085866990.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=d088a39e-3b53-4661-9903-7a163f1d72f9
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=d088a39e-3b53-4661-9903-7a163f1d72f9, clientIf=5
D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=3e721b5c-777f-49fa-ab56-926260648c4e
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=3e721b5c-777f-49fa-ab56-926260648c4e, clientIf=6
,D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2168): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 2168): handling starting scan
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866990.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866990.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085866990.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0,
,D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085866990.3779
,I/wpa_supplicant( 1095): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
I/jxcore-log( 3779): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 3779): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3779): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
D/BtGatt.AdvertiseManager( 2168): message : 1
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2168): Client app is not null!
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2168): stopScan() - queue size =1
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2168): stop scan
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
,I/jxcore-log( 3779): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,V/GoogleAuthProtoRequest( 3843): [418] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1225): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1225): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1225): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1225): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1225): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3779): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 3779): 
,W/ExperimentUpdateService( 3843): [418] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3843): [418] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3843): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3843): 	at com.a.a.a.k.a(SourceFile:117),
W/ExperimentUpdateService( 3843): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3843): 	,at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3843): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3843): Caused by: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3843): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3843): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3843): ,	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3843): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085867693.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085867693.3779","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback,
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085867693.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085867693.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=44395a9d-322b-471c-96a4-75b6b74e47f6
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=44395a9d-322b-471c-96a4-75b6b74e47f6, clientIf=5
,D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=184e01d9-4870-4745-9c4d-40c7143cd5c5
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=184e01d9-4870-4745-9c4d-40c7143cd5c5, clientIf=6
D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2168): start scan with filters
,D/BtGatt.ScanManager( 2168): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085867693.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085867693.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085867693.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/wpa_supplicant( 1095): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085867693.3779
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED
I/jxcore-log( 3779): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 3779): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
,I/jxcore-log( 3779): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 3779): 
,I/io.jxcore.node.ConnectionHelper( 3779): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 2168): message : 1
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2168): Client app is not null!
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2168): stopScan() - queue size =1
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully
,D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): stop scan
I/jxcore-log( 3779): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085868106.3779,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085868106.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
,I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085868106.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085868106.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=218a1c25-24e6-4b12-9f82-27356f9f2e9c
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=218a1c25-24e6-4b12-9f82-27356f9f2e9c, clientIf=5
D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising,
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=44b9b9cb-ca83-4cfe-8567-aadebf1d9d98
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=44b9b9cb-ca83-4cfe-8567-aadebf1d9d98, clientIf=6
,D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6,
D/BtGatt.GattService( 2168): start scan with filters
D/BtGatt.ScanManager( 2168): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085868106.3779","ra":"F8:CF:C5:D9:E5:61"}
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085868106.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085868106.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...
,I/wpa_supplicant( 1095): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI,
I/io.jxcore.node.ConnectionHelper( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085868106.3779
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 3779): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 3779): 
I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3779): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 3779): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 3779): connect: Invalid Bluetooth address: foobar
,I/jxcore-log( 3779): ok 78 Should not connect to a bad peer
I/jxcore-log( 3779): 
,I/io.jxcore.node.ConnectionHelper( 3779): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 2168): message : 1
,D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
,D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2168): Client app is not null!
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2168): stopScan() - queue size =1
D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully,
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): stop scan
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log( 3779): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully
,I/jxcore-log( 3779): # setup
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # ThaliEmitter throws on disconnect to bad peer,
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085868418.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085868418.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3779): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): start: OK
,I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3779): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085868418.3779
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): createAdvertiseData: From: 1454085868418.3779 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3779): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3779): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2168): registerClient() - UUID=91c8bbb5-a189-4586-8f10-5a8eb53c1faa
D/BtGatt.GattService( 2168): onClientRegistered() - UUID=91c8bbb5-a189-4586-8f10-5a8eb53c1faa, clientIf=5
,D/BluetoothLeAdvertiser( 3779): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2168): message : 0
,D/BtGatt.AdvertiseManager( 2168): starting multi advertising
,D/BtGatt.GattService( 2168): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 2168): registerClient() - UUID=12ddc8c2-209f-42be-887d-09e750672a58
,D/BtGatt.GattService( 2168): onClientRegistered() - UUID=12ddc8c2-209f-42be-887d-09e750672a58, clientIf=6
D/BluetoothLeScanner( 3779): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2168): start scan with filters
,D/BtGatt.ScanManager( 2168): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2168): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3779): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085868418.3779","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454085868418.3779","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454085868418.3779","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454085868418.3779
,I/io.jxcore.node.ConnectionHelper( 3779): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3779): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/jxcore-log( 3779): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log( 3779): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local service added successfully,
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: STARTED,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started,
I/wpa_supplicant( 1095): P2P-FIND-STOPPED 
D/io.jxcore.node.ConnectionHelper( 3779): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 3779): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 3779): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3779): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: RESTARTING
I/jxcore-log( 3779): ok 81 Disconnect should fail to a non-existant peer 
I/jxcore-log( 3779): 
I/io.jxcore.node.ConnectionHelper( 3779): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3779): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3779): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3779): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3779): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 2168): message : 1
D/BtGatt.AdvertiseManager( 2168): stop advertise for client 5
,D/BtGatt.GattService( 2168): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2168): Client app is not null!
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2168): stopScan() - queue size =1
,D/BtGatt.GattService( 2168): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3779): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3779): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): onIsWifiPeerDiscoveryStartedChanged: false,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3779): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3779): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3779): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3779): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3779): Local services cleared successfully
D/BtGatt.GattService( 2168): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2168): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 2168): stop scan
,D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2168): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3779): P2P device discovery stopped successfully
,I/jxcore-log( 3779): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 3779): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3779): Service requests cleared successfully
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted,
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 83 host address should match
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 84 port should match
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 85 peer should be available
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 86 peer should be unavailable
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 87 when receiving the first byebye, the second USN should not be set yet
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 88 USN should have changed from the first one
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 89 when receiving the second byebye, the first USN should be already set
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # messages with invalid location or USN should be ignored
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
,I/jxcore-log( 3779): 
I/jxcore-log( 3779): ok 90 should not have emitted with invalid port
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): WARN thaliWifiInfrastructure Received an invalid USN value: 
I/jxcore-log( 3779): ,
I/jxcore-log( 3779): ok 91 should not have emitted with invalid USN
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # verify that Thali-specific messages are filtered correctly
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 92 irrelevant messages should be ignored
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 93 relevant messages should not be ignored
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 94 messages from this device should be ignored
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #start should fail if called twice in a row
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 95 specific error should be received
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,E/jxcore-log( 3779): ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
E/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 96 specific error should be received
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startUpdateAdvertisingAndListening should fail if router server starting fails
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): ,
,E/jxcore-log( 3779): ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
E/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 97 specific error expected
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 98 server should respond with code 200
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup,
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #stop can be called multiple times in a row,
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 99 should be in stopped state
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 100 should still be in stopped state
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #startListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 101 should be in listening state
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 102 should still be in listening state
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #stopListeningForAdvertisements can be called multiple times in a row,
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown,
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 103 should not be in listening state
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 104 should still not be in listening state
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # #stopAdvertisingAndListening can be called multiple times in a row
,I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): ,
,I/jxcore-log( 3779): ok 105 should not be in advertising state
,I/jxcore-log( 3779): 
I/jxcore-log( 3779): ok 106 should still not be in advertising state
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # setup,
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # functions are run from a queue in the right order,
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): # teardown
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): ok 107 call order must match
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): Tests Complete
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 3779): 
,I/jxcore-log( 3779): Toggling radios to false
I/jxcore-log( 3779): 
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  822): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@23008eca mBinding = false
,I/chromium( 3779): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3779): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothManagerService(  822): Message: 2
,D/BluetoothManagerService(  822): Sending off request.
,D/BluetoothAdapterState( 2168): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2168): Setting state to 13
I/BluetoothAdapterState( 2168): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2168): onBluetoothDisable()
I/BluetoothAdapterState( 2168): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiService(  822): setWifiEnabled: false pid=3779, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothAdapterProperties( 2168): Scan Mode:20
D/BluetoothAdapterState( 2168): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,W/bt-btif ( 2168): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/btif_config_util( 2168): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
E/BtOppRfcommListener( 2168): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 2168): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2168): L2CAP - PSM: 0x0017 not found for deregistration
V/BluetoothMapMasInstance( 2168): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2168): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2168): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2168): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489),
V/BluetoothMapMasInstance( 2168): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2168): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2168): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2168): ,	,at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  822): Bluetooth State Change Intent: 12 -> 13
D/BluetoothMapService( 2168): onReceive
D/BluetoothMapService( 2168): STATE_TURNING_OFF
D/BluetoothMapService( 2168): MAP Service closeService in
D/BluetoothMapMasInstance( 2168): MAP Service shutdown
,I/BtOppRfcommListener( 2168): stopping Accept Thread
I/BtOppRfcommListener( 2168): BluetoothSocket listen thread finished
,I/jxcore-log( 3779): Radios toggled
I/jxcore-log( 3779): 
I/jxcore-log( 3779): ****TEST TOOK:  ms ****
I/jxcore-log( 3779): 
I/jxcore-log( 3779): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3779): 
E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  822): do suspend true
D/CommandListener(  354): Clearing all IP addresses on wlan0
V/NativeCrypto( 1225): Read error: ssl=0xb4887600: I/O error during system call, Connection timed out
V/NativeCrypto( 1225): SSL shutdown failed: ssl=0xb4887600: I/O error during system call, Broken pipe
D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
I/jxcore-log( 3779): Toggling radios to false
I/jxcore-log( 3779): 
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ActivityManager(  822): Start proc 4187:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  822): scanCount==0 - aborting
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  822): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@23008eca mBinding = false
D/BluetoothManagerService(  822): Message: 2
D/BluetoothManagerService(  822): Sending off request.
,D/WifiService(  822): setWifiEnabled: false pid=3779, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterState( 2168): CURRENT_STATE=PENDING, MESSAGE = USER_TURN_ON, isTurningOn=false, isTurningOff=true,
I/BluetoothAdapterState( 2168): CURRENT_STATE=PENDING: Alreadying turning off bluetooth... Ignoring USER_TURN_OFF...
I/jxcore-log( 3779): Radios toggled
I/jxcore-log( 3779): 
,D/WifiScanningService(  822): SCAN_AVAILABLE : 1
D/RttService(  822): SCAN_AVAILABLE : 1
D/WifiScanningService(  822): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  822): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  822): DefaultState
,D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
,E/native  (  822): do suspend true
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  822): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1075): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Disconnected - quitting
,D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent,
,D/Tethering(  822): MasterInitialState.processMessage what=3,
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1385): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1385): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,W/ContextImpl( 4187): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1500cd96:true
,I/wpa_supplicant( 1095): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 1095): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,W/bt-btif ( 2168): ag scb idx 1 not allocated
E/bt-btif ( 2168): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2168): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2168): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2168): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2168): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2168): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2168): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2168): RX termination
W/bt_userial( 2168): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2168): Leaving userial_read_thread()
D/bt_userial( 2168): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2168): hw_epilog_process
I/bt_userial_vendor( 2168): device fd = 53 close
,I/ActivityManager(  822): Start proc 4212:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,I/art     (  370): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 365us total 19.521ms
,D/LocalBluetoothProfileManager( 4187): Adding local MAP profile
D/BluetoothMap( 4187): Create BluetoothMap proxy object
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/AndroidRuntime( 4207): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,I/art     (  370): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 241us total 18.326ms
,D/AndroidRuntime( 4207): CheckJNI is OFF
I/art     (  822): Explicit concurrent mark sweep GC freed 44795(2MB) AllocSpace objects, 8(599KB) LOS objects, 31% free, 34MB/50MB, paused 4.064ms total 91.772ms
,D/LocalBluetoothProfileManager( 4187): LocalBluetoothProfileManager construction complete
,E/GpsLocationProvider(  822): No APN found to select.
,D/DockEventReceiver( 4187): finishStartingService: stopping service
,D/BluetoothInputDevice( 4187): Proxy object connected
,D/HidProfile( 4187): Bluetooth service connected
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 361us total 15.038ms
D/BluetoothPan( 4187): BluetoothPAN Proxy object connected
,D/PhoneInterfaceManager( 1385): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
D/PanProfile( 4187): Bluetooth service connected
E/PhoneInterfaceManager( 1385): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/BluetoothMap( 4187): Proxy object connected
,D/MapProfile( 4187): Bluetooth service connected
D/BluetoothMap( 4187): getConnectedDevices()
D/TelephonyManager(  822): getDataEnabled: retVal=false
D/BluetoothMap( 4187): Bluetooth is Not enabled
,I/ActivityManager(  822): Killing 2427:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/GKI_LINUX( 2168): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2168): GKI_exit_task 0 done
I/GKI_LINUX( 2168): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2168): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,E/GpsLocationProvider(  822): No APN found to select.
,D/HeadsetService( 2168): Received stop request...Stopping profile...
D/HeadsetStateMachine( 2168): Exit Disconnected: -1
,D/A2dpService( 2168): Received stop request...Stopping profile...
D/BluetoothHeadset(  822): Proxy object disconnected
,D/BluetoothHeadset(  822): Proxy object disconnected
D/BluetoothHeadset(  822): Proxy object disconnected
D/A2dpStateMachine( 2168): Exit Disconnected: -1
D/BluetoothHeadset( 1075): Proxy object disconnected
,D/BluetoothAdapterState( 2168): Stopping profile services that were post enabled
,D/BluetoothA2dp( 1075): Proxy object disconnected
,D/HidService( 2168): Received stop request...Stopping profile...,
D/BluetoothHeadset( 1385): Proxy object disconnected
D/BluetoothInputDevice( 1075): Proxy object disconnected
,D/BluetoothInputDevice( 4187): Proxy object disconnected
,D/HidProfile( 4187): Bluetooth service disconnected
D/BluetoothA2dp(  822): Proxy object disconnected
,D/HeadsetStateMachine( 2168): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2168): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2168): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 2168): Received stop request...Stopping profile...
D/PanService( 2168): Received stop request...Stopping profile...
D/BluetoothPan( 4187): BluetoothPAN Proxy object disconnected
D/PanProfile( 4187): Bluetooth service disconnected
D/BluetoothPan( 1075): BluetoothPAN Proxy object disconnected
D/BtGatt.DebugUtils( 2168): handleDebugAction() action=null
,D/BtGatt.GattService( 2168): Received stop request...Stopping profile...
D/BtGatt.GattService( 2168): stop()
D/BtGatt.AdvertiseManager( 2168): advertise clients cleared
D/AndroidRuntime( 4207): Calling main entry com.android.commands.pm.Pm
I/GKI_LINUX( 2168): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2168): GKI_exit_task 2 done
I/GKI_LINUX( 2168): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothMapService( 2168): Received stop request...Stopping profile...
,D/BluetoothMapService( 2168): stop()
D/BluetoothMapEmailAppObserver( 2168): deinitObservers()
D/BluetoothMapEmailAppObserver( 2168): removeReceiver()
D/BluetoothMap( 1075): Proxy object disconnected
,D/BluetoothMap( 4187): Proxy object disconnected
D/MapProfile( 4187): Bluetooth service disconnected
,W/BluetoothHidServiceJni( 2168): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2168): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2168): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2168): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2168): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 2168): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2168): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 2168): MAP Service closeService in
D/BluetoothAdapterState( 2168): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 2168): cleanup()
D/BluetoothMapService( 2168): MAP Service closeService in
D/BluetoothAdapterProperties( 2168): Setting state to 10
I/BluetoothAdapterState( 2168): Bluetooth adapter state changed: 13-> 10
I/BluetoothAdapterState( 2168): Entering OffState
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  822): Broadcasting onBluetoothStateChange(false) to 17 receivers.
D/BluetoothHeadset( 1385): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1075): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  822): onBluetoothStateChange: up=false
,D/BluetoothMap( 1075): onBluetoothStateChange: up=false
,D/BluetoothPbap( 4187): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
,D/BluetoothMap( 4187): onBluetoothStateChange: up=false
D/BluetoothHeadsetClient( 1075): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1075): 
E/BluetoothHeadsetClient( 1075): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@15f178a3
E/BluetoothHeadsetClient( 1075): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1075): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1075): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1075): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1075): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1075): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 4187): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1075): onBluetoothStateChange: up=false
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
D/BluetoothInputDevice( 1075): onBluetoothStateChange: up=false
I/ActivityManager(  822): Killing 3779:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  822): Skipping PackageSetting{268f9a4c com.example.hello/10273} due to missing metadata
,I/wpa_supplicant( 1095): wlan0: CTRL-EVENT-TERMINATING 
E/WifiMonitor(  822): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/WindowState(  822): WIN DEATH: Window{1005f253 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  822): Client connection lost with reason: 4
,W/ActivityManager(  822): Force removing ActivityRecord{b893718 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  822): Display changed displayId=0,
,D/BluetoothAvrcpController( 1075): onBluetoothStateChange: up=false
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,E/BluetoothAvrcpController( 1075): 
E/BluetoothAvrcpController( 1075): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@1ba437a0
E/BluetoothAvrcpController( 1075): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1075): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1075): 	,at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1075): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1075): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1075): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ActivityManager(  822): Spurious death for ProcessRecord{19bfca07 3779:com.test.thalitest/u0a265}, curProc for 3779: null
,I/Keyboard.Facilitator( 1265): resetDictionaries() : en_US
,W/Settings( 1809): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TaskPersister(  822): removeObsoleteFile: deleting file=28_task.xml
D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothA2dpSink( 1075): onBluetoothStateChange: up=false,
,E/BluetoothA2dpSink( 1075): 
E/BluetoothA2dpSink( 1075): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@339e9f59
E/BluetoothA2dpSink( 1075): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1075): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1075): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1075): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1075): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1075): 	at android.os.Binder.execTransact(Binder.java:446)
,I/Keyboard.Facilitator.DecoderInitializer( 1265): run()
,D/BluetoothManagerService(  822): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  822): Broadcasting onBluetoothServiceDown() to 7 receivers.
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,D/BluetoothManagerService(  822): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@23008eca mBinding = false
,D/BluetoothManagerService(  822): Sending unbind request.
,I/Decoder ( 1265): createOrResetDecoder
D/BluetoothManagerService(  822): Bluetooth State Change Intent: 13 -> 10
,W/Settings( 3667): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Tethering(  822): InitialState.processMessage what=4
,D/Tethering(  822): sendTetherStateChangedBroadcast 0, 0, 0
,I/GKI_LINUX( 2168): gki_task task_id=1 [BTIF] terminating
,I/art     ( 1075): Explicit concurrent mark sweep GC freed 58004(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 1.107ms total 72.429ms
,D/BluetoothAdapter( 1075): 169788003: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1075): 169788003: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2168): GKI_exit_task 1 done
I/GKI_LINUX( 2168): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2168): cleanupNative: return from cleanup
,I/art     ( 1542): Explicit concurrent mark sweep GC freed 1434(137KB) AllocSpace objects, 1(24KB) LOS objects, 37% free, 26MB/42MB, paused 1.327ms total 91.739ms
,I/art     ( 1542): WaitForGcToComplete blocked for 8.901ms for cause HeapTrim
D/BluetoothAdapter( 1075): 169788003: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 2168): System.exit called, status: 0
I/AndroidRuntime( 2168): VM exiting with result code 0, cleanup skipped.
,I/ConfigService( 1225): onCreate
,W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3779 uid 10265
I/Keyboard.Facilitator( 1265): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1265): run()
,D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1265): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1265): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1265): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1265): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1265): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1265): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1265): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1265): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1265): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1265): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1265): run()
I/StatsUtilsManager( 1265): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1265): shouldRecordStats() = Too Soon
,I/ActivityManager(  822): Process com.android.bluetooth (pid 2168) has died
,W/LocationOracleImpl( 1542): Best location was null
,I/HotwordRecognitionRnr( 1542): Starting hotword detection.
,I/MicrophoneInputStream( 1542): mic_starting com.google.android.apps.gsa.speech.audio.u@158c22bb
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 5005(364KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 894us total 24.400ms
I/AudioFlinger(  358): AudioFlinger's thread 0xb4d04000 ready to run
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1542): mic_started com.google.android.apps.gsa.speech.audio.u@158c22bb
,D/StrictMode( 4212): StrictMode policy violation; ~duration=529 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4212): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4212): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4212): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4212): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4212): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4212): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4212): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 4212): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 4212): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4212): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4212): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4212): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4212): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4212): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4212): StrictMode policy violation; ~duration=528 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4212): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4212): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4212): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4212): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4212): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4212): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4212): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4212): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4212): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4212): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4212): StrictMode policy violation; ~duration=526 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4212): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4212): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4212): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4212): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4212): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4212): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4212): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4212): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 4212): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4212): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4212): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4212): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4212): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4212): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4212): StrictMode policy violation; ~duration=512 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4212): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4212): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4212): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 4212): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4212): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4212): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4212): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4212): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4212): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4212): StrictMode policy violation; ~duration=502 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4212): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4212): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4212): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4212): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4212): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4212): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4212): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4212): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4212): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4212): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4212): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4212): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4212): StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 4212): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4212): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 4212): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 4212): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 4212): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 4212): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 4212): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 4212): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 4212): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 4212): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 4212): # via Binder call with stack:
D/StrictMode( 4212): android.os.StrictMode$LogStackTrace
D/StrictMode( 4212): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 4212): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 4212): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 4212): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 4212): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 4212): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 4212): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 4212): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 4212): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4212): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4212): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4212): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4212): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4212): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4212): StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4212): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4212): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4212): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4212): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4212): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4212): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4212): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 4212): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4212): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4212): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4212): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4212): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4212): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4212): StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4212): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4212): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4212): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4212): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4212): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4212): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4212): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4212): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4212): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4212): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4212): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4212): StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4212): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4212): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4212): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4212): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4212): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4212): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4212): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4212): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4212): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4212): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4212): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4212): StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4212): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4212): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4212): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4212): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4212): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4212): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4212): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 4212): 	at com.google.p.j.a(PG:121)
D/StrictMode( 4212): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 4212): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 4212): 	at com.google.p.e.a(PG:170)
D/StrictMode( 4212): 	at com.google.p.e.b(PG:21)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4212): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4212): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4212): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4212): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4212): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4212): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4212): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
D/Launcher.Workspace( 1408): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1408): 11683562 - stripEmptyScreens()
D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
W/com.google.a.a.a.b.a( 4212): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26b5b333:true
D/AuthorizationBluetoothService( 1225): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/art     (  822): Explicit concurrent mark sweep GC freed 16978(1127KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.479ms total 175.498ms
V/MusicLeanback( 3080): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/HotwordWorker( 1542): onReady
D/SprintDMReceiver( 3869): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3869): simOperator:  IMSI: null
D/SprintDMReceiver( 3869): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1783): onCreate
,I/art     ( 4207): System.exit called, status: 0
I/AndroidRuntime( 4207): VM exiting with result code 0.
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,I/iu.Environment( 1783): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1783): num queued entries: 0
,I/iu.UploadsManager( 1783): num updated entries: 0
I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599983 ms
,I/Babel   ( 3667): connection state changed from CONNECTED to DISCONNECTED
,I/iu.SyncManager( 1783): NEXT; no task
,D/SystemUpdateService( 1783): onDestroy
,V/MusicLeanback( 3080): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3869): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660740883
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,D/SprintDMHelper( 3869): simOperator:  IMSI: null
D/SprintDMReceiver( 3869): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1783): onCreate
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599981 ms
,D/SystemUpdateService( 1783): onDestroy
,D/BuaReceiver( 3492): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/ActivityManager(  822): Start proc 4277:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,E/SQLiteDatabase( 4277): Failed to open database '/data/data/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4277): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 4277): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/SQLiteDatabase( 4277): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteDatabase( 4277): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteDatabase( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4277): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4277): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4277): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4277): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 4277): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/SQLiteOpenHelper( 4277): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteOpenHelper( 4277): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteOpenHelper( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4277): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 4277): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/VoicemailCleanupService( 4277): Cleaning up data for package: com.test.thalitest
,E/SQLiteLog( 4277): (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,--------- beginning of crash
E/AndroidRuntime( 4277): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4277): Process: android.process.acore, PID: 4277
E/AndroidRuntime( 4277): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
E/AndroidRuntime( 4277): 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1068)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
E/AndroidRuntime( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/AndroidRuntime( 4277): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 4277): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/AndroidRuntime( 4277): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/AndroidRuntime( 4277): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4277): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4277): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 4277): Failed to open database '/data/data/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 4277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4277): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4277): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:181)
E/SQLiteDatabase( 4277): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/SQLiteDatabase( 4277): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( ,4277): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 4277): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/SQLiteDatabase( 4277): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/SQLiteDatabase( 4277): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4277): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4277): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4277): Sending signal. PID: 4277 SIG: 9
,I/ActivityManager(  822): Start proc 4298:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
E/lowmemorykiller(  256): Error writing /proc/4277/oom_score_adj; errno=22
,E/DropBoxManagerService(  822): Can't write: system_app_crash
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
,D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  822): Validating map...
,I/OpenGLRenderer(  822): Initialized EGL, version 1.4
,D/OpenGLRenderer(  822): Enabling debug mode 0
,I/ActivityManager(  822): Start proc 4319:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/ActivityManager(  822): Process android.process.acore (pid 4277) has died
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/SQLiteLog( 1225): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1225): Shutting down VM
E/AndroidRuntime( 1225): FATAL EXCEPTION: main
E/AndroidRuntime( 1225): Process: com.google.process.gapps, PID: 1225
E/AndroidRuntime( 1225): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1225): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 1225): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 1225): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 1225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1225): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1225): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 1225): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1225): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1225): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 1225): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 1225): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1225): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1225): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1225): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1225): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1225): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 1225): 	... 9 more
,E/DropBoxManagerService(  822): Can't write: system_app_crash,
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
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
,E/SQLiteDatabase( 4319): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4319): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4319): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4319): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4319): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4319): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4319): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4319): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4319): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4319): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4319): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4319): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4319): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4319): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4319): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4319): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 4319): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 4319): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4319): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4319): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4319): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4319): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4319): Process: com.android.keychain, PID: 4319
E/AndroidRuntime( 4319): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4319): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4319): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4319): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4319): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4319): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4319): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4319): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4319): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4319): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4319): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4319): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4319): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4319): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4319): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 4319): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396,)
E/AndroidRuntime( 4319): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4319): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4319): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4319): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
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
,I/HotwordDetector( 1542): Closing mic
I/MicrophoneInputStream( 1542): mic_close com.google.android.apps.gsa.speech.audio.u@158c22bb
,E/Search.SharedPreferencesProto( 1542): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,W/InputMethodManagerService(  822): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@ff73086 attribute=null, token = android.os.BinderProxy@2c89182
I/OpenGLRenderer(  822): Initialized EGL, version 1.4
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1542): Hotword detection finished
I/HotwordRecognitionRnr( 1542): Stopping hotword detection.
,W/LocationOracleImpl( 1542): Best location was null
,I/HotwordRecognitionRnr( 1542): Starting hotword detection.
I/MicrophoneInputStream( 1542): mic_starting com.google.android.apps.gsa.speech.audio.u@373c4f5f
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/AudioFlinger(  358): AudioFlinger's thread 0xb4d04000 ready to run
I/MicrophoneInputStream( 1542): mic_started com.google.android.apps.gsa.speech.audio.u@373c4f5f
,E/Search.SharedPreferencesProto( 1542): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
,D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
,E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,I/art     ( 1809): Explicit concurrent mark sweep GC freed 16170(978KB) AllocSpace objects, 9(144KB) LOS objects, 37% free, 26MB/42MB, paused 945us total 42.862ms,
,E/DataBuffer( 1809): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2600fa99),
I/HotwordDetector( 1542): Closing mic
I/MicrophoneInputStream( 1542): mic_close com.google.android.apps.gsa.speech.audio.u@373c4f5f
,E/Search.SharedPreferencesProto( 1542): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  822): Killing 3408:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1542): Hotword detection finished
,I/HotwordRecognitionRnr( 1542): Stopping hotword detection.
,E/native  ( 1265): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1265): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/ActivityManager(  822): Start proc 4361:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,E/SQLiteDatabase( 4361): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 4361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4361): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 4361): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/SQLiteDatabase( 4361): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteDatabase( 4361): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteDatabase( 4361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4361): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4361): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4361): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 4361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4361): 	at com.android.provider,s.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 4361): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/SQLiteOpenHelper( 4361): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteOpenHelper( 4361): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteOpenHelper( 4361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4361): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 4361): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4361): (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,E/AndroidRuntime( 4361): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4361): Process: android.process.acore, PID: 4361
E/AndroidRuntime( 4361): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
E/AndroidRuntime( 4361): 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1068)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
E/AndroidRuntime( 4361): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/AndroidRuntime( 4361): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 4361): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/AndroidRuntime( 4361): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/AndroidRuntime( 4361): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4361): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4361): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
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
,W/Icing   ( 1783): Usage reports not received in time.
,W/Icing   ( 1783): Usage reports not received in time.
,I/ActivityManager(  822): Killing 3388:com.android.providers.calendar/u0a3 (adj 15): empty #17
,E/QMI_FW  (  822): xport_send: Sendto failed for port 4608
,E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1,
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660740883
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/QMI_FW  (  822): xport_send: Sendto failed for port 4608
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660740883
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/QMI_FW  (  822): xport_send: Sendto failed for port 4608
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660740883
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/kickstart(  872): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
E/kickstart(  872): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  872): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb0
I/Atfwd_Daemon(  377): Modem Out Of Service --> Release ATCOP service client handles, if any
I/Atfwd_Daemon(  377): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb4
E/ThermalEngine(  367): qmi_clnt_error_cb: with error -2 called for clnt FUSION
I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb7
E/ThermalEngine(  367): modem_clnt_error_cb: with -2 called for clnt 0x7
I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb3
D/        (  358): csd_client_error_cb: error -2 cb_data 0xb547e060
I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb2
I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb6
I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb5
I/Atfwd_Daemon(  377): Received sys_event: 2 from QMI devId: rmnet_usb1
D/        (  358): csd_client_error_cb: MDM reset
E/        (  358): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
E/        (  358): csd_service_deinit: Error -1 deiniting CSD
,I/ThermalEngine(  367): qmi: Instance id 157 for fusion TS
,E/ThermalEngine(  367): qmi_clnt_error_cb: with error -2 called for clnt MODEM
,E/LocSvc_ApiV02(  822): E/void LocApiV02::errorCb(locClientHandleType, locClientErrorEnumType):2688]: Service unavailable error
E/LocSvc_ApiV02(  822): E/void LocApiV02::errorCb(locClientHandleType, locClientErrorEnumType):2688]: Service unavailable error
,E/        (  358): csd_service_deinit: notifier handle release rc:0
,D/        (  358): csd_service_init: qmi_client_notifier_init() successful
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0

```
