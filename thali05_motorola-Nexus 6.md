#### Test 5753124305d96c2_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  819): Waited long enough for: ServiceRecord{15782ee3 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,--------- beginning of main
D/AndroidRuntime( 3726): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3726): CheckJNI is OFF
D/AndroidRuntime( 3726): Calling main entry com.android.commands.am.Am
I/ActivityManager(  819): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  819): addAppToken: AppWindowToken{38cbaf4a token=Token{1736bcb5 ActivityRecord{91740ec u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
I/HotwordDetector( 1529): Closing mic
I/MicrophoneInputStream( 1529): mic_close com.google.android.apps.gsa.speech.audio.u@24dd852a
D/AndroidRuntime( 3726): Shutting down VM
V/WindowManager(  819): Adding window Window{b0a2b97 u0 Starting com.test.thalitest} at 2 of 7 (after Window{3eca825c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  819): Start proc 3741:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/ActivityManager(  819): Killing 3306:com.qualcomm.timeservice/1000 (adj 15): empty #17
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1529): Stopping hotword detection.
I/HotwordRecognitionRnr( 1529): Hotword detection finished
,I/ActivityManager(  819): Killing 3476:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659634963
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  819): Killing 3422:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/WebViewFactory( 3741): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3741): Time to load native libraries: 3 ms (timestamps 5188-5191)
I/LibraryLoader( 3741): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3741): Binding Chromium to main looper Looper (main, tid 1) {e7795ec}
I/LibraryLoader( 3741): Expected native library version number "",actual native library version number ""
I/chromium( 3741): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3741): Initializing chromium process, singleProcess=true
,W/art     ( 3741): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3741): ApplicationContext is null in ApplicationStatus
,W/chromium( 3741): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3741): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3741): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3741): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  819): Message: 20
D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@287d86a1:true
,W/art     ( 3741): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3741): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3741): CordovaWebView is running on device made by: motorola
,W/art     ( 3741): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3741): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3741): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3741): Validating map...
,V/WindowManager(  819): Adding window Window{2b445a11 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{b0a2b97 u0 Starting com.test.thalitest})
,W/chromium( 3741): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3741): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3741): Enabling debug mode 0
,I/ActivityManager(  819): Displayed com.test.thalitest/.MainActivity: +1s151ms
,I/Keyboard.Facilitator( 1230): onFinishInput()
,W/BindingManager( 3741): Cannot call determinedVisibility() - never saw a connection for the pid: 3741
,D/JsMessageQueue( 3741): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3741): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576397952
,I/chromium( 3741): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3741): Initializing JXcore engine
W/jxcore-log( 3741): JXcore engine is ready
,W/Thread-417( 3795): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10409]" dev="sockfs" ino=10409 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-417( 3795): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-417( 3795): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10548]" dev="sockfs" ino=10548 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-417( 3795): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22837]" dev="sockfs" ino=22837 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3741): Starting JXcore engine
,W/jxcore-log( 3741): Platform android
W/jxcore-log( 3741): 
W/jxcore-log( 3741): Process ARCH arm
W/jxcore-log( 3741): 
,I/jxcore-log( 3741): JXcore Cordova bridge is ready!
I/jxcore-log( 3741): 
,W/jxcore-log( 3741): JXcore engine is started
,I/jxcore-log( 3741): Toggling radios to true
I/jxcore-log( 3741): 
,D/BluetoothAdapter( 3741): enable(): BT is already enabled..!
,D/WifiService(  819): New client listening to asynchronous messages
D/WifiService(  819): setWifiEnabled: true pid=3741, uid=10265
,E/WifiService(  819): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3741): Radios toggled
I/jxcore-log( 3741): 
I/jxcore-log( 3741): My device name is: motorola-Nexus 6
I/jxcore-log( 3741): 
,I/wpa_supplicant( 1139): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  819): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1249): Read error: ssl=0xaec68e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1249): SSL shutdown failed: ssl=0xaec68e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  819): Start Disconnecting Watchdog 1
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
E/WifiStateMachine(  819): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/WifiNetworkAgent(  819): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  819): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  819): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/ConnectivityService(  819): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Disconnected - quitting
D/CSLegacyTypeTracker(  819): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 3047): type=WIFI subType= reason=null isConnected=false
D/Tethering(  819): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3047): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  819): MasterInitialState.processMessage what=3
D/ConnectivityService(  819): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  819): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,E/WifiConfigStore(  819): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  819): will read network variables netId=0
,E/WifiStateMachine(  819): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  819): will read network variables netId=0
,D/PhoneInterfaceManager( 1357): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1357): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  819): getDataEnabled: retVal=false
,I/ActivityManager(  819): Start proc 3802:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/GpsLocationProvider(  819): No APN found to select.
,D/PhoneInterfaceManager( 1357): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1357): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  819): getDataEnabled: retVal=false
,E/GpsLocationProvider(  819): No APN found to select.
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3567): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3567): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3567): [1] 5.onFinished: Scheduling replication attempt 1.
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 28856(1575KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 767us total 20.206ms
,I/ActivityManager(  819): Start proc 3828:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  819): Killing 3500:com.android.musicfx/u0a18 (adj 15): empty #17
,D/SprintDMReceiver( 3828): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3828): simOperator:  IMSI: null,
D/SprintDMReceiver( 3828): Not Sprint UICC, don't do anything.,
,I/SystemUpdateService( 1770): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1770): onCreate
,D/SystemUpdateService( 1770): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1770): active receiver: enabled
,I/SystemUpdateService( 1770): showing system update notification
,I/iu.Environment( 1770): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1770): num queued entries: 0
I/iu.UploadsManager( 1770): num updated entries: 0
I/iu.SyncManager( 1770): NEXT; no task
,I/ValidateNoPeople(  819): skipping global notification
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1770): retry (wakeup: false) in 3599960 ms
,D/SystemUpdateService( 1770): onDestroy
,I/Babel   ( 3633): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  819): Start proc 3848:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/ActivityManager(  819): Killing 3527:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/GAv4    ( 3848): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3848):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3848):   adb logcat -s GAv4
,W/GAv4    ( 3848): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3848): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3848): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3848): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3848): Time to load native libraries: 1 ms (timestamps 9079-9080)
,I/LibraryLoader( 3848): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3848): Binding Chromium to main looper Looper (main, tid 1) {29aa0b03}
,I/LibraryLoader( 3848): Expected native library version number "",actual native library version number ""
I/chromium( 3848): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 3848): Initializing chromium process, singleProcess=true
,W/art     ( 3848): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3848): ApplicationContext is null in ApplicationStatus
,W/chromium( 3848): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3848): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3848): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3848): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/NSApplication( 3848): Starting up...
,W/AudioManagerAndroid( 3848): Requires BLUETOOTH permission
,I/ActivityManager(  819): Start proc 3904:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  819): Killing 1473:android.process.acore/u0a5 (adj 15): empty #17
,V/MusicLeanback( 3047): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3828): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3828): simOperator:  IMSI: null
D/SprintDMReceiver( 3828): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1770): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1770): onCreate
,D/SystemUpdateService( 1770): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1770): active receiver: enabled
,I/SystemUpdateService( 1770): showing system update notification
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  819): skipping global notification
,V/SystemUpdateService( 1770): retry (wakeup: false) in 3599981 ms
,D/SystemUpdateService( 1770): onDestroy
,I/ActivityManager(  819): Killing 3607:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/wpa_supplicant( 1139): wlan0: Trying to associate with SSID 'NG7005g'
,I/art     (  819): Explicit concurrent mark sweep GC freed 34683(1731KB) AllocSpace objects, 9(144KB) LOS objects, 32% free, 33MB/49MB, paused 1.486ms total 77.872ms
,I/wpa_supplicant( 1139): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1139): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1139): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  819): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Setting iface cfg
,E/WifiStateMachine(  819): Start Dhcp Watchdog 2
,E/WifiStateMachine(  819):  WifiLinkLayerStats: 
E/WifiStateMachine(  819):  my bss beacon rx: 218
E/WifiStateMachine(  819):  RSSI mgmt: -51
E/WifiStateMachine(  819):  BE :  rx=150 tx=122 lost=0 retries=0
E/WifiStateMachine(  819):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  on_time : 9581 tx_time=155 rx_time=413 scan_time=0
,D/ConnectivityService(  819): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  819): do suspend false
,E/WifiStateMachine(  819): scanCount==0 - aborting
,I/dhcpcd  ( 3936): version 5.5.6 starting
,I/dhcpcd  ( 3936): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3936): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3936): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  819): Adding iface wlan0 to network 101
,E/WifiStateMachine(  819): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  819): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  819): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  819): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  819): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  819): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  819): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  819): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819):    accepting network in place of null
,D/ConnectivityService(  819): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  819): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524290
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  819): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3047): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3047): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  819): Start proc 3969:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,D/SprintDMReceiver( 3828): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1357): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1357): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,I/jxcore-log( 3741): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3741): 
,D/TelephonyManager(  819): getDataEnabled: retVal=false
,D/SprintDMHelper( 3828): simOperator:  IMSI: null
D/SprintDMReceiver( 3828): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1770): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1770): onCreate
,D/SystemUpdateService( 1770): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
E/GpsLocationProvider(  819): No APN found to select.
,I/SystemUpdateService( 1770): active receiver: enabled
,I/SystemUpdateService( 1770): showing system update notification
,I/iu.Environment( 1770): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 14:15:14 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454422514676], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454422514656]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  819): Validated
D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  819): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524290
,I/iu.UploadsManager( 1770): num queued entries: 0
I/iu.UploadsManager( 1770): num updated entries: 0
,I/iu.SyncManager( 1770): NEXT; no task
,D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  819): skipping global notification
D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1770): retry (wakeup: false) in 3599918 ms
,D/SystemUpdateService( 1770): onDestroy
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1770): NQAS connected
,E/HttpOperation( 3230): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3230): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3230): 	at jdm.a(PG:82)
E/HttpOperation( 3230): 	at jcs.o(PG:406)
E/HttpOperation( 3230): 	at jcn.a(PG:1379)
E/HttpOperation( 3230): 	at jcs.i(PG:143)
E/HttpOperation( 3230): 	at blb.a(PG:3937)
E/HttpOperation( 3230): 	at czp.a(PG:18188)
E/HttpOperation( 3230): 	at czp.a(PG:9081)
E/HttpOperation( 3230): 	at czq.run(PG:1686)
E/HttpOperation( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3230): 	at jdj.a(PG:4091)
E/HttpOperation( 3230): 	at jdj.a(PG:1125)
E/HttpOperation( 3230): 	at jdm.a(PG:77)
E/HttpOperation( 3230): 	... 12 more
E/HttpOperation( 3230): Caused by: faj: BadAuthentication
E/HttpOperation( 3230): 	at fal.a(PG:38)
E/HttpOperation( 3230): 	at jdj.a(PG:4089)
E/HttpOperation( 3230): 	... 14 more
,W/Kids    ( 1770): [AccountUtils] Account not ready
W/Kids    ( 1770): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1770): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1770): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1770): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1770): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1770): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1770): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1770): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1770): 	at java.lang.Thread.run(Thread.java:818)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3230): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3230): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3230): 	at jdm.a(PG:82)
E/HttpOperation( 3230): 	at jcs.o(PG:406)
E/HttpOperation( 3230): 	at jcn.a(PG:1379)
E/HttpOperation( 3230): 	at jcs.i(PG:143)
E/HttpOperation( 3230): 	at hec.a(PG:42)
E/HttpOperation( 3230): 	at hee.a(PG:102)
E/HttpOperation( 3230): 	at czr.a(PG:65)
E/HttpOperation( 3230): 	at kka.a(PG:108)
E/HttpOperation( 3230): 	at czp.a(PG:19176)
E/HttpOperation( 3230): 	at czp.a(PG:9081)
E/HttpOperation( 3230): 	at czq.run(PG:1686)
E/HttpOperation( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3230): 	at jdj.a(PG:4091)
E/HttpOperation( 3230): 	at jdj.a(PG:1125)
E/HttpOperation( 3230): 	at jdm.a(PG:77)
E/HttpOperation( 3230): 	... 15 more
E/HttpOperation( 3230): Caused by: faj: BadAuthentication
E/HttpOperation( 3230): 	at fal.a(PG:38)
E/HttpOperation( 3230): 	at jdj.a(PG:4089)
E/HttpOperation( 3230): 	... 17 more
,E/ExperimentLoader( 3230): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3230): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3230): 	at jdm.a(PG:82)
E/ExperimentLoader( 3230): 	at jcs.o(PG:406)
E/ExperimentLoader( 3230): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3230): 	at jcs.i(PG:143)
E/ExperimentLoader( 3230): 	at hec.a(PG:42)
E/ExperimentLoader( 3230): 	at hee.a(PG:102)
E/ExperimentLoader( 3230): 	at czr.a(PG:65)
E/ExperimentLoader( 3230): 	at kka.a(PG:108)
E/ExperimentLoader( 3230): 	at czp.a(PG:19176)
E/ExperimentLoader( 3230): 	at czp.a(PG:9081)
E/ExperimentLoader( 3230): 	at czq.run(PG:1686)
E/ExperimentLoader( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3230): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3230): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3230): 	at jdm.a(PG:77)
E/ExperimentLoader( 3230): 	... 15 more
E/ExperimentLoader( 3230): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3230): 	at fal.a(PG:38)
E/ExperimentLoader( 3230): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3230): 	... 17 more
I/Babel   ( 3633): connection state changed from DISCONNECTED to CONNECTED
D/GCM     ( 1249): Connected
D/GCM     ( 1249): Message class com.google.f.a.a.p
,V/KeepSync( 3969): Connecting to GoogleApiClient
I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3969): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 76408, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  819): Start proc 4013:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3969): IOException
E/KeepSync( 3969): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3969): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3969): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3969): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3969): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3969): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3969): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3969): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3969): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3969): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3969): 	... 10 more
W/KeepSync( 3969): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 76511, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/GAV2    ( 4013): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4013): Created application version: 3.6.8 (30608)
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 18266(1035KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 667us total 19.524ms
,I/BooksSync( 4013): Starting books sync for 61035162, extras: ade
,I/jxcore-log( 3741): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3741): 
,I/BooksConfig( 4013): GmsCore Version = 7.8.99 (2134222-430)
,I/jxcore-log( 3741): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3741): 
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/jxcore-log( 3741): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3741): 
,I/jxcore-log( 3741): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 3741): 
V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  819): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=15.66 rxSuccessRate=15.88 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,I/art     (  819): Explicit concurrent mark sweep GC freed 44668(2MB) AllocSpace objects, 4(158KB) LOS objects, 31% free, 34MB/50MB, paused 1.354ms total 77.866ms
,E/BooksAccountManager( 4013): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4013): Soft error
E/BooksSync( 4013): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4013): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4013): Sync error
E/BooksSync( 4013): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4013): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4013): Finished books sync
,I/ActivityManager(  819): Killing 3396:com.google.android.gm/u0a78 (adj 15): empty #17
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78065, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  819): Killing 2430:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/GAV2    ( 4013): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.33 rxSuccessRate=9.94 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3741): Test app app.js loaded
I/jxcore-log( 3741): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3741): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3741): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3741): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3741): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3741): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3741): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3741): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3741): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3741): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3741): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@398388a2 added. We now have 1 listener(s)
,I/jxcore-log( 3741): BLE advertisement is supported
I/jxcore-log( 3741): 
,I/chromium( 3741): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Finsky  ( 3567): [380] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3567): [380] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3567): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3567): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3567): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.23 rxSuccessRate=5.47 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.35 rxSuccessRate=1.52 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3567): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3567): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3567): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,V/KeepSync( 3969): Connecting to GoogleApiClient
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3230): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3230): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3230): 	at jdm.a(PG:82)
E/HttpOperation( 3230): 	at jcs.o(PG:406)
E/HttpOperation( 3230): 	at jcn.a(PG:1379)
E/HttpOperation( 3230): 	at jcs.i(PG:143)
E/HttpOperation( 3230): 	at blb.a(PG:3937)
E/HttpOperation( 3230): 	at czp.a(PG:18188)
E/HttpOperation( 3230): 	at czp.a(PG:9081)
E/HttpOperation( 3230): 	at czq.run(PG:1686)
E/HttpOperation( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3230): 	at jdj.a(PG:4091)
E/HttpOperation( 3230): 	at jdj.a(PG:1125)
E/HttpOperation( 3230): 	at jdm.a(PG:77)
E/HttpOperation( 3230): 	... 12 more
E/HttpOperation( 3230): Caused by: faj: BadAuthentication
E/HttpOperation( 3230): 	at fal.a(PG:38)
E/HttpOperation( 3230): 	at jdj.a(PG:4089)
E/HttpOperation( 3230): 	... 14 more
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3969): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3230): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3230): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3230): 	at jdm.a(PG:82)
E/HttpOperation( 3230): 	at jcs.o(PG:406)
E/HttpOperation( 3230): 	at jcn.a(PG:1379)
E/HttpOperation( 3230): 	at jcs.i(PG:143)
E/HttpOperation( 3230): 	at hec.a(PG:42)
E/HttpOperation( 3230): 	at hee.a(PG:102)
E/HttpOperation( 3230): 	at czr.a(PG:65)
E/HttpOperation( 3230): 	at kka.a(PG:108)
E/HttpOperation( 3230): 	at czp.a(PG:19176)
E/HttpOperation( 3230): 	at czp.a(PG:9081)
E/HttpOperation( 3230): 	at czq.run(PG:1686)
E/HttpOperation( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3230): 	at jdj.a(PG:4091)
E/HttpOperation( 3230): 	at jdj.a(PG:1125)
E/HttpOperation( 3230): 	at jdm.a(PG:77)
E/HttpOperation( 3230): 	... 15 more
E/HttpOperation( 3230): Caused by: faj: BadAuthentication
E/HttpOperation( 3230): 	at fal.a(PG:38)
E/HttpOperation( 3230): 	at jdj.a(PG:4089)
E/HttpOperation( 3230): 	... 17 more
E/ExperimentLoader( 3230): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3230): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3230): 	at jdm.a(PG:82)
E/ExperimentLoader( 3230): 	at jcs.o(PG:406)
E/ExperimentLoader( 3230): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3230): 	at jcs.i(PG:143)
E/ExperimentLoader( 3230): 	at hec.a(PG:42)
E/ExperimentLoader( 3230): 	at hee.a(PG:102)
E/ExperimentLoader( 3230): 	at czr.a(PG:65)
E/ExperimentLoader( 3230): 	at kka.a(PG:108)
E/ExperimentLoader( 3230): 	at czp.a(PG:19176)
E/ExperimentLoader( 3230): 	at czp.a(PG:9081)
E/ExperimentLoader( 3230): 	at czq.run(PG:1686)
E/ExperimentLoader( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3230): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3230): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3230): 	at jdm.a(PG:77)
E/ExperimentLoader( 3230): 	... 15 more
E/ExperimentLoader( 3230): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3230): 	at fal.a(PG:38)
E/ExperimentLoader( 3230): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3230): 	... 17 more
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 113211, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 4013): Starting books sync for 61035162, extras: ade
E/KeepSync( 3969): IOException
E/KeepSync( 3969): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3969): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3969): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3969): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3969): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3969): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3969): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3969): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3969): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3969): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3969): 	... 10 more
W/KeepSync( 3969): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 115501, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/BooksConfig( 4013): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4013): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4013): Soft error
E/BooksSync( 4013): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4013): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4013): Sync error
E/BooksSync( 4013): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4013): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4013): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 115713, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1230): run()
I/Keyboard.Facilitator( 1230): flushDynamicLanguageModels()
,I/ConfigService( 1249): onCreate
,I/ConfigService( 1249): onDestroy
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.83 rxSuccessRate=3.48 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 31891(1930KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 2.469ms total 66.334ms
,I/art     (  819): Explicit concurrent mark sweep GC freed 46904(2MB) AllocSpace objects, 17(554KB) LOS objects, 31% free, 34MB/50MB, paused 1.547ms total 74.193ms
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3567): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3567): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3567): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.47 rxSuccessRate=3.94 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  819): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  819): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (231 us)
,I/DisplayManagerService(  819): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0,
,V/ActivityManager(  819): Display changed displayId=0
,I/kickstart(  869): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  869): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  869): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  819): Excessive delay in setPowerMode(): 257ms
,I/DreamManagerService(  819): Entering dreamland.,
I/PowerManagerService(  819): Dozing...
I/DreamController(  819): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  819): cancelDelayedScan -> 12
,E/native  (  819): do suspend false
,I/Keyboard.Facilitator( 1230): onFinishInput()
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  819): cancelDelayedScan -> 14
,E/native  (  819): do suspend true
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3567): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3567): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3567): [1] 5.onFinished: Scheduling replication attempt 5.
,I/kickstart(  869): STATUS: Received file 'm9kefs1'
I/kickstart(  869): STATUS: 950272 bytes transferred in 1.020006 seconds
I/kickstart(  869): STATUS: Successfully downloaded files from target 
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  869): STATUS: Sahara protocol completed
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3802): [410] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1249): Vacuum at: now=1454422616831 tag=VacuumService
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1249): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3567): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/Finsky  ( 3567): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3567): [1] 5.onFinished: Giving up after 6 failures.
,W/ExperimentUpdateService( 3802): [410] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3802): [410] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3802): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3802): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3802): 	at com.a.a.k.run(SourceFile:110)
,E/Uploader( 1249): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1249): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1249): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1249): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1249): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1249): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1249): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1249): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1249): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1249): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1249): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1249): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249): No account for auth token provided
,W/Uploader( 1249):  no longer exists, so no auth token.
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1249): Failed to get auth token: User intervention required. Notification has been pushed.
,E/Uploader( 1249): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1249): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.b(SourceFile:477),
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1249): ,	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1249): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1249): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1249): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1249): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1249): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1249): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1249): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3230): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3230): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3230): 	at jdm.a(PG:82)
E/HttpOperation( 3230): 	at jcs.o(PG:406)
E/HttpOperation( 3230): 	at jcn.a(PG:1379)
E/HttpOperation( 3230): 	at jcs.i(PG:143)
E/HttpOperation( 3230): 	at blb.a(PG:3937)
E/HttpOperation( 3230): 	at czp.a(PG:18188)
E/HttpOperation( 3230): 	at czp.a(PG:9081)
E/HttpOperation( 3230): 	at czq.run(PG:1686)
E/HttpOperation( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3230): 	at jdj.a(PG:4091)
E/HttpOperation( 3230): 	at jdj.a(PG:1125)
E/HttpOperation( 3230): 	at jdm.a(PG:77)
E/HttpOperation( 3230): 	... 12 more
E/HttpOperation( 3230): Caused by: faj: BadAuthentication
E/HttpOperation( 3230): 	at fal.a(PG:38)
E/HttpOperation( 3230): 	at jdj.a(PG:4089)
E/HttpOperation( 3230): 	... 14 more
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3230): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3230): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3230): 	at jdm.a(PG:82)
E/HttpOperation( 3230): 	at jcs.o(PG:406)
E/HttpOperation( 3230): 	at jcn.a(PG:1379)
E/HttpOperation( 3230): 	at jcs.i(PG:143)
E/HttpOperation( 3230): 	at hec.a(PG:42)
E/HttpOperation( 3230): 	at hee.a(PG:102)
E/HttpOperation( 3230): 	at czr.a(PG:65)
E/HttpOperation( 3230): 	at kka.a(PG:108)
E/HttpOperation( 3230): 	at czp.a(PG:19176)
E/HttpOperation( 3230): 	at czp.a(PG:9081)
E/HttpOperation( 3230): 	at czq.run(PG:1686)
E/HttpOperation( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3230): 	at jdj.a(PG:4091)
E/HttpOperation( 3230): 	at jdj.a(PG:1125)
E/HttpOperation( 3230): 	at jdm.a(PG:77)
E/HttpOperation( 3230): 	... 15 more
E/HttpOperation( 3230): Caused by: faj: BadAuthentication
E/HttpOperation( 3230): 	at fal.a(PG:38)
E/HttpOperation( 3230): 	at jdj.a(PG:4089)
E/HttpOperation( 3230): 	... 17 more
E/ExperimentLoader( 3230): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3230): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3230): 	at jdm.a(PG:82)
E/ExperimentLoader( 3230): 	at jcs.o(PG:406)
E/ExperimentLoader( 3230): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3230): 	at jcs.i(PG:143)
E/ExperimentLoader( 3230): 	at hec.a(PG:42)
E/ExperimentLoader( 3230): 	at hee.a(PG:102)
E/ExperimentLoader( 3230): 	at czr.a(PG:65)
E/ExperimentLoader( 3230): 	at kka.a(PG:108)
E/ExperimentLoader( 3230): 	at czp.a(PG:19176)
E/ExperimentLoader( 3230): 	at czp.a(PG:9081)
E/ExperimentLoader( 3230): 	at czq.run(PG:1686)
E/ExperimentLoader( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3230): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3230): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3230): 	at jdm.a(PG:77)
E/ExperimentLoader( 3230): 	... 15 more
E/ExperimentLoader( 3230): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3230): 	at fal.a(PG:38)
E/ExperimentLoader( 3230): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3230): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 195197, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3802): [411] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 44952(2MB) AllocSpace objects, 13(396KB) LOS objects, 31% free, 34MB/50MB, paused 1.892ms total 92.291ms
,W/ExperimentUpdateService( 3802): [411] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3802): [411] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3802): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3802): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3802): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1230): run()
I/Keyboard.Facilitator( 1230): flushDynamicLanguageModels()
,I/ConfigService( 1249): onCreate
,I/BooksSync( 4013): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4013): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3969): Connecting to GoogleApiClient
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3969): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 63170(3MB) AllocSpace objects, 9(907KB) LOS objects, 36% free, 27MB/43MB, paused 1.055ms total 50.250ms
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4013): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4013): Soft error
E/BooksSync( 4013): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4013): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4013): Sync error
E/BooksSync( 4013): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4013): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4013): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 199104, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3969): IOException
E/KeepSync( 3969): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3969): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3969): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3969): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3969): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3969): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3969): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3969): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3969): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3969): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3969): 	... 10 more
,W/KeepSync( 3969): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 199569, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1249): onDestroy
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3802): [412] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3802): [412] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3802): [412] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3802): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3802): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3802): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3802): [413] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3802): [414] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3802): [414] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3802): [414] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	,at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3802): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3802): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3802): 	at com.a.a.k.run(SourceFile:110)
W/ExperimentUpdateService( 3802): [413] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3802): [413] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3802): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	,at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3802): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3802): Caused by: com.a.a.a: User needs to (re)enter credentials.
,W/ExperimentUpdateService( 3802): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3802): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3230): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3230): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3230): 	at jdm.a(PG:82)
E/HttpOperation( 3230): 	at jcs.o(PG:406)
E/HttpOperation( 3230): 	at jcn.a(PG:1379)
E/HttpOperation( 3230): 	at jcs.i(PG:143)
E/HttpOperation( 3230): 	at blb.a(PG:3937)
E/HttpOperation( 3230): 	at czp.a(PG:18188)
E/HttpOperation( 3230): 	at czp.a(PG:9081)
E/HttpOperation( 3230): 	at czq.run(PG:1686)
E/HttpOperation( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3230): 	at jdj.a(PG:4091)
E/HttpOperation( 3230): 	at jdj.a(PG:1125)
E/HttpOperation( 3230): 	at jdm.a(PG:77)
E/HttpOperation( 3230): 	... 12 more
E/HttpOperation( 3230): Caused by: faj: BadAuthentication
E/HttpOperation( 3230): 	at fal.a(PG:38)
E/HttpOperation( 3230): 	at jdj.a(PG:4089)
E/HttpOperation( 3230): 	... 14 more
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3230): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3230): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3230): 	at jdm.a(PG:82)
E/HttpOperation( 3230): 	at jcs.o(PG:406)
E/HttpOperation( 3230): 	at jcn.a(PG:1379)
E/HttpOperation( 3230): 	at jcs.i(PG:143)
E/HttpOperation( 3230): 	at hec.a(PG:42)
E/HttpOperation( 3230): 	at hee.a(PG:102)
E/HttpOperation( 3230): 	at czr.a(PG:65)
E/HttpOperation( 3230): 	at kka.a(PG:108)
E/HttpOperation( 3230): 	at czp.a(PG:19176)
E/HttpOperation( 3230): 	at czp.a(PG:9081)
E/HttpOperation( 3230): 	at czq.run(PG:1686)
E/HttpOperation( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
,E/HttpOperation( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3230): 	at java.lang.Thread.run(Thread.java:818)
,E/HttpOperation( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3230): 	at jdj.a(PG:4091)
E/HttpOperation( 3230): 	at jdj.a(PG:1125)
E/HttpOperation( 3230): 	at jdm.a(PG:77)
E/HttpOperation( 3230): 	... 15 more
E/HttpOperation( 3230): Caused by: faj: BadAuthentication
E/HttpOperation( 3230): 	at fal.a(PG:38)
,E/HttpOperation( 3230): 	at jdj.a(PG:4089)
E/HttpOperation( 3230): 	... 17 more
,E/ExperimentLoader( 3230): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3230): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3230): ,	,at jdm.a(PG:82)
E/ExperimentLoader( 3230): 	at jcs.o(PG:406),
E/ExperimentLoader( 3230): 	at jcn.a(PG:1379)
,E/ExperimentLoader( 3230): 	at jcs.i(PG:143)
E/ExperimentLoader( 3230): ,	at hec.a(PG:42)
E/ExperimentLoader( 3230): 	,at hee.a(PG:102)
E/ExperimentLoader( 3230): 	,at czr.a(PG:65)
,E/ExperimentLoader( 3230): ,	at kka.a(PG:108)
E/ExperimentLoader( 3230): 	at czp.a(PG:19176)
,E/ExperimentLoader( 3230): 	at czp.a(PG:9081)
E/ExperimentLoader( 3230): 	at czq.run(PG:1686)
E/ExperimentLoader( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3230): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3230): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3230): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3230): 	at jdm.a(PG:77)
E/ExperimentLoader( 3230): 	... 15 more
E/ExperimentLoader( 3230): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3230): 	at fal.a(PG:38)
E/ExperimentLoader( 3230): ,	at jdj.a(PG:4089)
E/ExperimentLoader( 3230): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 317375, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1a60c609}
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1a60c609}
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@60ba2f}
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@60ba2f}
,V/GoogleAuthProtoRequest( 3802): [415] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  819): Explicit concurrent mark sweep GC freed 34832(1597KB) AllocSpace objects, 13(679KB) LOS objects, 31% free, 34MB/50MB, paused 1.649ms total 69.687ms
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova,
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3802): [415] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3802): [415] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3802): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3802): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3802): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1249): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1249): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1249): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1249): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1249): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1249): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1249): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3567): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 3567): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3567): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3567): ,	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3567): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3567): 	,at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3567): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3567): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,I/BooksSync( 4013): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4013): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3969): Connecting to GoogleApiClient
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3969): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/BooksAccountManager( 4013): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4013): Soft error
E/BooksSync( 4013): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4013): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4013): Sync error
E/BooksSync( 4013): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4013): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4013): Finished books sync
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 354560, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3969): IOException
E/KeepSync( 3969): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3969): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3969): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3969): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3969): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3969): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3969): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3969): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3969): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3969): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3969): 	... 10 more
W/KeepSync( 3969): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 356119, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3802): [416] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3802): [416] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3802): [416] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3802): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3802): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3802): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3802): [417] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 55276(2MB) AllocSpace objects, 14(1543KB) LOS objects, 36% free, 27MB/43MB, paused 1.030ms total 38.974ms
,W/ExperimentUpdateService( 3802): [417] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3802): [417] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3802): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3802): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3802): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3230): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3230): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3230): 	at jdm.a(PG:82)
E/HttpOperation( 3230): 	at jcs.o(PG:406)
E/HttpOperation( 3230): 	at jcn.a(PG:1379)
E/HttpOperation( 3230): 	at jcs.i(PG:143)
E/HttpOperation( 3230): 	at blb.a(PG:3937)
E/HttpOperation( 3230): 	at czp.a(PG:18188)
E/HttpOperation( 3230): 	at czp.a(PG:9081)
E/HttpOperation( 3230): 	at czq.run(PG:1686)
E/HttpOperation( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3230): 	at jdj.a(PG:4091)
E/HttpOperation( 3230): 	at jdj.a(PG:1125)
E/HttpOperation( 3230): 	at jdm.a(PG:77)
E/HttpOperation( 3230): 	... 12 more
E/HttpOperation( 3230): Caused by: faj: BadAuthentication
E/HttpOperation( 3230): 	at fal.a(PG:38)
E/HttpOperation( 3230): 	at jdj.a(PG:4089)
E/HttpOperation( 3230): 	... 14 more
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3230): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3230): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3230): 	at jdm.a(PG:82)
E/HttpOperation( 3230): 	at jcs.o(PG:406)
E/HttpOperation( 3230): 	at jcn.a(PG:1379)
E/HttpOperation( 3230): 	at jcs.i(PG:143)
E/HttpOperation( 3230): 	at hec.a(PG:42)
E/HttpOperation( 3230): 	at hee.a(PG:102)
E/HttpOperation( 3230): 	at czr.a(PG:65)
E/HttpOperation( 3230): 	at kka.a(PG:108)
E/HttpOperation( 3230): 	at czp.a(PG:19176)
E/HttpOperation( 3230): 	at czp.a(PG:9081)
E/HttpOperation( 3230): 	at czq.run(PG:1686)
E/HttpOperation( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3230): 	at jdj.a(PG:4091)
E/HttpOperation( 3230): 	at jdj.a(PG:1125)
E/HttpOperation( 3230): 	at jdm.a(PG:77)
E/HttpOperation( 3230): 	... 15 more
E/HttpOperation( 3230): Caused by: faj: BadAuthentication
E/HttpOperation( 3230): 	at fal.a(PG:38)
E/HttpOperation( 3230): 	at jdj.a(PG:4089)
E/HttpOperation( 3230): 	... 17 more
,E/ExperimentLoader( 3230): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3230): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3230): 	at jdm.a(PG:82)
E/ExperimentLoader( 3230): 	at jcs.o(PG:406)
E/ExperimentLoader( 3230): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3230): 	at jcs.i(PG:143),
E/ExperimentLoader( 3230): 	at hec.a(PG:42)
E/ExperimentLoader( 3230): 	at hee.a(PG:102)
E/ExperimentLoader( 3230): 	at czr.a(PG:65)
E/ExperimentLoader( 3230): 	at kka.a(PG:108)
E/ExperimentLoader( 3230): 	at czp.a(PG:19176)
E/ExperimentLoader( 3230): 	at czp.a(PG:9081)
E/ExperimentLoader( 3230): 	at czq.run(PG:1686)
E/ExperimentLoader( 3230): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3230): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3230): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3230): 	at jdm.a(PG:77)
E/ExperimentLoader( 3230): 	... 15 more
,E/ExperimentLoader( 3230): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3230): 	at fal.a(PG:38)
E/ExperimentLoader( 3230): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3230): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 561285, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,I/BooksSync( 4013): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4013): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 36560(1596KB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 2.509ms total 88.361ms
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4013): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4013): Soft error
E/BooksSync( 4013): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4013): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4013): Sync error
E/BooksSync( 4013): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4013): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4013): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 635569, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3802): [418] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3802): [418] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3802): [418] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3802): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3802): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3802): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,V/KeepSync( 3969): Connecting to GoogleApiClient
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): 	... 7 more
,V/KeepSync( 3969): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3969): IOException
E/KeepSync( 3969): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3969): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3969): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3969): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3969): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3969): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3969): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3969): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3969): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3969): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3969): 	... 10 more
W/KeepSync( 3969): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 638519, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3802): [419] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3802): [419] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3802): [419] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3802): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3802): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3802): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2158): Stopping oneshot timer
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3230): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3230): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3230): 	at jdm.a(PG:82)
E/HttpOperation( 3230): 	at jcs.o(PG:406)
E/HttpOperation( 3230): 	at jcn.a(PG:1379)
E/HttpOperation( 3230): 	at jcs.i(PG:143)
E/HttpOperation( 3230): 	at blb.a(PG:3937)
E/HttpOperation( 3230): 	at czp.a(PG:18188)
E/HttpOperation( 3230): 	at czp.a(PG:9081)
E/HttpOperation( 3230): 	at czq.run(PG:1686)
E/HttpOperation( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3230): 	at jdj.a(PG:4091)
E/HttpOperation( 3230): 	at jdj.a(PG:1125)
E/HttpOperation( 3230): 	at jdm.a(PG:77)
E/HttpOperation( 3230): 	... 12 more
E/HttpOperation( 3230): Caused by: faj: BadAuthentication
E/HttpOperation( 3230): 	at fal.a(PG:38)
E/HttpOperation( 3230): 	at jdj.a(PG:4089)
E/HttpOperation( 3230): 	... 14 more
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3230): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3230): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3230): 	at jdm.a(PG:82)
E/HttpOperation( 3230): 	at jcs.o(PG:406)
E/HttpOperation( 3230): 	at jcn.a(PG:1379)
E/HttpOperation( 3230): 	at jcs.i(PG:143)
E/HttpOperation( 3230): 	at hec.a(PG:42)
E/HttpOperation( 3230): 	at hee.a(PG:102)
E/HttpOperation( 3230): 	at czr.a(PG:65)
E/HttpOperation( 3230): 	at kka.a(PG:108)
E/HttpOperation( 3230): 	at czp.a(PG:19176)
E/HttpOperation( 3230): 	at czp.a(PG:9081)
E/HttpOperation( 3230): 	at czq.run(PG:1686)
E/HttpOperation( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3230): 	at jdj.a(PG:4091)
E/HttpOperation( 3230): 	at jdj.a(PG:1125)
E/HttpOperation( 3230): 	at jdm.a(PG:77)
E/HttpOperation( 3230): 	... 15 more
E/HttpOperation( 3230): Caused by: faj: BadAuthentication
E/HttpOperation( 3230): 	at fal.a(PG:38)
E/HttpOperation( 3230): 	at jdj.a(PG:4089)
E/HttpOperation( 3230): 	... 17 more
E/ExperimentLoader( 3230): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3230): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3230): 	at jdm.a(PG:82)
E/ExperimentLoader( 3230): 	at jcs.o(PG:406)
E/ExperimentLoader( 3230): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3230): 	at jcs.i(PG:143)
E/ExperimentLoader( 3230): 	at hec.a(PG:42)
E/ExperimentLoader( 3230): 	at hee.a(PG:102)
E/ExperimentLoader( 3230): 	at czr.a(PG:65)
E/ExperimentLoader( 3230): 	at kka.a(PG:108)
E/ExperimentLoader( 3230): 	at czp.a(PG:19176)
E/ExperimentLoader( 3230): 	at czp.a(PG:9081)
E/ExperimentLoader( 3230): 	at czq.run(PG:1686)
E/ExperimentLoader( 3230): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3230): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3230): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3230): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3230): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3230): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3230): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3230): 	at jdm.a(PG:77)
E/ExperimentLoader( 3230): 	... 15 more
E/ExperimentLoader( 3230): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3230): 	at fal.a(PG:38)
E/ExperimentLoader( 3230): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3230): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1048451, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1fc6b3be}
,I/EventLogService( 1770): Opted in for usage reporting
D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1fc6b3be}
,I/EventLogService( 1770): Aggregate from 1454421720252 (log), 1454421720252 (data)
,D/GCM     ( 1249): Message class com.google.f.a.a.i
,I/art     ( 1249): Explicit concurrent mark sweep GC freed 62924(3MB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 27MB/43MB, paused 2.174ms total 43.047ms
,W/EventLogAggregator( 1770): Unknown tag: snet_gcore
,W/EventLogAggregator( 1770): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1770): dumping service [account]
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3802): [420] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     (  819): Explicit concurrent mark sweep GC freed 40876(1934KB) AllocSpace objects, 9(521KB) LOS objects, 31% free, 34MB/50MB, paused 1.701ms total 68.621ms
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3802): [420] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3802): [420] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3802): 	,at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3802): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3802): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,I/BooksSync( 4013): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4013): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4013): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4013): Soft error,
E/BooksSync( 4013): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4013): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4013): Sync error
,E/BooksSync( 4013): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4013): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4013): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1151664, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3802): [421] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3802): [421] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3802): [421] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3802): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3802): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3802): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3802): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3802): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,V/KeepSync( 3969): Connecting to GoogleApiClient
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1770): Handling authorization failure
E/ClientConnectionOperation( 1770): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
,E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1770): Caused by: com.google.android.gms.auth.ad: BadAuthentication
,E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
,E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1770): ,	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1770): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1770): ,	... 7 more
V/KeepSync( 3969): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3969): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1249): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1249): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1249): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1249): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1249): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3969): IOException
E/KeepSync( 3969): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3969): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3969): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3969): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3969): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3969): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3969): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3969): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3969): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3969): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3969): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3969): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3969): 	... 10 more
W/KeepSync( 3969): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1187555, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/UsageStatsService(  819): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2158): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4354): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4354): CheckJNI is OFF
D/AndroidRuntime( 4354): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  819): Killing 3741:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  819): Skipping PackageSetting{300ecf28 com.example.hello/10273} due to missing metadata
I/WindowState(  819): WIN DEATH: Window{2b445a11 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  819): Client connection lost with reason: 4
W/ActivityManager(  819): Force removing ActivityRecord{91740ec u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
V/ActivityManager(  819): Display changed displayId=0
W/ActivityManager(  819): Spurious death for ProcessRecord{37a761d 3741:com.test.thalitest/u0a265}, curProc for 3741: null
I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
I/Keyboard.Facilitator( 1230): resetDictionaries() : en_US
D/BuaReceiver( 3457): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator.DecoderInitializer( 1230): run()
D/TaskPersister(  819): removeObsoleteFile: deleting file=28_task.xml
I/Decoder ( 1230): createOrResetDecoder
I/InputReader(  819): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  819): Start proc 4371:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     ( 1063): Explicit concurrent mark sweep GC freed 75399(3MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 7.399ms total 79.532ms
W/InputMethodManagerService(  819): Got RemoteException sending setActive(false) notification to pid 3741 uid 10265
I/Keyboard.Facilitator( 1230): onFinishInput()
I/art     ( 1529): Explicit concurrent mark sweep GC freed 1448(129KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 804us total 110.037ms
I/art     ( 1529): WaitForGcToComplete blocked for 13.180ms for cause HeapTrim
I/art     (  819): Explicit concurrent mark sweep GC freed 28927(1639KB) AllocSpace objects, 9(238KB) LOS objects, 31% free, 34MB/50MB, paused 2.251ms total 114.767ms
I/ConfigService( 1249): onCreate
I/art     (  819): WaitForGcToComplete blocked for 102.734ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1230): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1230): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1230): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1230): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1230): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1230): run()
I/StatsUtilsManager( 1230): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1230): shouldRecordStats() = Too Soon
I/art     ( 1401): Explicit concurrent mark sweep GC freed 5713(420KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 610us total 23.309ms
W/LocationOracleImpl( 1529): Best location was null
I/HotwordRecognitionRnr( 1529): Starting hotword detection.
D/JobSchedulerService(  819): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  819): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/MicrophoneInputStream( 1529): mic_starting com.google.android.apps.gsa.speech.audio.u@30131461
I/AudioFlinger(  356): AudioFlinger's thread 0xb405a000 ready to run
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1529): mic_started com.google.android.apps.gsa.speech.audio.u@30131461
D/audio_hw_primary(  356): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  356): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  356): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  356): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  356): enable_audio_route: apply and update mixer path: audio-record
D/VoicemailCleanupService( 4371): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  819): Start proc 4410:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
D/Launcher.Workspace( 1401): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1401): 11683562 - stripEmptyScreens()
I/art     ( 1789): Explicit concurrent mark sweep GC freed 16652(997KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.600ms total 28.522ms
E/DataBuffer( 1789): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@28a6d40b)
I/art     (  819): Explicit concurrent mark sweep GC freed 8633(414KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 1.710ms total 171.453ms
I/HotwordWorker( 1529): onReady
I/ActivityManager(  819): Start proc 4432:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/art     (  367): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 212us total 9.549ms
I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 273us total 9.244ms
D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3cb3386b}
I/ContactLocale( 4371): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=22.50 rxSuccessRate=27.00 targetRoamBSSID=any RSSI=-51
I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 195us total 8.768ms
W/ContextImpl( 4432): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=68.25 rxSuccessRate=192.50 targetRoamBSSID=any RSSI=-51
E/NetworkScheduler.SchedulerReceiver( 1249): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1249): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1770): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1770): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/art     ( 4354): System.exit called, status: 0
I/AndroidRuntime( 4354): VM exiting with result code 0.
D/ChimeraCfgMgr( 1770): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1770): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1770): Clearing selected account for com.test.thalitest
W/Launcher( 1401): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3a7ad497 new=com.google.android.velvet.VelvetApplication@3a7ad497
I/UpdateIcingCorporaServi( 1529): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/LocationSettingsChecker( 1770): Removing dialog suppression flag for package com.test.thalitest
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659634963
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  819): Killing 3378:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
D/GOOGLEHELP_CompatibleDatabase( 1770): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1770): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1770): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1770): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1770): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1770): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1770): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1770): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/kickstart(  869): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_lock
I/ActivityManager(  819): Start proc 4461:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
E/SQLiteLog( 4371): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 4371): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4371): Process: android.process.acore, PID: 4371
E/AndroidRuntime( 4371): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4371): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4371): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 4371): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4371): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4371): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4371): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4371): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
E/AndroidRuntime( 4371): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
E/AndroidRuntime( 4371): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1706)
E/AndroidRuntime( 4371): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4371): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4371): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4371): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/kickstart(  869): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  869): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
I/ActivityManager(  819): Start proc 4479:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/SQLiteDatabase( 1770): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1770): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1770): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1770): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1770): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1770): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1770): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1770): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1770): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1770): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1770): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1770): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1770): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1770): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1770): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1770): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1770): Opened phenotype.db in read-only mode
E/DropBoxManagerService(  819): Can't write: system_app_crash
E/DropBoxManagerService(  819): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
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
D/OpenGLRenderer(  819): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  819): Validating map...
I/UpdateIcingCorporaServi( 1529): UpdateCorporaTask done [took 162 ms] updated apps [took 162 ms] 
I/ConfigFetchService( 1770): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1770): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
I/ConfigFetchService( 1770): service connected
W/ResourcesManager( 4479): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4479): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/PeopleContactsSync( 1770): CP2 sync disabled
I/Icing   ( 1770): doRemovePackageData com.test.thalitest
W/BaseAppContext( 1770): Using Auth Proxy for data requests.
W/BaseAppContext( 1770): Using Auth Proxy for data requests.
I/OpenGLRenderer(  819): Initialized EGL, version 1.4
E/SQLiteDatabase( 1770): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1770): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1770): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1770): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1770): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1770): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1770): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1770): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1770): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1770): Runtime exception while performing operation
E/ClearPendingStateOp( 1770): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1770): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1770): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1770): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1770): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1770): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1770): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1770): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1770): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1770): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1770): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1770): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1770): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1770): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1770): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1770): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1770): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1770): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1770): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1770): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1770): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1770): 	at java.lang.Thread.run(Thread.java:818)
I/MultiDex( 4479): VM with version 2.1.0 has multidex support
I/MultiDex( 4479): install
D/OpenGLRenderer(  819): Enabling debug mode 0
E/DropBoxManagerService(  819): Can't write: system_app_wtf
E/DropBoxManagerService(  819): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
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
I/MultiDex( 4479): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 4479): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ProviderInstaller( 4479): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4479): Failed to open lock file
W/NativeLibraryUtils( 4479): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4479): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4479): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4479): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4479): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4479): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4479): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4479): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4479): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4479): 	... 3 more
I/ActivityManager(  819): Killing 3358:com.android.providers.calendar/u0a3 (adj 15): empty #17
I/HotwordDetector( 1529): Closing mic
I/MicrophoneInputStream( 1529): mic_close com.google.android.apps.gsa.speech.audio.u@30131461
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1529): Hotword detection finished
I/HotwordRecognitionRnr( 1529): Stopping hotword detection.
E/Search.SharedPreferencesProto( 1529): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/ActivityManager(  819): Killing 3047:com.google.android.music:main/u0a66 (adj 15): empty #17
I/GAv4    ( 4461): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4461):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4461):   adb logcat -s GAv4
W/GAv4    ( 4461): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4461): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4461): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4461): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4461): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4461): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4461): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4461): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4461): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4461): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4461): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4461): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4461): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4461): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4461): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4461): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4461): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4461): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4461): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4461): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4461): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4461): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4461): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4461): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4461): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4461): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4461): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4461): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4461): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4461): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4461): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4461): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4461): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4461): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4461): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4461): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4461): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4461): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4461): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4461): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4461): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4461): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4461): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4461): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4461): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4461): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4461): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4461): 	at aen.run(PG:536)
E/native  ( 1230): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1230): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1230): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1230): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1230): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1230): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1230): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1230): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/SQLiteDatabase( 4461): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4461): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4461): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4461): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4461): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4461): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4461): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4461): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4461): 	at aej.c(PG:139)
E/SQLiteDatabase( 4461): 	at aej.b(PG:398)
E/SQLiteDatabase( 4461): 	at agf.f(PG:417)
E/SQLiteDatabase( 4461): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4461): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4461): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4461): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4461): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4461): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4461): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4461): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4461): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4461): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4461): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4461): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4461): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4461): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4461): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4461): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4461): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4461): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4461): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4461): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4461): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4461): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4461): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4461): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4461): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4461): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4461): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4461): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4461): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 4461): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4461): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4461): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4461): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4461): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4461): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4461): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4461): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4461): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 4461): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4461): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4461): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4461): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4461): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4461): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4461): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4461): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4461): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4461): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4461): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4461): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4461): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4461): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4461): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 4461): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4461): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  819): Start proc 4526:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  819): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/JNIHelp ( 4461): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
V/WindowManager(  819): addAppToken: AppWindowToken{39b8eae9 token=Token{22713770 ActivityRecord{30f655b3 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4461): Sending signal. PID: 4461 SIG: 9
E/lowmemorykiller(  257): Error writing /proc/4461/oom_score_adj; errno=22
E/JavaBinder(  819): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  819): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  819): android.os.TransactionTooLargeException
W/ActivityManager(  819): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  819): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  819): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:1249)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:2952)
W/ActivityManager(  819): 	at com.android.server.am.ActivityStackSupervisor.attachApplicationLocked(ActivityStackSupervisor.java:564)
W/ActivityManager(  819): 	at com.android.server.am.ActivityManagerService.attachApplicationLocked(ActivityManagerService.java:6021)
W/ActivityManager(  819): 	at com.android.server.am.ActivityManagerService.attachApplication(ActivityManagerService.java:6083)
W/ActivityManager(  819): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:480)
W/ActivityManager(  819): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  819): 	at android.os.Binder.execTransact(Binder.java:446)
E/kickstart(  869): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  869): WARNING: function: sahara_start:892 Retrying memory read request
I/Icing   ( 1770): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
I/ActivityManager(  819): Start proc 4543:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  819): Spurious death for ProcessRecord{148e8ca 4543:com.google.android.apps.docs/u0a46}, curProc for 4461: null
W/OpenGLRenderer( 1401): Incorrectly called buildLayer on View: ew, destroying layer...
E/Icing   ( 1770): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1770): Could not init tag ds.tag.deleted
E/ActivityThread( 1401): Performing stop of activity that is not resumed: {com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
E/ActivityThread( 1401): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
E/ActivityThread( 1401): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3344)
E/ActivityThread( 1401): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3425)
E/ActivityThread( 1401): 	at android.app.ActivityThread.access$1100(ActivityThread.java:151)
E/ActivityThread( 1401): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1332)
E/ActivityThread( 1401): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1401): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 1401): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/ActivityThread( 1401): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1401): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1401): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/ActivityThread( 1401): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
I/ActivityManager(  819): Activity reported stop, but no longer stopping: ActivityRecord{25eb7656 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t27}
E/SQLiteDatabase( 4526): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4526): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4526): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4526): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4526): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4526): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4526): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4526): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4526): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4526): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4526): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4526): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4526): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4526): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4526): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4526): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4526): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4526): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4526): Shutting down VM
D/GCM     ( 1249): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/AndroidRuntime( 4526): FATAL EXCEPTION: main
E/AndroidRuntime( 4526): Process: com.android.documentsui, PID: 4526
E/AndroidRuntime( 4526): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4526): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4526): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4526): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4526): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4526): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4526): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4526): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4526): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4526): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4526): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4526): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4526): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteOpenHelper.ge,tDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4526): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4526): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4526): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4526): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4526): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4526): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4526): 	... 9 more
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
I/Icing   ( 1770): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
I/ActivityManager(  819): Killing 3828:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
D/AuthorizationBluetoothService( 1249): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/ActivityManager(  819): Start proc 4565:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
V/GmsCoreStatsServiceLauncher( 1770): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 4479): callingUid 10011, callindPid: 4479
E/Icing   ( 1770): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1770): Writing status failed
E/Icing   ( 1770): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)

```
