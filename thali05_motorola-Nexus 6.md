#### Test 58497659c9ea290_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  822): Waited long enough for: ServiceRecord{3c213179 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,--------- beginning of main
D/AndroidRuntime( 3719): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3719): CheckJNI is OFF
D/AndroidRuntime( 3719): Calling main entry com.android.commands.am.Am
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{161ab0f0 token=Token{32dbc533 ActivityRecord{370d44a2 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3719): Shutting down VM
I/HotwordDetector( 1486): Closing mic
I/MicrophoneInputStream( 1486): mic_close com.google.android.apps.gsa.speech.audio.u@15ae5de2
V/WindowManager(  822): Adding window Window{2aba4025 u0 Starting com.test.thalitest} at 2 of 7 (after Window{364df26 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  822): Start proc 3733:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1486): Stopping hotword detection.
I/HotwordRecognitionRnr( 1486): Hotword detection finished
I/ActivityManager(  822): Killing 2562:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/WebViewFactory( 3733): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3733): Time to load native libraries: 5 ms (timestamps 3961-3966)
I/LibraryLoader( 3733): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3733): Binding Chromium to main looper Looper (main, tid 1) {26538e26}
,I/LibraryLoader( 3733): Expected native library version number "",actual native library version number ""
I/chromium( 3733): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659417875
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/BrowserStartupController( 3733): Initializing chromium process, singleProcess=true
,W/art     ( 3733): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 3733): ApplicationContext is null in ApplicationStatus
,W/chromium( 3733): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3733): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3733): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3733): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a8dec7f:true
,W/art     ( 3733): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3733): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3733): CordovaWebView is running on device made by: motorola,
,W/art     ( 3733): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3733): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3733): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3733): Validating map...
,V/WindowManager(  822): Adding window Window{1fc0f36f u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2aba4025 u0 Starting com.test.thalitest})
,W/chromium( 3733): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3733): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3733): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +728ms
,I/Keyboard.Facilitator( 1211): onFinishInput()
,W/BindingManager( 3733): Cannot call determinedVisibility() - never saw a connection for the pid: 3733
,D/JsMessageQueue( 3733): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  822): Killing 3501:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3440:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,D/jxcore_app_log( 3733): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576386944
,I/chromium( 3733): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3733): Initializing JXcore engine
W/jxcore-log( 3733): JXcore engine is ready
,W/Thread-411( 3786): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12528]" dev="sockfs" ino=12528 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-411( 3786): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-411( 3786): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9846]" dev="sockfs" ino=9846 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-411( 3786): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20297]" dev="sockfs" ino=20297 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3733): Starting JXcore engine
,W/jxcore-log( 3733): Platform android,
W/jxcore-log( 3733): 
W/jxcore-log( 3733): Process ARCH arm
W/jxcore-log( 3733): 
,I/jxcore-log( 3733): JXcore Cordova bridge is ready!
I/jxcore-log( 3733): 
W/jxcore-log( 3733): JXcore engine is started
,I/jxcore-log( 3733): Toggling radios to true
I/jxcore-log( 3733): 
,D/BluetoothAdapter( 3733): enable(): BT is already enabled..!
,D/WifiService(  822): setWifiEnabled: true pid=3733, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  822): New client listening to asynchronous messages
,I/jxcore-log( 3733): Radios toggled
I/jxcore-log( 3733): 
I/jxcore-log( 3733): My device name is: motorola-Nexus 6
I/jxcore-log( 3733): 
,I/wpa_supplicant( 1182): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1508): Read error: ssl=0x9d0d6e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1508): SSL shutdown failed: ssl=0x9d0d6e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  822): Start Disconnecting Watchdog 1,
,E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  822): MasterInitialState.processMessage what=3
I/NetworkMonitor( 3059): type=WIFI subType= reason=null isConnected=false
,D/NetworkChangeNotifierAutoDetect( 1486): Network connectivity changed, type is: 6
,V/MusicLeanback( 3059): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): will read network variables netId=0
,I/ActivityManager(  822): Start proc 3793:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,E/GpsLocationProvider(  822): No APN found to select.
,D/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMReceiver( 3793): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3793): simOperator:  IMSI: null
D/SprintDMReceiver( 3793): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1767): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     (  822): Explicit concurrent mark sweep GC freed 34077(1664KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 1.385ms total 50.180ms
,D/SystemUpdateService( 1767): onCreate
,D/SystemUpdateService( 1767): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1767): active receiver: enabled
,I/SystemUpdateService( 1767): showing system update notification
,I/iu.Environment( 1767): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1767): num queued entries: 0
I/iu.UploadsManager( 1767): num updated entries: 0
I/iu.SyncManager( 1767): NEXT; no task
,D/ChimeraCfgMgr( 1767): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1767): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  822): skipping global notification
,I/Babel   ( 2775): connection state changed from CONNECTED to DISCONNECTED
,V/SystemUpdateService( 1767): retry (wakeup: false) in 3599938 ms
,I/ActivityManager(  822): Start proc 3813:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1767): onDestroy
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4    ( 3813): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3813):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3813):   adb logcat -s GAv4
,D/Finsky  ( 3594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3594): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3594): [1] 5.onFinished: Scheduling replication attempt 1.
,W/GAv4    ( 3813): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  822): Killing 3521:com.android.musicfx/u0a18 (adj 15): empty #17
,W/GAv4    ( 3813): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3813): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3813): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3813): Time to load native libraries: 1 ms (timestamps 7633-7634)
I/LibraryLoader( 3813): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3813): Binding Chromium to main looper Looper (main, tid 1) {3a555fc5}
,I/LibraryLoader( 3813): Expected native library version number "",actual native library version number ""
,I/chromium( 3813): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3813): Initializing chromium process, singleProcess=true
,W/art     ( 3813): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3813): ApplicationContext is null in ApplicationStatus
,W/chromium( 3813): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3813): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3813): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3813): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3813): Requires BLUETOOTH permission
,I/NSApplication( 3813): Starting up...
,I/ActivityManager(  822): Start proc 3869:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  822): Killing 3553:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/ActivityManager(  822): Killing 1376:android.process.acore/u0a5 (adj 15): empty #17
,V/MusicLeanback( 3059): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3793): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3793): simOperator:  IMSI: null
D/SprintDMReceiver( 3793): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1767): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1767): onCreate
,D/SystemUpdateService( 1767): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1767): active receiver: enabled
,I/SystemUpdateService( 1767): showing system update notification
,I/ValidateNoPeople(  822): skipping global notification
,D/ChimeraCfgMgr( 1767): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1767): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
V/SystemUpdateService( 1767): retry (wakeup: false) in 3599968 ms
,D/SystemUpdateService( 1767): onDestroy
,I/wpa_supplicant( 1182): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 1182): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1182): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1182): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 205
E/WifiStateMachine(  822):  RSSI mgmt: -53
E/WifiStateMachine(  822):  BE :  rx=186 tx=154 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 9376 tx_time=152 rx_time=334 scan_time=0
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60,
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/dhcpcd  ( 3898): version 5.5.6 starting
,I/dhcpcd  ( 3898): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3898): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3898): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3733): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3733): 
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 101
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822):    accepting network in place of null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} },
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,I/NetworkMonitor( 3059): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1486): Network connectivity changed, type is: 2
,V/MusicLeanback( 3059): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  822): Start proc 3930:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/ActivityManager(  822): Start proc 3947:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,D/SprintDMReceiver( 3793): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,I/jxcore-log( 3733): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3733): 
,D/SprintDMHelper( 3793): simOperator:  IMSI: null
D/SprintDMReceiver( 3793): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1767): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1767): onCreate
D/SystemUpdateService( 1767): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  822): No APN found to select.
,I/SystemUpdateService( 1767): active receiver: enabled
,I/iu.Environment( 1767): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1767): num queued entries: 0
I/iu.UploadsManager( 1767): num updated entries: 0
I/iu.SyncManager( 1767): NEXT; no task
,D/ChimeraCfgMgr( 1767): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1767): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/SystemUpdateService( 1767): showing system update notification
,I/jxcore-log( 3733): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3733): 
,I/art     ( 1508): Explicit concurrent mark sweep GC freed 25160(1278KB) AllocSpace objects, 6(661KB) LOS objects, 38% free, 25MB/41MB, paused 844us total 32.346ms
,I/ValidateNoPeople(  822): skipping global notification
,W/GAV2    ( 3930): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/SystemUpdateService( 1767): retry (wakeup: false) in 3599919 ms
,D/SystemUpdateService( 1767): onDestroy
,I/BooksApp( 3930): Created application version: 3.6.8 (30608)
,I/jxcore-log( 3733): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3733): 
,I/Babel   ( 2775): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3733): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3733): 
,I/BooksSync( 3930): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3947): Connecting to GoogleApiClient
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1767): Handling authorization failure
E/ClientConnectionOperation( 1767): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1767): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1767): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1767): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1767): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1767): 	... 7 more
,V/KeepSync( 3947): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,D/GCM     ( 1508): Connected
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,I/BooksConfig( 3930): GmsCore Version = 7.8.99 (2134222-430)
,D/ConnectivityService(  822): reportInetCondition: type=1 ok, revalidate
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  822): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/GCM     ( 1508): Message class com.google.f.a.a.p
,D/ConnectivityService(  822): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 36374(1751KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.362ms total 60.701ms
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3930): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): Soft error
E/BooksSync( 3930): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3930): Sync error
E/BooksSync( 3930): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3930): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 75741, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3733): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3733): 
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3947): IOException
E/KeepSync( 3947): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3947): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3947): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3947): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3947): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3947): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3947): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3947): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3947): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3947): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3947): 	... 10 more
,W/KeepSync( 3947): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 75903, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3231): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3231): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3231): 	at jdm.a(PG:82)
E/HttpOperation( 3231): 	at jcs.o(PG:406)
E/HttpOperation( 3231): 	at jcn.a(PG:1379)
E/HttpOperation( 3231): 	at jcs.i(PG:143)
E/HttpOperation( 3231): 	at blb.a(PG:3937)
E/HttpOperation( 3231): 	at czp.a(PG:18188)
E/HttpOperation( 3231): 	at czp.a(PG:9081)
E/HttpOperation( 3231): 	at czq.run(PG:1686)
E/HttpOperation( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3231): 	at jdj.a(PG:4091)
E/HttpOperation( 3231): 	at jdj.a(PG:1125)
E/HttpOperation( 3231): 	at jdm.a(PG:77)
E/HttpOperation( 3231): 	... 12 more
E/HttpOperation( 3231): Caused by: faj: BadAuthentication
E/HttpOperation( 3231): 	at fal.a(PG:38)
E/HttpOperation( 3231): 	at jdj.a(PG:4089)
E/HttpOperation( 3231): 	... 14 more
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3231): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3231): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3231): 	at jdm.a(PG:82)
E/HttpOperation( 3231): 	at jcs.o(PG:406)
E/HttpOperation( 3231): 	at jcn.a(PG:1379)
E/HttpOperation( 3231): 	at jcs.i(PG:143)
E/HttpOperation( 3231): 	at hec.a(PG:42)
E/HttpOperation( 3231): 	at hee.a(PG:102)
E/HttpOperation( 3231): 	at czr.a(PG:65)
E/HttpOperation( 3231): 	at kka.a(PG:108)
E/HttpOperation( 3231): 	at czp.a(PG:19176)
E/HttpOperation( 3231): 	at czp.a(PG:9081)
E/HttpOperation( 3231): 	at czq.run(PG:1686)
E/HttpOperation( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3231): 	at jdj.a(PG:4091)
E/HttpOperation( 3231): 	at jdj.a(PG:1125)
E/HttpOperation( 3231): 	at jdm.a(PG:77)
E/HttpOperation( 3231): 	... 15 more
E/HttpOperation( 3231): Caused by: faj: BadAuthentication
E/HttpOperation( 3231): 	at fal.a(PG:38)
E/HttpOperation( 3231): 	at jdj.a(PG:4089)
E/HttpOperation( 3231): 	... 17 more
,E/ExperimentLoader( 3231): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3231): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3231): 	at jdm.a(PG:82)
E/ExperimentLoader( 3231): 	at jcs.o(PG:406)
E/ExperimentLoader( 3231): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3231): 	at jcs.i(PG:143)
E/ExperimentLoader( 3231): 	at hec.a(PG:42)
E/ExperimentLoader( 3231): 	at hee.a(PG:102)
E/ExperimentLoader( 3231): 	at czr.a(PG:65)
E/ExperimentLoader( 3231): 	at kka.a(PG:108)
E/ExperimentLoader( 3231): 	at czp.a(PG:19176)
E/ExperimentLoader( 3231): 	at czp.a(PG:9081)
E/ExperimentLoader( 3231): 	at czq.run(PG:1686)
E/ExperimentLoader( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3231): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3231): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3231): 	at jdm.a(PG:77)
E/ExperimentLoader( 3231): 	... 15 more
E/ExperimentLoader( 3231): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3231): 	at fal.a(PG:38)
E/ExperimentLoader( 3231): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3231): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 76474, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 3634:com.google.android.gms:car/u0a11 (adj 15): empty #17
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=14.16 rxSuccessRate=14.50 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  822): Killing 3412:com.google.android.gm/u0a78 (adj 15): empty #17
,I/art     ( 1508): Explicit concurrent mark sweep GC freed 20394(1177KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 966us total 23.592ms
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=-4ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Feb 2016 23:27:12 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454714833007], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454714832985]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated,
,D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101],
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101],
,D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,V/Herrevad( 1767): NQAS connected
,I/GAV2    ( 3930): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3733): Test app app.js loaded
I/jxcore-log( 3733): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): ,	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3377e95d added. We now have 1 listener(s)
,I/chromium( 3733): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3733): BLE advertisement is supported
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): TAP version 13
,I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
,I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #generatePreambleAndBeacons empty keys to notify
,I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 1 should be equal
,I/jxcore-log( 3733): 
I/jxcore-log( 3733): ok 2 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 3 should be equal
I/jxcore-log( 3733): 
I/jxcore-log( 3733): ok 4 should be equal
,I/jxcore-log( 3733): 
I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
I/jxcore-log( 3733): # setup,
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 3733): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=7.58 rxSuccessRate=11.75 targetRoamBSSID=any RSSI=-54
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3733): ok 5 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 6 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 7 should be equal
I/jxcore-log( 3733): 
I/jxcore-log( 3733): ok 8 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
I/jxcore-log( 3733): # setup
,I/jxcore-log( 3733): 
I/jxcore-log( 3733): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 9 should throw,
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown,
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
,I/jxcore-log( 3733): ,
I/jxcore-log( 3733): # #parseBeacons invalid expiration in beaconStreamWithPreAmble,
,I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 10 should throw
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #parseBeacons no beacons returns null
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 11 should be equal
,I/jxcore-log( 3733): 
I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
,I/jxcore-log( 3733): 
I/jxcore-log( 3733): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 3733): 
I/jxcore-log( 3733): ok 12 should throw
I/jxcore-log( 3733): ,
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
I/jxcore-log( 3733): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): not ok 13 (unnamed assert)
I/jxcore-log( 3733): 
I/jxcore-log( 3733):   ---
I/jxcore-log( 3733): 
I/jxcore-log( 3733):     operator: fail
I/jxcore-log( 3733): 
,I/jxcore-log( 3733):   ...
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 14 should be equal
I/jxcore-log( 3733): 
I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
I/jxcore-log( 3733): # #parseBeacons addressBookCallback returns null for all
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 15 (unnamed assert)
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 16 should be equal
I/jxcore-log( 3733): 
I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
I/jxcore-log( 3733): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 17 (unnamed assert)
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 18 (unnamed assert)
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
I/jxcore-log( 3733): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 19 (unnamed assert)
I/jxcore-log( 3733): 
I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,D/Finsky  ( 3594): [380] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3594): [380] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3594): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3594): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.02 rxSuccessRate=2.90 targetRoamBSSID=any RSSI=-54
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.08 rxSuccessRate=2.51 targetRoamBSSID=any RSSI=-53
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@37283813}
,I/GoogleURLConnFactory( 1802): Using platform SSLCertificateSocketFactory
,W/GoogleHttpClient( 1802): Ignoring unsupported parameter: http.conn-manager.max-per-route
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3594): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3594): [1] 5.onFinished: Scheduling replication attempt 3.
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@37283813}
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,I/BooksSync( 3930): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3947): Connecting to GoogleApiClient
,I/BooksConfig( 3930): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1767): Handling authorization failure
E/ClientConnectionOperation( 1767): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1767): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ClientConnectionOperation( 1767): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1767): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1767): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1767): 	,at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1767): 	,at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1767): 	,at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
,E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1767): 	,at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1767): 	,at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1767),: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1767): ,	... 7 more
V/KeepSync( 3947): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 50013(2MB) AllocSpace objects, 11(176KB) LOS objects, 31% free, 34MB/50MB, paused 1.514ms total 113.040ms
,E/KeepSync( 3947): IOException
E/KeepSync( 3947): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3947): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3947): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3947): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3947): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3947): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3947): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3947): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3947): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3947): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3947): 	... 10 more
W/KeepSync( 3947): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 112663, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3930): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3930): Soft error
E/BooksSync( 3930): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3930): Sync error
E/BooksSync( 3930): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3930): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 113150, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3231): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3231): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3231): 	at jdm.a(PG:82)
E/HttpOperation( 3231): 	at jcs.o(PG:406)
E/HttpOperation( 3231): 	at jcn.a(PG:1379)
E/HttpOperation( 3231): 	at jcs.i(PG:143)
E/HttpOperation( 3231): 	at blb.a(PG:3937)
E/HttpOperation( 3231): 	at czp.a(PG:18188)
E/HttpOperation( 3231): 	at czp.a(PG:9081)
E/HttpOperation( 3231): 	at czq.run(PG:1686)
E/HttpOperation( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3231): 	at jdj.a(PG:4091)
E/HttpOperation( 3231): 	at jdj.a(PG:1125)
E/HttpOperation( 3231): 	at jdm.a(PG:77)
E/HttpOperation( 3231): 	... 12 more
E/HttpOperation( 3231): Caused by: faj: BadAuthentication
E/HttpOperation( 3231): 	at fal.a(PG:38)
E/HttpOperation( 3231): 	at jdj.a(PG:4089)
E/HttpOperation( 3231): 	... 14 more
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3231): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3231): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3231): 	at jdm.a(PG:82)
E/HttpOperation( 3231): 	at jcs.o(PG:406)
E/HttpOperation( 3231): 	at jcn.a(PG:1379)
E/HttpOperation( 3231): 	at jcs.i(PG:143)
E/HttpOperation( 3231): 	at hec.a(PG:42)
E/HttpOperation( 3231): 	at hee.a(PG:102)
E/HttpOperation( 3231): 	at czr.a(PG:65)
E/HttpOperation( 3231): 	at kka.a(PG:108)
E/HttpOperation( 3231): 	at czp.a(PG:19176)
E/HttpOperation( 3231): 	at czp.a(PG:9081)
E/HttpOperation( 3231): 	at czq.run(PG:1686)
E/HttpOperation( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3231): 	at jdj.a(PG:4091)
E/HttpOperation( 3231): 	at jdj.a(PG:1125)
E/HttpOperation( 3231): 	at jdm.a(PG:77)
E/HttpOperation( 3231): 	... 15 more
E/HttpOperation( 3231): Caused by: faj: BadAuthentication
E/HttpOperation( 3231): 	at fal.a(PG:38)
E/HttpOperation( 3231): 	at jdj.a(PG:4089)
E/HttpOperation( 3231): 	... 17 more
,E/ExperimentLoader( 3231): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3231): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3231): ,	at jdm.a(PG:82),
E/ExperimentLoader( 3231): 	at jcs.o(PG:406),
E/ExperimentLoader( 3231): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3231): 	at jcs.i(PG:143)
E/ExperimentLoader( 3231): 	at hec.a(PG:42)
E/ExperimentLoader( 3231): 	at hee.a(PG:102)
E/ExperimentLoader( 3231): 	at czr.a(PG:65)
E/ExperimentLoader( 3231): 	at kka.a(PG:108)
,E/ExperimentLoader( 3231): 	at czp.a(PG:19176)
E/ExperimentLoader( 3231): 	at czp.a(PG:9081)
E/ExperimentLoader( 3231): 	at czq.run(PG:1686)
E/ExperimentLoader( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3231): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3231): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3231): 	at jdm.a(PG:77)
E/ExperimentLoader( 3231): 	... 15 more
E/ExperimentLoader( 3231): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3231): 	at fal.a(PG:38)
E/ExperimentLoader( 3231): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3231): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 114558, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1211): run()
,I/Keyboard.Facilitator( 1211): flushDynamicLanguageModels()
,I/ConfigService( 1508): onCreate
,I/ConfigService( 1508): onDestroy
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.33 rxSuccessRate=2.56 targetRoamBSSID=any RSSI=-53
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3594): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3594): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.54 rxSuccessRate=4.53 targetRoamBSSID=any RSSI=-53
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (239 us)
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3594): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3594): [1] 5.onFinished: Scheduling replication attempt 5.
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  822): Display changed displayId=0
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1,
I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 275ms
,I/DreamManagerService(  822): Entering dreamland.
,I/PowerManagerService(  822): Dozing...
,I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1211): onFinishInput()
,E/WifiStateMachine(  822): cancelDelayedScan -> 14
,E/native  (  822): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  872): STATUS: Received file 'm9kefs1',
I/kickstart(  872): STATUS: 950272 bytes transferred in 0.994998 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1508): Using platform SSLCertificateSocketFactory
,I/art     ( 1508): Explicit concurrent mark sweep GC freed 39534(2MB) AllocSpace objects, 8(693KB) LOS objects, 37% free, 26MB/42MB, paused 1.978ms total 52.421ms
V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3594): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3594): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3594): [1] 5.onFinished: Giving up after 6 failures.
,V/GoogleAuthProtoRequest( 3093): [305] a.<init>: mAccountName set to: thalitester@gmail.com
,I/PhenotypeFlagCommitter( 1508): Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3093): [305] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3093): [305] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): 	at com.a.a.a.k.a(SourceFile:117)
,W/ExperimentUpdateService( 3093): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3093): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3093): 	,at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3093): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.g.a(SourceFile:79),
W/ExperimentUpdateService( 3093): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3093): 	at com.a.a.k.run(SourceFile:110)
,I/VacuumService( 1508): Vacuum at: now=1454714930725 tag=VacuumService
,I/GoogleURLConnFactory( 1508): Using platform SSLCertificateSocketFactory
,W/Uploader( 1508): No account for auth token provided
,W/Uploader( 1508): No account for auth token provided
,I/art     (  822): Explicit concurrent mark sweep GC freed 46303(2MB) AllocSpace objects, 13(396KB) LOS objects, 31% free, 34MB/50MB, paused 2.645ms total 90.243ms,
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,E/Uploader( 1508): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1508): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1508): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1508): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1508): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1508): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1508): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1508): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1508): No account for auth token provided
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1508): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1508): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1508): ,	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1508): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1508): No account for auth token provided
,W/Uploader( 1508): No account for auth token provided,
,W/Uploader( 1508): No account for auth token provided
,W/Uploader( 1508): No account for auth token provided
,W/Uploader( 1508): No account for auth token provided
,W/Uploader( 1508): No account for auth token provided
,W/Uploader( 1508): No account for auth token provided
,W/Uploader( 1508):  no longer exists, so no auth token.
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1508): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1508): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1508): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1508): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1508): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1508): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1508): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1508): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1508): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1508): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
,E/Uploader( 1508): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1508): No account for auth token provided
,W/Uploader( 1508): No account for auth token provided
,W/Uploader( 1508): No account for auth token provided
,W/ProcessCpuTracker(  822): Skipping unknown process pid 4063
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,V/KeepSync( 3947): Connecting to GoogleApiClient
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1767): Handling authorization failure
E/ClientConnectionOperation( 1767): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1767): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1767): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1767): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1767): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1767): 	... 7 more
,V/KeepSync( 3947): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3947): IOException
E/KeepSync( 3947): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3947): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3947): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3947): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3947): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3947): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3947): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3947): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3947): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3947): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3947): 	... 10 more
W/KeepSync( 3947): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 194044, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,V/GoogleAuthProtoRequest( 3093): [306] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3093): [306] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3093): [306] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3093): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3093): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3093): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3093): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1211): run()
I/Keyboard.Facilitator( 1211): flushDynamicLanguageModels()
,I/ConfigService( 1508): onCreate
,I/BooksSync( 3930): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3930): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3231): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3231): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3231): 	at jdm.a(PG:82)
E/HttpOperation( 3231): 	at jcs.o(PG:406)
E/HttpOperation( 3231): 	at jcn.a(PG:1379)
E/HttpOperation( 3231): 	at jcs.i(PG:143)
E/HttpOperation( 3231): 	at blb.a(PG:3937)
E/HttpOperation( 3231): 	at czp.a(PG:18188)
E/HttpOperation( 3231): 	at czp.a(PG:9081)
E/HttpOperation( 3231): 	at czq.run(PG:1686)
E/HttpOperation( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3231): 	at jdj.a(PG:4091)
E/HttpOperation( 3231): 	at jdj.a(PG:1125)
E/HttpOperation( 3231): 	at jdm.a(PG:77)
E/HttpOperation( 3231): 	... 12 more
E/HttpOperation( 3231): Caused by: faj: BadAuthentication
E/HttpOperation( 3231): 	at fal.a(PG:38)
E/HttpOperation( 3231): 	at jdj.a(PG:4089)
E/HttpOperation( 3231): 	... 14 more
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3930): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3930): Soft error
E/BooksSync( 3930): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3930): Sync error
E/BooksSync( 3930): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3930): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 195269, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3231): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3231): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3231): 	at jdm.a(PG:82)
E/HttpOperation( 3231): 	at jcs.o(PG:406)
E/HttpOperation( 3231): 	at jcn.a(PG:1379)
E/HttpOperation( 3231): 	at jcs.i(PG:143)
E/HttpOperation( 3231): 	at hec.a(PG:42)
E/HttpOperation( 3231): 	at hee.a(PG:102)
E/HttpOperation( 3231): 	at czr.a(PG:65)
E/HttpOperation( 3231): 	at kka.a(PG:108)
E/HttpOperation( 3231): 	at czp.a(PG:19176)
E/HttpOperation( 3231): 	at czp.a(PG:9081)
E/HttpOperation( 3231): 	at czq.run(PG:1686)
E/HttpOperation( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3231): 	at jdj.a(PG:4091)
E/HttpOperation( 3231): 	at jdj.a(PG:1125)
E/HttpOperation( 3231): 	at jdm.a(PG:77)
E/HttpOperation( 3231): 	... 15 more
E/HttpOperation( 3231): Caused by: faj: BadAuthentication
E/HttpOperation( 3231): 	at fal.a(PG:38)
E/HttpOperation( 3231): 	at jdj.a(PG:4089)
E/HttpOperation( 3231): 	... 17 more
,E/ExperimentLoader( 3231): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3231): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3231): 	at jdm.a(PG:82)
E/ExperimentLoader( 3231): 	at jcs.o(PG:406)
E/ExperimentLoader( 3231): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3231): 	at jcs.i(PG:143)
E/ExperimentLoader( 3231): 	at hec.a(PG:42)
E/ExperimentLoader( 3231): 	at hee.a(PG:102)
E/ExperimentLoader( 3231): 	at czr.a(PG:65)
E/ExperimentLoader( 3231): 	at kka.a(PG:108)
E/ExperimentLoader( 3231): 	at czp.a(PG:19176)
E/ExperimentLoader( 3231): 	at czp.a(PG:9081)
E/ExperimentLoader( 3231): 	at czq.run(PG:1686)
E/ExperimentLoader( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/ExperimentLoader( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3231): ,	at jdj.a(PG:4091)
E/ExperimentLoader( 3231): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3231): 	at jdm.a(PG:77)
E/ExperimentLoader( 3231): 	... 15 more
E/ExperimentLoader( 3231): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3231): 	at fal.a(PG:38)
E/ExperimentLoader( 3231): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3231): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 197823, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1508): onDestroy
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,I/ActivityManager(  822): Start proc 4095:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4095): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4095):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4095):   adb logcat -s GAv4
,W/GAv4    ( 4095): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4095): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4095): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  822): Killing 2484:com.google.android.calendar/u0a37 (adj 15): empty #17
,V/GoogleAuthProtoRequest( 3093): [307] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1508): Explicit concurrent mark sweep GC freed 80139(4MB) AllocSpace objects, 9(753KB) LOS objects, 36% free, 28MB/44MB, paused 1.353ms total 52.162ms
,I/art     (  822): Explicit concurrent mark sweep GC freed 34328(1509KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.541ms total 72.724ms
,W/ExperimentUpdateService( 3093): [307] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3093): [307] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3093): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3093): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3093): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3093): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3947): Connecting to GoogleApiClient
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1767): Handling authorization failure
E/ClientConnectionOperation( 1767): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1767): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1767): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1767): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1767): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
,E/ClientConnectionOperation( 1767): 	... 7 more
V/KeepSync( 3947): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3947): IOException
E/KeepSync( 3947): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3947): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3947): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3947): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3947): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3947): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3947): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3947): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3947): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3947): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3947): 	... 10 more
W/KeepSync( 3947): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 317126, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # multiplex can send data
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 20 String should be length:200
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # enqueue and run in order
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 21 firstPromise setTimeout
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 22 firstPromise result
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 23 firstPromise testValue
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 24 secondPromise setTimeout
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 25 secondPromise result
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 26 secondPromise testValue
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 27 thirdPromise in promise
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 28 thirdPromise result
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 29 thirdPromise testValue
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # basic
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 30 sane
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # another
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 31 sane
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 32 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 33 null
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 34 (unnamed assert)
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 35 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 36 should not throw
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 37 (unnamed assert)
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 38 (unnamed assert)
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 39 should not throw
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 40 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 41 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 42 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # failed to get mobile documents path,
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 43 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 44 should be equal
I/jxcore-log( 3733): 
I/jxcore-log( 3733): ok 45 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 46 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #init should register the networkChanged event
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 47 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #startBroadcasting should throw on null device name
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 48 should throw
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 49 should throw
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 50 should throw
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 51 should throw
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #startBroadcasting should throw on negative port
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 52 should throw
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #startBroadcasting should throw on too large port
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 53 should throw
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 54 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 55 should be equal
I/jxcore-log( 3733): 
I/jxcore-log( 3733): ok 56 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 57 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 58 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 59 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): ,
,I/jxcore-log( 3733): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 60 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 61 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 62 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 63 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 64 should be equal
I/jxcore-log( 3733): 
I/jxcore-log( 3733): ok 65 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 66 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 67 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 68 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 69 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 70 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 71 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): ok 72 should be equal
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # teardown
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # setup
I/jxcore-log( 3733): 
,I/jxcore-log( 3733): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3733): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3733): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3733): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3733): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3733): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e16e2d2 added. We now have 2 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): onDiscoveryModeChanged: Mode set to WIFI
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3733): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454715068452.3733
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3733): bind: Binding a new listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3733): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3733): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454715068452.3733","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3733): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3733): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3733): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3733): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3733): start: OK
I/io.jxcore.node.ConnectionHelper( 3733): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3733): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454715068452.3733, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3733): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3733): bind: Binding a new listener,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3733): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3733): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3733): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454715068452.3733","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3733): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454715068452.3733","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3733): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454715068452.3733","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3733): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3733): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3733): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454715068452.3733, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3733): start: OK
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3733): ok 73 Should be able to call startBroadcasting without error
I/jxcore-log( 3733): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3733): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): startWifiPeerDiscovery: Wi-Fi Direct OK
I/io.jxcore.node.ConnectionHelper( 3733): stop
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): start: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3733): stop: Stopping Bluetooth...
,I/io.jxcore.node.ConnectionHelper( 3733): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3733): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3733): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3733): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3733): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3733): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3733): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3733): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3733): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3733): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3733): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3733): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3733): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3733): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3733): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3733): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3733): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3733): setState: NOT_INITIALIZED
I/wpa_supplicant( 1182): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3733): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3733): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3733): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3733): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3733): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3733): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3733): ok 74 Should be able to call stopBroadcasting without error
,I/jxcore-log( 3733): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3733): load: 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3733): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3733): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3733): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Automate Bluetooth MAC address resolution: true, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Discovery mode: WIFI, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): 	,Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fbb2ff added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3733): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI,
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3733): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454715068541.3733
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3733): bind: Binding a new listener,
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3733): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3733): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454715068541.3733","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3733): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3733): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3733): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3733): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3733): start: OK
I/io.jxcore.node.ConnectionHelper( 3733): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3733): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3733): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3733): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454715068541.3733, mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3733): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3733): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3733): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3733): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3733): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3733): createAdvertiseData: From: 1454715068541.3733 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3733): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2154): registerClient() - UUID=f6943063-5f70-49b4-b8a3-b4ef99908e5c
,D/BtGatt.GattService( 2154): onClientRegistered() - UUID=f6943063-5f70-49b4-b8a3-b4ef99908e5c, clientIf=5
D/BluetoothLeScanner( 3733): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2154): start scan with filters
,D/BtGatt.ScanManager( 2154): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3733): setState: State changed from NOT_STARTED to STARTING
D/BluetoothAdapterService( 2154): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e474a67
,D/BtGatt.GattService( 2154): registerClient() - UUID=1759d1a3-42ab-4c8c-8650-7e168a82d6e3
,D/BtGatt.GattService( 2154): onClientRegistered() - UUID=1759d1a3-42ab-4c8c-8650-7e168a82d6e3, clientIf=6
D/BluetoothLeAdvertiser( 3733): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2154): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,D/BtGatt.ScanManager( 2154): callback done for clientIf - 5 status - 0
,D/BtGatt.AdvertiseManager( 2154): message : 0
,D/BtGatt.GattService( 2154): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2154): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2154): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2154): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/BtGatt.AdvertiseManager( 2154): starting multi advertising
,D/BtGatt.GattService( 2154): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2154): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3733): setState: State changed from NOT_STARTED to STARTING,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3733): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454715068541.3733","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3733): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454715068541.3733","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3733): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454715068541.3733","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3733): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3733): start: Starting P2P device discovery...
I/wpa_supplicant( 1182): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3733): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): start: OK
I/io.jxcore.node.ConnectionHelper( 3733): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454715068541.3733, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3733): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3733): createAdvertiseData: From: 1454715068541.3733 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3733): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/jxcore-log( 3733): ok 75 Should be able to call startBroadcasting without error
I/jxcore-log( 3733): 
,D/BtGatt.AdvertiseManager( 2154): message : 1
,D/BtGatt.AdvertiseManager( 2154): stop advertise for client 6
I/io.jxcore.node.ConnectionHelper( 3733): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3733): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3733): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3733): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3733): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3733): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3733): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3733): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3733): setState: NOT_STARTED
D/BtGatt.GattService( 2154): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2154): Client app is not null!
,D/BtGatt.GattService( 2154): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3733): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3733): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2154): registerClient() - UUID=5c1585a5-96f1-4536-9d5d-d235a096d434
,D/BtGatt.GattService( 2154): onClientRegistered() - UUID=5c1585a5-96f1-4536-9d5d-d235a096d434, clientIf=6
D/BluetoothLeAdvertiser( 3733): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2154): message : 0
,D/BtGatt.AdvertiseManager( 2154): starting multi advertising
,D/BtGatt.GattService( 2154): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2154): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3733): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3733): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3733): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3733): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3733): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3733): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3733): stopProvideBluetoothMacAddressMode
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3733): stop
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3733): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3733): onIsAdvertiserStartedChanged: true
,D/btif_config_util( 2154): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@208f9070}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@208f9070}
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1508): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1508): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1508): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1508): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1508): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1508): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1508): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3594): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3594): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3594): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3594): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3594): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3594): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3594): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3594): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,I/BooksSync( 3930): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3930): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3231): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3231): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3231): 	at jdm.a(PG:82)
E/HttpOperation( 3231): 	at jcs.o(PG:406)
E/HttpOperation( 3231): 	at jcn.a(PG:1379)
E/HttpOperation( 3231): 	at jcs.i(PG:143)
E/HttpOperation( 3231): 	at blb.a(PG:3937)
E/HttpOperation( 3231): 	at czp.a(PG:18188)
E/HttpOperation( 3231): 	at czp.a(PG:9081)
E/HttpOperation( 3231): 	at czq.run(PG:1686)
E/HttpOperation( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3231): 	at jdj.a(PG:4091)
E/HttpOperation( 3231): 	at jdj.a(PG:1125)
E/HttpOperation( 3231): 	at jdm.a(PG:77)
E/HttpOperation( 3231): 	... 12 more
E/HttpOperation( 3231): Caused by: faj: BadAuthentication
E/HttpOperation( 3231): 	at fal.a(PG:38)
E/HttpOperation( 3231): 	at jdj.a(PG:4089)
E/HttpOperation( 3231): 	... 14 more
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3930): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 3930): Soft error
E/BooksSync( 3930): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3930): Sync error
E/BooksSync( 3930): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3930): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 349341, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/HttpOperation( 3231): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3231): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3231): 	at jdm.a(PG:82)
E/HttpOperation( 3231): 	at jcs.o(PG:406)
E/HttpOperation( 3231): 	at jcn.a(PG:1379)
E/HttpOperation( 3231): 	at jcs.i(PG:143)
E/HttpOperation( 3231): 	at hec.a(PG:42)
E/HttpOperation( 3231): 	at hee.a(PG:102)
E/HttpOperation( 3231): 	at czr.a(PG:65)
E/HttpOperation( 3231): 	at kka.a(PG:108)
E/HttpOperation( 3231): 	at czp.a(PG:19176)
E/HttpOperation( 3231): 	at czp.a(PG:9081)
E/HttpOperation( 3231): 	at czq.run(PG:1686)
E/HttpOperation( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3231): 	at jdj.a(PG:4091)
E/HttpOperation( 3231): 	at jdj.a(PG:1125)
E/HttpOperation( 3231): 	at jdm.a(PG:77)
E/HttpOperation( 3231): 	... 15 more
E/HttpOperation( 3231): Caused by: faj: BadAuthentication
E/HttpOperation( 3231): 	at fal.a(PG:38)
E/HttpOperation( 3231): 	at jdj.a(PG:4089)
E/HttpOperation( 3231): 	... 17 more
,E/ExperimentLoader( 3231): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3231): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3231): 	at jdm.a(PG:82)
E/ExperimentLoader( 3231): 	at jcs.o(PG:406)
E/ExperimentLoader( 3231): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3231): 	at jcs.i(PG:143)
E/ExperimentLoader( 3231): 	at hec.a(PG:42)
E/ExperimentLoader( 3231): 	at hee.a(PG:102)
E/ExperimentLoader( 3231): 	at czr.a(PG:65)
E/ExperimentLoader( 3231): 	at kka.a(PG:108)
E/ExperimentLoader( 3231): 	at czp.a(PG:19176)
E/ExperimentLoader( 3231): 	at czp.a(PG:9081)
E/ExperimentLoader( 3231): 	at czq.run(PG:1686)
E/ExperimentLoader( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3231): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3231): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3231): 	at jdm.a(PG:77)
E/ExperimentLoader( 3231): 	... 15 more
E/ExperimentLoader( 3231): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3231): 	at fal.a(PG:38)
E/ExperimentLoader( 3231): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3231): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 353808, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3093): [308] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3093): [308] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3093): [308] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3093): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3093): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3093): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3093): 	at com.a.a.k.run(SourceFile:110)
,I/wpa_supplicant( 1182): P2P-FIND-STOPPED 
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/art     (  822): Explicit concurrent mark sweep GC freed 31896(1449KB) AllocSpace objects, 13(867KB) LOS objects, 31% free, 34MB/50MB, paused 1.397ms total 95.284ms
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2f43f663}
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2f43f663}
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,V/KeepSync( 3947): Connecting to GoogleApiClient
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1767): Handling authorization failure,
E/ClientConnectionOperation( 1767): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
,E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1767): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1767): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ClientConnectionOperation( 1767): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1767): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1767): 	,at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1767): 	,at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1767),: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1767): 	... 7 more
V/KeepSync( 3947): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3947): IOException
E/KeepSync( 3947): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3947): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3947): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3947): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3947): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3947): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3947): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3947): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3947): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3947): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3947): 	... 10 more
W/KeepSync( 3947): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 562850, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3930): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3930): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3930): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3930): Soft error
E/BooksSync( 3930): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3930): Sync error
E/BooksSync( 3930): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3930): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 627377, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1508): Explicit concurrent mark sweep GC freed 55719(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.217ms total 54.671ms
,E/HttpOperation( 3231): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3231): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3231): 	at jdm.a(PG:82)
E/HttpOperation( 3231): 	at jcs.o(PG:406)
E/HttpOperation( 3231): 	at jcn.a(PG:1379)
E/HttpOperation( 3231): 	at jcs.i(PG:143)
E/HttpOperation( 3231): 	at blb.a(PG:3937)
E/HttpOperation( 3231): 	at czp.a(PG:18188)
E/HttpOperation( 3231): 	at czp.a(PG:9081)
E/HttpOperation( 3231): 	at czq.run(PG:1686)
E/HttpOperation( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3231): 	at jdj.a(PG:4091)
E/HttpOperation( 3231): 	at jdj.a(PG:1125)
E/HttpOperation( 3231): 	at jdm.a(PG:77)
E/HttpOperation( 3231): 	... 12 more
E/HttpOperation( 3231): Caused by: faj: BadAuthentication
E/HttpOperation( 3231): 	at fal.a(PG:38)
E/HttpOperation( 3231): 	at jdj.a(PG:4089)
E/HttpOperation( 3231): 	... 14 more
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3231): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3231): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3231): 	at jdm.a(PG:82)
E/HttpOperation( 3231): 	at jcs.o(PG:406)
E/HttpOperation( 3231): 	at jcn.a(PG:1379)
E/HttpOperation( 3231): 	at jcs.i(PG:143)
E/HttpOperation( 3231): 	at hec.a(PG:42)
E/HttpOperation( 3231): 	at hee.a(PG:102)
E/HttpOperation( 3231): 	at czr.a(PG:65)
E/HttpOperation( 3231): 	at kka.a(PG:108)
E/HttpOperation( 3231): 	at czp.a(PG:19176)
E/HttpOperation( 3231): 	at czp.a(PG:9081)
E/HttpOperation( 3231): 	at czq.run(PG:1686)
E/HttpOperation( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3231): 	at jdj.a(PG:4091)
E/HttpOperation( 3231): 	at jdj.a(PG:1125)
E/HttpOperation( 3231): 	at jdm.a(PG:77)
E/HttpOperation( 3231): 	... 15 more
E/HttpOperation( 3231): Caused by: faj: BadAuthentication
E/HttpOperation( 3231): 	at fal.a(PG:38)
E/HttpOperation( 3231): 	at jdj.a(PG:4089)
E/HttpOperation( 3231): 	... 17 more
,E/ExperimentLoader( 3231): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3231): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3231): 	at jdm.a(PG:82),
E/ExperimentLoader( 3231): 	at jcs.o(PG:406)
E/ExperimentLoader( 3231): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3231): 	at jcs.i(PG:143)
E/ExperimentLoader( 3231): 	at hec.a(PG:42)
E/ExperimentLoader( 3231): 	at hee.a(PG:102)
E/ExperimentLoader( 3231): 	at czr.a(PG:65)
E/ExperimentLoader( 3231): 	at kka.a(PG:108)
E/ExperimentLoader( 3231): 	at czp.a(PG:19176)
E/ExperimentLoader( 3231): 	at czp.a(PG:9081)
,E/ExperimentLoader( 3231): 	at czq.run(PG:1686)
E/ExperimentLoader( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/ExperimentLoader( 3231): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3231): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3231): 	at jdm.a(PG:77)
E/ExperimentLoader( 3231): 	... 15 more
E/ExperimentLoader( 3231): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3231): 	at fal.a(PG:38)
E/ExperimentLoader( 3231): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3231): 	... 17 more,
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 636259, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3093): [309] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3093): [309] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.,
W/ExperimentUpdateService( 3093): [309] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3093): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3093): ,	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3093): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3093): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,V/KeepSync( 3947): Connecting to GoogleApiClient
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1767): Handling authorization failure,
E/ClientConnectionOperation( 1767): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1767): ,	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1767): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1767): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1767): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1767): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1767): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1767): 	... 7 more
,V/KeepSync( 3947): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3947): (284) automatic index on blob_node(is_deleted)
,I/art     (  822): Explicit concurrent mark sweep GC freed 45902(2MB) AllocSpace objects, 8(410KB) LOS objects, 31% free, 34MB/50MB, paused 2.382ms total 97.715ms
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3947): IOException
E/KeepSync( 3947): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3947): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3947): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3947): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3947): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3947): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3947): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3947): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3947): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3947): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3947): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3947): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3947): 	... 10 more
W/KeepSync( 3947): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1053539, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,I/BooksSync( 3930): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3930): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3930): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3930): Soft error
E/BooksSync( 3930): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3930): Sync error
E/BooksSync( 3930): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3930): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3930): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1127560, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3093): [310] a.<init>: mAccountName set to: thalitester@gmail.com
,I/EventLogService( 1767): Opted in for usage reporting
I/EventLogService( 1767): Aggregate from 1454713936921 (log), 1454713936921 (data)
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3093): [310] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3093): [310] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3093): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3093): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3093): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3093): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3093): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3093): 	at com.a.a.k.run(SourceFile:110)
,W/EventLogAggregator( 1767): Unknown tag: snet_gcore
W/EventLogAggregator( 1767): Unknown tag: snet_launch_service
,D/GCM     ( 1508): Message class com.google.f.a.a.i
,I/ServiceDumpSys( 1767): dumping service [account]
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3231): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3231): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3231): 	at jdm.a(PG:82)
E/HttpOperation( 3231): 	at jcs.o(PG:406)
E/HttpOperation( 3231): 	at jcn.a(PG:1379)
E/HttpOperation( 3231): 	at jcs.i(PG:143)
E/HttpOperation( 3231): 	at blb.a(PG:3937)
E/HttpOperation( 3231): 	at czp.a(PG:18188)
E/HttpOperation( 3231): 	at czp.a(PG:9081)
E/HttpOperation( 3231): ,	at czq.run(PG:1686)
E/HttpOperation( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3231): 	at jdj.a(PG:4091)
E/HttpOperation( 3231): 	at jdj.a(PG:1125)
E/HttpOperation( 3231): 	at jdm.a(PG:77)
E/HttpOperation( 3231): 	... 12 more
E/HttpOperation( 3231): Caused by: faj: BadAuthentication
E/HttpOperation( 3231): 	at fal.a(PG:38)
,E/HttpOperation( 3231): 	at jdj.a(PG:4089)
E/HttpOperation( 3231): 	... 14 more
,I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3231): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3231): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3231): 	at jdm.a(PG:82)
E/HttpOperation( 3231): 	at jcs.o(PG:406)
E/HttpOperation( 3231): 	at jcn.a(PG:1379)
E/HttpOperation( 3231): 	at jcs.i(PG:143)
E/HttpOperation( 3231): 	at hec.a(PG:42)
E/HttpOperation( 3231): 	at hee.a(PG:102)
E/HttpOperation( 3231): 	at czr.a(PG:65)
E/HttpOperation( 3231): 	at kka.a(PG:108)
E/HttpOperation( 3231): 	at czp.a(PG:19176)
E/HttpOperation( 3231): 	at czp.a(PG:9081)
E/HttpOperation( 3231): 	at czq.run(PG:1686)
E/HttpOperation( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3231): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3231): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3231): 	at jdj.a(PG:4091)
E/HttpOperation( 3231): 	at jdj.a(PG:1125)
E/HttpOperation( 3231): 	at jdm.a(PG:77)
E/HttpOperation( 3231): 	... 15 more
E/HttpOperation( 3231): Caused by: faj: BadAuthentication
E/HttpOperation( 3231): 	at fal.a(PG:38)
E/HttpOperation( 3231): 	at jdj.a(PG:4089)
E/HttpOperation( 3231): 	... 17 more
,E/ExperimentLoader( 3231): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3231): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3231): ,	at jdm.a(PG:82)
E/ExperimentLoader( 3231): ,	at jcs.o(PG:406)
E/ExperimentLoader( 3231): ,	at jcn.a(PG:1379),
E/ExperimentLoader( 3231): 	at jcs.i(PG:143)
E/ExperimentLoader( 3231): 	,at hec.a(PG:42)
E/ExperimentLoader( 3231): 	at hee.a(PG:102)
E/ExperimentLoader( 3231): ,	at czr.a(PG:65)
E/ExperimentLoader( 3231): 	at kka.a(PG:108)
E/ExperimentLoader( 3231): 	at czp.a(PG:19176),
E/ExperimentLoader( 3231): 	at czp.a(PG:9081)
E/ExperimentLoader( 3231): 	at czq.run(PG:1686),
E/ExperimentLoader( 3231): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/ExperimentLoader( 3231): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3231): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3231): 	at java.lang.Thread.run(Thread.java:818)
,E/ExperimentLoader( 3231): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3231): 	at jdj.a(PG:4091)
,E/ExperimentLoader( 3231): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3231): 	at jdm.a(PG:77)
E/ExperimentLoader( 3231): 	... 15 more
E/ExperimentLoader( 3231): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3231): 	at fal.a(PG:38)
,E/ExperimentLoader( 3231): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3231): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1175199, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,I/art     ( 1508): Explicit concurrent mark sweep GC freed 61544(2MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 2.175ms total 46.663ms
,W/bt-btm  ( 2154): Request to stop oneshot timer with non empty queue
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2154): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4339): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4339): CheckJNI is OFF
D/AndroidRuntime( 4339): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 3733:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  822): Skipping PackageSetting{37073a82 com.example.hello/10273} due to missing metadata
E/JavaBinder( 2154): !!! FAILED BINDER TRANSACTION !!!
E/BtGatt.GattService( 2154): Exception: android.os.TransactionTooLargeException
D/BtGatt.GattService( 2154): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2154): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2154): stop scan
D/BtGatt.ScanManager( 2154): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2154): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2154): configureRegularScanParams() - queue emtpy, scan stopped
E/libprocessgroup(  822): failed to kill 1 processes for processgroup 3733
W/ActivityManager(  822): Force removing ActivityRecord{370d44a2 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
E/JavaBinder(  822): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  822): !!! FAILED BINDER TRANSACTION !!!
D/BtGatt.GattService( 2154): Binder is dead - unregistering client (6)!
D/WifiService(  822): Client connection lost with reason: 4
D/BtGatt.AdvertiseManager( 2154): message : 1
D/BtGatt.AdvertiseManager( 2154): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2154): app died - unregistering client : 6
D/BtGatt.GattService( 2154): unregisterClient() - clientIf=6
D/BtGatt.GattService( 2154): onAdvertiseInstanceDisabled() - clientIf=255, status=0
E/BtGatt.ContextMap( 2154): Context not found for ID 255
V/ActivityManager(  822): Display changed displayId=0
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
I/Keyboard.Facilitator( 1211): resetDictionaries() : en_US
I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
D/BuaReceiver( 3483): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
D/TaskPersister(  822): removeObsoleteFile: deleting file=28_task.xml
I/Keyboard.Facilitator.DecoderInitializer( 1211): run()
I/Decoder ( 1211): createOrResetDecoder
I/ActivityManager(  822): Start proc 4354:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     ( 1062): Explicit concurrent mark sweep GC freed 71815(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 702us total 52.319ms
I/ConfigService( 1508): onCreate
I/art     ( 1486): Explicit concurrent mark sweep GC freed 2620(183KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 30.361ms total 65.926ms
I/art     (  822): Explicit concurrent mark sweep GC freed 34440(1977KB) AllocSpace objects, 12(380KB) LOS objects, 31% free, 34MB/50MB, paused 4.195ms total 85.648ms
I/art     (  822): WaitForGcToComplete blocked for 10.748ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1211): run()
W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3733 uid 10265
I/Keyboard.Facilitator( 1211): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1211): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1211): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1211): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1211): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1211): run()
I/StatsUtilsManager( 1211): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1211): shouldRecordStats() = Too Soon
W/LocationOracleImpl( 1486): Best location was null
I/HotwordRecognitionRnr( 1486): Starting hotword detection.
I/MicrophoneInputStream( 1486): mic_starting com.google.android.apps.gsa.speech.audio.u@2c75bf32
I/art     ( 1294): Explicit concurrent mark sweep GC freed 5061(370KB) AllocSpace objects, 11(1298KB) LOS objects, 31% free, 35MB/51MB, paused 737us total 27.440ms
I/AudioFlinger(  358): AudioFlinger's thread 0xb4042000 ready to run
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1486): mic_started com.google.android.apps.gsa.speech.audio.u@2c75bf32
D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/GLSUser ( 1508): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1508): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1508): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1508): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/art     (  822): Explicit concurrent mark sweep GC freed 8177(401KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 1.408ms total 150.467ms
D/VoicemailCleanupService( 4354): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  822): Start proc 4396:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
V/GLSActivity( 1508): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ContactLocale( 4354): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/HotwordWorker( 1486): onReady
D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@223ad8f3}
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=60.75 rxSuccessRate=84.50 targetRoamBSSID=any RSSI=-53
W/Search.LoginHelper( 1486): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1486): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 1486): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1486): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1486): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1486): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1486): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1486): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1486): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1486): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1486): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 1486): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1486): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 1486): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1486): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1486): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1486): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1486): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1486): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1486): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1486): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1486): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1486): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
I/ActivityManager(  822): Start proc 4418:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
D/Launcher.Workspace( 1294): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1294): 11683562 - stripEmptyScreens()
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=34.38 rxSuccessRate=186.75 targetRoamBSSID=any RSSI=-53
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659417875
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
W/ContextImpl( 4418): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1508): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1508): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/art     ( 4339): System.exit called, status: 0
I/AndroidRuntime( 4339): VM exiting with result code 0.
D/ChimeraCfgMgr( 1767): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1767): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1767): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1767): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1767): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1767): Module APK com.google.android.play.games already loaded
I/ActivityManager(  822): Killing 3389:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
I/LocationSettingsChecker( 1767): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1767): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1767): disk I/O error (code 3850)
E/DriveAsyncService( 1767): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1767): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1767): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1767): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1767): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1767): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1767): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1767): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1767): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1767): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1767): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1767): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1767): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1767): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1767): 	at java.lang.Thread.run(Thread.java:818)
I/UpdateIcingCorporaServi( 1486): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteDatabase( 1767): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1767): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1767): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1767): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1767): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1767): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1767): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1767): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1767): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1767): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1767): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1767): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1767): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1767): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1767): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1767): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1767): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1767): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1767): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1767): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1767): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1767): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1767): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1767): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1767): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
--------- beginning of crash
E/AndroidRuntime( 1767): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1767): Process: com.google.android.gms, PID: 1767
E/AndroidRuntime( 1767): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1767): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1767): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1767): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1767): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1767): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1767): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1767): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1767): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1767): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1767): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1767): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1486): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/ActivityManager(  822): Start proc 4449:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/SQLiteDatabase( 1767): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1767): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1767): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1767): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1767): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1767): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1767): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1767): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1767): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1767): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1767): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1767): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1767): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1767): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1767): Opened phenotype.db in read-only mode
W/ResourcesManager(  822): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  822): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
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
I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 329us total 19.136ms
D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  822): Validating map...
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 399us total 17.220ms
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 332us total 14.751ms
I/OpenGLRenderer(  822): Initialized EGL, version 1.4
D/OpenGLRenderer(  822): Enabling debug mode 0
I/ActivityManager(  822): Start proc 4470:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 1486): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 1486): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1486): Process: com.google.android.googlequicksearchbox:search, PID: 1486
E/AndroidRuntime( 1486): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1486): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1486): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1486): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1486): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1486): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1486): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1486): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1486): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1486): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1486): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1486): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1486): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1486): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1486): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1486): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1486): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1486): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1486): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1486): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1486): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
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
I/ConfigFetchService( 1767): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1767): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
W/ResourcesManager( 4449): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4449): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ConfigFetchService( 1767): service connected
I/Icing   ( 1767): doRemovePackageData com.test.thalitest
I/PeopleContactsSync( 1767): CP2 sync disabled
W/BaseAppContext( 1767): Using Auth Proxy for data requests.
W/BaseAppContext( 1767): Using Auth Proxy for data requests.
E/SQLiteDatabase( 1767): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1767): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1767): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1767): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1767): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1767): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1767): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1767): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1767): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1767): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1767): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1767): Runtime exception while performing operation
E/ClearPendingStateOp( 1767): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1767): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1767): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1767): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1767): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1767): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1767): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1767): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1767): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1767): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1767): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1767): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1767): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1767): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1767): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1767): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1767): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1767): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1767): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1767): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1767): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1767): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  822): Can't write: system_app_wtf
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
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
I/MultiDex( 4449): VM with version 2.1.0 has multidex support
I/MultiDex( 4449): install
I/MultiDex( 4449): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 4449): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  822): Killing 3369:com.android.providers.calendar/u0a3 (adj 15): empty #17
I/ProviderInstaller( 4449): Installed default security provider GmsCore_OpenSSL
I/HotwordDetector( 1486): Closing mic
I/MicrophoneInputStream( 1486): mic_close com.google.android.apps.gsa.speech.audio.u@2c75bf32
D/GFEEDBACK_SendErrorReportOperation( 1767): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 1767): Error saving report: java.io.IOException: failed to create reports directory
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1486): Hotword detection finished
I/HotwordRecognitionRnr( 1486): Stopping hotword detection.
E/Search.SharedPreferencesProto( 1486): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
W/NativeLibraryUtils( 4449): Failed to open lock file
W/NativeLibraryUtils( 4449): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4449): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4449): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4449): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4449): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4449): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4449): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4449): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4449): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4449): 	... 3 more
W/Launcher( 1294): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@5437bb9 new=com.google.android.velvet.VelvetApplication@5437bb9
I/ActivityManager(  822): Killing 3059:com.google.android.music:main/u0a66 (adj 15): empty #17
E/SQLiteLog( 1294): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
E/native  ( 1211): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1211): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/ActivityManager(  822): Start proc 4501:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
E/native  ( 1211): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1211): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1211): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1211): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1211): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1211): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/kickstart(  872): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  872): WARNING: function: sahara_start:892 Retrying memory read request
I/GAv4    ( 4501): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4501):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4501):   adb logcat -s GAv4
W/GAv4    ( 4501): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4501): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4501): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4501): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4501): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4501): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4501): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4501): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4501): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4501): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4501): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4501): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4501): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4501): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4501): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4501): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4501): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4501): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4501): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4501): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4501): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4501): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4501): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4501): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4501): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4501): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4501): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4501): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4501): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4501): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4501): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4501): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4501): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4501): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4501): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4501): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4501): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4501): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4501): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4501): 	at aen.run(PG:536)
W/GAv4    ( 4501): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4501): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4501): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4501): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4501): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4501): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4501): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4501): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 4501): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4501): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4501): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4501): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4501): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4501): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4501): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4501): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4501): 	at aej.c(PG:139)
E/SQLiteDatabase( 4501): 	at aej.b(PG:398)
E/SQLiteDatabase( 4501): 	at agf.f(PG:417)
E/SQLiteDatabase( 4501): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4501): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4501): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4501): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4501): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4501): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4501): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4501): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4501): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4501): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E,/AbstractDatabaseInstance( 4501): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4501): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4501): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4501): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4501): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4501): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4501): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4501): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4501): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4501): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4501): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 4501): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4501): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/GAv4    ( 4501): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4501): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4501): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4501): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4501): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4501): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4501): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4501): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4501): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4501): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4501): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4501): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4501): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4501): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4501): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4501): 	at aen.run(PG:536)
I/ActivityManager(  822): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{2eaa63d2 token=Token{2e14ce5d ActivityRecord{1b517034 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4501): Sending signal. PID: 4501 SIG: 9
E/lowmemorykiller(  257): Error writing /proc/4501/oom_score_adj; errno=22
E/JavaBinder(  822): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  822): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  822): android.os.TransactionTooLargeException
W/ActivityManager(  822): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  822): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  822): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  822): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  822): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  822): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  822): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  822): 	at android.os.Binder.execTransact(Binder.java:446)
I/art     ( 1802): Explicit concurrent mark sweep GC freed 25279(1579KB) AllocSpace objects, 8(151KB) LOS objects, 37% free, 26MB/42MB, paused 1.323ms total 56.254ms

```
