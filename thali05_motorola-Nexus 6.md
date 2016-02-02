#### Test 575312435db8e90_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  820): Waited long enough for: ServiceRecord{2ae51444 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,--------- beginning of main
D/AndroidRuntime( 3612): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3612): CheckJNI is OFF
D/AndroidRuntime( 3612): Calling main entry com.android.commands.am.Am
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{351ff60 token=Token{1d9e8763 ActivityRecord{12d5f192 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  820): Adding window Window{236770d5 u0 Starting com.test.thalitest} at 2 of 7 (after Window{19e4b943 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3612): Shutting down VM
I/HotwordDetector( 1497): Closing mic
I/MicrophoneInputStream( 1497): mic_close com.google.android.apps.gsa.speech.audio.u@28228d8a
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/ActivityManager(  820): Start proc 3626:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1497): Hotword detection finished
I/HotwordRecognitionRnr( 1497): Stopping hotword detection.
I/ActivityManager(  820): Killing 3242:com.android.chrome/u0a40 (adj 15): empty #17
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1702950163
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3626): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3626): Time to load native libraries: 3 ms (timestamps 2114-2117)
I/LibraryLoader( 3626): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3626): Binding Chromium to main looper Looper (main, tid 1) {ca91ddd}
,I/LibraryLoader( 3626): Expected native library version number "",actual native library version number ""
I/chromium( 3626): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3626): Initializing chromium process, singleProcess=true
,W/art     ( 3626): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3626): ApplicationContext is null in ApplicationStatus
,W/chromium( 3626): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3626): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3626): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3626): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e24daf:true
,W/art     ( 3626): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3626): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3626): CordovaWebView is running on device made by: motorola
,W/art     ( 3626): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3626): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3626): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3626): Validating map...
,V/WindowManager(  820): Adding window Window{3148009f u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{236770d5 u0 Starting com.test.thalitest})
,W/chromium( 3626): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3626): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3626): Enabling debug mode 0
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +683ms
,I/Keyboard.Facilitator( 1241): onFinishInput()
,W/BindingManager( 3626): Cannot call determinedVisibility() - never saw a connection for the pid: 3626
,D/JsMessageQueue( 3626): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3626): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576393856
,I/chromium( 3626): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3626): Initializing JXcore engine
W/jxcore-log( 3626): JXcore engine is ready
,W/Thread-386( 3680): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12750]" dev="sockfs" ino=12750 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-386( 3680): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-386( 3680): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11078]" dev="sockfs" ino=11078 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-386( 3680): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23564]" dev="sockfs" ino=23564 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3626): Starting JXcore engine
,I/ActivityManager(  820): Killing 3395:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,W/jxcore-log( 3626): Platform android
W/jxcore-log( 3626): 
W/jxcore-log( 3626): Process ARCH arm
W/jxcore-log( 3626): 
,I/ActivityManager(  820): Killing 2223:com.android.defcontainer/u0a7 (adj 15): empty #18
,I/jxcore-log( 3626): JXcore Cordova bridge is ready!
I/jxcore-log( 3626): 
W/jxcore-log( 3626): JXcore engine is started
,I/jxcore-log( 3626): Toggling radios to true
I/jxcore-log( 3626): 
,D/BluetoothAdapter( 3626): enable(): BT is already enabled..!,
,D/WifiService(  820): New client listening to asynchronous messages
,D/WifiService(  820): setWifiEnabled: true pid=3626, uid=10265,
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3626): Radios toggled
I/jxcore-log( 3626): 
,I/jxcore-log( 3626): My device name is: motorola-Nexus 6
I/jxcore-log( 3626): 
,I/wpa_supplicant( 1138): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1374): Read error: ssl=0xaeca8400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1374): SSL shutdown failed: ssl=0xaeca8400: I/O error during system call, Broken pipe
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  820): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,I/art     (  820): Explicit concurrent mark sweep GC freed 27647(1355KB) AllocSpace objects, 6(284KB) LOS objects, 32% free, 33MB/49MB, paused 1.470ms total 56.630ms
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
E/GpsLocationProvider(  820): No APN found to select.
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  820): MasterInitialState.processMessage what=3
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/WifiConfigStore(  820): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): will read network variables netId=0
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  820): MasterInitialState.processMessage what=3
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,E/WifiConfigStore(  820): will read network variables netId=0
,D/NetworkChangeNotifierAutoDetect( 1497): Network connectivity changed, type is: 6
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/MusicLeanback( 3077): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/Finsky  ( 3489): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3489): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3489): [1] 5.onFinished: Scheduling replication attempt 1.
,D/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/ActivityManager(  820): Start proc 3687:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 3687): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3687): simOperator:  IMSI: null
,D/SprintDMReceiver( 3687): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1777): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1777): onCreate
,D/SystemUpdateService( 1777): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1777): active receiver: enabled
I/SystemUpdateService( 1777): showing system update notification
,I/iu.Environment( 1777): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1777): num queued entries: 0
I/iu.UploadsManager( 1777): num updated entries: 0
,I/iu.SyncManager( 1777): NEXT; no task
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1777): retry (wakeup: false) in 3599986 ms
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1777): onDestroy
,I/Babel   ( 2789): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  820): Start proc 3707:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/ActivityManager(  820): Killing 3417:com.android.musicfx/u0a18 (adj 15): empty #17
,I/GAv4    ( 3707): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3707):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3707):   adb logcat -s GAv4
,W/GAv4    ( 3707): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3707): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3707): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3707): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3707): Time to load native libraries: 3 ms (timestamps 5652-5655)
I/LibraryLoader( 3707): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3707): Binding Chromium to main looper Looper (main, tid 1) {211e9dc8}
,I/LibraryLoader( 3707): Expected native library version number "",actual native library version number ""
,I/chromium( 3707): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3707): Initializing chromium process, singleProcess=true
,W/art     ( 3707): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 3707): ApplicationContext is null in ApplicationStatus
,W/chromium( 3707): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3707): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
,E/libEGL  ( 3707): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3707): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3707): Requires BLUETOOTH permission
,I/NSApplication( 3707): Starting up...
,I/ActivityManager(  820): Start proc 3763:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  820): Killing 3449:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/ActivityManager(  820): Killing 1419:android.process.acore/u0a5 (adj 15): empty #17
,V/MusicLeanback( 3077): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3687): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3687): simOperator:  IMSI: null
D/SprintDMReceiver( 3687): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1777): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) },
,D/SystemUpdateService( 1777): onCreate
,D/SystemUpdateService( 1777): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1777): active receiver: enabled
,I/SystemUpdateService( 1777): showing system update notification
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1777): retry (wakeup: false) in 3599967 ms
,D/SystemUpdateService( 1777): onDestroy
,I/wpa_supplicant( 1138): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 1138): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1138): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1138): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 2
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 203
E/WifiStateMachine(  820):  RSSI mgmt: -51
E/WifiStateMachine(  820):  BE :  rx=171 tx=151 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 10111 tx_time=154 rx_time=466 scan_time=0
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60,
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/dhcpcd  ( 3792): version 5.5.6 starting
,I/dhcpcd  ( 3792): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3792): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3792): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 101
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  820): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/NetworkMonitor( 3077): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1497): Network connectivity changed, type is: 2
V/MusicLeanback( 3077): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 3687): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3687): simOperator:  IMSI: null
,D/SprintDMReceiver( 3687): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1777): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1777): onCreate
,D/AlarmManagerService(  820): Setting time of day to sec=1454412272
W/AlarmManagerService(  820): Unable to set rtc to 1454412272: Invalid argument
,I/ActivityManager(  820): Start proc 3827:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 11:24:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454412272253], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454412272239]}
,D/SystemUpdateService( 1777): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Validated
,D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 322us total 36.754ms
,I/iu.Environment( 1777): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1777): num queued entries: 0
I/iu.UploadsManager( 1777): num updated entries: 0
I/iu.SyncManager( 1777): NEXT; no task
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 321us total 15.504ms
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 231us total 12.692ms
,I/SystemUpdateService( 1777): active receiver: enabled
,I/jxcore-log( 3626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3626): 
I/SystemUpdateService( 1777): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1777): retry (wakeup: false) in 3599957 ms
,I/ActivityManager(  820): Start proc 3857:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,D/SystemUpdateService( 1777): onDestroy
,I/Babel   ( 2789): connection state changed from DISCONNECTED to CONNECTED
,W/GAV2    ( 3827): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksApp( 3827): Created application version: 3.6.8 (30608)
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
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/BooksSync( 3827): Starting books sync for 61035162, extras: ade
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at blb.a(PG:3937)
E/HttpOperation( 3262): 	at czp.a(PG:18188)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 12 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 14 more
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at hec.a(PG:42)
E/HttpOperation( 3262): 	at hee.a(PG:102)
E/HttpOperation( 3262): 	at czr.a(PG:65)
E/HttpOperation( 3262): 	at kka.a(PG:108)
E/HttpOperation( 3262): 	at czp.a(PG:19176)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 15 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 17 more
E/ExperimentLoader( 3262): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): 	at jdm.a(PG:82)
E/ExperimentLoader( 3262): 	at jcs.o(PG:406)
E/ExperimentLoader( 3262): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3262): 	at jcs.i(PG:143)
E/ExperimentLoader( 3262): 	at hec.a(PG:42)
E/ExperimentLoader( 3262): 	at hee.a(PG:102)
E/ExperimentLoader( 3262): 	at czr.a(PG:65)
E/ExperimentLoader( 3262): 	at kka.a(PG:108)
E/ExperimentLoader( 3262): 	at czp.a(PG:19176)
E/ExperimentLoader( 3262): 	at czp.a(PG:9081)
E/ExperimentLoader( 3262): 	at czq.run(PG:1686)
E/ExperimentLoader( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3262): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3262): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3262): 	at jdm.a(PG:77)
E/ExperimentLoader( 3262): 	... 15 more
E/ExperimentLoader( 3262): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3262): 	at fal.a(PG:38)
E/ExperimentLoader( 3262): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3262): 	... 17 more
,D/GCM     ( 1374): Connected
D/GCM     ( 1374): Message class com.google.f.a.a.p
,I/art     ( 1374): Explicit concurrent mark sweep GC freed 25392(1428KB) AllocSpace objects, 6(661KB) LOS objects, 38% free, 26MB/42MB, paused 881us total 21.318ms
,I/BooksConfig( 3827): GmsCore Version = 7.8.99 (2134222-430)
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 75733, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 49014(2MB) AllocSpace objects, 7(112KB) LOS objects, 32% free, 33MB/49MB, paused 1.090ms total 51.016ms
,I/ActivityManager(  820): Start proc 3894:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimeService( 3894): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454412272780
D/        ( 3894): TimeServiceNative: User Time to be set is 1454412272780
D/QC-time-services( 3894): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3894): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 3894): Lib:time_genoff_operation: pargs->ts_val = 1454412272780
D/QC-time-services(  373): Daemon: Connection accepted:time_genoff
D/QC-time-services(  373): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454412272780
,D/QC-time-services(  373): Daemon:genoff_opr: Base = 2, val = 1454412272780, operation = 0
D/QC-time-services(  373): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/20/70 7:36:56
D/QC-time-services(  373): Daemon:Value read from RTC seconds = 14715416000
,D/QC-time-services(  373): Daemon:new time 1454412272780 
D/QC-time-services(  373): Daemon: delta 1439696856780 genoff 1439696856780 
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696856780 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services( 3894): Lib:time_genoff_operation: Send to server  passed!!,
,D/QC-time-services(  373): Updating the TOD offset,
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696856780 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,V/KeepSync( 3857): Connecting to GoogleApiClient
,E/BooksAccountManager( 3827): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3827): Soft error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3827): Sync error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3827): Finished books sync
E/QC-time-services(  373): Daemon:Update to modem bit set
D/QC-time-services(  373): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  373): Daemon: Base = 2, Value being sent to MODEM = 1138447472780
,E/QC-time-services( 3894): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  820): Killing 2950:com.google.android.gm/u0a78 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 76051, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/QC-time-services(  373): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  373): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/jxcore-log( 3626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3626): 
,I/jxcore-log( 3626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3626): 
,I/jxcore-log( 3626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3626): 
,I/jxcore-log( 3626): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3626): 
,I/ActivityManager(  820): Start proc 3917:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3857): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,I/GAv4    ( 3917): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3917):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3917):   adb logcat -s GAv4
,W/GAv4    ( 3917): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3917): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/GAv4    ( 3917): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Killing 3317:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1777): NQAS connected
,I/ActivityManager(  820): Start proc 3944:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3944): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/KeepSync( 3857): IOException
E/KeepSync( 3857): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3857): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3857): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3857): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3857): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3857): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3857): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3857): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3857): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3857): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3857): 	... 10 more
W/KeepSync( 3857): Sync result 2
,I/ActivityManager(  820): Killing 3531:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 76671, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/CalendarProvider2( 3944): Created com.android.providers.calendar.CalendarAlarmManager@44f4db4(com.android.providers.calendar.CalendarProvider2@ca91ddd)
,E/SQLiteLog( 3944): (284) automatic index on view_events(_id)
,I/CalendarProvider2( 3944): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3944): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.53 rxSuccessRate=10.77 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,I/GAV2    ( 3827): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3626): Test app app.js loaded
I/jxcore-log( 3626): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3626): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3626): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3626): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3626): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3626): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3626): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3626): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3626): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3626): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3626): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c56e9b added. We now have 1 listener(s)
,I/chromium( 3626): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3626): BLE advertisement is supported
I/jxcore-log( 3626): 
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.53 rxSuccessRate=10.77 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/ActivityManager(  820): Killing 3489:com.android.vending/u0a19 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3340:com.google.android.gms.wearable/u0a11 (adj 15): empty #18
,I/ActivityManager(  820): Start proc 3977:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,D/Finsky  ( 3977): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3977): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  820): Start proc 4013:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3977): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3977): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4013): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4013): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  820): Killing 3077:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/Finsky  ( 3977): [409] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,I/MultiDex( 4013): VM with version 2.1.0 has multidex support
I/MultiDex( 4013): install
I/MultiDex( 4013): VM has multidex support, MultiDex support library is disabled.
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3977): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3977): [1] 2.run: Finished loading 1 libraries.
,V/JNIHelp ( 4013): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 3977): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ProviderInstaller( 4013): Installed default security provider GmsCore_OpenSSL
,I/art     (  820): Explicit concurrent mark sweep GC freed 25769(1184KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 2.385ms total 84.258ms,
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1374): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1777): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/Finsky  ( 3977): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  820): Start proc 4041:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 1777): Restart initialization of location
,D/Finsky  ( 3977): [409] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,W/ResourcesManager( 4041): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4041): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1374): Explicit concurrent mark sweep GC freed 17724(1051KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.131ms total 40.896ms
,I/MultiDex( 4041): VM with version 2.1.0 has multidex support
I/MultiDex( 4041): install
I/MultiDex( 4041): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4041): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4041): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1374): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/WearableService( 4041): callingUid 10011, callindPid: 4041
,V/GmsCoreStatsServiceLauncher( 1777): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/LocationInitializer( 1777): Restart initialization of location
,E/MDM     ( 1801): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1801): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/Finsky  ( 3977): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/Finsky  ( 3977): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3977): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3977): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3977): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3977): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3977): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3977): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 1801): client connected with version: 7571000
,I/ActivityManager(  820): Killing 3687:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3707:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.30 rxSuccessRate=4.52 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3977): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3977): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3977): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.79 rxSuccessRate=5.05 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3977): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3977): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3977): [1] 5.onFinished: Scheduling replication attempt 3.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1241): run()
,I/Keyboard.Facilitator( 1241): flushDynamicLanguageModels()
,I/ConfigService( 1374): onCreate
,I/BooksSync( 3827): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3827): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3262): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at blb.a(PG:3937)
E/HttpOperation( 3262): 	at czp.a(PG:18188)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 12 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 14 more
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at hec.a(PG:42)
E/HttpOperation( 3262): 	at hee.a(PG:102)
E/HttpOperation( 3262): 	at czr.a(PG:65)
E/HttpOperation( 3262): 	at kka.a(PG:108)
E/HttpOperation( 3262): 	at czp.a(PG:19176)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 15 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 17 more
,E/ExperimentLoader( 3262): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): 	at jdm.a(PG:82)
E/ExperimentLoader( 3262): 	at jcs.o(PG:406)
E/ExperimentLoader( 3262): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3262): 	at jcs.i(PG:143)
E/ExperimentLoader( 3262): 	at hec.a(PG:42)
E/ExperimentLoader( 3262): 	at hee.a(PG:102)
E/ExperimentLoader( 3262): 	at czr.a(PG:65)
E/ExperimentLoader( 3262): 	at kka.a(PG:108)
E/ExperimentLoader( 3262): 	at czp.a(PG:19176)
E/ExperimentLoader( 3262): 	at czp.a(PG:9081)
E/ExperimentLoader( 3262): 	at czq.run(PG:1686)
E/ExperimentLoader( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3262): ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3262): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3262): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3262): 	at jdm.a(PG:77)
E/ExperimentLoader( 3262): 	... 15 more
E/ExperimentLoader( 3262): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3262): 	at fal.a(PG:38)
E/ExperimentLoader( 3262): ,	at jdj.a(PG:4089)
E/ExperimentLoader( 3262): 	... 17 more
,E/BooksAccountManager( 3827): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3827): Soft error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3827): Sync error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3827): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 109845, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  820): Explicit concurrent mark sweep GC freed 39005(1830KB) AllocSpace objects, 13(396KB) LOS objects, 32% free, 33MB/49MB, paused 1.645ms total 109.593ms
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 110833, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3857): Connecting to GoogleApiClient
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3857): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3857): IOException
E/KeepSync( 3857): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3857): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3857): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3857): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3857): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3857): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3857): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3857): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3857): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3857): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3857): 	... 10 more
W/KeepSync( 3857): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 112214, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1374): onDestroy
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.60 rxSuccessRate=2.67 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1374): Explicit concurrent mark sweep GC freed 36978(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.476ms total 64.556ms
,D/Finsky  ( 3977): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3977): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3977): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.35 rxSuccessRate=3.54 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (232 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  820): Display changed displayId=0
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
,D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  820): Excessive delay in setPowerMode(): 274ms
,I/DreamManagerService(  820): Entering dreamland.
,I/PowerManagerService(  820): Dozing...
I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 12
,E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1241): onFinishInput()
,E/WifiStateMachine(  820): cancelDelayedScan -> 14
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/native  (  820): do suspend true
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  870): STATUS: Received file 'm9kefs2'
I/kickstart(  870): STATUS: 950272 bytes transferred in 0.993923 seconds
,I/kickstart(  870): STATUS: Successfully downloaded files from target 
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  870): STATUS: Sahara protocol completed
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3977): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3977): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3977): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1374): Using platform SSLCertificateSocketFactory
,V/GoogleAuthProtoRequest( 3124): [305] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3124): [305] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3124): [305] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3124): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3124): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3124): 	at com.a.a.k.run(SourceFile:110)
,I/VacuumService( 1374): Vacuum at: now=1454412370442 tag=VacuumService
,I/GoogleURLConnFactory( 1374): Using platform SSLCertificateSocketFactory
,W/Uploader( 1374): No account for auth token provided
,W/Uploader( 1374): No account for auth token provided
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1374): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1374): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1374): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1374): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1374): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1374): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1374): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1374): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1374): No account for auth token provided
,I/art     (  820): Explicit concurrent mark sweep GC freed 44977(2MB) AllocSpace objects, 11(270KB) LOS objects, 31% free, 34MB/50MB, paused 1.398ms total 74.965ms
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1374): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1374): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,E/Uploader( 1374): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1374): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1374): No account for auth token provided
,W/Uploader( 1374): No account for auth token provided,
,W/Uploader( 1374): No account for auth token provided
,W/Uploader( 1374): No account for auth token provided
,W/Uploader( 1374): No account for auth token provided
,W/Uploader( 1374): No account for auth token provided
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,W/Uploader( 1374): No account for auth token provided
,W/Uploader( 1374):  no longer exists, so no auth token.
,W/Uploader( 1374): No account for auth token provided
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1374): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1374): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1374): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1374): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1374): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1374): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1374): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1374): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1374): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1374): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1374): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1374): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1374): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1374): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1374): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1374): ,	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1374): ,	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1374): No account for auth token provided
,W/Uploader( 1374): No account for auth token provided
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3977): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3977): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3977): [1] 5.onFinished: Giving up after 6 failures.
,I/BooksSync( 3827): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3827): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3827): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3827): Soft error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3827): Sync error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3827): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 194627, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1241): run()
I/Keyboard.Facilitator( 1241): flushDynamicLanguageModels()
,V/GoogleAuthProtoRequest( 3124): [306] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ConfigService( 1374): onCreate
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3124): [306] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3124): [306] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3124): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3124): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3124): 	at com.a.a.k.run(SourceFile:110)
,I/art     ( 1374): Explicit concurrent mark sweep GC freed 82815(4MB) AllocSpace objects, 10(767KB) LOS objects, 36% free, 28MB/44MB, paused 1.673ms total 70.051ms
,V/KeepSync( 3857): Connecting to GoogleApiClient
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1777): Handling authorization failure,
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
,E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1777): 	... 7 more
,E/HttpOperation( 3262): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at blb.a(PG:3937)
E/HttpOperation( 3262): 	at czp.a(PG:18188)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 12 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 14 more
V/KeepSync( 3857): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at hec.a(PG:42)
E/HttpOperation( 3262): 	at hee.a(PG:102)
E/HttpOperation( 3262): 	at czr.a(PG:65)
E/HttpOperation( 3262): 	at kka.a(PG:108)
E/HttpOperation( 3262): 	at czp.a(PG:19176)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 15 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 17 more
,E/ExperimentLoader( 3262): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): 	at jdm.a(PG:82)
E/ExperimentLoader( 3262): 	at jcs.o(PG:406)
E/ExperimentLoader( 3262): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3262): 	at jcs.i(PG:143)
E/ExperimentLoader( 3262): 	at hec.a(PG:42)
E/ExperimentLoader( 3262): 	at hee.a(PG:102)
E/ExperimentLoader( 3262): 	at czr.a(PG:65)
E/ExperimentLoader( 3262): 	at kka.a(PG:108)
E/ExperimentLoader( 3262): 	at czp.a(PG:19176)
E/ExperimentLoader( 3262): 	at czp.a(PG:9081)
E/ExperimentLoader( 3262): 	at czq.run(PG:1686)
E/ExperimentLoader( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3262): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3262): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3262): 	at jdm.a(PG:77)
E/ExperimentLoader( 3262): 	... 15 more
E/ExperimentLoader( 3262): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3262): 	at fal.a(PG:38)
E/ExperimentLoader( 3262): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3262): 	... 17 more
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 197113, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3857): IOException
E/KeepSync( 3857): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3857): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3857): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3857): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3857): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3857): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3857): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3857): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3857): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3857): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3857): 	... 10 more
,W/KeepSync( 3857): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 198218, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1374): onDestroy
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/BooksSync( 3827): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3827): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 34493(1514KB) AllocSpace objects, 7(394KB) LOS objects, 31% free, 34MB/50MB, paused 2.284ms total 89.315ms
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3827): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3827): Soft error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3827): Sync error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3827): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 315989, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/EventLogService( 1777): Opted in for usage reporting
,I/EventLogService( 1777): Aggregate from 1454410656580 (log), 1454410656580 (data)
,V/GoogleAuthProtoRequest( 3124): [307] a.<init>: mAccountName set to: thalitester@gmail.com
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@313260b3}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/EventLogAggregator( 1777): Unknown tag: snet_gcore
W/EventLogAggregator( 1777): Unknown tag: snet_launch_service
,W/ExperimentUpdateService( 3124): [307] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3124): [307] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3124): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3124): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3124): 	at com.a.a.k.run(SourceFile:110)
,I/ServiceDumpSys( 1777): dumping service [account]
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@313260b3}
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/KeepSync( 3857): Connecting to GoogleApiClient
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
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
,V/KeepSync( 3857): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at blb.a(PG:3937)
E/HttpOperation( 3262): 	at czp.a(PG:18188)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 12 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 14 more
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at hec.a(PG:42)
E/HttpOperation( 3262): 	at hee.a(PG:102)
E/HttpOperation( 3262): 	at czr.a(PG:65)
E/HttpOperation( 3262): 	at kka.a(PG:108)
E/HttpOperation( 3262): 	at czp.a(PG:19176)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 15 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 17 more
,E/ExperimentLoader( 3262): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): 	at jdm.a(PG:82)
E/ExperimentLoader( 3262): 	at jcs.o(PG:406)
E/ExperimentLoader( 3262): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3262): 	at jcs.i(PG:143)
E/ExperimentLoader( 3262): 	at hec.a(PG:42)
E/ExperimentLoader( 3262): 	at hee.a(PG:102)
E/ExperimentLoader( 3262): 	at czr.a(PG:65)
E/ExperimentLoader( 3262): 	at kka.a(PG:108)
E/ExperimentLoader( 3262): 	at czp.a(PG:19176)
E/ExperimentLoader( 3262): 	at czp.a(PG:9081)
E/ExperimentLoader( 3262): 	at czq.run(PG:1686)
E/ExperimentLoader( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3262): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3262): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3262): 	at jdm.a(PG:77)
E/ExperimentLoader( 3262): 	... 15 more
E/ExperimentLoader( 3262): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3262): 	at fal.a(PG:38)
E/ExperimentLoader( 3262): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3262): 	... 17 more
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3857): IOException
E/KeepSync( 3857): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3857): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3857): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3857): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3857): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3857): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3857): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3857): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3857): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3857): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3857): 	... 10 more
,W/KeepSync( 3857): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 352534, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 350733, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1374): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1374): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1374): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1374): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1374): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3977): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3977): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3977): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3977): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3977): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3977): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3977): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3977): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3124): [308] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3124): [308] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3124): [308] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3124): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3124): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3124): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/art     ( 1374): Explicit concurrent mark sweep GC freed 50317(2MB) AllocSpace objects, 16(1764KB) LOS objects, 36% free, 27MB/43MB, paused 1.359ms total 42.521ms
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/BooksSync( 3827): Starting books sync for 61035162, extras: ade
,I/art     (  820): Explicit concurrent mark sweep GC freed 34336(1633KB) AllocSpace objects, 14(789KB) LOS objects, 31% free, 34MB/50MB, paused 1.618ms total 102.057ms
,I/BooksConfig( 3827): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3827): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3827): Soft error,
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3827): Sync error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3827): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 558607, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at blb.a(PG:3937)
E/HttpOperation( 3262): 	at czp.a(PG:18188)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 12 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 14 more
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at hec.a(PG:42)
E/HttpOperation( 3262): 	at hee.a(PG:102)
E/HttpOperation( 3262): 	at czr.a(PG:65)
E/HttpOperation( 3262): 	at kka.a(PG:108)
E/HttpOperation( 3262): 	at czp.a(PG:19176)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 15 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 17 more
,E/ExperimentLoader( 3262): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): 	at jdm.a(PG:82)
E/ExperimentLoader( 3262): 	at jcs.o(PG:406)
E/ExperimentLoader( 3262): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3262): 	at jcs.i(PG:143)
E/ExperimentLoader( 3262): 	at hec.a(PG:42)
E/ExperimentLoader( 3262): 	at hee.a(PG:102)
E/ExperimentLoader( 3262): 	at czr.a(PG:65)
E/ExperimentLoader( 3262): 	at kka.a(PG:108)
E/ExperimentLoader( 3262): 	at czp.a(PG:19176)
E/ExperimentLoader( 3262): 	at czp.a(PG:9081)
E/ExperimentLoader( 3262): 	at czq.run(PG:1686)
E/ExperimentLoader( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3262): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3262): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3262): 	at jdm.a(PG:77)
E/ExperimentLoader( 3262): 	... 15 more
E/ExperimentLoader( 3262): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3262): 	at fal.a(PG:38)
E/ExperimentLoader( 3262): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3262): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 628076, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3857): Connecting to GoogleApiClient
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3857): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3857): IOException
E/KeepSync( 3857): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3857): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3857): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3857): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3857): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3857): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3857): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3857): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3857): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3857): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3857): 	... 10 more
W/KeepSync( 3857): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 631630, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3124): [309] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3124): [309] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3124): [309] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3124): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3124): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3124): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2125): Stopping oneshot timer
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/BooksSync( 3827): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3827): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3827): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3827): Soft error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3827): Sync error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3827): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1043075, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/GCM     ( 1374): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/art     (  820): Explicit concurrent mark sweep GC freed 46367(2MB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 1.460ms total 74.181ms
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1374): Explicit concurrent mark sweep GC freed 65585(3MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 1.854ms total 68.799ms
,E/HttpOperation( 3262): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at blb.a(PG:3937)
E/HttpOperation( 3262): 	at czp.a(PG:18188)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 12 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 14 more
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at hec.a(PG:42)
E/HttpOperation( 3262): 	at hee.a(PG:102)
E/HttpOperation( 3262): 	at czr.a(PG:65)
E/HttpOperation( 3262): 	at kka.a(PG:108)
E/HttpOperation( 3262): 	at czp.a(PG:19176)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 15 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 17 more
,E/ExperimentLoader( 3262): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): 	at jdm.a(PG:82)
E/ExperimentLoader( 3262): 	at jcs.o(PG:406)
E/ExperimentLoader( 3262): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3262): 	at jcs.i(PG:143)
E/ExperimentLoader( 3262): 	at hec.a(PG:42)
E/ExperimentLoader( 3262): 	at hee.a(PG:102)
E/ExperimentLoader( 3262): 	at czr.a(PG:65)
E/ExperimentLoader( 3262): 	at kka.a(PG:108)
E/ExperimentLoader( 3262): 	at czp.a(PG:19176)
,E/ExperimentLoader( 3262): 	at czp.a(PG:9081)
E/ExperimentLoader( 3262): 	at czq.run(PG:1686)
E/ExperimentLoader( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3262): 	,at jdj.a(PG:4091)
E/ExperimentLoader( 3262): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3262): 	at jdm.a(PG:77)
E/ExperimentLoader( 3262): 	... 15 more
E/ExperimentLoader( 3262): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3262): 	at fal.a(PG:38)
E/ExperimentLoader( 3262): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3262): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1131406, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3124): [310] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3124): [310] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3124): [310] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3124): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3124): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3124): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3857): Connecting to GoogleApiClient
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3857): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3857): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3857): IOException
E/KeepSync( 3857): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3857): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3857): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3857): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3857): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3857): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3857): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3857): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3857): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3857): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3857): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3857): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3857): 	... 10 more
W/KeepSync( 3857): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1168550, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/UsageStatsService(  820): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2125): Stopping oneshot timer
,I/ProcessStatsService(  820): Prepared write state in 31ms
,I/ProcessStatsService(  820): Pruning old procstats: /data/system/procstats/state-2016-02-01-11-30-00.bin
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/ActivityManager(  820): Killing 1497:com.google.android.googlequicksearchbox:search/u0a28 (adj 13): empty for 1824s
,D/WifiService(  820): Client connection lost with reason: 4
,I/ActivityManager(  820): Killing 2415:com.google.android.calendar/u0a37 (adj 13): empty for 1825s
,I/ActivityManager(  820): Killing 3944:com.android.providers.calendar/u0a3 (adj 13): empty for 1825s
,I/ActivityManager(  820): Killing 2789:com.google.android.talk/u0a61 (adj 13): empty for 1826s
,I/ActivityManager(  820): Killing 3284:com.google.android.apps.photos/u0a71 (adj 13): empty for 1826s
,I/ActivityManager(  820): Killing 3894:com.qualcomm.timeservice/1000 (adj 15): empty for 1827s
,I/ActivityManager(  820): Killing 3763:com.android.chrome/u0a40 (adj 15): empty for 1827s
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/BooksSync( 3827): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3827): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 52861(2MB) AllocSpace objects, 16(694KB) LOS objects, 31% free, 34MB/50MB, paused 2.581ms total 106.657ms
,E/BooksAccountManager( 3827): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3827): Soft error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3827): Sync error
E/BooksSync( 3827): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3827): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3827): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 2011759, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/Finsky  ( 3977): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1374): Message class com.google.f.a.a.i
,V/GoogleAuthProtoRequest( 3124): [311] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1777): Opted in for usage reporting
I/EventLogService( 1777): Aggregate from 1454412517412 (log), 1454412517412 (data)
,I/ServiceDumpSys( 1777): dumping service [account]
,I/art     ( 1374): Explicit concurrent mark sweep GC freed 82529(3MB) AllocSpace objects, 8(882KB) LOS objects, 36% free, 27MB/43MB, paused 2.098ms total 61.242ms
,W/Finsky  ( 3977): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3124): [311] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3124): [311] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3124): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3124): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3124): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.a.a.a(SourceFile:167),
W/ExperimentUpdateService( 3124): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3124): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3977): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3977): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3977): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3977): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3977): [1] DailyHygiene.reschedule: Scheduling new run in 82 minutes (failures=3)
,D/DeviceConnectionService( 1801): client connected with version: 7571000
,I/GoogleURLConnFactory( 1777): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at blb.a(PG:3937)
E/HttpOperation( 3262): 	at czp.a(PG:18188)
E/HttpOperation( 3262): 	at czp.a(PG:9087)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 12 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 14 more
,W/GLSActivity( 1374): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1374): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1374): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1374): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1374): 	at android.os.Binder.execTransact(Binder.java:446)
,W/SubscribedFeeds( 1777): Hard error
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 2137527, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 2167905, reason: Periodic
,I/ActivityManager(  820): Start proc 4536:com.google.android.calendar/u0a37 for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService
,E/SQLiteLog( 4536): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  820): Start proc 4558:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at blb.a(PG:3937)
E/HttpOperation( 3262): 	at czp.a(PG:18188)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 12 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 14 more
,W/ResourcesManager( 4558): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at hec.a(PG:42)
E/HttpOperation( 3262): 	at hee.a(PG:102)
E/HttpOperation( 3262): 	at czr.a(PG:65)
E/HttpOperation( 3262): 	at kka.a(PG:108)
E/HttpOperation( 3262): 	at czp.a(PG:19176)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 15 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 17 more
,E/ExperimentLoader( 3262): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): 	at jdm.a(PG:82)
E/ExperimentLoader( 3262): 	at jcs.o(PG:406)
E/ExperimentLoader( 3262): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3262): 	at jcs.i(PG:143)
E/ExperimentLoader( 3262): 	at hec.a(PG:42)
E/ExperimentLoader( 3262): 	at hee.a(PG:102)
E/ExperimentLoader( 3262): 	at czr.a(PG:65)
E/ExperimentLoader( 3262): 	at kka.a(PG:108)
E/ExperimentLoader( 3262): 	at czp.a(PG:19176)
E/ExperimentLoader( 3262): 	at czp.a(PG:9081)
E/ExperimentLoader( 3262): 	at czq.run(PG:1686)
E/ExperimentLoader( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3262): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3262): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3262): 	at jdm.a(PG:77)
E/ExperimentLoader( 3262): 	... 15 more
E/ExperimentLoader( 3262): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3262): 	at fal.a(PG:38)
E/ExperimentLoader( 3262): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3262): 	... 17 more
,I/CalendarProvider2( 4558): Created com.android.providers.calendar.CalendarAlarmManager@44f4db4(com.android.providers.calendar.CalendarProvider2@ca91ddd)
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1131889, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  820): Explicit concurrent mark sweep GC freed 31584(1601KB) AllocSpace objects, 17(460KB) LOS objects, 31% free, 34MB/50MB, paused 1.926ms total 74.276ms
,I/AnalyticsLogBase( 4536): PlayLogger.onLoggerConnected
,I/AnalyticsLogBase( 4536): PlayLogger.onLoggerConnected
,E/DataBuffer( 1801): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3b01c48d)
I/art     ( 1801): Explicit concurrent mark sweep GC freed 17609(1039KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.063ms total 28.408ms
,E/DataBuffer( 1801): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3bb1d642)
,E/DataBuffer( 1801): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@130c8653)
,W/ResourcesManager( 4536): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4536): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GCoreUlr( 1801): Uploading GCM registration ID for account#2#
,V/JNIHelp ( 4536): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/BaseAppContext( 1801): Using Auth Proxy for data requests.
,I/ProviderInstaller( 4536): Installed default security provider GmsCore_OpenSSL
,W/AbstractGoogleClient( 4536): Application name is not set. Call Builder#setApplicationName.
,I/GLSUser ( 1801): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1801): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/GCoreUlr( 1801): 
E/GCoreUlr( 1801): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1801): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1801): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1801): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1801): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1801): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1801): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1801): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1801): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1801): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1801): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1801): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1801): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1801): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1801): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1801): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 2137549, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 2168829, reason: Periodic
,I/ActivityManager(  820): Start proc 4588:com.google.android.gm/u0a78 for service com.google.android.gm/.provider.MailSyncAdapterService
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/CalendarSyncAdapter( 4536): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 4536): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 4536): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 4536): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 4536): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 4536): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 4536): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 4536): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 4536): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2382)
E/CalendarSyncAdapter( 4536): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1850)
E/CalendarSyncAdapter( 4536): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:1733)
E/CalendarSyncAdapter( 4536): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:503)
E/CalendarSyncAdapter( 4536): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:392)
E/CalendarSyncAdapter( 4536): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 4536): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 4536): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 4536): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 4536): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 4536): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 4536): 	... 12 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 2137544, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 2169126, reason: Periodic
,I/Gmail   ( 4588): getAccountsCursor
,I/ActivityManager(  820): Start proc 4611:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,D/ActivityThread( 4588): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 399us total 20.064ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 351us total 14.411ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 487us total 21.913ms
,I/ActivityManager(  820): Start proc 4628:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,I/[@@    ] SyncAdapterProxy( 1374): Delagator disabled, using the (deprecated) GData sync adapter
,W/GAV2    ( 4588): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Exchange( 4628): EasService.onCreate
,W/ActivityManager(  820): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 4628): RestartPingTask
,I/Gmail   ( 4588): Observing account changes for notifications
,I/Exchange( 4628): RestartPingsTask did not start any pings.
I/Exchange( 4628): PSS stopIfIdle
I/Exchange( 4628): PSS has no active accounts; stopping service.
,W/Gmail   ( 4588): Sync started for account: account:61035162
,I/ContactLocale( 4611): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/Gmail   ( 4588): getAccountsCursor
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 4628): onDestroy
,I/ActivityManager(  820): Killing 4013:com.google.android.gms:car/u0a11 (adj 15): empty for 2048s
,E/SQLiteLog( 4588): (283) recovered 22 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 4588): notifyAccountChanged
,I/Gmail   ( 4588): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4588): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4588): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4588): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/art     ( 1374): Explicit concurrent mark sweep GC freed 45174(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 993us total 29.074ms
,I/Gmail   ( 4588): notifyAccountChanged
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1374): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1374): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1374): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1374): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1374): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 1374): innerSync failed,
D/ContactsSyncAdapter( 1374): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1374): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
,D/ContactsSyncAdapter( 1374): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1374): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1374): 	at com.google.android.syncadapters.contacts.delegation.SyncAdapterProxy.onPerformLoggedSync(SyncAdapterProxy.java:123)
D/ContactsSyncAdapter( 1374): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1374): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1374): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1374): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
D/ContactsSyncAdapter( 1374): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1374): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
D/ContactsSyncAdapter( 1374): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1374): 	at android.os.Binder.execTransact(Binder.java:446)
,I/CalendarProvider2( 4558): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager(  820): Killing 4041:com.google.android.gms.wearable/u0a11 (adj 15): empty for 2043s
,W/ContentResolver( 4558): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/Gmail   ( 4588): getAccountsCursor
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 2137562, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 2169650, reason: Periodic
,I/Gmail   ( 4588): getAccountsCursor
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4588): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4353, normalSync: true
,I/art     (  820): Explicit concurrent mark sweep GC freed 21875(934KB) AllocSpace objects, 3(142KB) LOS objects, 31% free, 34MB/50MB, paused 1.956ms total 53.618ms
,W/ResourcesManager( 4588): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4588): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 4588): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/ReminderSync( 1777): AuthError [T SyncAdapterThread-1:id=265:priority=5:group=main]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 2137567, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 2171229, reason: Periodic
,I/ProviderInstaller( 4588): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  820): Start proc 4679:com.google.android.apps.magazines/u0a67 for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1374): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1374): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1374): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1374): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1374): 	at android.os.Binder.execTransact(Binder.java:446)
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4    ( 4679): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4679):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4679):   adb logcat -s GAv4
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 4679): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4679): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GLSActivity( 1374): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1374): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1374): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1374): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1374): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GAv4    ( 4679): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Gmail   ( 4588): notifyAccountChanged
,I/Gmail   ( 4588): getAccountsCursor
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4588): notifyAccountChanged
,I/Gmail   ( 4588): getAccountsCursor
,W/Gmail   ( 4588): Sync complete for account: account:61035162
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 2137554, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 2170389, reason: Periodic
,I/ActivityManager(  820): Start proc 4716:com.android.chrome/u0a40 for service com.android.chrome/org.chromium.chrome.browser.sync.ChromeBrowserSyncAdapterService
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 4679): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/Finsky  ( 3977): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3977): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3977): [1] 5.onFinished: Scheduling replication attempt 1.
,I/LibraryLoader( 4679): Time to load native libraries: 3 ms (timestamps 9959-9962)
I/LibraryLoader( 4679): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4679): Binding Chromium to main looper Looper (main, tid 1) {3ce51d86}
,I/LibraryLoader( 4679): Expected native library version number "",actual native library version number ""
I/chromium( 4679): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4679): Initializing chromium process, singleProcess=true
,W/art     ( 4679): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4679): ApplicationContext is null in ApplicationStatus
,W/chromium( 4679): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4679): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4679): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 4679): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/DelayedSyncController( 4716): Delaying sync.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/AudioManagerAndroid( 4679): Requires BLUETOOTH permission
,I/NSApplication( 4679): Starting up...
,I/art     ( 1374): Explicit concurrent mark sweep GC freed 16948(978KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.260ms total 23.339ms
,I/SyncAdapterService( 4679): Ignoring sync request for non-current account
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.,
,I/ActivityManager(  820): Start proc 4760:com.google.android.music:main/u0a66 for service com.google.android.music/.sync.SyncAdapterService
,I/ActivityManager(  820): Start proc 4778:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,I/MusicStore( 4760): Database version: 120
,W/ResourcesManager( 4760): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4760): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4760): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4760): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4760): GMSCore installation verified
,I/ConfigStore( 4760): Config Database version: 1
,I/MediaRouter( 4760): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/ActivityManager(  820): Start proc 4803:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,I/GHttpClientFactory( 4760): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 4760): Using platform SSLCertificateSocketFactory
,I/NetworkMonitor( 4760): type=WIFI subType= reason=null isConnected=true
,I/MusicLifecycle( 4760): Sync started
,I/NetworkMonitor( 4760): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 4760): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  820): Explicit concurrent mark sweep GC freed 19595(801KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 1.637ms total 50.224ms
,I/GoogleURLConnFactory( 4760): Using platform SSLCertificateSocketFactory
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 4778): Sync request not initiated by GCP app. Dropping
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1777): [CredentialSyncAdapter] Unknown sync event.
,W/GLSActivity( 1374): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1374): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1374): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1374): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1374): 	at android.os.Binder.execTransact(Binder.java:446)
,I/MusicLifecycle( 4760): Sync ended
W/MusicSyncAdapter( 4760): Sync failed due to an authentication issue.
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 2137587, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 2172301, reason: Periodic
,I/MusicLeanback( 4760): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 4760): Stop autocaching.
,I/ActivityManager(  820): Start proc 4837:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,W/ResourcesManager( 4837): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4837): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 4837): VM with version 2.1.0 has multidex support
I/MultiDex( 4837): install
I/MultiDex( 4837): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4837): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4837): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1374): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1777): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 4837): callingUid 10011, callindPid: 4837
,D/LocationInitializer( 1777): Restart initialization of location
,E/MDM     ( 1801): [157] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 4760): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 4760): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAV2    ( 4536): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 4588): Thread[GAThread,5,main]: No campaign data found.
,I/MusicLeanback( 4760): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 4760): Stop autocaching.
,E/GmsUtils( 4760): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 4760): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  820): Killing 3857:com.google.android.keep/u0a79 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3917:com.google.android.deskclock/u0a44 (adj 15): empty #17
,V/GoogleAuthProtoRequest( 3124): [312] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3124): [313] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3124): [312] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3124): [312] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3124): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3124): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3124): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3124): [313] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3124): [313] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3124): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3124): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3124): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3124): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3977): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3977): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3977): [1] 5.onFinished: Scheduling replication attempt 2.
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1374): Explicit concurrent mark sweep GC freed 17994(936KB) AllocSpace objects, 8(882KB) LOS objects, 37% free, 26MB/42MB, paused 1.678ms total 52.431ms
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3977): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3977): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3977): [1] 5.onFinished: Scheduling replication attempt 3.
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 22281(946KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.820ms total 87.573ms
,E/HttpOperation( 3262): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at blb.a(PG:3937)
E/HttpOperation( 3262): 	at czp.a(PG:18188)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 12 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 14 more
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3262): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3262): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3262): 	at jdm.a(PG:82)
E/HttpOperation( 3262): 	at jcs.o(PG:406)
E/HttpOperation( 3262): 	at jcn.a(PG:1379)
E/HttpOperation( 3262): 	at jcs.i(PG:143)
E/HttpOperation( 3262): 	at hec.a(PG:42)
E/HttpOperation( 3262): 	at hee.a(PG:102)
E/HttpOperation( 3262): 	at czr.a(PG:65)
E/HttpOperation( 3262): 	at kka.a(PG:108)
E/HttpOperation( 3262): 	at czp.a(PG:19176)
E/HttpOperation( 3262): 	at czp.a(PG:9081)
E/HttpOperation( 3262): 	at czq.run(PG:1686)
E/HttpOperation( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3262): 	at jdj.a(PG:4091)
E/HttpOperation( 3262): 	at jdj.a(PG:1125)
E/HttpOperation( 3262): 	at jdm.a(PG:77)
E/HttpOperation( 3262): 	... 15 more
E/HttpOperation( 3262): Caused by: faj: BadAuthentication
E/HttpOperation( 3262): 	at fal.a(PG:38)
E/HttpOperation( 3262): 	at jdj.a(PG:4089)
E/HttpOperation( 3262): 	... 17 more
,E/ExperimentLoader( 3262): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3262): 	at jdm.a(PG:82)
E/ExperimentLoader( 3262): 	at jcs.o(PG:406)
E/ExperimentLoader( 3262): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3262): 	at jcs.i(PG:143)
E/ExperimentLoader( 3262): 	at hec.a(PG:42)
E/ExperimentLoader( 3262): 	at hee.a(PG:102)
E/ExperimentLoader( 3262): 	at czr.a(PG:65)
E/ExperimentLoader( 3262): 	at kka.a(PG:108)
E/ExperimentLoader( 3262): 	at czp.a(PG:19176)
E/ExperimentLoader( 3262): 	at czp.a(PG:9081)
E/ExperimentLoader( 3262): 	at czq.run(PG:1686)
E/ExperimentLoader( 3262): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3262): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3262): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3262): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3262): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3262): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3262): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3262): 	at jdm.a(PG:77)
E/ExperimentLoader( 3262): 	... 15 more
E/ExperimentLoader( 3262): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3262): 	at fal.a(PG:38)
E/ExperimentLoader( 3262): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3262): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 2169797, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3977): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3977): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3977): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ActivityManager(  820): Start proc 4896:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4896): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4896):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4896):   adb logcat -s GAv4
,W/GAv4    ( 4896): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4896): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4896): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Killing 3827:com.google.android.apps.books/u0a34 (adj 15): empty #17
,V/GoogleAuthProtoRequest( 3124): [314] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3124): [314] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3124): [314] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3124): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3124): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3124): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3124): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3124): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3977): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3977): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3977): [1] 5.onFinished: Scheduling replication attempt 5.
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/ActivityManager(  820): Start proc 4922:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,V/KeepSync( 4922): Connecting to GoogleApiClient
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4922): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4922): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4922): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4922): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1374): Explicit concurrent mark sweep GC freed 24291(1357KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.994ms total 29.262ms
,E/KeepSync( 4922): IOException
E/KeepSync( 4922): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4922): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4922): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4922): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4922): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4922): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4922): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4922): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4922): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4922): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4922): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4922): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4922): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4922): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4922): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4922): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4922): 	... 10 more
W/KeepSync( 4922): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 2211950, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 4628:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1374): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1374): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1374): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1374): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3977): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3977): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3977): [1] 5.onFinished: Giving up after 6 failures.
,I/wpa_supplicant( 1138): wlan0: WPA: Group rekeying completed with c0:ff:d4:d3:aa:4a [GTK=CCMP]
,I/jxcore-log( 3626): Toggling radios to false,
I/jxcore-log( 3626): 
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  820): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1b62ec34 mBinding = false
,D/BluetoothManagerService(  820): Message: 2
,D/BluetoothManagerService(  820): Sending off request.
,D/WifiService(  820): setWifiEnabled: false pid=3626, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothAdapterState( 2125): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2125): Setting state to 13
I/BluetoothAdapterState( 2125): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  820): Message: 60
,D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothAdapterProperties( 2125): onBluetoothDisable()
I/BluetoothAdapterState( 2125): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothMapService( 2125): onReceive
D/BluetoothMapService( 2125): STATE_TURNING_OFF
D/BluetoothMapService( 2125): MAP Service closeService in
D/BluetoothMapMasInstance( 2125): MAP Service shutdown
,V/BluetoothMapMasInstance( 2125): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2125): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2125): ,	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2125): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2125): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2125): ,	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2125): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2125): 	,at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
I/BtOppRfcommListener( 2125): stopping Accept Thread
,E/BtOppRfcommListener( 2125): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 2125): BluetoothSocket listen thread finished
,I/jxcore-log( 3626): Radios toggled
I/jxcore-log( 3626): 
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  820): do suspend true
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1374): Read error: ssl=0x9d018400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1374): SSL shutdown failed: ssl=0x9d018400: I/O error during system call, Broken pipe
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ActivityManager(  820): Start proc 4968:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/BluetoothAdapterProperties( 2125): Scan Mode:20
D/BluetoothAdapterState( 2125): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 2125): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
W/bt-btif ( 2125): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
W/bt-l2cap( 2125): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2125): L2CAP - PSM: 0x0017 not found for deregistration
,E/WifiStateMachine(  820): scanCount==0 - aborting
,D/WifiScanningService(  820): SCAN_AVAILABLE : 1
,D/RttService(  820): SCAN_AVAILABLE : 1
D/WifiScanningService(  820): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  820): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
E/native  (  820): do suspend true
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  820): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Disconnected - quitting
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1073): CM callback handler got msg 524292
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 4760): type=WIFI subType= reason=null isConnected=false
,D/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,W/ContextImpl( 4968): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/GpsLocationProvider(  820): No APN found to select.
,D/BluetoothManagerService(  820): Message: 20,
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c5c97a0:true
,D/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/wpa_supplicant( 1138): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 1138): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/ActivityManager(  820): Start proc 4990:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 347us total 15.778ms
,D/BluetoothManagerService(  820): Message: 30
,E/GpsLocationProvider(  820): No APN found to select.
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 331us total 15.110ms
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 4968): Adding local MAP profile
,D/BluetoothMap( 4968): Create BluetoothMap proxy object
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 229us total 13.471ms
,W/bt-btif ( 2125): ag scb idx 1 not allocated
E/bt-btif ( 2125): BTA AG is already disabled, ignoring ...
D/bt_userial( 2125): RX termination
W/bt_userial( 2125): select_read return size <=0:-1, exiting userial_read_thread
,D/bt_userial( 2125): Leaving userial_read_thread()
,W/bt-l2cap( 2125): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2125): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2125): L2CAP - PSM: 0x0019 not found for deregistration,
W/bt-l2cap( 2125): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2125): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2125): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2125): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2125): hw_epilog_process,
I/bt_userial_vendor( 2125): device fd = 53 close
,I/art     (  820): Explicit concurrent mark sweep GC freed 37012(1756KB) AllocSpace objects, 3(142KB) LOS objects, 31% free, 34MB/50MB, paused 1.464ms total 65.371ms
D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30,
,D/LocalBluetoothProfileManager( 4968): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4968): finishStartingService: stopping service
,D/BluetoothInputDevice( 4968): Proxy object connected
,D/HidProfile( 4968): Bluetooth service connected
,D/BluetoothPan( 4968): BluetoothPAN Proxy object connected
D/PanProfile( 4968): Bluetooth service connected
D/BluetoothMap( 4968): Proxy object connected
D/MapProfile( 4968): Bluetooth service connected
D/BluetoothMap( 4968): getConnectedDevices()
,D/BluetoothMap( 4968): Bluetooth is Not enabled
,I/ActivityManager(  820): Killing 4611:android.process.acore/u0a5 (adj 15): empty #17
,I/GKI_LINUX( 2125): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2125): GKI_exit_task 0 done
I/GKI_LINUX( 2125): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2125): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,I/wpa_supplicant( 1138): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  820): InitialState.processMessage what=4
E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/HeadsetService( 2125): Received stop request...Stopping profile...
,D/Tethering(  820): sendTetherStateChangedBroadcast 0, 0, 0
,D/HeadsetStateMachine( 2125): Exit Disconnected: -1,
D/BluetoothHeadset(  820): Proxy object disconnected
,D/BluetoothHeadset( 1286): Proxy object disconnected
D/BluetoothHeadset( 1073): Proxy object disconnected
W/Settings( 1801): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothHeadset(  820): Proxy object disconnected
D/BluetoothHeadset(  820): Proxy object disconnected
,D/A2dpService( 2125): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2125): Exit Disconnected: -1
,D/BluetoothA2dp( 1073): Proxy object disconnected
D/HidService( 2125): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 1073): Proxy object disconnected
D/HeadsetStateMachine( 2125): Unbinding service...
D/BluetoothInputDevice( 4968): Proxy object disconnected
,D/HidProfile( 4968): Bluetooth service disconnected
D/BluetoothA2dp(  820): Proxy object disconnected
W/BluetoothHeadsetServiceJni( 2125): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2125): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothAdapterState( 2125): Stopping profile services that were post enabled
D/HealthService( 2125): Received stop request...Stopping profile...
D/PanService( 2125): Received stop request...Stopping profile...
,D/BtGatt.DebugUtils( 2125): handleDebugAction() action=null
D/BluetoothPan( 4968): BluetoothPAN Proxy object disconnected
,D/PanProfile( 4968): Bluetooth service disconnected
D/BtGatt.GattService( 2125): Received stop request...Stopping profile...
D/BtGatt.GattService( 2125): stop()
D/BtGatt.AdvertiseManager( 2125): advertise clients cleared
D/BluetoothPan( 1073): BluetoothPAN Proxy object disconnected
,I/GKI_LINUX( 2125): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2125): GKI_exit_task 2 done
I/GKI_LINUX( 2125): GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothMapService( 2125): Received stop request...Stopping profile...
,D/BluetoothMapService( 2125): stop()
D/BluetoothMapEmailAppObserver( 2125): deinitObservers()
,D/BluetoothMapEmailAppObserver( 2125): removeReceiver()
,W/BluetoothHidServiceJni( 2125): Cleaning up Bluetooth HID Interface...
,D/BluetoothMap( 1073): Proxy object disconnected
W/bt-btif ( 2125): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2125): Cleaning up Bluetooth GID callback object
,W/BluetoothHealthServiceJni( 2125): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2125): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 2125): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 2125): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 2125): MAP Service closeService in
,D/BluetoothAdapterState( 2125): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 2125): cleanup()
D/BluetoothMapService( 2125): MAP Service closeService in
,D/BluetoothAdapterProperties( 2125): Setting state to 10
I/BluetoothAdapterState( 2125): Bluetooth adapter state changed: 13-> 10
,I/BluetoothAdapterState( 2125): Entering OffState
D/BluetoothManagerService(  820): Message: 60,
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  820): Broadcasting onBluetoothStateChange(false) to 17 receivers.
D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  820): onBluetoothStateChange: up=false
D/BluetoothPbap( 4968): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
D/BluetoothMap( 4968): onBluetoothStateChange: up=false
D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 1073): onBluetoothStateChange: up=false
,D/BluetoothAvrcpController( 1073): onBluetoothStateChange: up=false,
E/BluetoothAvrcpController( 1073): 
E/BluetoothAvrcpController( 1073): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@25134484
E/BluetoothAvrcpController( 1073): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029),
E/BluetoothAvrcpController( 1073): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1073): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1073): 	,at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1073): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1073): 	,at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothA2dpSink( 1073): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1073): 
E/BluetoothA2dpSink( 1073): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@2a2c946d
E/BluetoothA2dpSink( 1073): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1073): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1073): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1073): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1073): ,	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1073): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset( 1073): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1073): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1286): onBluetoothStateChange: up=false
D/BluetoothMap( 1073): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 4968): onBluetoothStateChange: up=false
D/BluetoothHeadsetClient( 1073): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1073): 
E/BluetoothHeadsetClient( 1073): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@38298a2
E/BluetoothHeadsetClient( 1073): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1073): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1073): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1073): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1073): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1073): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothManagerService(  820): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  820): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  820): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1b62ec34 mBinding = false
,D/BluetoothManagerService(  820): Sending unbind request.
,D/BluetoothManagerService(  820): Bluetooth State Change Intent: 13 -> 10,
,D/BluetoothAdapter( 1073): 759271236: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1073): 759271236: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1073): 759271236: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2125): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2125): GKI_exit_task 1 done
,I/GKI_LINUX( 2125): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2125): cleanupNative: return from cleanup
,I/art     ( 2125): System.exit called, status: 0,
I/AndroidRuntime( 2125): VM exiting with result code 0, cleanup skipped.
,D/StrictMode( 4990): StrictMode policy violation; ~duration=213 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4990): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4990): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4990): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4990): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4990): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4990): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4990): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 4990): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 4990): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4990): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4990): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4990): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4990): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4990): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 4990): StrictMode policy violation; ~duration=212 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4990): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4990): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4990): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4990): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4990): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4990): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4990): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4990): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4990): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4990): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 4990): StrictMode policy violation; ~duration=210 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4990): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4990): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4990): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
,D/StrictMode( 4990): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4990): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4990): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4990): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4990): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 4990): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4990): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4990): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4990): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4990): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4990): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4990): StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4990): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4990): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4990): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 4990): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4990): ,	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4990): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4990): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4990): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4990): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4990): StrictMode policy violation; ~duration=198 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4990): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4990): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4990): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4990): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4990): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4990): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4990): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4990): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4990): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4990): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4990): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4990): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4990): StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 4990): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4990): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 4990): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 4990): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 4990): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 4990): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 4990): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 4990): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 4990): 	at android.content.ContentProviderNative.onTransact(ContentProvid,erNative.java:122)
D/StrictMode( 4990): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 4990): # via Binder call with stack:
D/StrictMode( 4990): android.os.StrictMode$LogStackTrace
D/StrictMode( 4990): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 4990): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 4990): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 4990): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 4990): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 4990): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 4990): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 4990): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 4990): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4990): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4990): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4990): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4990): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4990): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4990): StrictMode policy violation; ~duration=41 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4990): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4990): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4990): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4990): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4990): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4990): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4990): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 4990): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4990): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4990): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4990): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4990): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4990): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4990): StrictMode policy violation; ~duration=40 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4990): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4990): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4990): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4990): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4990): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4990): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4990): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4990): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4990): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4990): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4990): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4990): StrictMode policy violation; ~duration=40 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4990): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4990): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4990): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4990): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4990): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4990): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4990): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4990): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4990): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4990): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4990): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4990): StrictMode policy violation; ~duration=39 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4990): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4990): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4990): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4990): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4990): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4990): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4990): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 4990): 	at com.google.p.j.a(PG:121)
D/StrictMode( 4990): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 4990): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 4990): 	at com.google.p.e.a(PG:170)
D/StrictMode( 4990): 	at com.google.p.e.b(PG:21)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4990): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4990): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4990): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4990): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4990): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4990): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4990): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4990): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
I/ActivityManager(  820): Process com.android.bluetooth (pid 2125) has died
W/com.google.a.a.a.b.a( 4990): Application name is not set. Call Builder#setApplicationName.
D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1bf541e8:true
I/ActivityManager(  820): Killing 4558:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1374): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  820): Start proc 5019:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,W/ResourcesManager( 5019): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5019): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5019): MmsConfig.loadMmsSettings
I/Babel_SMS( 5019): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 5019): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5019): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5019): MmsConfig.loadFromResources
E/Babel_SMS( 5019): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5019): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,W/Settings( 5019): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5019): startup - clean
,I/Babel   ( 5019): deleted: false for 0
,I/Babel_telephony( 5019): TeleModule.launchCompleted
,W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 5019): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 5019): BAM#gBA: invalid account id: -1
W/Babel   ( 5019): BAM#gBA: invalid account id: -1
,I/Babel_telephony( 5019): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
,V/MusicLeanback( 4760): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/VideoCapabilities( 5019): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 5019): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5019): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5019): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5019): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  820): Start proc 5049:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,W/VideoCapabilities( 5019): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  820): Killing 4536:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/vclib   ( 5019): onServiceConnected
W/Babel   ( 5019): Attempted to change video mute state without an active call.
,D/SprintDMReceiver( 5049): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 5049): simOperator:  IMSI: null
D/SprintDMReceiver( 5049): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1777): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1777): onCreate
,D/SystemUpdateService( 1777): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1777): active receiver: enabled
,I/SystemUpdateService( 1777): showing system update notification
,I/iu.Environment( 1777): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1777): num queued entries: 0
,I/iu.UploadsManager( 1777): num updated entries: 0
I/iu.SyncManager( 1777): NEXT; no task
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1777): retry (wakeup: false) in 3599979 ms
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1777): onDestroy
,I/Babel   ( 5019): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  820): Start proc 5070:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  820): Killing 4588:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  820): Killing 4803:com.google.android.apps.cloudprint/u0a41 (adj 15): empty #17
,V/MusicLeanback( 4760): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 5049): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 5049): simOperator:  IMSI: null
D/SprintDMReceiver( 5049): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1777): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1777): onCreate
,D/SystemUpdateService( 1777): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1777): active receiver: enabled
,I/SystemUpdateService( 1777): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1777): retry (wakeup: false) in 3599951 ms
,D/SystemUpdateService( 1777): onDestroy
,W/ContextImpl( 4968): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  820): Start proc 5092:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,D/DockEventReceiver( 4968): finishStartingService: stopping service
,W/ResourcesManager( 5092): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 5092): Adding HeadsetService
D/AdapterServiceConfig( 5092): Adding A2dpService
,D/AdapterServiceConfig( 5092): Adding HidService
,D/AdapterServiceConfig( 5092): Adding HealthService
,D/AdapterServiceConfig( 5092): Adding PanService
D/AdapterServiceConfig( 5092): Adding GattService
D/AdapterServiceConfig( 5092): Adding BluetoothMapService
,I/ActivityManager(  820): Killing 4778:com.google.android.apps.cloudprint:sync/u0a41 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1374): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }

```
