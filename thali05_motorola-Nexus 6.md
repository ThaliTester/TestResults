#### Test 58752353dc32d9f_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/CheckinService( 1769): Done disabling old GoogleServicesFramework version
,D/AndroidRuntime( 3581): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3581): CheckJNI is OFF
D/AndroidRuntime( 3581): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{3ed1c0e0 token=Token{33265ee3 ActivityRecord{3fc07712 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  820): Adding window Window{8aec75b u0 Starting com.test.thalitest} at 2 of 7 (after Window{13d00873 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3581): Shutting down VM
I/HotwordDetector( 1512): Closing mic
I/MicrophoneInputStream( 1512): mic_close com.google.android.apps.gsa.speech.audio.u@34db6909
I/ActivityManager(  820): Start proc 3595:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1512): Stopping hotword detection.
I/HotwordRecognitionRnr( 1512): Hotword detection finished
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660728595
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/art     (  820): Explicit concurrent mark sweep GC freed 28948(1615KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 34MB/50MB, paused 1.759ms total 67.091ms
,I/ActivityManager(  820): Killing 3189:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/WebViewFactory( 3595): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3595): Time to load native libraries: 2 ms (timestamps 646-648)
,I/LibraryLoader( 3595): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3595): Binding Chromium to main looper Looper (main, tid 1) {1c5e5eb}
,I/LibraryLoader( 3595): Expected native library version number "",actual native library version number ""
I/chromium( 3595): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3595): Initializing chromium process, singleProcess=true
W/art     ( 3595): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3595): ApplicationContext is null in ApplicationStatus
W/chromium( 3595): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3595): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3595): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3595): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37c234c5:true
,W/art     ( 3595): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3595): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3595): CordovaWebView is running on device made by: motorola
,W/art     ( 3595): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3595): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3595): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3595): Validating map...
,V/WindowManager(  820): Adding window Window{3072d935 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{8aec75b u0 Starting com.test.thalitest})
,W/chromium( 3595): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3595): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3595): Enabling debug mode 0
,I/Keyboard.Facilitator( 1231): onFinishInput()
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +893ms
,W/BindingManager( 3595): Cannot call determinedVisibility() - never saw a connection for the pid: 3595
,D/JsMessageQueue( 3595): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3595): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576399872
,I/chromium( 3595): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  820): Waited long enough for: ServiceRecord{1e68cad2 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,W/jxcore-log( 3595): Initializing JXcore engine
W/jxcore-log( 3595): JXcore engine is ready
,W/Thread-392( 3648): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9635]" dev="sockfs" ino=9635 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-392( 3648): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-392( 3648): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11710]" dev="sockfs" ino=11710 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-392( 3648): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23561]" dev="sockfs" ino=23561 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3595): Starting JXcore engine
,W/jxcore-log( 3595): Platform android
W/jxcore-log( 3595): 
W/jxcore-log( 3595): Process ARCH arm
W/jxcore-log( 3595): 
,I/jxcore-log( 3595): JXcore Cordova bridge is ready!
I/jxcore-log( 3595): 
W/jxcore-log( 3595): JXcore engine is started
,I/jxcore-log( 3595): Toggling radios to true
I/jxcore-log( 3595): 
,D/BluetoothAdapter( 3595): enable(): BT is already enabled..!
,D/WifiService(  820): setWifiEnabled: true pid=3595, uid=10265
,E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  820): New client listening to asynchronous messages
,I/jxcore-log( 3595): Radios toggled
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): My device name is: motorola-Nexus 6
I/jxcore-log( 3595): 
,I/wpa_supplicant( 1139): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1,
E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1348): Read error: ssl=0xb4887000: I/O error during system call, Connection timed out
,V/NativeCrypto( 1348): SSL shutdown failed: ssl=0xb4887000: I/O error during system call, Broken pipe
,E/WifiStateMachine(  820): Start Disconnecting Watchdog 1
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1061): CM callback handler got msg 524292
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1512): Network connectivity changed, type is: 6
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3331): type=WIFI subType= reason=null isConnected=false
,D/PhoneInterfaceManager( 1279): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
V/MusicLeanback( 3331): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/PhoneInterfaceManager( 1279): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/WifiConfigStore(  820): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): will read network variables netId=0
E/GpsLocationProvider(  820): No APN found to select.
,D/PhoneInterfaceManager( 1279): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1279): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/ActivityManager(  820): Start proc 3656:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
E/WifiConfigStore(  820): will read network variables netId=0
E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 3656): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3656): simOperator:  IMSI: null
D/SprintDMReceiver( 3656): Not Sprint UICC, don't do anything.
,I/ActivityManager(  820): Killing 3219:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/SystemUpdateService( 1769): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1769): onCreate
,D/SystemUpdateService( 1769): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1769): active receiver: enabled
,I/SystemUpdateService( 1769): showing system update notification
,I/iu.Environment( 1769): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1769): num queued entries: 0
I/iu.UploadsManager( 1769): num updated entries: 0
I/iu.SyncManager( 1769): NEXT; no task
,I/ValidateNoPeople(  820): skipping global notification
,D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1769): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
V/SystemUpdateService( 1769): retry (wakeup: false) in 3599952 ms
,I/ActivityManager(  820): Start proc 3676:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 2937): connection state changed from UNKNOWN to DISCONNECTED
,D/SystemUpdateService( 1769): onDestroy
,I/GAv4    ( 3676): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3676):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3676):   adb logcat -s GAv4
,W/GAv4    ( 3676): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3676): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3676): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,I/WebViewFactory( 3676): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3676): Time to load native libraries: 2 ms (timestamps 4345-4347)
I/LibraryLoader( 3676): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3676): Binding Chromium to main looper Looper (main, tid 1) {2582ef8f}
,I/LibraryLoader( 3676): Expected native library version number "",actual native library version number ""
I/chromium( 3676): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3676): Initializing chromium process, singleProcess=true
,W/art     ( 3676): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3676): ApplicationContext is null in ApplicationStatus,
,W/chromium( 3676): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3676): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3676): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3676): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3676): Requires BLUETOOTH permission
,I/NSApplication( 3676): Starting up...
,I/ActivityManager(  820): Start proc 3732:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 323us total 15.009ms
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 230us total 13.154ms
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 231us total 9.432ms
,I/ActivityManager(  820): Start proc 3754:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  820): Killing 3019:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3060): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3060): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3060): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  820): Killing 3274:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  820): Killing 2710:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/wpa_supplicant( 1139): wlan0: Trying to associate with SSID 'NG7005g'
,V/MusicLeanback( 3331): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3656): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3656): simOperator:  IMSI: null
D/SprintDMReceiver( 3656): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1769): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1769): onCreate
,D/SystemUpdateService( 1769): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1769): active receiver: enabled
,I/SystemUpdateService( 1769): showing system update notification
,D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1769): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1769): retry (wakeup: false) in 3599982 ms
,D/SystemUpdateService( 1769): onDestroy
,I/wpa_supplicant( 1139): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1139): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1139): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
E/WifiStateMachine(  820): Start Dhcp Watchdog 2
,E/WifiStateMachine(  820):  WifiLinkLayerStats: ,
E/WifiStateMachine(  820):  my bss beacon rx: 190
E/WifiStateMachine(  820):  RSSI mgmt: -52
E/WifiStateMachine(  820):  BE :  rx=163 tx=147 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 8359 tx_time=147 rx_time=399 scan_time=0,
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/dhcpcd  ( 3784): version 5.5.6 starting
,I/dhcpcd  ( 3784): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3784): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3784): wlan0: leased 192.168.1.122 for 86400 seconds,
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 101
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  820): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1061): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1512): Network connectivity changed, type is: 2
,I/NetworkMonitor( 3331): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1279): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1279): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,V/MusicLeanback( 3331): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 3656): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3656): simOperator:  IMSI: null
D/SprintDMReceiver( 3656): Not Sprint UICC, don't do anything.
I/SystemUpdateService( 1769): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1769): onCreate
,D/SystemUpdateService( 1769): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1769): active receiver: enabled
,I/SystemUpdateService( 1769): showing system update notification
,I/iu.Environment( 1769): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1769): num queued entries: 0
I/iu.UploadsManager( 1769): num updated entries: 0
,I/iu.SyncManager( 1769): NEXT; no task
,D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1769): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1769): retry (wakeup: false) in 3599973 ms
,D/SystemUpdateService( 1769): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Feb 2016 14:11:21 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455113481505], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455113481478]}
,D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Validated
,D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1061): CM callback handler got msg 524290
,I/Babel   ( 2937): connection state changed from DISCONNECTED to CONNECTED
,V/Herrevad( 1769): NQAS connected
,D/GCM     ( 1348): Connected
,D/GCM     ( 1348): Message class com.google.f.a.a.p
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3595): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3595): 
,I/ActivityManager(  820): Killing 3391:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/jxcore-log( 3595): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3595): ,
,I/jxcore-log( 3595): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3595): 
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=16.53 rxSuccessRate=16.78 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,I/ActivityManager(  820): Killing 3411:com.android.musicfx/u0a18 (adj 15): empty #17
,D/Finsky  ( 3060): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/art     (  820): Explicit concurrent mark sweep GC freed 52396(2MB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 1.479ms total 85.953ms
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/jxcore-log( 3595): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3595): 
,I/art     ( 1348): Explicit concurrent mark sweep GC freed 23150(1187KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 799us total 30.077ms
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3060): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3595): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3595): 
,I/jxcore-log( 3595): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3595): 
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3060): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.27 rxSuccessRate=8.89 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3060): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 3060): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3060): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3060): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1790): client connected with version: 7571000
,I/jxcore-log( 3595): Test app app.js loaded
I/jxcore-log( 3595): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3595): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3595): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3595): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3595): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3595): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3595): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3595): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3595): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3595): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3595): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@829c675 added. We now have 1 listener(s)
,I/chromium( 3595): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3595): BLE advertisement is supported
I/jxcore-log( 3595): 
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.27 rxSuccessRate=3.18 targetRoamBSSID=any RSSI=-52
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3060): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3060): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3060): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  820): Start proc 3844:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3503): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3503): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3503): 	at jdm.a(PG:82)
E/HttpOperation( 3503): 	at jcs.o(PG:406)
E/HttpOperation( 3503): 	at jcn.a(PG:1379)
E/HttpOperation( 3503): 	at jcs.i(PG:143)
E/HttpOperation( 3503): 	at blb.a(PG:3937)
E/HttpOperation( 3503): 	at czp.a(PG:18188)
E/HttpOperation( 3503): 	at czp.a(PG:9081)
E/HttpOperation( 3503): 	at czq.run(PG:1686)
E/HttpOperation( 3503): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3503): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3503): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3503): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3503): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3503): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3503): 	at jdj.a(PG:4091)
E/HttpOperation( 3503): 	at jdj.a(PG:1125)
E/HttpOperation( 3503): 	at jdm.a(PG:77)
E/HttpOperation( 3503): 	... 12 more
E/HttpOperation( 3503): Caused by: faj: BadAuthentication
E/HttpOperation( 3503): 	at fal.a(PG:38)
E/HttpOperation( 3503): 	at jdj.a(PG:4089)
E/HttpOperation( 3503): 	... 14 more
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/KeepSync( 3844): Connecting to GoogleApiClient,
,E/HttpOperation( 3503): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3503): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3503): 	at jdm.a(PG:82)
E/HttpOperation( 3503): 	at jcs.o(PG:406)
E/HttpOperation( 3503): 	at jcn.a(PG:1379)
E/HttpOperation( 3503): 	,at jcs.i(PG:143)
E/HttpOperation( 3503): 	at hec.a(PG:42)
E/HttpOperation( 3503): 	at hee.a(PG:102)
E/HttpOperation( 3503): 	at czr.a(PG:65)
E/HttpOperation( 3503): 	at kka.a(PG:108)
E/HttpOperation( 3503): 	at czp.a(PG:19176)
E/HttpOperation( 3503): ,	at czp.a(PG:9081)
E/HttpOperation( 3503): 	at czq.run(PG:1686)
E/HttpOperation( 3503): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3503): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/HttpOperation( 3503): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3503): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3503): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3503): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3503): 	,at jdj.a(PG:4091)
E/HttpOperation( 3503): 	at jdj.a(PG:1125)
E/HttpOperation( 3503): 	at jdm.a(PG:77)
E/HttpOperation( 3503): 	... 15 more
E/HttpOperation( 3503): Caused by: faj: BadAuthentication
E/HttpOperation( 3503): 	at fal.a(PG:38)
E/HttpOperation( 3503): ,	at jdj.a(PG:4089)
E/HttpOperation( 3503): 	... 17 more
E/ExperimentLoader( 3503): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3503): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3503): 	at jdm.a(PG:82)
E/ExperimentLoader( 3503): 	at jcs.o(PG:406)
,E/ExperimentLoader( 3503): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3503): 	at jcs.i(PG:143)
E/ExperimentLoader( 3503): 	at hec.a(PG:42)
E/ExperimentLoader( 3503): 	at hee.a(PG:102)
E/ExperimentLoader( 3503): 	at czr.a(PG:65)
E/ExperimentLoader( 3503): 	at kka.a(PG:108)
E/ExperimentLoader( 3503): ,	at czp.a(PG:19176)
E/ExperimentLoader( 3503): 	at czp.a(PG:9081)
E/ExperimentLoader( 3503): 	at czq.run(PG:1686)
E/ExperimentLoader( 3503): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3503): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3503): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3503): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3503): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3503): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3503): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3503): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3503): 	at jdm.a(PG:77)
E/ExperimentLoader( 3503): 	... 15 more
E/ExperimentLoader( 3503): Caused by: faj: BadAuthentication,
E/ExperimentLoader( 3503): 	at fal.a(PG:38)
E/ExperimentLoader( 3503): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3503): 	... 17 more
,I/art     ( 1348): Explicit concurrent mark sweep GC freed 21004(1200KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 25MB/41MB, paused 972us total 21.704ms
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1769): Handling authorization failure
E/ClientConnectionOperation( 1769): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1769): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1769): 	... 7 more
,V/KeepSync( 3844): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3844): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3844): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3844): (284) automatic index on blob_node(is_deleted)
D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 78460, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Start proc 3876:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3844): IOException
E/KeepSync( 3844): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3844): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3844): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3844): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3844): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3844): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3844): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3844): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3844): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3844): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3844): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3844): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3844): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3844): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3844): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3844): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3844): 	... 10 more
,W/KeepSync( 3844): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 77619, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,W/GAV2    ( 3876): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3876): Created application version: 3.6.8 (30608)
,I/art     (  820): Explicit concurrent mark sweep GC freed 32538(1486KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.983ms total 88.007ms
,I/BooksSync( 3876): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3876): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3876): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3876): Soft error
,E/BooksSync( 3876): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3876): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3876): Sync error
,E/BooksSync( 3876): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3876): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3876): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 81556, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 3117:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3458:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,I/GAV2    ( 3876): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.35 rxSuccessRate=2.14 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3060): [290] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3060): [290] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3060): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3060): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3060): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2389): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2389): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1231): run()
I/Keyboard.Facilitator( 1231): flushDynamicLanguageModels()
,I/ConfigService( 1348): onCreate
,I/ConfigService( 1348): onDestroy
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.90 rxSuccessRate=2.66 targetRoamBSSID=any RSSI=-52
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3060): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3060): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3060): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.47 rxSuccessRate=2.10 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (279 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  820): Display changed displayId=0
,I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  820): Excessive delay in setPowerMode(): 253ms
,I/DreamManagerService(  820): Entering dreamland.,
I/PowerManagerService(  820): Dozing...
,I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 12
,E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1231): onFinishInput()
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): cancelDelayedScan -> 14
,E/native  (  820): do suspend true
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/EventLogService( 1769): Opted in for usage reporting
,I/EventLogService( 1769): Aggregate from 1455111768561 (log), 1455111768561 (data)
,W/EventLogAggregator( 1769): Unknown tag: snet_gcore
,W/EventLogAggregator( 1769): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1769): dumping service [account]
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3060): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 3060): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3060): [1] 5.onFinished: Scheduling replication attempt 5.
,I/kickstart(  870): STATUS: Received file 'm9kefs2'
I/kickstart(  870): STATUS: 950272 bytes transferred in 0.995833 seconds
I/kickstart(  870): STATUS: Successfully downloaded files from target 
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  870): STATUS: Sahara protocol completed
,I/BooksSync( 3876): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3876): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3503): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3503): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3503): 	at jdm.a(PG:82)
E/HttpOperation( 3503): 	at jcs.o(PG:406)
E/HttpOperation( 3503): 	at jcn.a(PG:1379)
E/HttpOperation( 3503): 	at jcs.i(PG:143)
E/HttpOperation( 3503): 	at blb.a(PG:3937)
E/HttpOperation( 3503): 	at czp.a(PG:18188)
E/HttpOperation( 3503): 	at czp.a(PG:9081)
E/HttpOperation( 3503): 	at czq.run(PG:1686)
E/HttpOperation( 3503): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3503): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3503): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3503): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3503): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3503): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3503): 	at jdj.a(PG:4091)
E/HttpOperation( 3503): 	at jdj.a(PG:1125)
E/HttpOperation( 3503): 	at jdm.a(PG:77)
E/HttpOperation( 3503): 	... 12 more
E/HttpOperation( 3503): Caused by: faj: BadAuthentication
E/HttpOperation( 3503): 	at fal.a(PG:38)
E/HttpOperation( 3503): 	at jdj.a(PG:4089)
E/HttpOperation( 3503): 	... 14 more
,I/art     (  820): Explicit concurrent mark sweep GC freed 45524(2MB) AllocSpace objects, 16(350KB) LOS objects, 31% free, 34MB/50MB, paused 1.625ms total 84.506ms
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3876): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3876): Soft error
E/BooksSync( 3876): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3876): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3876): Sync error
E/BooksSync( 3876): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3876): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3876): Finished books sync
,E/HttpOperation( 3503): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3503): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3503): 	at jdm.a(PG:82)
E/HttpOperation( 3503): 	at jcs.o(PG:406)
E/HttpOperation( 3503): 	at jcn.a(PG:1379)
E/HttpOperation( 3503): 	at jcs.i(PG:143)
E/HttpOperation( 3503): 	at hec.a(PG:42)
E/HttpOperation( 3503): 	at hee.a(PG:102)
E/HttpOperation( 3503): 	at czr.a(PG:65)
E/HttpOperation( 3503): 	at kka.a(PG:108)
E/HttpOperation( 3503): 	at czp.a(PG:19176)
E/HttpOperation( 3503): 	at czp.a(PG:9081)
E/HttpOperation( 3503): 	at czq.run(PG:1686)
E/HttpOperation( 3503): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3503): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3503): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3503): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3503): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3503): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3503): 	at jdj.a(PG:4091)
E/HttpOperation( 3503): 	at jdj.a(PG:1125)
E/HttpOperation( 3503): 	at jdm.a(PG:77)
E/HttpOperation( 3503): 	... 15 more
E/HttpOperation( 3503): Caused by: faj: BadAuthentication
E/HttpOperation( 3503): 	at fal.a(PG:38)
E/HttpOperation( 3503): 	at jdj.a(PG:4089)
E/HttpOperation( 3503): 	... 17 more
,E/ExperimentLoader( 3503): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3503): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3503): 	at jdm.a(PG:82)
E/ExperimentLoader( 3503): 	at jcs.o(PG:406)
E/ExperimentLoader( 3503): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3503): 	at jcs.i(PG:143)
E/ExperimentLoader( 3503): 	at hec.a(PG:42)
E/ExperimentLoader( 3503): 	at hee.a(PG:102)
E/ExperimentLoader( 3503): 	at czr.a(PG:65)
E/ExperimentLoader( 3503): 	at kka.a(PG:108)
E/ExperimentLoader( 3503): 	at czp.a(PG:19176)
E/ExperimentLoader( 3503): 	at czp.a(PG:9081)
E/ExperimentLoader( 3503): 	at czq.run(PG:1686)
E/ExperimentLoader( 3503): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3503): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3503): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3503): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3503): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3503): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3503): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3503): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3503): 	at jdm.a(PG:77)
E/ExperimentLoader( 3503): 	... 15 more
E/ExperimentLoader( 3503): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3503): 	at fal.a(PG:38)
E/ExperimentLoader( 3503): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3503): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 139570, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1348): Explicit concurrent mark sweep GC freed 30765(1825KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.268ms total 48.422ms
,V/KeepSync( 3844): Connecting to GoogleApiClient
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 137343, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1769): Handling authorization failure
E/ClientConnectionOperation( 1769): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1769): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1769): 	... 7 more
,V/KeepSync( 3844): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3844): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3844): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3844): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3844): IOException
E/KeepSync( 3844): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3844): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3844): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3844): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3844): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3844): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3844): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3844): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3844): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3844): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3844): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3844): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3844): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3844): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3844): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3844): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3844): 	... 10 more
W/KeepSync( 3844): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 140072, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2389): Disconnected process message: 10, size: 0
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1348): Vacuum at: now=1455113589704 tag=VacuumService
,V/GoogleAuthProtoRequest( 3296): [340] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GoogleURLConnFactory( 1348): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3060): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3060): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3060): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ExperimentUpdateService( 3296): [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3296): [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3296): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3296): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3296): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3296): ,	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3296): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3296): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3296): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3296): ,	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3296): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3296): 	at com.a.a.k.run(SourceFile:110)
V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1348): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1348): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1348): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1348): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1348): No account for auth token provided
,W/Uploader( 1348): No account for auth token provided
,W/Uploader( 1348): No account for auth token provided
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1348): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1348): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1348): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1348): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1348): No account for auth token provided
,W/Uploader( 1348): No account for auth token provided,
,W/Uploader( 1348): No account for auth token provided
,W/Uploader( 1348): No account for auth token provided
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1348): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1348): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1348): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1348): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1348): No account for auth token provided,
,W/Uploader( 1348): No account for auth token provided
,W/Uploader( 1348): No account for auth token provided
,W/Uploader( 1348):  no longer exists, so no auth token.
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1348): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1348): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1348): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1348): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1348): No account for auth token provided
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1348): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1348): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1348): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1348): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1348): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1348): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2389): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3296): [341] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3296): [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3296): [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3296): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3296): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3296): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3296): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3296): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3296): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3296): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3296): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3296): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3296): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1231): run()
,I/Keyboard.Facilitator( 1231): flushDynamicLanguageModels()
,I/ConfigService( 1348): onCreate
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3503): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3503): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 3503): 	at jdm.a(PG:82)
E/HttpOperation( 3503): 	at jcs.o(PG:406)
E/HttpOperation( 3503): ,	at jcn.a(PG:1379)
E/HttpOperation( 3503): 	at jcs.i(PG:143)
E/HttpOperation( 3503): 	at blb.a(PG:3937)
E/HttpOperation( 3503): 	at czp.a(PG:18188)
,E/HttpOperation( 3503): 	at czp.a(PG:9081)
E/HttpOperation( 3503): 	at czq.run(PG:1686)
E/HttpOperation( 3503): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3503): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/HttpOperation( 3503): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3503): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3503): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3503): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/HttpOperation( 3503): 	at jdj.a(PG:4091)
E/HttpOperation( 3503): 	at jdj.a(PG:1125)
E/HttpOperation( 3503): 	at jdm.a(PG:77)
E/HttpOperation( 3503): 	... 12 more
E/HttpOperation( 3503): Caused by: faj: BadAuthentication
,E/HttpOperation( 3503): 	at fal.a(PG:38)
E/HttpOperation( 3503): 	at jdj.a(PG:4089)
E/HttpOperation( 3503): 	... 14 more
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 36667(1608KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 2.114ms total 91.517ms
,E/HttpOperation( 3503): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3503): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3503): 	at jdm.a(PG:82)
E/HttpOperation( 3503): 	at jcs.o(PG:406)
E/HttpOperation( 3503): 	at jcn.a(PG:1379)
E/HttpOperation( 3503): 	at jcs.i(PG:143)
E/HttpOperation( 3503): 	at hec.a(PG:42)
E/HttpOperation( 3503): 	at hee.a(PG:102)
E/HttpOperation( 3503): 	at czr.a(PG:65)
E/HttpOperation( 3503): 	at kka.a(PG:108)
E/HttpOperation( 3503): 	at czp.a(PG:19176)
E/HttpOperation( 3503): 	,at czp.a(PG:9081)
E/HttpOperation( 3503): 	at czq.run(PG:1686)
E/HttpOperation( 3503): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3503): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3503): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3503): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3503): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3503): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3503): 	at jdj.a(PG:4091)
E/HttpOperation( 3503): 	at jdj.a(PG:1125)
E/HttpOperation( 3503): 	at jdm.a(PG:77)
E/HttpOperation( 3503): 	... 15 more
E/HttpOperation( 3503): Caused by: faj: BadAuthentication
E/HttpOperation( 3503): 	,at fal.a(PG:38)
E/HttpOperation( 3503): 	at jdj.a(PG:4089)
E/HttpOperation( 3503): 	... 17 more
E/ExperimentLoader( 3503): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3503): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3503): 	at jdm.a(PG:82)
E/ExperimentLoader( 3503): 	at jcs.o(PG:406)
E/ExperimentLoader( 3503): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3503): 	at jcs.i(PG:143)
E/ExperimentLoader( 3503): 	at hec.a(PG:42)
E/ExperimentLoader( 3503): 	at hee.a(PG:102)
E/ExperimentLoader( 3503): 	at czr.a(PG:65)
E/ExperimentLoader( 3503): 	at kka.a(PG:108),
E/ExperimentLoader( 3503): 	at czp.a(PG:19176)
E/ExperimentLoader( 3503): 	at czp.a(PG:9081)
E/ExperimentLoader( 3503): 	at czq.run(PG:1686)
E/ExperimentLoader( 3503): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3503): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3503): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3503): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3503): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3503): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3503): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3503): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3503): 	at jdm.a(PG:77)
E/ExperimentLoader( 3503): ,	... 15 more
E/ExperimentLoader( 3503): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3503): 	at fal.a(PG:38)
E/ExperimentLoader( 3503): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3503): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 227524, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1348): onDestroy
,D/HeadsetStateMachine( 2389): Disconnected process message: 10, size: 0
,I/BooksSync( 3876): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3844): Connecting to GoogleApiClient
,I/BooksConfig( 3876): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1769): Handling authorization failure
E/ClientConnectionOperation( 1769): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1769): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1769): 	... 7 more
,V/KeepSync( 3844): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3844): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3844): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3844): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1348): Explicit concurrent mark sweep GC freed 66588(3MB) AllocSpace objects, 9(925KB) LOS objects, 36% free, 27MB/43MB, paused 2.395ms total 45.271ms
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3876): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3876): Soft error
E/BooksSync( 3876): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3876): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3876): Sync error
E/BooksSync( 3876): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3876): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3876): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 230338, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3844): IOException
E/KeepSync( 3844): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3844): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3844): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3844): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3844): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3844): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3844): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3844): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3844): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3844): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3844): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3844): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3844): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3844): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3844): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3844): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3844): 	... 10 more
W/KeepSync( 3844): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 232855, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3595): --= Surplus to requirements =--
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST TOOK:  ms ****
I/jxcore-log( 3595): 
I/jxcore-log( 3595): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3595): 
,D/AndroidRuntime( 3986): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3986): CheckJNI is OFF
,D/AndroidRuntime( 3986): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
,I/ActivityManager(  820): Killing 3595:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  820): Skipping PackageSetting{cf1b44 com.example.hello/10273} due to missing metadata
,D/WifiService(  820): Client connection lost with reason: 4
,I/WindowState(  820): WIN DEATH: Window{3072d935 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/ActivityManager(  820): Force removing ActivityRecord{3fc07712 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  820): Display changed displayId=0
,I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,W/ActivityManager(  820): Spurious death for ProcessRecord{119990f5 3595:com.test.thalitest/u0a265}, curProc for 3595: null
,D/TaskPersister(  820): removeObsoleteFile: deleting file=28_task.xml
,I/Keyboard.Facilitator( 1231): resetDictionaries() : en_US
,I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1512): Explicit concurrent mark sweep GC freed 3077(230KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 997us total 31.712ms
D/BuaReceiver( 3373): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/Keyboard.Facilitator.DecoderInitializer( 1231): run()
,I/Decoder ( 1231): createOrResetDecoder
,W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3595 uid 10265
,I/Keyboard.Facilitator( 1231): onFinishInput()
,D/VoicemailCleanupService( 1412): Cleaning up data for package: com.test.thalitest
,I/art     (  820): Explicit concurrent mark sweep GC freed 21620(1254KB) AllocSpace objects, 11(741KB) LOS objects, 31% free, 34MB/50MB, paused 1.555ms total 63.374ms
,I/ActivityManager(  820): Start proc 4003:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/art     ( 1061): Explicit concurrent mark sweep GC freed 56806(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 1.740ms total 70.807ms
,I/art     (  820): WaitForGcToComplete blocked for 61.914ms for cause Explicit
,I/ConfigService( 1348): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1231): run()
,I/art     ( 1325): Explicit concurrent mark sweep GC freed 5707(420KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.073ms total 36.061ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1231): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run() : Loading LM = user
W/LocationOracleImpl( 1512): Best location was null
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1231): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1231): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1231): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1231): run()
I/StatsUtilsManager( 1231): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1231): shouldRecordStats() = Too Soon
,I/HotwordRecognitionRnr( 1512): Starting hotword detection.
I/MicrophoneInputStream( 1512): mic_starting com.google.android.apps.gsa.speech.audio.u@3e203a21
,I/AudioFlinger(  357): AudioFlinger's thread 0xb4019000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1512): mic_started com.google.android.apps.gsa.speech.audio.u@3e203a21
,I/ActivityManager(  820): Start proc 4030:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
,E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,W/ContextImpl( 4030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1348): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1348): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/art     (  820): Explicit concurrent mark sweep GC freed 7495(349KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 1.111ms total 139.672ms
,I/HotwordWorker( 1512): onReady
,V/GoogleAuthProtoRequest( 3296): [343] a.<init>: mAccountName set to: thalitester@gmail.com
,D/PackageBroadcastService( 1769): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1769): Module APK com.google.android.play.games already loaded
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@33b84781}
D/AccountUtils( 1769): Clearing selected account for com.test.thalitest
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1769): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1769): Removing dialog suppression flag for package com.test.thalitest
,I/UpdateIcingCorporaServi( 1512): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1325): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2bc72763 new=com.google.android.velvet.VelvetApplication@2bc72763
D/GOOGLEHELP_CompatibleDatabase( 1769): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1769): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1769): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1769): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1769): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1769): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1769): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1769): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1769): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1769): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1769): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1769): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1769): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  820): Start proc 4068:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660728595
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,D/Launcher.Workspace( 1325): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1325): 11683562 - stripEmptyScreens()
,I/ConfigFetchService( 1769): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,W/BaseAppContext( 1769): Using Auth Proxy for data requests.
,I/ConfigFetchService( 1769): service connected
,I/PeopleContactsSync( 1769): CP2 sync disabled
,I/art     ( 3986): System.exit called, status: 0
I/AndroidRuntime( 3986): VM exiting with result code 0.
I/UpdateIcingCorporaServi( 1512): UpdateCorporaTask done [took 77 ms] updated apps [took 77 ms] 
W/BaseAppContext( 1769): Using Auth Proxy for data requests.
I/Icing   ( 1769): doRemovePackageData com.test.thalitest
,I/GLSUser ( 1348): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1348): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1348): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1348): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3296): [343] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3296): [343] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3296): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3296): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3296): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3296): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3296): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3296): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3296): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3296): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3296): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3296): 	at com.a.a.k.run(SourceFile:110)
,I/GAv4    ( 4068): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4068):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4068):   adb logcat -s GAv4
,W/GAv4    ( 4068): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4068): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4068): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
,W/AnalyticsTrackerProxyImpl( 4068): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4068): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4068): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4068): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4068): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4068): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4068): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4068): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4068): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4068): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4068): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4068): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabas,e.java:694)
E/SQLiteDatabase( 4068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4068): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4068): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4068): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4068): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4068): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4068): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4068): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4068): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4068): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4068): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4068): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4068): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4068): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4068): 	at aen.run(PG:536)
,W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4068): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4068): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4068): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4068): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4068): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4068): 	at aej.c(PG:139)
E/SQLiteDatabase( 4068): 	at aej.b(PG:398)
E/SQLiteDatabase( 4068): 	at agf.f(PG:417)
E/SQLiteDatabase( 4068): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4068): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4068): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/Abstract,DatabaseInstance( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4068): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4068): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4068): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4068): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4068): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4068): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4068): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4068): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4068): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4068): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4068): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4068): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4068): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 4068): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4068): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/ActivityManager(  820): Start proc 4105:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,E/GAv4    ( 4068): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4068): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
I/ActivityManager(  820): Killing 2302:com.google.android.calendar/u0a37 (adj 15): empty #17
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4068): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4068): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4068): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4068): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4068): 	at aen.run(PG:536)
,V/JNIHelp ( 4068): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4068): Installed default security provider GmsCore_OpenSSL
,E/SQLiteDatabase( 4068): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4068): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4068): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4068): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4068): 	at aej.c(PG:139)
E/SQLiteDatabase( 4068): 	at aej.a(PG:358)
E/SQLiteDatabase( 4068): 	at aej.a(PG:345)
E/SQLiteDatabase( 4068): 	at agf.c(PG:884)
E/SQLiteDatabase( 4068): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 4068): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4068): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4068): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4068): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 4068): Failed to query Account133 object,
E/AbstractDatabaseInstance( 4068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209),
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4068): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4068): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4068): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4068): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
E/AbstractDatabaseInstance( 4068): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4068): 	at ael.a(PG:1521)
,E/AbstractDatabaseInstance( 4068): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4068): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4068): ,	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4068): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4068): 	,at agf.c(PG:884)
E/AbstractDatabaseInstance( 4068): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 4068): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
,E/AbstractDatabaseInstance( 4068): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4068): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 4068): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4068): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4068): 	at java.lang.Thread.run(Thread.java:818),
W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4068): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4068): Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4068): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4068): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4068): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4068): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4068): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4068): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4068): java.lang.RuntimeException: An error occured while executing doInBackground()
,E/CAKEMIX_CRASHED( 4068): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/CAKEMIX_CRASHED( 4068): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/CAKEMIX_CRASHED( 4068): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222),
E/CAKEMIX_CRASHED( 4068): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/CAKEMIX_CRASHED( 4068): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/CAKEMIX_CRASHED( 4068): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/CAKEMIX_CRASHED( 4068): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/CAKEMIX_CRASHED( 4068): 	at java.lang.Thread.run(Thread.java:818)
,E/CAKEMIX_CRASHED( 4068): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4068): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4068): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4068): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4068): 	at aej.c(PG:139)
E/CAKEMIX_CRASHED( 4068): 	at aej.a(PG:358)
E/CAKEMIX_CRASHED( 4068): 	at aej.a(PG:345)
E/CAKEMIX_CRASHED( 4068): 	at agf.c(PG:884)
E/CAKEMIX_CRASHED( 4068): 	at aii.doInBackground(PG:1063)
E/CAKEMIX_CRASHED( 4068): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/CAKEMIX_CRASHED( 4068): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/CAKEMIX_CRASHED( 4068): 	... 4 more
,I/ActivityManager(  820): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,V/WindowManager(  820): addAppToken: AppWindowToken{7c978a4 token=Token{2736cb37 ActivityRecord{3e605036 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
,I/Process ( 4068): Sending signal. PID: 4068 SIG: 9
,I/ActivityManager(  820): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
I/HotwordDetector( 1512): Closing mic
I/MicrophoneInputStream( 1512): mic_close com.google.android.apps.gsa.speech.audio.u@3e203a21
,V/GLSActivity( 1348): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/lowmemorykiller(  256): Error writing /proc/4068/oom_score_adj; errno=22
,E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager(  820): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
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
,D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record,
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1512): Hotword detection finished
,I/HotwordRecognitionRnr( 1512): Stopping hotword detection.
,I/ActivityManager(  820): Start proc 4126:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,W/ActivityManager(  820): Spurious death for ProcessRecord{14943499 4126:com.google.android.apps.docs/u0a46}, curProc for 4068: null
,W/OpenGLRenderer( 1325): Incorrectly called buildLayer on View: ew, destroying layer...
,E/native  ( 1231): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1231): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1231): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1231): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/SQLiteDatabase( 4105): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4105): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4105): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4105): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4105): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4105): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4105): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4105): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4105): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4105): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4105): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4105): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4105): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4105): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4105): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4105): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4105): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4105): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4105): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4105): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4105): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4105): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4105): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4105): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4105): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4105): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4105): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4105): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4105): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4105): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/AndroidRuntime( 4105): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 4105): FATAL EXCEPTION: main
E/AndroidRuntime( 4105): Process: com.android.documentsui, PID: 4105
E/AndroidRuntime( 4105): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4105): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4105): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4105): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4105): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4105): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4105): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4105): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4105): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4105): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4105): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4105): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4105): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4105): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4105): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4105): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4105): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4105): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4105): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4105): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4105): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4105): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4105): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4105): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4105): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4105): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4105): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4105): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4105): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4105): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4105): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4105): 	... 9 more
,E/Search.SharedPreferencesProto( 1512): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  820): Start proc 4145:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,E/DropBoxManagerService(  820): Can't write: system_app_crash
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
,D/OpenGLRenderer(  820): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  820): Validating map...
,I/ActivityManager(  820): Killing 3331:com.google.android.music:main/u0a66 (adj 15): empty #17
,E/native  ( 1231): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1231): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1231): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1231): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/ActivityManager(  820): Killing 3656:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/OpenGLRenderer(  820): Initialized EGL, version 1.4
,D/ExternalStorage( 4145): After updating volumes, found 1 active roots
D/OpenGLRenderer(  820): Enabling debug mode 0
,I/Icing   ( 1769): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
,I/GAv4    ( 4126): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4126):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4126):   adb logcat -s GAv4
,W/GAv4    ( 4126): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4126): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/Icing   ( 1769): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
,E/Icing   ( 1769): Could not init tag ds.tag.deleted
,W/GAv4    ( 4126): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4126): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4126): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4126): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4126): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4126): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4126): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4126): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4126): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4126): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4126): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4126): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4126): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4126): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4126): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4126): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4126): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4126): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4126): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4126): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4126): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4126): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4126): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4126): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4126): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4126): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4126): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4126): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4126): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4126): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4126): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4126): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4126): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4126): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4126): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4126): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4126): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4126): 	at aen.run(PG:536)
,I/Icing   ( 1769): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,E/SQLiteDatabase( 4126): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4126): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4126): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4126): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4126): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4126): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4126): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4126): 	at aej.c(PG:139)
E/SQLiteDatabase( 4126): 	at aej.b(PG:398)
E/SQLiteDatabase( 4126): 	at agf.f(PG:417)
E/SQLiteDatabase( 4126): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4126): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4126): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4126): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4126): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4126): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/Abstract,DatabaseInstance( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4126): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4126): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4126): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4126): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4126): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4126): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4126): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4126): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4126): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4126): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4126): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4126): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 4126): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4126): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/ErrorNotificationActivity( 4126): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
,V/JNIHelp ( 4126): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/OpenGLRenderer( 4126): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 4126): Validating map...
,V/WindowManager(  820): Adding window Window{1de44e88 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 8 (after Window{13d00873 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,I/ProviderInstaller( 4126): Installed default security provider GmsCore_OpenSSL
,V/WindowManager(  820): Adding window Window{2fce1c46 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 9 (before Window{1de44e88 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
,W/GAv4    ( 4126): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4126): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4126): Error opening database: android.database.sqlite.SQLiteException: Database open failed,
,E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4126): Error opening database: android.database.sqlite.SQLiteException: Database open failed,
E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
E/GAv4    ( 4126): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed,
E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4126): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4126): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
,W/GAv4    ( 4126): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4126): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed,
E/CAKEMIX_CRASHED( 4126): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/CAKEMIX_CRASHED( 4126): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4126): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4126): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463),
E/CAKEMIX_CRASHED( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4126): ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4126): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4126): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4126): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4126): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4126): 	at aev.getWritableDatabase(PG:238),
E/CAKEMIX_CRASHED( 4126): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4126): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4126): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4126): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4126): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4126): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
,E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4126): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4126): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4126): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4126): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4126): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4126): 	at aej.c(PG:139)
E/SQLiteDatabase( 4126): 	at aej.a(PG:358)
E/SQLiteDatabase( 4126): 	at aej.a(PG:345)
E/SQLiteDatabase( 4126): 	at agf.d(PG:281)
E/SQLiteDatabase( 4126): 	at agf.b(PG:312)
E/SQLiteDatabase( 4126): 	at agf.a(PG:221)
E/SQLiteDatabase( 4126): 	,at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/SQLiteDatabase( 4126): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/SQLiteDatabase( 4126): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4126): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4126): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 4126): 	at android.os.Binder.execTransact(Binder.java:446)
E/AbstractDatabaseInstance( 4126): Failed to query Account133 object
E/AbstractDatabaseInstance( 4126): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
,E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4126): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4126): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4126): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4126): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4126): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4126): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4126): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4126): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4126): 	at agf.d(PG:281)
E/AbstractDatabaseInstance( 4126): 	at agf.b(PG:312)
E/AbstractDatabaseInstance( 4126): 	at agf.a(PG:221)
E/AbstractDatabaseInstance( 4126): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/AbstractDatabaseInstance( 4126): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/AbstractDatabaseInstance( 4126): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AbstractDatabaseInstance( 4126): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AbstractDatabaseInstance( 4126): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/AbstractDatabaseInstance( 4126): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DatabaseUtils( 4126): Writing exception to parcel
E/DatabaseUtils( 4126): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 4126): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/DatabaseUtils( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DatabaseUtils( 4126): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DatabaseUtils( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DatabaseUtils( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DatabaseUtils( 4126): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/DatabaseUtils( 4126): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/DatabaseUtils( 4126): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/DatabaseUtils( 4126): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/DatabaseUtils( 4126): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/DatabaseUtils( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 4126): 	at aev.getWritableDatabase(PG:238)
E/DatabaseUtils( 4126): 	at ael.a(PG:1521)
E/DatabaseUtils( 4126): 	at hix$a.a(PG:125)
E/DatabaseUtils( 4126): 	at aej.c(PG:139)
E/DatabaseUtils( 4126): ,	at aej.a(PG:358)
E/DatabaseUtils( 4126): 	at aej.a(PG:345)
E/DatabaseUtils( 4126): 	at agf.d(PG:281)
E/DatabaseUtils( 4126): 	at agf.b(PG:312)
E/DatabaseUtils( 4126): 	at agf.a(PG:221)
E/DatabaseUtils( 4126): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/DatabaseUtils( 4126): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/DatabaseUtils( 4126): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 4126): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 4126): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 4126): 	at android.os.Binder.execTransact(Binder.java:446)
,W/Documents( 4105): Failed to load some roots from com.google.android.apps.docs.storage: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/Documents( 4105): Update found 6 roots in 768ms
,I/ActivityManager(  820): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,E/SQLiteDatabase( 4126): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4126): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4126): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4126): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4126): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4126): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4126): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4126): 	at aej.c(PG:139)
E/SQLiteDatabase( 4126): 	at aej.a(PG:358)
E/SQLiteDatabase( 4126): 	at aej.a(PG:345)
E/SQLiteDatabase( 4126): 	at agf.c(PG:884)
E/SQLiteDatabase( 4126): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 4126): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4126): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4126): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4126): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4126): Failed to query Account133 object
E/AbstractDatabaseInstance( 4126): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4126): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4126): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDataba,seInstance( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4126): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4126): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4126): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4126): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4126): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4126): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4126): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4126): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 4126): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 4126): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AbstractDatabaseInstance( 4126): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4126): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 4126): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4126): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4126): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 4126): Sending signal. PID: 4126 SIG: 9
E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!,
,E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!,
,W/InputDispatcher(  820): channel '1de44e88 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  820): channel '1de44e88 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  820): channel '2fce1c46 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  820): channel '2fce1c46 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,I/ActivityManager(  820): Process com.google.android.apps.docs (pid 4126) has died
,I/WindowState(  820): WIN DEATH: Window{2fce1c46 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,W/InputDispatcher(  820): Attempted to unregister already unregistered input channel '2fce1c46 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
I/WindowState(  820): WIN DEATH: Window{1de44e88 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
W/InputDispatcher(  820): Attempted to unregister already unregistered input channel '1de44e88 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
W/ActivityManager(  820): Force removing ActivityRecord{3e605036 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}: app died, no saved state
,I/ActivityManager(  820): Killing 3676:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@33b84781}
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1cb3cb34}
,E/SQLiteDatabase( 1348): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1348): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1348): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1348): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1348): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1348): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1348): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1348): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1348): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1348): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1348): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1348): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1348): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1348): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1348): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1348): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1348): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1348): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1348): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1348): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1348): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1348): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1348): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 1348): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1348): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1348): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1348): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1348): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1348): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1348): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1348): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1348): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
,E/SQLiteOpenHelper( 1348): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1348): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1348): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1348): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1348): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1348): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1348): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1348): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1348): 	,at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1348): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1348): ,	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1348): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1348): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1348): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1348): Opened phenotype.db in read-only mode
E/SQLiteLog( 1348): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1348): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1348): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1348): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1348): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1348): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1348): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1348): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1348): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1348): 	,at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1348): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1348): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1348): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1348): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1348): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1348): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1348): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1348): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1348): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1348): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1348): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1348): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1348): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1348): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1348): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1348): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1348): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  820): Start proc 4196:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4196): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4196):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4196):   adb logcat -s GAv4
,W/GAv4    ( 4196): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4196): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4196): Couldn't rename file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4196): Couldn't rename file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4196): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4196): Couldn't rename file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
,I/ActivityManager(  820): Killing 3732:com.android.chrome/u0a40 (adj 15): empty #17
,E/SQLiteDatabase( 4196): Failed to open database '/data/data/com.google.android.deskclock/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4196): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4196): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4196): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4196): 	at com.google.android.gms.analytics.internal.zzi$zza.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4196): 	at com.google.android.gms.analytics.internal.zzi.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4196): 	at com.google.android.gms.analytics.internal.zzi.zza(Unknown Source)
E/SQLiteDatabase( 4196): 	at com.google.android.gms.analytics.internal.zzi.zzgA(Unknown Source)
E/SQLiteDatabase( 4196): 	at com.google.android.gms.analytics.internal.zzi.isEmpty(Unknown Source)
E/SQLiteDatabase( 4196): 	at com.google.android.gms.analytics.internal.zzk.zzgO(Unknown Source)
E/SQLiteDatabase( 4196): 	at com.google.android.gms.analytics.internal.zzk$3.run(Unknown Source)
E/SQLiteDatabase( 4196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4196): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4196): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4196): 	at com.google.android.gms.measurement.MeasurementService$zzc.run(Unknown Source)
E/GAv4    ( 4196): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4196): Couldn't rename file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4196): Failed to open database '/data/data/com.google.android.deskclock/databases/google_analytics_v4.db'.,
E/SQLiteDatabase( 4196): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4196): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4196): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4196): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
,E/SQLiteDatabase( 4196): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4196): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
E/SQLiteDatabase( 4196): 	at com.google.android.gms.analytics.internal.zzi$zza.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4196): 	at com.google.android.gms.analytics.internal.zzi.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4196): ,	at com.google.android.gms.analytics.internal.zzi.zza(Unknown Source)
E/SQLiteDatabase( 4196): 	at com.google.android.gms.analytics.internal.zzi.zzgA(Unknown Source)
E/SQLiteDatabase( 4196): 	,at com.google.android.gms.analytics.internal.zzi.isEmpty(Unknown Source)
E/SQLiteDatabase( 4196): 	at com.google.android.gms.analytics.internal.zzk.zzgO(Unknown Source)
E/SQLiteDatabase( 4196): 	at com.google.android.gms.analytics.internal.zzk$3.run(Unknown Source)
,E/SQLiteDatabase( 4196): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4196): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4196): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4196): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4196): 	at java.lang.Thread.run(Thread.java:818),
E/SQLiteDatabase( 4196): 	at com.google.android.gms.measurement.MeasurementService$zzc.run(Unknown Source)
E/GAv4    ( 4196): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/GAv4    ( 4196): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4196): Couldn't rename file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4196): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4196): Couldn't rename file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4196): Couldn't rename file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.deskclock/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/Search.SharedPreferencesProto( 1512): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ConfigService( 1348): onDestroy
,E/QMI_FW  (  820): xport_send: Sendto failed for port 4352
E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660728595
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 

```
