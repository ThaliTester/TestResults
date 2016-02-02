#### Test 575312438097721_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/CheckinService( 1793): Done disabling old GoogleServicesFramework version
,D/AndroidRuntime( 3625): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3625): CheckJNI is OFF
D/AndroidRuntime( 3625): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{2cc7e6b0 token=Token{3d4939f3 ActivityRecord{2d289462 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3625): Shutting down VM
V/WindowManager(  822): Adding window Window{16de0ee5 u0 Starting com.test.thalitest} at 2 of 7 (after Window{16669c3b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/MicrophoneInputStream( 1523): mic_close com.google.android.apps.gsa.speech.audio.u@17534d1c
I/HotwordDetector( 1523): Closing mic
I/ActivityManager(  822): Start proc 3639:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1523): Hotword detection finished
I/HotwordRecognitionRnr( 1523): Stopping hotword detection.
I/ActivityManager(  822): Killing 3232:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/WebViewFactory( 3639): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3639): Time to load native libraries: 2 ms (timestamps 1087-1089)
I/LibraryLoader( 3639): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3639): Binding Chromium to main looper Looper (main, tid 1) {8570327}
,I/LibraryLoader( 3639): Expected native library version number "",actual native library version number ""
I/chromium( 3639): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1721988371
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/BrowserStartupController( 3639): Initializing chromium process, singleProcess=true
,W/art     ( 3639): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3639): ApplicationContext is null in ApplicationStatus
,W/chromium( 3639): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3639): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3639): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3639): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  822): Message: 20
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@189f9d3f:true
,W/art     ( 3639): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3639): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3639): CordovaWebView is running on device made by: motorola
,W/art     ( 3639): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3639): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3639): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3639): Validating map...
,V/WindowManager(  822): Adding window Window{1500542f u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{16de0ee5 u0 Starting com.test.thalitest})
,W/chromium( 3639): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3639): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3639): Enabling debug mode 0
,I/Keyboard.Facilitator( 1236): onFinishInput()
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +727ms
,W/BindingManager( 3639): Cannot call determinedVisibility() - never saw a connection for the pid: 3639
,D/JsMessageQueue( 3639): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3639): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576320128
,I/chromium( 3639): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3639): Initializing JXcore engine
W/jxcore-log( 3639): JXcore engine is ready
,W/Thread-401( 3691): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11467]" dev="sockfs" ino=11467 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-401( 3691): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-401( 3691): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10586]" dev="sockfs" ino=10586 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-401( 3691): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22696]" dev="sockfs" ino=22696 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3639): Starting JXcore engine,
,W/jxcore-log( 3639): Platform android
W/jxcore-log( 3639): 
,W/jxcore-log( 3639): Process ARCH arm
W/jxcore-log( 3639): 
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{31a31a5e u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/jxcore-log( 3639): JXcore Cordova bridge is ready!
I/jxcore-log( 3639): 
W/jxcore-log( 3639): JXcore engine is started
,I/jxcore-log( 3639): Toggling radios to true
I/jxcore-log( 3639): 
,D/BluetoothAdapter( 3639): enable(): BT is already enabled..!
,D/WifiService(  822): New client listening to asynchronous messages
,D/WifiService(  822): setWifiEnabled: true pid=3639, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3639): Radios toggled
I/jxcore-log( 3639): 
I/jxcore-log( 3639): My device name is: motorola-Nexus 6
I/jxcore-log( 3639): 
,I/wpa_supplicant( 1132): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 1255): Read error: ssl=0xb4888a00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1255): SSL shutdown failed: ssl=0xb4888a00: I/O error during system call, Broken pipe
D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  822): MasterInitialState.processMessage what=3
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1523): Network connectivity changed, type is: 6
,V/MusicLeanback( 3327): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1319): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1319): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  822): will read network variables netId=0
,I/ActivityManager(  822): Start proc 3700:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
E/WifiConfigStore(  822): will read network variables netId=0
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 10.713ms
,D/PhoneInterfaceManager( 1319): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1319): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 11.257ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 9.177ms
,I/ActivityManager(  822): Start proc 3726:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  822): Killing 3001:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,D/SprintDMReceiver( 3726): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3726): simOperator:  IMSI: null
,D/SprintDMReceiver( 3726): Not Sprint UICC, don't do anything.
,I/ActivityManager(  822): Killing 3273:com.android.settings/1000 (adj 15): empty #17,
,I/SystemUpdateService( 1793): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1793): onCreate
,D/SystemUpdateService( 1793): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1793): active receiver: enabled
,I/SystemUpdateService( 1793): showing system update notification
,I/iu.Environment( 1793): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1793): num queued entries: 0
,I/iu.UploadsManager( 1793): num updated entries: 0
D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.SyncManager( 1793): NEXT; no task
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1793): retry (wakeup: false) in 3599943 ms
,I/ActivityManager(  822): Start proc 3746:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1793): onDestroy
,I/Babel   ( 2953): connection state changed from UNKNOWN to DISCONNECTED
,I/GAv4    ( 3746): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3746):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3746):   adb logcat -s GAv4
,W/GAv4    ( 3746): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3746): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3746): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  822): Explicit concurrent mark sweep GC freed 29344(1500KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 2.331ms total 87.997ms
,I/WebViewFactory( 3746): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3746): Time to load native libraries: 1 ms (timestamps 5162-5163)
,I/LibraryLoader( 3746): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3746): Binding Chromium to main looper Looper (main, tid 1) {393124da}
,I/LibraryLoader( 3746): Expected native library version number "",actual native library version number ""
,I/chromium( 3746): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3746): Initializing chromium process, singleProcess=true
W/art     ( 3746): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3746): ApplicationContext is null in ApplicationStatus
,W/chromium( 3746): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3746): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3746): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3746): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3746): Requires BLUETOOTH permission
,I/NSApplication( 3746): Starting up...
,I/ActivityManager(  822): Start proc 3803:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  822): Killing 3295:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/wpa_supplicant( 1132): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  822): Start proc 3825:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 18990(931KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.352ms total 47.247ms
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  822): Killing 3390:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/wpa_supplicant( 1132): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1132): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1132): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
V/MusicLeanback( 3327): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 189
E/WifiStateMachine(  822):  RSSI mgmt: -51
E/WifiStateMachine(  822):  BE :  rx=177 tx=155 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 8538 tx_time=158 rx_time=351 scan_time=0
D/Finsky  ( 3042): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3042): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3042): [1] 5.onFinished: Scheduling replication attempt 1.
,D/SprintDMReceiver( 3726): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3726): simOperator:  IMSI: null
D/SprintDMReceiver( 3726): Not Sprint UICC, don't do anything.
D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,I/SystemUpdateService( 1793): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1793): onCreate
,D/SystemUpdateService( 1793): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ActivityManager(  822): Killing 3411:com.android.musicfx/u0a18 (adj 15): empty #17
,I/SystemUpdateService( 1793): active receiver: enabled
,I/SystemUpdateService( 1793): showing system update notification
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1793): retry (wakeup: false) in 3599843 ms
,D/SystemUpdateService( 1793): onDestroy
,D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/dhcpcd  ( 3858): version 5.5.6 starting
,I/dhcpcd  ( 3858): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3858): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3858): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3639): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3639): 
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  822): Adding iface wlan0 to network 101
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
D/Tethering(  822): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3327): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1523): Network connectivity changed, type is: 2
,V/MusicLeanback( 3327): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1319): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1319): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMReceiver( 3726): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3726): simOperator:  IMSI: null
D/SprintDMReceiver( 3726): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1793): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1793): onCreate
,D/SystemUpdateService( 1793): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1793): active receiver: enabled
,I/iu.Environment( 1793): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1793): num queued entries: 0
,I/iu.UploadsManager( 1793): num updated entries: 0
I/iu.SyncManager( 1793): NEXT; no task
,I/SystemUpdateService( 1793): showing system update notification
,D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1793): retry (wakeup: false) in 3599974 ms
,D/SystemUpdateService( 1793): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 16:14:16 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454429656916], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454429656895]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1793): [AccountUtils] Account not ready
W/Kids    ( 1793): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1793): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1793): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1793): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1793): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1793): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1793): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1793): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1793): 	at java.lang.Thread.run(Thread.java:818)
,I/Babel   ( 2953): connection state changed from DISCONNECTED to CONNECTED
,V/Herrevad( 1793): NQAS connected
,D/GCM     ( 1255): Connected
,D/GCM     ( 1255): Message class com.google.f.a.a.p
,I/jxcore-log( 3639): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3639): 
,I/jxcore-log( 3639): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3639): 
,I/jxcore-log( 3639): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3639): 
,I/jxcore-log( 3639): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,I/jxcore-log( 3639): 
,I/ActivityManager(  822): Killing 3457:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=16.78 rxSuccessRate=15.72 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,I/ActivityManager(  822): Killing 3133:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/jxcore-log( 3639): Test app app.js loaded
I/jxcore-log( 3639): 
,I/chromium( 3639): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3639): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3639): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3639): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3639): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3639): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3639): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3639): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3639): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3639): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3639): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bc9df35 added. We now have 1 listener(s)
,I/jxcore-log( 3639): BLE advertisement is supported
I/jxcore-log( 3639): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.89 rxSuccessRate=8.86 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,D/Finsky  ( 3042): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3042): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3042): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3042): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3042): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3042): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3042): [1] DailyHygiene.reschedule: Scheduling new run in 278 minutes (failures=4)
,I/art     (  822): Explicit concurrent mark sweep GC freed 42731(2006KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.593ms total 94.760ms
,D/DeviceConnectionService( 1769): client connected with version: 7571000,
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.47 rxSuccessRate=4.71 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3042): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3042): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3042): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  822): Start proc 3920:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 26792(1569KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 26MB/42MB, paused 705us total 21.097ms
,E/HttpOperation( 3501): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3501): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3501): 	at jdm.a(PG:82)
E/HttpOperation( 3501): 	at jcs.o(PG:406)
E/HttpOperation( 3501): 	at jcn.a(PG:1379)
E/HttpOperation( 3501): 	at jcs.i(PG:143)
E/HttpOperation( 3501): 	at blb.a(PG:3937)
E/HttpOperation( 3501): 	at czp.a(PG:18188)
E/HttpOperation( 3501): 	at czp.a(PG:9081)
E/HttpOperation( 3501): 	at czq.run(PG:1686)
E/HttpOperation( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3501): 	at jdj.a(PG:4091)
E/HttpOperation( 3501): 	at jdj.a(PG:1125)
E/HttpOperation( 3501): 	at jdm.a(PG:77)
E/HttpOperation( 3501): 	... 12 more
E/HttpOperation( 3501): Caused by: faj: BadAuthentication
E/HttpOperation( 3501): 	at fal.a(PG:38)
E/HttpOperation( 3501): 	at jdj.a(PG:4089)
E/HttpOperation( 3501): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/HttpOperation( 3501): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3501): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3501): 	at jdm.a(PG:82)
E/HttpOperation( 3501): 	at jcs.o(PG:406)
E/HttpOperation( 3501): 	at jcn.a(PG:1379)
E/HttpOperation( 3501): 	at jcs.i(PG:143)
E/HttpOperation( 3501): 	at hec.a(PG:42)
E/HttpOperation( 3501): 	at hee.a(PG:102)
E/HttpOperation( 3501): 	at czr.a(PG:65)
E/HttpOperation( 3501): 	at kka.a(PG:108)
E/HttpOperation( 3501): 	at czp.a(PG:19176)
E/HttpOperation( 3501): 	at czp.a(PG:9081)
E/HttpOperation( 3501): 	at czq.run(PG:1686)
E/HttpOperation( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3501): 	at jdj.a(PG:4091)
E/HttpOperation( 3501): 	at jdj.a(PG:1125)
E/HttpOperation( 3501): 	at jdm.a(PG:77)
E/HttpOperation( 3501): 	... 15 more
E/HttpOperation( 3501): Caused by: faj: BadAuthentication
E/HttpOperation( 3501): 	at fal.a(PG:38)
E/HttpOperation( 3501): 	at jdj.a(PG:4089)
E/HttpOperation( 3501): 	... 17 more
E/ExperimentLoader( 3501): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3501): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3501): 	at jdm.a(PG:82)
E/ExperimentLoader( 3501): 	at jcs.o(PG:406)
E/ExperimentLoader( 3501): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3501): 	at jcs.i(PG:143)
E/ExperimentLoader( 3501): 	at hec.a(PG:42)
E/ExperimentLoader( 3501): 	at hee.a(PG:102)
E/ExperimentLoader( 3501): 	at czr.a(PG:65)
E/ExperimentLoader( 3501): 	at kka.a(PG:108)
E/ExperimentLoader( 3501): 	at czp.a(PG:19176)
E/ExperimentLoader( 3501): 	at czp.a(PG:9081)
E/ExperimentLoader( 3501): 	at czq.run(PG:1686)
E/ExperimentLoader( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3501): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3501): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3501): 	at jdm.a(PG:77)
E/ExperimentLoader( 3501): 	... 15 more
E/ExperimentLoader( 3501): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3501): 	at fal.a(PG:38)
E/ExperimentLoader( 3501): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3501): 	... 17 more
,V/KeepSync( 3920): Connecting to GoogleApiClient
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 78825, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  822): Start proc 3950:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,E/ClientConnectionOperation( 1793): Handling authorization failure
E/ClientConnectionOperation( 1793): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1793): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1793): 	... 7 more
,V/KeepSync( 3920): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3920): IOException
E/KeepSync( 3920): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3920): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3920): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3920): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3920): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3920): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3920): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3920): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3920): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3920): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3920): 	... 10 more
W/KeepSync( 3920): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 79306, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/GAV2    ( 3950): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3950): Created application version: 3.6.8 (30608)
,I/BooksSync( 3950): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3950): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3950): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3950): Soft error,
E/BooksSync( 3950): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3950): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3950): Sync error
E/BooksSync( 3950): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3950): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3950): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 79345, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 2308:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/ActivityManager(  822): Killing 1426:android.process.acore/u0a5 (adj 15): empty #18
,I/GAV2    ( 3950): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.54 rxSuccessRate=2.04 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3042): [289] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 37105(1743KB) AllocSpace objects, 13(302KB) LOS objects, 31% free, 34MB/50MB, paused 1.365ms total 96.559ms
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3042): [289] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/ActivityManager(  822): Start proc 3988:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 3988): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3988):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3988):   adb logcat -s GAv4
,W/GAv4    ( 3988): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3988): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3988): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  822): Killing 3534:com.google.android.gm/u0a78 (adj 15): empty #17
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3042): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3042): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3042): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1236): run()
,I/Keyboard.Facilitator( 1236): flushDynamicLanguageModels()
,I/ConfigService( 1255): onCreate
,I/ConfigService( 1255): onDestroy
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.41 rxSuccessRate=2.15 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3042): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3042): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3042): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.35 rxSuccessRate=2.61 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (316 us)
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6482000,
,D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0,
V/ActivityManager(  822): Display changed displayId=0
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0,
D/SurfaceControl(  822): Excessive delay in setPowerMode(): 275ms
,I/DreamManagerService(  822): Entering dreamland.
I/PowerManagerService(  822): Dozing...
I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1236): onFinishInput()
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): cancelDelayedScan -> 14,
,E/native  (  822): do suspend true,
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  872): STATUS: Received file 'm9kefs2'
,I/kickstart(  872): STATUS: 950272 bytes transferred in 0.999637 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
I/kickstart(  872): STATUS: Sahara protocol completed
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 26841(1507KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.689ms total 50.219ms
,D/Finsky  ( 3042): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3042): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3042): [1] 5.onFinished: Scheduling replication attempt 5.
,I/BooksSync( 3950): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3950): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3501): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3501): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3501): 	at jdm.a(PG:82)
E/HttpOperation( 3501): 	at jcs.o(PG:406)
E/HttpOperation( 3501): 	at jcn.a(PG:1379)
E/HttpOperation( 3501): 	at jcs.i(PG:143)
E/HttpOperation( 3501): 	at blb.a(PG:3937)
E/HttpOperation( 3501): 	at czp.a(PG:18188)
E/HttpOperation( 3501): 	at czp.a(PG:9081)
E/HttpOperation( 3501): 	at czq.run(PG:1686)
E/HttpOperation( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3501): 	at jdj.a(PG:4091)
E/HttpOperation( 3501): 	at jdj.a(PG:1125)
E/HttpOperation( 3501): 	at jdm.a(PG:77)
E/HttpOperation( 3501): 	... 12 more
E/HttpOperation( 3501): Caused by: faj: BadAuthentication
E/HttpOperation( 3501): 	at fal.a(PG:38)
E/HttpOperation( 3501): 	at jdj.a(PG:4089)
E/HttpOperation( 3501): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/HttpOperation( 3501): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3501): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3501): 	at jdm.a(PG:82)
E/HttpOperation( 3501): 	at jcs.o(PG:406)
E/HttpOperation( 3501): 	at jcn.a(PG:1379)
E/HttpOperation( 3501): 	at jcs.i(PG:143)
E/HttpOperation( 3501): 	at hec.a(PG:42)
E/HttpOperation( 3501): 	at hee.a(PG:102)
E/HttpOperation( 3501): 	at czr.a(PG:65)
E/HttpOperation( 3501): 	at kka.a(PG:108)
E/HttpOperation( 3501): 	at czp.a(PG:19176)
E/HttpOperation( 3501): 	at czp.a(PG:9081)
E/HttpOperation( 3501): 	at czq.run(PG:1686)
E/HttpOperation( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3501): 	at jdj.a(PG:4091)
E/HttpOperation( 3501): 	at jdj.a(PG:1125)
E/HttpOperation( 3501): 	at jdm.a(PG:77)
E/HttpOperation( 3501): 	... 15 more
E/HttpOperation( 3501): Caused by: faj: BadAuthentication
E/HttpOperation( 3501): 	at fal.a(PG:38)
E/HttpOperation( 3501): 	at jdj.a(PG:4089)
E/HttpOperation( 3501): 	... 17 more
E/ExperimentLoader( 3501): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3501): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3501): 	at jdm.a(PG:82)
E/ExperimentLoader( 3501): 	at jcs.o(PG:406)
E/ExperimentLoader( 3501): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3501): 	at jcs.i(PG:143)
E/ExperimentLoader( 3501): 	at hec.a(PG:42)
E/ExperimentLoader( 3501): 	at hee.a(PG:102)
E/ExperimentLoader( 3501): 	at czr.a(PG:65)
E/ExperimentLoader( 3501): 	at kka.a(PG:108)
E/ExperimentLoader( 3501): 	at czp.a(PG:19176)
E/ExperimentLoader( 3501): 	at czp.a(PG:9081)
E/ExperimentLoader( 3501): 	at czq.run(PG:1686)
E/ExperimentLoader( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3501): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3501): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3501): 	at jdm.a(PG:77)
E/ExperimentLoader( 3501): 	... 15 more
E/ExperimentLoader( 3501): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3501): 	at fal.a(PG:38)
E/ExperimentLoader( 3501): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3501): 	... 17 more
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3950): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 3950): Soft error
E/BooksSync( 3950): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3950): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3950): Sync error,
E/BooksSync( 3950): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3950): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3950): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 140180, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3920): Connecting to GoogleApiClient
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 140474, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1793): Handling authorization failure
E/ClientConnectionOperation( 1793): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1793): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1793): 	... 7 more
,V/KeepSync( 3920): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 44759(2MB) AllocSpace objects, 13(396KB) LOS objects, 31% free, 34MB/50MB, paused 2.281ms total 88.982ms
,E/KeepSync( 3920): IOException
E/KeepSync( 3920): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3920): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3920): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3920): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3920): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3920): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3920): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3920): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3920): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3920): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3920): 	... 10 more
,W/KeepSync( 3920): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 141734, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51,
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1255): Vacuum at: now=1454429764762 tag=VacuumService
,V/GoogleAuthProtoRequest( 3700): [395] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3042): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3042): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3042): [1] 5.onFinished: Giving up after 6 failures.
,W/ExperimentUpdateService( 3700): [395] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3700): [395] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3700): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
,W/ExperimentUpdateService( 3700): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3700): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.a.a(SourceFile:93)
,W/ExperimentUpdateService( 3700): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1255): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1255): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1255): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1255): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1255): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1255): Failed to get auth token: User intervention required. Notification has been pushed.
,E/Uploader( 1255): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1255): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.c(SourceFile:550),
E/Uploader( 1255): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
,E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1255): ,	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1255): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,E/Uploader( 1255): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1255): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1255): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1255): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided
,W/Uploader( 1255): No account for auth token provided,
,W/Uploader( 1255):  no longer exists, so no auth token.
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1255): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1255): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1255): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1255): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1255): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1255): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GoogleAuthProtoRequest( 3700): [396] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3700): [396] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3700): [396] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3700): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3700): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3700): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3700): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1236): run()
I/Keyboard.Facilitator( 1236): flushDynamicLanguageModels()
,I/ConfigService( 1255): onCreate
,I/ConfigService( 1255): onDestroy
,I/BooksSync( 3950): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3950): GmsCore Version = 7.8.99 (2134222-430),
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3950): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3950): Soft error
E/BooksSync( 3950): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3950): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3950): Sync error
E/BooksSync( 3950): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3950): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3950): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 230198, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 68724(3MB) AllocSpace objects, 8(736KB) LOS objects, 36% free, 27MB/43MB, paused 1.760ms total 70.944ms
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/KeepSync( 3920): Connecting to GoogleApiClient
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1793): Handling authorization failure
E/ClientConnectionOperation( 1793): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1793): 	,at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1793): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:310),
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1793): 	,at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1793): 	... 7 more
,V/KeepSync( 3920): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted),
,I/art     (  822): Explicit concurrent mark sweep GC freed 35787(1570KB) AllocSpace objects, 3(142KB) LOS objects, 31% free, 34MB/50MB, paused 1.738ms total 80.224ms
,E/HttpOperation( 3501): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3501): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3501): 	at jdm.a(PG:82)
E/HttpOperation( 3501): 	at jcs.o(PG:406)
E/HttpOperation( 3501): 	at jcn.a(PG:1379)
E/HttpOperation( 3501): 	at jcs.i(PG:143)
E/HttpOperation( 3501): 	at blb.a(PG:3937)
E/HttpOperation( 3501): 	at czp.a(PG:18188)
E/HttpOperation( 3501): 	at czp.a(PG:9081)
E/HttpOperation( 3501): 	at czq.run(PG:1686)
E/HttpOperation( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3501): 	at jdj.a(PG:4091)
E/HttpOperation( 3501): 	at jdj.a(PG:1125)
E/HttpOperation( 3501): 	at jdm.a(PG:77)
E/HttpOperation( 3501): 	... 12 more
E/HttpOperation( 3501): Caused by: faj: BadAuthentication
E/HttpOperation( 3501): 	at fal.a(PG:38)
E/HttpOperation( 3501): 	at jdj.a(PG:4089)
E/HttpOperation( 3501): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3501): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3501): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3501): 	at jdm.a(PG:82)
E/HttpOperation( 3501): 	at jcs.o(PG:406)
E/HttpOperation( 3501): 	at jcn.a(PG:1379)
E/HttpOperation( 3501): 	at jcs.i(PG:143)
E/HttpOperation( 3501): 	at hec.a(PG:42)
E/HttpOperation( 3501): 	at hee.a(PG:102)
E/HttpOperation( 3501): 	at czr.a(PG:65)
E/HttpOperation( 3501): 	at kka.a(PG:108)
E/HttpOperation( 3501): 	at czp.a(PG:19176)
E/HttpOperation( 3501): 	at czp.a(PG:9081)
E/HttpOperation( 3501): 	at czq.run(PG:1686)
E/HttpOperation( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3501): 	at jdj.a(PG:4091)
E/HttpOperation( 3501): 	at jdj.a(PG:1125)
E/HttpOperation( 3501): 	at jdm.a(PG:77)
E/HttpOperation( 3501): 	... 15 more
E/HttpOperation( 3501): Caused by: faj: BadAuthentication
E/HttpOperation( 3501): 	at fal.a(PG:38)
E/HttpOperation( 3501): 	at jdj.a(PG:4089)
E/HttpOperation( 3501): 	... 17 more
,E/ExperimentLoader( 3501): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3501): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3501): 	at jdm.a(PG:82)
E/ExperimentLoader( 3501): 	at jcs.o(PG:406)
E/ExperimentLoader( 3501): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3501): 	at jcs.i(PG:143)
E/ExperimentLoader( 3501): 	at hec.a(PG:42)
E/ExperimentLoader( 3501): 	at hee.a(PG:102)
E/ExperimentLoader( 3501): 	at czr.a(PG:65)
E/ExperimentLoader( 3501): 	at kka.a(PG:108)
E/ExperimentLoader( 3501): 	,at czp.a(PG:19176)
E/ExperimentLoader( 3501): 	at czp.a(PG:9081)
E/ExperimentLoader( 3501): 	at czq.run(PG:1686)
E/ExperimentLoader( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3501): 	at java.lang.Thread.run(Thread.java:818),
E/ExperimentLoader( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3501): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3501): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3501): 	at jdm.a(PG:77)
E/ExperimentLoader( 3501): 	... 15 more
E/ExperimentLoader( 3501): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3501): 	at fal.a(PG:38)
E/ExperimentLoader( 3501): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3501): 	... 17 more
,E/KeepSync( 3920): IOException
E/KeepSync( 3920): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3920): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3920): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3920): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3920): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3920): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3920): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3920): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3920): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3920): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3920): 	... 10 more
W/KeepSync( 3920): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 234736, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 232307, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3700): [398] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3700): [398] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3700): [398] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3700): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3700): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3700): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3700): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/BooksSync( 3950): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3950): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1255): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1255): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1255): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1255): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1255): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1255): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1255): 	at android.os.Binder.execTransact(Binder.java:446)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,E/PlayEventLogger( 3042): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3042): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3042): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3042): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3042): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3042): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3042): 	at android.os.Binder.execTransact(Binder.java:446)
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3950): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3950): Soft error
E/BooksSync( 3950): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3950): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3950): Sync error
E/BooksSync( 3950): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3950): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3950): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 353520, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/System  ( 3042): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@36578bdb}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@36578bdb}
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed,
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/KeepSync( 3920): Connecting to GoogleApiClient
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1793): Handling authorization failure
E/ClientConnectionOperation( 1793): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1793): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1793): 	... 7 more
,V/KeepSync( 3920): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 3501): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3501): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3501): 	at jdm.a(PG:82)
E/HttpOperation( 3501): 	at jcs.o(PG:406)
E/HttpOperation( 3501): 	at jcn.a(PG:1379)
E/HttpOperation( 3501): 	at jcs.i(PG:143)
E/HttpOperation( 3501): 	at blb.a(PG:3937)
E/HttpOperation( 3501): 	at czp.a(PG:18188)
E/HttpOperation( 3501): 	at czp.a(PG:9081)
E/HttpOperation( 3501): 	at czq.run(PG:1686)
E/HttpOperation( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3501): 	at jdj.a(PG:4091)
E/HttpOperation( 3501): 	at jdj.a(PG:1125)
E/HttpOperation( 3501): 	at jdm.a(PG:77)
E/HttpOperation( 3501): 	... 12 more
E/HttpOperation( 3501): Caused by: faj: BadAuthentication
E/HttpOperation( 3501): 	at fal.a(PG:38)
E/HttpOperation( 3501): 	at jdj.a(PG:4089)
E/HttpOperation( 3501): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3501): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3501): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3501): 	at jdm.a(PG:82)
E/HttpOperation( 3501): 	at jcs.o(PG:406)
E/HttpOperation( 3501): 	at jcn.a(PG:1379)
E/HttpOperation( 3501): 	at jcs.i(PG:143)
E/HttpOperation( 3501): 	at hec.a(PG:42)
E/HttpOperation( 3501): 	at hee.a(PG:102)
E/HttpOperation( 3501): 	at czr.a(PG:65)
E/HttpOperation( 3501): 	at kka.a(PG:108)
E/HttpOperation( 3501): 	at czp.a(PG:19176)
E/HttpOperation( 3501): 	at czp.a(PG:9081)
E/HttpOperation( 3501): 	at czq.run(PG:1686)
E/HttpOperation( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3501): 	at jdj.a(PG:4091)
E/HttpOperation( 3501): 	at jdj.a(PG:1125)
E/HttpOperation( 3501): 	at jdm.a(PG:77)
E/HttpOperation( 3501): 	... 15 more
E/HttpOperation( 3501): Caused by: faj: BadAuthentication
E/HttpOperation( 3501): 	at fal.a(PG:38)
E/HttpOperation( 3501): 	at jdj.a(PG:4089)
E/HttpOperation( 3501): 	... 17 more
E/ExperimentLoader( 3501): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3501): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3501): 	at jdm.a(PG:82)
E/ExperimentLoader( 3501): 	at jcs.o(PG:406)
E/ExperimentLoader( 3501): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3501): 	at jcs.i(PG:143)
E/ExperimentLoader( 3501): 	at hec.a(PG:42)
E/ExperimentLoader( 3501): 	at hee.a(PG:102)
E/ExperimentLoader( 3501): 	at czr.a(PG:65)
E/ExperimentLoader( 3501): 	at kka.a(PG:108)
E/ExperimentLoader( 3501): 	at czp.a(PG:19176)
E/ExperimentLoader( 3501): 	at czp.a(PG:9081)
E/ExperimentLoader( 3501): 	at czq.run(PG:1686)
E/ExperimentLoader( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3501): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3501): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3501): 	at jdm.a(PG:77)
E/ExperimentLoader( 3501): 	... 15 more
E/ExperimentLoader( 3501): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3501): 	at fal.a(PG:38)
E/ExperimentLoader( 3501): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3501): 	... 17 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3920): IOException
E/KeepSync( 3920): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3920): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3920): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3920): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3920): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3920): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3920): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3920): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3920): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3920): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3920): 	... 10 more
,W/KeepSync( 3920): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 391827, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 387615, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3700): [399] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  822): Explicit concurrent mark sweep GC freed 35169(1609KB) AllocSpace objects, 16(821KB) LOS objects, 31% free, 34MB/50MB, paused 1.842ms total 96.395ms
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3700): [399] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3700): [399] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3700): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3700): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3700): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3700): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/BooksSync( 3950): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3950): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 55188(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.573ms total 61.549ms
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3950): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3950): Soft error
E/BooksSync( 3950): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3950): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3950): Sync error
E/BooksSync( 3950): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3950): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3950): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 599808, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3501): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3501): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3501): 	at jdm.a(PG:82)
E/HttpOperation( 3501): 	at jcs.o(PG:406)
E/HttpOperation( 3501): 	at jcn.a(PG:1379)
E/HttpOperation( 3501): 	at jcs.i(PG:143)
E/HttpOperation( 3501): 	at blb.a(PG:3937)
E/HttpOperation( 3501): 	at czp.a(PG:18188)
E/HttpOperation( 3501): 	at czp.a(PG:9081)
E/HttpOperation( 3501): 	at czq.run(PG:1686)
E/HttpOperation( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3501): 	at jdj.a(PG:4091)
E/HttpOperation( 3501): 	at jdj.a(PG:1125)
E/HttpOperation( 3501): 	at jdm.a(PG:77)
E/HttpOperation( 3501): 	... 12 more
E/HttpOperation( 3501): Caused by: faj: BadAuthentication
E/HttpOperation( 3501): 	at fal.a(PG:38)
E/HttpOperation( 3501): 	at jdj.a(PG:4089)
E/HttpOperation( 3501): 	... 14 more
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3501): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3501): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3501): 	at jdm.a(PG:82)
E/HttpOperation( 3501): 	at jcs.o(PG:406)
E/HttpOperation( 3501): 	at jcn.a(PG:1379)
E/HttpOperation( 3501): 	at jcs.i(PG:143)
E/HttpOperation( 3501): 	at hec.a(PG:42)
E/HttpOperation( 3501): 	at hee.a(PG:102)
E/HttpOperation( 3501): 	at czr.a(PG:65)
E/HttpOperation( 3501): 	at kka.a(PG:108)
E/HttpOperation( 3501): 	at czp.a(PG:19176)
E/HttpOperation( 3501): 	at czp.a(PG:9081)
E/HttpOperation( 3501): 	at czq.run(PG:1686)
E/HttpOperation( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3501): 	at jdj.a(PG:4091)
E/HttpOperation( 3501): 	at jdj.a(PG:1125)
E/HttpOperation( 3501): 	at jdm.a(PG:77)
E/HttpOperation( 3501): 	... 15 more
E/HttpOperation( 3501): Caused by: faj: BadAuthentication
E/HttpOperation( 3501): 	at fal.a(PG:38)
E/HttpOperation( 3501): 	at jdj.a(PG:4089)
E/HttpOperation( 3501): 	... 17 more
,E/ExperimentLoader( 3501): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3501): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3501): 	at jdm.a(PG:82)
E/ExperimentLoader( 3501): 	at jcs.o(PG:406)
E/ExperimentLoader( 3501): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3501): 	at jcs.i(PG:143)
E/ExperimentLoader( 3501): 	at hec.a(PG:42)
E/ExperimentLoader( 3501): 	at hee.a(PG:102)
E/ExperimentLoader( 3501): 	at czr.a(PG:65)
E/ExperimentLoader( 3501): 	at kka.a(PG:108)
E/ExperimentLoader( 3501): 	at czp.a(PG:19176)
E/ExperimentLoader( 3501): 	at czp.a(PG:9081)
E/ExperimentLoader( 3501): 	at czq.run(PG:1686)
E/ExperimentLoader( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3501): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3501): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3501): 	at jdm.a(PG:77)
E/ExperimentLoader( 3501): 	... 15 more
E/ExperimentLoader( 3501): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3501): 	at fal.a(PG:38)
E/ExperimentLoader( 3501): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3501): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 668026, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3920): Connecting to GoogleApiClient
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1793): Handling authorization failure
E/ClientConnectionOperation( 1793): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1793): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1793): 	... 7 more
,V/KeepSync( 3920): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3920): IOException
E/KeepSync( 3920): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3920): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3920): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3920): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3920): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3920): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3920): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3920): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3920): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3920): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3920): 	... 10 more
W/KeepSync( 3920): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 676562, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3700): [400] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3700): [400] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3700): [400] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3700): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3700): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3700): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3700): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3700): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3700): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2395): Stopping oneshot timer
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/GCM     ( 1255): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/art     (  822): Explicit concurrent mark sweep GC freed 51412(2MB) AllocSpace objects, 11(553KB) LOS objects, 31% free, 34MB/50MB, paused 1.656ms total 77.486ms
,I/BooksSync( 3950): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3950): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3950): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3950): Soft error
E/BooksSync( 3950): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3950): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3950): Sync error
E/BooksSync( 3950): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3950): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3950): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1091812, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3501): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3501): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3501): 	at jdm.a(PG:82)
E/HttpOperation( 3501): 	at jcs.o(PG:406)
E/HttpOperation( 3501): 	at jcn.a(PG:1379)
E/HttpOperation( 3501): 	at jcs.i(PG:143)
E/HttpOperation( 3501): 	at blb.a(PG:3937)
E/HttpOperation( 3501): 	at czp.a(PG:18188)
E/HttpOperation( 3501): 	at czp.a(PG:9081)
E/HttpOperation( 3501): 	at czq.run(PG:1686)
E/HttpOperation( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3501): 	at jdj.a(PG:4091)
E/HttpOperation( 3501): 	at jdj.a(PG:1125)
E/HttpOperation( 3501): 	at jdm.a(PG:77)
E/HttpOperation( 3501): 	... 12 more
E/HttpOperation( 3501): Caused by: faj: BadAuthentication
E/HttpOperation( 3501): 	at fal.a(PG:38)
E/HttpOperation( 3501): 	at jdj.a(PG:4089)
E/HttpOperation( 3501): 	... 14 more
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 64395(3MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 1.440ms total 64.123ms
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3501): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3501): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3501): 	at jdm.a(PG:82)
E/HttpOperation( 3501): 	at jcs.o(PG:406)
E/HttpOperation( 3501): 	at jcn.a(PG:1379)
E/HttpOperation( 3501): 	at jcs.i(PG:143)
E/HttpOperation( 3501): 	at hec.a(PG:42)
E/HttpOperation( 3501): 	at hee.a(PG:102)
E/HttpOperation( 3501): 	at czr.a(PG:65)
E/HttpOperation( 3501): 	at kka.a(PG:108)
E/HttpOperation( 3501): 	at czp.a(PG:19176)
E/HttpOperation( 3501): 	at czp.a(PG:9081)
E/HttpOperation( 3501): 	at czq.run(PG:1686)
E/HttpOperation( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3501): 	at jdj.a(PG:4091)
E/HttpOperation( 3501): 	at jdj.a(PG:1125)
E/HttpOperation( 3501): 	at jdm.a(PG:77)
E/HttpOperation( 3501): 	... 15 more
E/HttpOperation( 3501): Caused by: faj: BadAuthentication
E/HttpOperation( 3501): 	at fal.a(PG:38)
E/HttpOperation( 3501): 	at jdj.a(PG:4089)
E/HttpOperation( 3501): 	... 17 more
,E/ExperimentLoader( 3501): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3501): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3501): 	at jdm.a(PG:82)
E/ExperimentLoader( 3501): 	at jcs.o(PG:406)
E/ExperimentLoader( 3501): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3501): 	at jcs.i(PG:143)
E/ExperimentLoader( 3501): 	at hec.a(PG:42)
E/ExperimentLoader( 3501): 	at hee.a(PG:102)
E/ExperimentLoader( 3501): 	at czr.a(PG:65)
E/ExperimentLoader( 3501): 	at kka.a(PG:108)
E/ExperimentLoader( 3501): 	at czp.a(PG:19176)
E/ExperimentLoader( 3501): 	at czp.a(PG:9081)
E/ExperimentLoader( 3501): 	at czq.run(PG:1686)
E/ExperimentLoader( 3501): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3501): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3501): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3501): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3501): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3501): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3501): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3501): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3501): 	at jdm.a(PG:77)
E/ExperimentLoader( 3501): 	... 15 more
E/ExperimentLoader( 3501): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3501): 	at fal.a(PG:38)
E/ExperimentLoader( 3501): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3501): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1176176, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,V/KeepSync( 3920): Connecting to GoogleApiClient
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1793): Handling authorization failure
E/ClientConnectionOperation( 1793): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1793): Caused by: com.google.android.gms.auth.ad: BadAuthentication
,E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1793): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1793),: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1793): 	... 7 more
V/KeepSync( 3920): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3920): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1255): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1255): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1255): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1255): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3920): IOException
E/KeepSync( 3920): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3920): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3920): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3920): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3920): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3920): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3920): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3920): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3920): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3920): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3920): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3920): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3920): 	... 10 more
W/KeepSync( 3920): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1223544, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4292): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4292): CheckJNI is OFF
D/AndroidRuntime( 4292): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 3639:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  822): Skipping PackageSetting{32710a53 com.example.hello/10273} due to missing metadata
I/WindowState(  822): WIN DEATH: Window{1500542f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  822): Client connection lost with reason: 4
E/libprocessgroup(  822): failed to kill 1 processes for processgroup 3639
W/ActivityManager(  822): Force removing ActivityRecord{2d289462 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
V/ActivityManager(  822): Display changed displayId=0
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
W/ActivityManager(  822): Spurious death for ProcessRecord{25e12769 3639:com.test.thalitest/u0a265}, curProc for 3639: null
I/Keyboard.Facilitator( 1236): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1236): run()
D/TaskPersister(  822): removeObsoleteFile: deleting file=28_task.xml
I/Decoder ( 1236): createOrResetDecoder
D/BuaReceiver( 3373): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  822): Start proc 4308:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     ( 1066): Explicit concurrent mark sweep GC freed 73825(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 891us total 70.346ms
W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3639 uid 10265
I/art     (  822): Explicit concurrent mark sweep GC freed 31592(1746KB) AllocSpace objects, 11(364KB) LOS objects, 31% free, 34MB/50MB, paused 1.372ms total 86.456ms
I/Keyboard.Facilitator( 1236): onFinishInput()
I/art     ( 1523): Explicit concurrent mark sweep GC freed 3675(325KB) AllocSpace objects, 1(25KB) LOS objects, 36% free, 27MB/43MB, paused 1.682ms total 110.149ms
I/art     (  822): WaitForGcToComplete blocked for 95.422ms for cause Explicit
I/ConfigService( 1255): onCreate
I/art     ( 1347): Explicit concurrent mark sweep GC freed 5080(371KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 818us total 21.351ms
W/LocationOracleImpl( 1523): Best location was null
I/HotwordRecognitionRnr( 1523): Starting hotword detection.
I/MicrophoneInputStream( 1523): mic_starting com.google.android.apps.gsa.speech.audio.u@2f03c1fd
D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/AudioFlinger(  357): AudioFlinger's thread 0xb4d2d000 ready to run
I/MicrophoneInputStream( 1523): mic_started com.google.android.apps.gsa.speech.audio.u@2f03c1fd
I/Keyboard.Facilitator.MainLanguageModelLoader( 1236): run()
D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
I/Keyboard.Facilitator.MainLanguageModelLoader( 1236): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1236): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1236): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1236): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1236): run()
I/StatsUtilsManager( 1236): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1236): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 4308): Cleaning up data for package: com.test.thalitest
I/art     (  822): Explicit concurrent mark sweep GC freed 7075(326KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 2.400ms total 135.733ms
I/ActivityManager(  822): Start proc 4347:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/HotwordWorker( 1523): onReady
D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1a52e63c}
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=28.25 rxSuccessRate=37.50 targetRoamBSSID=any RSSI=-51
I/ContactLocale( 4308): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=62.12 rxSuccessRate=188.25 targetRoamBSSID=any RSSI=-51
I/ActivityManager(  822): Start proc 4366:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
W/ContextImpl( 4366): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1721988371
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/art     ( 4292): System.exit called, status: 0
I/AndroidRuntime( 4292): VM exiting with result code 0.
E/NetworkScheduler.SchedulerReceiver( 1255): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1255): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  822): Killing 3432:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
D/PackageBroadcastService( 1793): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1793): Clearing selected account for com.test.thalitest
I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1793): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1793): Removing dialog suppression flag for package com.test.thalitest
D/Launcher.Workspace( 1347): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1347): 11683562 - stripEmptyScreens()
D/ChimeraCfgMgr( 1793): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1793): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1793): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1793): disk I/O error (code 3850)
E/DriveAsyncService( 1793): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1793): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1793): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1793): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1793): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1793): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1793): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1793): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1793): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1793): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1347): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
E/SQLiteLog( 1793): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 1793): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1793): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1793): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1793): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1793): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1793): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1793): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1793): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1793): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1793): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1793): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1793): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1793): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1793): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1793): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1793): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1793): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1793): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1793): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1793): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1793): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1793): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1793): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1793): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1793): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1793): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1793): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1793): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1793): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1793): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1793): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1793): Sending signal. PID: 1793 SIG: 9
I/ActivityManager(  822): Start proc 4400:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/lowmemorykiller(  255): Error writing /proc/1793/oom_score_adj; errno=22
I/UpdateIcingCorporaServi( 1523): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 197us total 10.632ms
W/Launcher( 1347): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@227917be new=com.google.android.velvet.VelvetApplication@227917be
E/SQLiteLog( 1347): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 8.822ms
W/ResourcesManager( 4400): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4400): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 8.726ms
E/SQLiteLog( 1523): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/WifiService(  822): Client connection lost with reason: 4
I/MultiDex( 4400): VM with version 2.1.0 has multidex support
I/MultiDex( 4400): install
I/MultiDex( 4400): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  822): Start proc 4417:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/ActivityManager(  822): Start proc 4435:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
I/ActivityManager(  822): Process com.google.android.gms (pid 1793) has died
E/SharedPreferencesImpl( 1523): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
--------- beginning of crash
E/AndroidRuntime( 1523): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1523): Process: com.google.android.googlequicksearchbox:search, PID: 1523
E/AndroidRuntime( 1523): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1523): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1523): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1523): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1523): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1523): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1523): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1523): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1523): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1523): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1523): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1523): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
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
D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  822): Validating map...
V/JNIHelp ( 4400): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/OpenGLRenderer(  822): Initialized EGL, version 1.4
D/OpenGLRenderer(  822): Enabling debug mode 0
I/ProviderInstaller( 4400): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  822): Start proc 4457:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
I/ActivityManager(  822): Killing 3327:com.google.android.music:main/u0a66 (adj 15): empty #17
W/NativeLibraryUtils( 4400): Failed to open lock file
W/NativeLibraryUtils( 4400): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4400): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4400): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4400): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4400): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4400): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4400): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4400): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4400): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4400): 	... 3 more
W/ResourcesManager( 4457): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4457): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 4457): VM with version 2.1.0 has multidex support
I/MultiDex( 4457): install
I/MultiDex( 4457): VM has multidex support, MultiDex support library is disabled.
I/HotwordDetector( 1523): Closing mic
I/MicrophoneInputStream( 1523): mic_close com.google.android.apps.gsa.speech.audio.u@2f03c1fd
E/SQLiteDatabase( 4457): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4457): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 4457): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 4457): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4457): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4457): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4457): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4457): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4457): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 4457): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 4457): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4457): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4457): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4457): 	at java.lang.Thread.run(Thread.java:818)
E/Search.SharedPreferencesProto( 1523): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
V/JNIHelp ( 4457): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/HotwordRecognitionRnr( 1523): Hotword detection finished
I/HotwordRecognitionRnr( 1523): Stopping hotword detection.
I/ProviderInstaller( 4457): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4457): Failed to open lock file
W/NativeLibraryUtils( 4457): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4457): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4457): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4457): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4457): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4457): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4457): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4457): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4457): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4457): 	... 3 more
I/GAv4    ( 4417): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4417):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4417):   adb logcat -s GAv4
W/GAv4    ( 4417): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4417): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4417): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
W/GAv4    ( 4417): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4417): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4417): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4417): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4417): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4417): 	at aen.run(PG:536)
E/SQLiteDatabase( 4417): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4417): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4417): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4417): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4417): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4417): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4417): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4417): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4417): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4417): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4417): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4417): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4417): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4417): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4417): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/Icing   ( 4457): Storage manager: low false usage 1.98MB avail 20.74GB capacity 22.09GB
E/SQLiteDatabase( 4457): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4457): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteDatabase( 4457): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4457): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4457): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 4457): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 4457): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteDatabase( 4457): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteDatabase( 4457): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4457): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4457): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 4457): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4457): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteOpenHelper( 4457): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteOpenHelper( 4457): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteOpenHelper( 4457): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteOpenHelper( 4457): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteOpenHelper( 4457): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteOpenHelper( 4457): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteOpenHelper( 4457): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteOpenHelper( 4457): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4457): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 4457): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4457): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4457): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager(  822): Killing 3726:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
W/SQLiteOpenHelper( 4457): Opened reminders.db in read-only mode
W/Icing   ( 4457): Received bad json for section weights override -- ignoring.
E/SQLiteDatabase( 4457): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4457): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/SQLiteDatabase( 4457): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 4457): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 4457): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4457): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4457): 	at java.lang.Thread.run(Thread.java:818)
W/Icing   ( 4457): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4457): Received bad json for section weights override -- ignoring.
W/Icing   ( 4457): Received bad json for corpus context scoring override -- ignoring.
E/AndroidRuntime( 4457): FATAL EXCEPTION: AsyncTask #3
E/AndroidRuntime( 4457): Process: com.google.android.gms, PID: 4457
E/AndroidRuntime( 4457): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 4457): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/AndroidRuntime( 4457): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 4457): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 4457): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 4457): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 4457): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4457): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4457): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4457): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4457): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/AndroidRuntime( 4457): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 4457): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 4457): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AndroidRuntime( 4457): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4457): 	... 4 more
E/DropBoxManagerService(  822): Can't write: system_app_crash
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
W/ResourcesManager(  822): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  822): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 4417): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4417): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/SQLiteDatabase( 4417): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4417): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4417): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4417): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4417): 	at aej.c(PG:139)
E/SQLiteDatabase( 4417): 	at aej.b(PG:398)
E/SQLiteDatabase( 4417): 	at agf.f(PG:417)
E/SQLiteDatabase( 4417): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4417): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4417): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4417): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4417): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4417): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4417): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4417): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4417): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4417): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4417): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4417): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4417): 	at java.lang.Thread.run(Thread.java:818)
I/GAv4-SVC( 4457): Google Analytics 7.8.99 is starting up.
D/GFEEDBACK_SendErrorReportOperation( 4457): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 4457): Error saving report: java.io.IOException: failed to create reports directory
E/Icing   ( 4457): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids for write failed: Read-only file system
E/Icing   ( 4457): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids
E/Icing   ( 4457): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata for write failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
E/Icing   ( 4457): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring for write failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
E/Icing   ( 4457): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs for write failed: Read-only file system
E/Icing   ( 4457): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs
E/Icing   ( 4457): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.tags.h for write failed: Read-only file system
E/Icing   ( 4457): Trie initialize fail
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
E/Icing   ( 4457): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h for write failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
E/Icing   ( 4457): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage for write failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
E/Icing   ( 4457): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage for write failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
E/Icing   ( 4457): Init docstore failed
E/Icing   ( 4457): Index init failed, resetting corpora
V/JNIHelp ( 4417): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  822): Start proc 4511:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.index failed: Read-only file system
E/Icing   ( 4457): Clearing index failed
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
E/Icing   ( 4457): D,eleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-0 failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-24 failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-30 failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user.__unseen__i.43133bd20a9b3232 failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
E/Icing   ( 4457): Clearing docstore failed
E/Icing   ( 4457): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/compact_status failed: Read-only file system
E/Icing   ( 4457): Deleting compact status failed
I/ActivityManager(  822): Killing 3746:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
I/ProviderInstaller( 4417): Installed default security provider GmsCore_OpenSSL
E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
V/GLSActivity( 1255): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
E/native  ( 1236): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1236): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
W/GAv4    ( 4417): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4417): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4417): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4417): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4417): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4417): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4417): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4417): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4417): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4417): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4417): 	at aej.c(PG:139)
E/SQLiteDatabase( 4417): 	at aej.a(PG:358)
E/SQLiteDatabase( 4417): 	at aej.a(PG:345)
E/SQLiteDatabase( 4417): 	at agf.c(PG:884)
E/SQLiteDatabase( 4417): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 4417): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4417): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4417): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4417): Failed to query Account133 object
E/AbstractDatabaseInstance( 4417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDataba
```
