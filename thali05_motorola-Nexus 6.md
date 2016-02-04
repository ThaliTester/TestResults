#### Test 58135655a1ee273_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/CheckinService( 1781): Done disabling old GoogleServicesFramework version
,D/AndroidRuntime( 3555): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3555): CheckJNI is OFF
D/AndroidRuntime( 3555): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{3f06f92d token=Token{28794444 ActivityRecord{131e0157 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3555): Shutting down VM
V/WindowManager(  823): Adding window Window{cb59eae u0 Starting com.test.thalitest} at 2 of 7 (after Window{8c8722e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/MicrophoneInputStream( 1532): mic_close com.google.android.apps.gsa.speech.audio.u@129f6555
I/HotwordDetector( 1532): Closing mic
I/ActivityManager(  823): Start proc 3569:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1532): Stopping hotword detection.
I/HotwordRecognitionRnr( 1532): Hotword detection finished
I/ActivityManager(  823): Killing 3176:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1701111059
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3569): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3569): Time to load native libraries: 11 ms (timestamps 2015-2026)
I/LibraryLoader( 3569): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3569): Binding Chromium to main looper Looper (main, tid 1) {38681ac4}
,I/LibraryLoader( 3569): Expected native library version number "",actual native library version number ""
,I/chromium( 3569): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3569): Initializing chromium process, singleProcess=true
,W/art     ( 3569): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3569): ApplicationContext is null in ApplicationStatus
,W/chromium( 3569): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3569): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3569): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3569): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ed55e0:true
,W/art     ( 3569): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3569): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3569): CordovaWebView is running on device made by: motorola
,W/art     ( 3569): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3569): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3569): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3569): Validating map...
,V/WindowManager(  823): Adding window Window{3071f710 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{cb59eae u0 Starting com.test.thalitest})
,W/chromium( 3569): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3569): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3569): Enabling debug mode 0
,I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +931ms
,I/Keyboard.Facilitator( 1242): onFinishInput()
,W/BindingManager( 3569): Cannot call determinedVisibility() - never saw a connection for the pid: 3569
,D/JsMessageQueue( 3569): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3569): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576326784
,I/chromium( 3569): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3569): Initializing JXcore engine
,W/jxcore-log( 3569): JXcore engine is ready
,W/Thread-391( 3623): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10829]" dev="sockfs" ino=10829 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-391( 3623): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-391( 3623): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11677]" dev="sockfs" ino=11677 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-391( 3623): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22751]" dev="sockfs" ino=22751 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3569): Starting JXcore engine
,W/jxcore-log( 3569): Platform android
W/jxcore-log( 3569): 
W/jxcore-log( 3569): Process ARCH arm
W/jxcore-log( 3569): 
,I/jxcore-log( 3569): JXcore Cordova bridge is ready!
I/jxcore-log( 3569): 
W/jxcore-log( 3569): JXcore engine is started
,I/ActivityManager(  823): Waited long enough for: ServiceRecord{33c8fe6e u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/jxcore-log( 3569): Toggling radios to true
I/jxcore-log( 3569): 
,D/BluetoothAdapter( 3569): enable(): BT is already enabled..!
,D/WifiService(  823): setWifiEnabled: true pid=3569, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  823): New client listening to asynchronous messages
,I/jxcore-log( 3569): Radios toggled
I/jxcore-log( 3569): 
I/jxcore-log( 3569): My device name is: motorola-Nexus 6
I/jxcore-log( 3569): 
,I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1268): Read error: ssl=0xaed2b200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1268): SSL shutdown failed: ssl=0xaed2b200: I/O error during system call, Broken pipe
,D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Forcing reevaluation
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  823): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Disconnected - quitting
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
D/ConnectivityManager.CallbackHandler( 1075): CM callback handler got msg 524292
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  823): MasterInitialState.processMessage what=3
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkChangeNotifierAutoDetect( 1532): Network connectivity changed, type is: 6
,D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering(  823): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3305): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/GpsLocationProvider(  823): No APN found to select.
,D/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/WifiConfigStore(  823): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  823): will read network variables netId=0
,I/ActivityManager(  823): Start proc 3632:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  823): will read network variables netId=0,
,I/art     (  823): Explicit concurrent mark sweep GC freed 31094(1567KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 5.985ms total 67.998ms
,E/GpsLocationProvider(  823): No APN found to select.
,I/ActivityManager(  823): Start proc 3659:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  823): Killing 3208:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,D/SprintDMReceiver( 3659): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3659): simOperator:  IMSI: null
,D/SprintDMReceiver( 3659): Not Sprint UICC, don't do anything.
,I/ActivityManager(  823): Killing 3001:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/SystemUpdateService( 1781): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1781): onCreate
,D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1781): active receiver: enabled
,I/SystemUpdateService( 1781): showing system update notification
,I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1781): num queued entries: 0
,I/iu.UploadsManager( 1781): num updated entries: 0
I/iu.SyncManager( 1781): NEXT; no task
,I/ValidateNoPeople(  823): skipping global notification
D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1781): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,V/SystemUpdateService( 1781): retry (wakeup: false) in 3599949 ms
,D/SystemUpdateService( 1781): onDestroy
,I/ActivityManager(  823): Start proc 3679:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 2950): connection state changed from UNKNOWN to DISCONNECTED
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 321us total 23.942ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 325us total 13.291ms,
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 320us total 12.968ms,
,I/GAv4    ( 3679): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3679):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3679):   adb logcat -s GAv4
,W/GAv4    ( 3679): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3679): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3679): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3679): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3679): Time to load native libraries: 6 ms (timestamps 6529-6535)
I/LibraryLoader( 3679): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3679): Binding Chromium to main looper Looper (main, tid 1) {9a210bb}
,I/LibraryLoader( 3679): Expected native library version number "",actual native library version number "",
I/chromium( 3679): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3679): Initializing chromium process, singleProcess=true,
W/art     ( 3679): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3679): ApplicationContext is null in ApplicationStatus
,W/chromium( 3679): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3679): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3679): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3679): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3679): Requires BLUETOOTH permission
,I/NSApplication( 3679): Starting up...
,I/ActivityManager(  823): Start proc 3735:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  823): Killing 3253:com.android.settings/1000 (adj 15): empty #17
,I/wpa_supplicant( 1155): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  823): Start proc 3763:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  823): Killing 3273:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/wpa_supplicant( 1155): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1155): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  354): Setting iface cfg
E/WifiStateMachine(  823): Start Dhcp Watchdog 2
,E/WifiStateMachine(  823):  WifiLinkLayerStats: ,
E/WifiStateMachine(  823):  my bss beacon rx: 198
E/WifiStateMachine(  823):  RSSI mgmt: -51
E/WifiStateMachine(  823):  BE :  rx=170 tx=154 lost=0 retries=0
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0,
E/WifiStateMachine(  823):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 8112 tx_time=158 rx_time=347 scan_time=0
,D/ConnectivityService(  823): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/native  (  823): do suspend false
,E/WifiStateMachine(  823): scanCount==0 - aborting
,V/MusicLeanback( 3305): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3659): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3659): simOperator:  IMSI: null
D/SprintDMReceiver( 3659): Not Sprint UICC, don't do anything.
I/SystemUpdateService( 1781): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1781): onCreate
,D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1781): active receiver: enabled
,I/SystemUpdateService( 1781): showing system update notification
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1781): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1781): retry (wakeup: false) in 3599958 ms
,D/SystemUpdateService( 1781): onDestroy
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dhcpcd  ( 3790): version 5.5.6 starting
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3042): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3042): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3042): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  823): Killing 3372:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/dhcpcd  ( 3790): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3790): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3790): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3569): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3569): 
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  823): Adding iface wlan0 to network 101
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  823): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823):    accepting network in place of null
,D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1075): CM callback handler got msg 524290
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  823): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3305): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  823): Killing 3392:com.android.musicfx/u0a18 (adj 15): empty #17
D/NetworkChangeNotifierAutoDetect( 1532): Network connectivity changed, type is: 2
,V/MusicLeanback( 3305): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 14:46:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454597192231], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454597192208]}
,I/ActivityManager(  823): Start proc 3822:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/ActivityManager(  823): Killing 3444:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Validated
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1355): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1075): CM callback handler got msg 524290
D/TelephonyManager(  823): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3659): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3659): simOperator:  IMSI: null
D/SprintDMReceiver( 3659): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1781): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1781): onCreate
,E/GpsLocationProvider(  823): No APN found to select.
,D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1781): active receiver: enabled
,I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1781): num queued entries: 0
I/iu.UploadsManager( 1781): num updated entries: 0
I/iu.SyncManager( 1781): NEXT; no task
,I/SystemUpdateService( 1781): showing system update notification
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1781): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1781): retry (wakeup: false) in 3599946 ms
,D/SystemUpdateService( 1781): onDestroy
,I/art     ( 1268): Explicit concurrent mark sweep GC freed 18203(868KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.033ms total 20.927ms
,V/Herrevad( 1781): NQAS connected
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Babel   ( 2950): connection state changed from DISCONNECTED to CONNECTED
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3480): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3480): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3480): 	at jdm.a(PG:82)
E/HttpOperation( 3480): 	at jcs.o(PG:406)
E/HttpOperation( 3480): 	at jcn.a(PG:1379)
E/HttpOperation( 3480): 	at jcs.i(PG:143)
E/HttpOperation( 3480): 	at blb.a(PG:3937)
E/HttpOperation( 3480): 	at czp.a(PG:18188)
E/HttpOperation( 3480): 	at czp.a(PG:9081)
E/HttpOperation( 3480): 	at czq.run(PG:1686)
E/HttpOperation( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3480): 	at jdj.a(PG:4091)
E/HttpOperation( 3480): 	at jdj.a(PG:1125)
E/HttpOperation( 3480): 	at jdm.a(PG:77)
E/HttpOperation( 3480): 	... 12 more
E/HttpOperation( 3480): Caused by: faj: BadAuthentication
E/HttpOperation( 3480): 	at fal.a(PG:38)
E/HttpOperation( 3480): 	at jdj.a(PG:4089)
E/HttpOperation( 3480): 	... 14 more
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3480): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3480): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3480): 	at jdm.a(PG:82)
E/HttpOperation( 3480): 	at jcs.o(PG:406)
E/HttpOperation( 3480): 	at jcn.a(PG:1379)
E/HttpOperation( 3480): 	at jcs.i(PG:143)
E/HttpOperation( 3480): 	at hec.a(PG:42)
E/HttpOperation( 3480): 	at hee.a(PG:102)
E/HttpOperation( 3480): 	at czr.a(PG:65)
E/HttpOperation( 3480): 	at kka.a(PG:108)
E/HttpOperation( 3480): 	at czp.a(PG:19176)
E/HttpOperation( 3480): 	at czp.a(PG:9081)
E/HttpOperation( 3480): 	at czq.run(PG:1686)
E/HttpOperation( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3480): 	at jdj.a(PG:4091)
E/HttpOperation( 3480): 	at jdj.a(PG:1125)
E/HttpOperation( 3480): 	at jdm.a(PG:77)
E/HttpOperation( 3480): 	... 15 more
E/HttpOperation( 3480): Caused by: faj: BadAuthentication
E/HttpOperation( 3480): 	at fal.a(PG:38)
E/HttpOperation( 3480): 	at jdj.a(PG:4089)
E/HttpOperation( 3480): 	... 17 more
,E/ExperimentLoader( 3480): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3480): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3480): 	at jdm.a(PG:82)
E/ExperimentLoader( 3480): 	at jcs.o(PG:406)
E/ExperimentLoader( 3480): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3480): 	at jcs.i(PG:143)
E/ExperimentLoader( 3480): 	at hec.a(PG:42)
E/ExperimentLoader( 3480): 	at hee.a(PG:102)
E/ExperimentLoader( 3480): 	at czr.a(PG:65)
E/ExperimentLoader( 3480): 	at kka.a(PG:108)
E/ExperimentLoader( 3480): 	at czp.a(PG:19176)
E/ExperimentLoader( 3480): 	at czp.a(PG:9081)
E/ExperimentLoader( 3480): 	at czq.run(PG:1686)
E/ExperimentLoader( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3480): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3480): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3480): 	at jdm.a(PG:77)
E/ExperimentLoader( 3480): 	... 15 more
E/ExperimentLoader( 3480): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3480): 	at fal.a(PG:38)
E/ExperimentLoader( 3480): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3480): 	... 17 more
,D/GCM     ( 1268): Connected
D/GCM     ( 1268): Message class com.google.f.a.a.p
V/KeepSync( 3822): Connecting to GoogleApiClient
,I/jxcore-log( 3569): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3569): 
,I/art     (  823): Explicit concurrent mark sweep GC freed 38253(1823KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.352ms total 49.746ms
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 79519, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Start proc 3865:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3569): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3569): 
E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3822): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,W/GAV2    ( 3865): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/jxcore-log( 3569): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3569): 
,I/BooksApp( 3865): Created application version: 3.6.8 (30608)
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3569): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3569): 
,E/KeepSync( 3822): IOException
E/KeepSync( 3822): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3822): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3822): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3822): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3822): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3822): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3822): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3822): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3822): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3822): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3822): 	... 10 more
W/KeepSync( 3822): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 78571, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3865): Starting books sync for 61035162, extras: ade
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/BooksConfig( 3865): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3865): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3865): Soft error
E/BooksSync( 3865): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3865): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3865): Sync error
E/BooksSync( 3865): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3865): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3865): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 79798, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Killing 1445:android.process.acore/u0a5 (adj 15): empty #17
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=17.25 rxSuccessRate=16.00 targetRoamBSSID=any RSSI=-50
,E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,D/Finsky  ( 3042): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1268): Explicit concurrent mark sweep GC freed 22528(1383KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 767us total 25.525ms
I/art     ( 1268): WaitForGcToComplete blocked for 21.804ms for cause HeapTrim
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3042): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3042): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GAV2    ( 3865): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.12 rxSuccessRate=9.50 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3569): Test app app.js loaded
I/jxcore-log( 3569): 
,I/chromium( 3569): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a7bfd30 added. We now have 1 listener(s)
,I/jxcore-log( 3569): BLE advertisement is supported
I/jxcore-log( 3569): 
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3042): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3042): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3042): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3042): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1808): client connected with version: 7571000
,I/ActivityManager(  823): Killing 3100:com.google.android.gm/u0a78 (adj 15): empty #17
,D/Finsky  ( 3042): [290] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 28712(1263KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 3.301ms total 91.014ms
,D/Finsky  ( 3042): [290] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.44 rxSuccessRate=5.30 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3042): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3042): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3042): [1] 5.onFinished: Scheduling replication attempt 2.,
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.54 rxSuccessRate=1.78 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3042): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3042): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3042): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0,
,I/Keyboard.Facilitator.LanguageModelFlusher( 1242): run()
,I/Keyboard.Facilitator( 1242): flushDynamicLanguageModels()
,I/ConfigService( 1268): onCreate
,I/ConfigService( 1268): onDestroy
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.60 rxSuccessRate=1.79 targetRoamBSSID=any RSSI=-51
,V/KeepSync( 3822): Connecting to GoogleApiClient
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3822): GoogleApiClient failed to connect with error code: 4
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 3480): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3480): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3480): 	at jdm.a(PG:82)
E/HttpOperation( 3480): 	at jcs.o(PG:406)
E/HttpOperation( 3480): 	at jcn.a(PG:1379)
E/HttpOperation( 3480): 	at jcs.i(PG:143)
E/HttpOperation( 3480): 	at blb.a(PG:3937)
E/HttpOperation( 3480): 	at czp.a(PG:18188)
E/HttpOperation( 3480): 	at czp.a(PG:9081)
E/HttpOperation( 3480): 	at czq.run(PG:1686)
E/HttpOperation( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3480): 	at jdj.a(PG:4091)
E/HttpOperation( 3480): 	at jdj.a(PG:1125)
E/HttpOperation( 3480): 	at jdm.a(PG:77)
E/HttpOperation( 3480): 	... 12 more
E/HttpOperation( 3480): Caused by: faj: BadAuthentication
E/HttpOperation( 3480): 	at fal.a(PG:38)
E/HttpOperation( 3480): 	at jdj.a(PG:4089)
E/HttpOperation( 3480): 	... 14 more
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3480): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3480): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3480): 	at jdm.a(PG:82)
E/HttpOperation( 3480): 	at jcs.o(PG:406)
E/HttpOperation( 3480): 	at jcn.a(PG:1379)
E/HttpOperation( 3480): 	at jcs.i(PG:143)
E/HttpOperation( 3480): 	at hec.a(PG:42)
E/HttpOperation( 3480): 	at hee.a(PG:102)
E/HttpOperation( 3480): 	at czr.a(PG:65)
E/HttpOperation( 3480): 	at kka.a(PG:108)
E/HttpOperation( 3480): 	at czp.a(PG:19176)
E/HttpOperation( 3480): 	at czp.a(PG:9081)
E/HttpOperation( 3480): 	at czq.run(PG:1686)
E/HttpOperation( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3480): 	at jdj.a(PG:4091)
E/HttpOperation( 3480): 	at jdj.a(PG:1125)
E/HttpOperation( 3480): 	at jdm.a(PG:77)
E/HttpOperation( 3480): 	... 15 more
E/HttpOperation( 3480): Caused by: faj: BadAuthentication
E/HttpOperation( 3480): 	at fal.a(PG:38)
E/HttpOperation( 3480): 	at jdj.a(PG:4089)
E/HttpOperation( 3480): 	... 17 more
,E/ExperimentLoader( 3480): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3480): java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 3480): 	,at jdm.a(PG:82),
E/ExperimentLoader( 3480): 	at jcs.o(PG:406)
E/ExperimentLoader( 3480): 	,at jcn.a(PG:1379)
E/ExperimentLoader( 3480): 	at jcs.i(PG:143),
E/ExperimentLoader( 3480): ,	at hec.a(PG:42)
E/ExperimentLoader( 3480): 	,at hee.a(PG:102)
E/ExperimentLoader( 3480): 	at czr.a(PG:65),
E/ExperimentLoader( 3480): 	at kka.a(PG:108)
E/ExperimentLoader( 3480): 	,at czp.a(PG:19176)
E/ExperimentLoader( 3480): 	at czp.a(PG:9081),
E/ExperimentLoader( 3480): 	at czq.run(PG:1686)
E/ExperimentLoader( 3480): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3480): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ExperimentLoader( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error,
E/ExperimentLoader( 3480): 	at jdj.a(PG:4091),
E/ExperimentLoader( 3480): 	at jdj.a(PG:1125)
,E/ExperimentLoader( 3480): 	at jdm.a(PG:77)
E/ExperimentLoader( 3480): 	,... 15 more
E/ExperimentLoader( 3480): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3480): 	,at fal.a(PG:38)
E/ExperimentLoader( 3480): 	at jdj.a(PG:4089),
E/ExperimentLoader( 3480): 	... 17 more
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3822): IOException
E/KeepSync( 3822): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3822): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3822): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3822): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3822): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3822): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3822): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3822): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3822): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3822): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3822): 	... 10 more
W/KeepSync( 3822): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 111711, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3865): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3865): GmsCore Version = 7.8.99 (2134222-430)
D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 113240, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3865): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3865): Soft error
E/BooksSync( 3865): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3865): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3865): Sync error
E/BooksSync( 3865): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3865): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3865): Finished books sync,
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 113541, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3042): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3042): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3042): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.35 rxSuccessRate=3.46 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (210 us)
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  823): Display changed displayId=0
,I/kickstart(  878): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
I/kickstart(  878): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  878): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1,
I/kickstart(  878): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  823): Excessive delay in setPowerMode(): 264ms
,I/DreamManagerService(  823): Entering dreamland.,
I/PowerManagerService(  823): Dozing...
,I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  823): cancelDelayedScan -> 12
,E/native  (  823): do suspend false
,I/Keyboard.Facilitator( 1242): onFinishInput()
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  823): cancelDelayedScan -> 14
,E/native  (  823): do suspend true
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  878): STATUS: Received file 'm9kefs1'
I/kickstart(  878): STATUS: 950272 bytes transferred in 0.995728 seconds
I/kickstart(  878): STATUS: Successfully downloaded files from target 
I/kickstart(  878): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  878): STATUS: Sahara protocol completed
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 54261(2MB) AllocSpace objects, 23(556KB) LOS objects, 31% free, 34MB/50MB, paused 1.495ms total 81.952ms
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1268): Explicit concurrent mark sweep GC freed 37102(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 938us total 46.345ms
,D/Finsky  ( 3042): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3042): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3042): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3632): [385] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1268): Vacuum at: now=1454597292660 tag=VacuumService
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3632): [385] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3632): [385] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3632): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3632): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3632): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3632): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1268): Using platform SSLCertificateSocketFactory
,W/Uploader( 1268): No account for auth token provided
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1268): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1268): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1268): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1268): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1268): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1268): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1268): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1268): No account for auth token provided
,W/Uploader( 1268): No account for auth token provided
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1268): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1268): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1268): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1268): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1268): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1268): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1268): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1268): No account for auth token provided
,W/Uploader( 1268): No account for auth token provided
,W/Uploader( 1268): No account for auth token provided
,W/Uploader( 1268): No account for auth token provided
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1268): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1268): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1268): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1268): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1268): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1268): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1268): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1268): No account for auth token provided
,W/Uploader( 1268): No account for auth token provided
,W/Uploader( 1268): No account for auth token provided
,W/Uploader( 1268): No account for auth token provided
,W/Uploader( 1268):  no longer exists, so no auth token.
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1268): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1268): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1268): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1268): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1268): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1268): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1268): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1268): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3042): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3042): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3042): [1] 5.onFinished: Giving up after 6 failures.
,V/KeepSync( 3822): Connecting to GoogleApiClient
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
,E/ClientConnectionOperation( 1781): 	... 7 more
V/KeepSync( 3822): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3822): IOException
E/KeepSync( 3822): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
,E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3822): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3822): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3822): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3822): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3822): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3822): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259),
E/KeepSync( 3822): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3822): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3822): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3822): 	... 10 more
W/KeepSync( 3822): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 202774, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3632): [386] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova,
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3632): [386] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3632): [386] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3632): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3632): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3632): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): 	at com.google.android.flib.a.a.a(SourceFile:167),
W/ExperimentUpdateService( 3632): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3632): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1242): run()
I/Keyboard.Facilitator( 1242): flushDynamicLanguageModels()
,I/ConfigService( 1268): onCreate
,I/ConfigService( 1268): onDestroy
,I/BooksSync( 3865): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3865): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     (  823): Explicit concurrent mark sweep GC freed 34479(1476KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 3.130ms total 108.263ms
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3480): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3480): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3480): 	at jdm.a(PG:82)
E/HttpOperation( 3480): 	at jcs.o(PG:406)
E/HttpOperation( 3480): 	at jcn.a(PG:1379)
E/HttpOperation( 3480): 	at jcs.i(PG:143)
E/HttpOperation( 3480): 	at blb.a(PG:3937)
E/HttpOperation( 3480): 	at czp.a(PG:18188)
E/HttpOperation( 3480): 	at czp.a(PG:9081)
E/HttpOperation( 3480): 	at czq.run(PG:1686)
E/HttpOperation( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3480): 	at jdj.a(PG:4091)
E/HttpOperation( 3480): 	at jdj.a(PG:1125)
E/HttpOperation( 3480): 	at jdm.a(PG:77)
E/HttpOperation( 3480): 	... 12 more
E/HttpOperation( 3480): Caused by: faj: BadAuthentication
E/HttpOperation( 3480): 	at fal.a(PG:38)
E/HttpOperation( 3480): 	at jdj.a(PG:4089)
E/HttpOperation( 3480): 	... 14 more
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/BooksAccountManager( 3865): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3865): Soft error
E/BooksSync( 3865): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3865): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksSync( 3865): Sync error
E/BooksSync( 3865): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3865): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3865): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 205869, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/HttpOperation( 3480): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3480): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3480): 	at jdm.a(PG:82)
E/HttpOperation( 3480): 	at jcs.o(PG:406)
E/HttpOperation( 3480): 	at jcn.a(PG:1379)
E/HttpOperation( 3480): 	at jcs.i(PG:143)
E/HttpOperation( 3480): 	at hec.a(PG:42)
E/HttpOperation( 3480): 	at hee.a(PG:102)
E/HttpOperation( 3480): 	at czr.a(PG:65)
E/HttpOperation( 3480): 	at kka.a(PG:108)
E/HttpOperation( 3480): 	at czp.a(PG:19176)
E/HttpOperation( 3480): 	at czp.a(PG:9081)
E/HttpOperation( 3480): 	at czq.run(PG:1686)
E/HttpOperation( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3480): 	at jdj.a(PG:4091)
E/HttpOperation( 3480): 	at jdj.a(PG:1125)
E/HttpOperation( 3480): 	at jdm.a(PG:77)
E/HttpOperation( 3480): 	... 15 more
E/HttpOperation( 3480): Caused by: faj: BadAuthentication
E/HttpOperation( 3480): 	at fal.a(PG:38)
E/HttpOperation( 3480): 	at jdj.a(PG:4089)
E/HttpOperation( 3480): 	... 17 more
,E/ExperimentLoader( 3480): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3480): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3480): 	at jdm.a(PG:82)
E/ExperimentLoader( 3480): 	at jcs.o(PG:406)
E/ExperimentLoader( 3480): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3480): 	at jcs.i(PG:143)
E/ExperimentLoader( 3480): 	at hec.a(PG:42)
E/ExperimentLoader( 3480): 	at hee.a(PG:102)
E/ExperimentLoader( 3480): 	at czr.a(PG:65)
E/ExperimentLoader( 3480): 	at kka.a(PG:108)
E/ExperimentLoader( 3480): 	at czp.a(PG:19176)
E/ExperimentLoader( 3480): 	at czp.a(PG:9081)
E/ExperimentLoader( 3480): 	at czq.run(PG:1686)
E/ExperimentLoader( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3480): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3480): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3480): 	at jdm.a(PG:77)
E/ExperimentLoader( 3480): 	... 15 more
E/ExperimentLoader( 3480): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3480): 	at fal.a(PG:38)
E/ExperimentLoader( 3480): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3480): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 206275, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3632): [387] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1268): Explicit concurrent mark sweep GC freed 61384(3MB) AllocSpace objects, 7(698KB) LOS objects, 36% free, 27MB/43MB, paused 1.511ms total 53.048ms
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3632): [387] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3632): [387] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3632): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3632): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3632): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3632): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,I/jxcore-log( 3569): TAP version 13
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # multiplex can send data
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_multiplex can send data
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_multiplex can send data_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 1 String should be length:200
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # enqueue and run in order
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_enqueue and run in order
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_enqueue and run in order_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 2 firstPromise setTimeout
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 3 firstPromise result
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 4 firstPromise testValue
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 5 secondPromise setTimeout
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 6 secondPromise result
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 7 secondPromise testValue
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 8 thirdPromise in promise
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 9 thirdPromise result
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 10 thirdPromise testValue
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # basic
,I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_basic
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_basic_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 11 sane
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # another
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_another
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_another_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 12 sane
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_successfully create a new pkcs12 file and return hash value_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 13 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 14 null
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 15 (unnamed assert)
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 16 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 17 should not throw
I/jxcore-log( 3569): 
I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): ,
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,I/jxcore-log( 3569): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3569): 
I/jxcore-log( 3569): ack: setup_successfully read a previous pkcs12 file and return hash value_ok
I/jxcore-log( 3569): 
I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 18 (unnamed assert)
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 19 (unnamed assert)
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 20 should not throw
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 21 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 22 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_failed to extract public key because of corrupt pkcs12 file_ok
I/jxcore-log( 3569): 
I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 23 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # failed to get mobile documents path
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_failed to get mobile documents path
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_failed to get mobile documents path_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 24 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#init should register the peerAvailabilityChanged event
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#init should register the peerAvailabilityChanged event_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 25 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 26 should be equal
I/jxcore-log( 3569): 
I/jxcore-log( 3569): ok 27 should be equal
I/jxcore-log( 3569): 
I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #init should register the networkChanged event
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#init should register the networkChanged event
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#init should register the networkChanged event_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 28 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #startBroadcasting should throw on null device name
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#startBroadcasting should throw on null device name
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#startBroadcasting should throw on null device name_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 29 should throw
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#startBroadcasting should throw on empty string device name
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#startBroadcasting should throw on empty string device name_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 30 should throw
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#startBroadcasting should throw on non-number port
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#startBroadcasting should throw on non-number port_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 31 should throw
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#startBroadcasting should throw on NaN port
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#startBroadcasting should throw on NaN port_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 32 should throw
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #startBroadcasting should throw on negative port
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#startBroadcasting should throw on negative port
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#startBroadcasting should throw on negative port_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 33 should throw
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #startBroadcasting should throw on too large port
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#startBroadcasting should throw on too large port
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#startBroadcasting should throw on too large port_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 34 should throw
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3569): ,
,I/jxcore-log( 3569): got: setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3569): ,
I/jxcore-log( 3569): ack: setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 35 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 36 should be equal
I/jxcore-log( 3569): 
I/jxcore-log( 3569): ok 37 should be equal
I/jxcore-log( 3569): 
I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 38 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 39 should be equal
I/jxcore-log( 3569): 
I/jxcore-log( 3569): ok 40 should be equal
I/jxcore-log( 3569): 
I/jxcore-log( 3569): # setup
,I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 41 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 42 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 43 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 44 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#connect should call Mobile("Connect") with a port and without an error_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 45 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 46 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 47 should be equal
I/jxcore-log( 3569): 
I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_#connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_#connect should call Mobile("Connect") and handle an error_ok
I/jxcore-log( 3569): 
I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 48 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 49 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_should call Mobile("Disconnect") without an error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_should call Mobile("Disconnect") without an error_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 50 should be equal,
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 51 should be equal,
I/jxcore-log( 3569): ,
I/jxcore-log( 3569): # setup,
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # should call Mobile("Disconnect") and handle an error,
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_should call Mobile("Disconnect") and handle an error,
I/jxcore-log( 3569): 
I/jxcore-log( 3569): ack: setup_should call Mobile("Disconnect") and handle an error_ok
I/jxcore-log( 3569): ,
,I/jxcore-log( 3569): # teardown,
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ok 52 should be equal,
I/jxcore-log( 3569): 
I/jxcore-log( 3569): ok 53 should be equal
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): got: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): ack: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error_ok
I/jxcore-log( 3569): 
,I/jxcore-log( 3569): # teardown
I/jxcore-log( 3569): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): ,	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@110f9da9 added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423043.3569
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423043.3569","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423043.3569, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): bind: Binding a new listener
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3569): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423043.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423043.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423043.3569","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423043.3569, mode: WIFI
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3569): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3569): 
I/io.jxcore.node.ConnectionHelper( 3569): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: NOT_STARTED
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3569): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: NOT_INITIALIZED
I/wpa_supplicant( 1155): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3569): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3569): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3569): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 3569): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d03b03a added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423146.3569
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423146.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: OK
,I/io.jxcore.node.ConnectionHelper( 3569): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3569): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423146.3569, mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3569): createAdvertiseData: From: 1454597423146.3569 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2406): registerClient() - UUID=4ac10e4d-616d-4b16-b94d-f16404565c77
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=4ac10e4d-616d-4b16-b94d-f16404565c77, clientIf=5
D/BluetoothLeScanner( 3569): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2406): start scan with filters
,D/BtGatt.ScanManager( 2406): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setState: State changed from NOT_STARTED to STARTING
,D/BluetoothAdapterService( 2406): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34134dad
,D/BtGatt.GattService( 2406): registerClient() - UUID=e1191561-f7ea-4e73-b529-b4c01e4a043d
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=e1191561-f7ea-4e73-b529-b4c01e4a043d, clientIf=6
,D/BluetoothLeAdvertiser( 3569): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2406): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
,D/BtGatt.AdvertiseManager( 2406): message : 0
,D/BtGatt.GattService( 2406): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.AdvertiseManager( 2406): starting multi advertising
,D/BtGatt.GattService( 2406): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2406): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423146.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423146.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423146.3569","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 1155): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423146.3569, mode: BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3569): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3569): createAdvertiseData: From: 1454597423146.3569 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/jxcore-log( 3569): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 3569): 
,D/BtGatt.AdvertiseManager( 2406): message : 1
,I/io.jxcore.node.ConnectionHelper( 3569): stop
D/BtGatt.AdvertiseManager( 2406): stop advertise for client 6
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): Shutting down...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): onServerStopped
D/BtGatt.GattService( 2406): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2406): Client app is not null!
D/BtGatt.GattService( 2406): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): stop: Stopped,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2406): registerClient() - UUID=93591dca-3729-4ba9-9d6b-49772f4422ec
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=93591dca-3729-4ba9-9d6b-49772f4422ec, clientIf=6
D/BluetoothLeAdvertiser( 3569): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2406): message : 0
,D/BtGatt.AdvertiseManager( 2406): starting multi advertising
,D/BtGatt.GattService( 2406): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2406): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3569): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local service added successfully
I/wpa_supplicant( 1155): P2P-FIND-STOPPED 
,I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: NOT_STARTED,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): onStartSuccess
D/BtGatt.AdvertiseManager( 2406): message : 1
,D/BtGatt.AdvertiseManager( 2406): stop advertise for client 6,
D/BtGatt.GattService( 2406): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2406): Client app is not null!
D/BtGatt.GattService( 2406): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: true
,D/BtGatt.GattService( 2406): stopScan() - queue size =1,
,D/BtGatt.GattService( 2406): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2406): stop scan
,D/BtGatt.GattService( 2406): unregisterClient() - clientIf=5
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): stop: Stopped
,D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue emtpy, scan stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: false,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3569): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3569): Service requests cleared successfully
I/jxcore-log( 3569): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 3569): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Connection timeout in milliseconds: 15000, 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	,Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): ,	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise TX power level: 1, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be4a21d added. We now have 4 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): setDiscoveryMode: BLE_AND_WIFI -> WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423470.3569
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423470.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3569): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423470.3569, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Waiting for incoming connections...
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423470.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423470.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423470.3569","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423470.3569, mode: WIFI
I/wpa_supplicant( 1155): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3569): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 3569): 
,I/io.jxcore.node.ConnectionHelper( 3569): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): onServerStopped
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3569): stopProvideBluetoothMacAddressMode
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): stop: Stopping P2P device discovery...
I/wpa_supplicant( 1155): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3569): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3569): Service requests cleared successfully
I/jxcore-log( 3569): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 3569): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	,Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fae4319 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI,
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423551.3569
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423551.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3569): getBluetoothService() called with no BluetoothManagerCallback,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423551.3569, mode: BLE_AND_WIFI,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3569): createAdvertiseData: From: 1454597423551.3569 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2406): registerClient() - UUID=73e465d0-1692-48fb-bfcb-1af3487cbe08
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=73e465d0-1692-48fb-bfcb-1af3487cbe08, clientIf=5
D/BluetoothLeScanner( 3569): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2406): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setState: State changed from NOT_STARTED to STARTING
D/BtGatt.ScanManager( 2406): handling starting scan
,D/BtGatt.GattService( 2406): registerClient() - UUID=17b16955-c445-4b22-9965-372888b6c7a2
,D/BtGatt.GattService( 2406): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2406): onClientRegistered() - UUID=17b16955-c445-4b22-9965-372888b6c7a2, clientIf=6
D/BluetoothLeAdvertiser( 3569): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2406): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
D/BtGatt.AdvertiseManager( 2406): message : 0
,D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.AdvertiseManager( 2406): starting multi advertising
,D/BtGatt.GattService( 2406): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2406): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423551.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423551.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423551.3569","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
,I/io.jxcore.node.ConnectionHelper( 3569): start: OK
I/wpa_supplicant( 1155): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423551.3569, mode: BLE_AND_WIFI
I/jxcore-log( 3569): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 3569): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3569): createAdvertiseData: From: 1454597423551.3569 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3569): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): Shutting down...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): onServerStopped
D/BtGatt.AdvertiseManager( 2406): message : 1
,D/BtGatt.AdvertiseManager( 2406): stop advertise for client 6
D/BtGatt.GattService( 2406): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2406): Client app is not null!
D/BtGatt.GattService( 2406): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2406): registerClient() - UUID=f7a59f2d-b3e3-4b18-ad61-c849e5f3c319
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=f7a59f2d-b3e3-4b18-ad61-c849e5f3c319, clientIf=6
D/BluetoothLeAdvertiser( 3569): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2406): message : 0
,D/BtGatt.AdvertiseManager( 2406): starting multi advertising
,D/BtGatt.GattService( 2406): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2406): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3569): stopProvideBluetoothMacAddressMode
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): onStartSuccess
I/wpa_supplicant( 1155): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 2406): message : 1
,D/BtGatt.AdvertiseManager( 2406): stop advertise for client 6
D/BtGatt.GattService( 2406): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2406): Client app is not null!
D/BtGatt.GattService( 2406): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [SCANNING]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: true
,D/BtGatt.GattService( 2406): stopScan() - queue size =1,
,D/BtGatt.GattService( 2406): unregisterClient() - clientIf=5
D/BtGatt.GattService( 2406): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsScannerStartedChanged: false
D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
,D/BtGatt.ScanManager( 2406): stop scan
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
,D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopBlePeerDiscoverer: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3569): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3569): Service requests cleared successfully
I/jxcore-log( 3569): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 3569): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Connection timeout in milliseconds: 15000, 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	,Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): ,	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe7dedb added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): setDiscoveryMode: BLE_AND_WIFI -> WIFI,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423782.3569
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423782.3569","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423782.3569, mode: WIFI
W/BluetoothAdapter( 3569): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Waiting for incoming connections...
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423782.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423782.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423782.3569","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423782.3569, mode: WIFI
I/wpa_supplicant( 1155): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 3569): start: OK
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1155): P2P-FIND-STOPPED 
I/jxcore-log( 3569): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 3569): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3569): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3569): stopProvideBluetoothMacAddressMode,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3569): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
,I/jxcore-log( 3569): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 3569): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3569): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f7b8db7 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423863.3569,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423863.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423863.3569, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
W/BluetoothAdapter( 3569): getBluetoothService() called with no BluetoothManagerCallback
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3569): createAdvertiseData: From: 1454597423863.3569 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2406): registerClient() - UUID=ebfab509-adf6-44fd-9359-2fb1524fd0d1
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=ebfab509-adf6-44fd-9359-2fb1524fd0d1, clientIf=5
D/BluetoothLeScanner( 3569): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2406): start scan with filters
,D/BtGatt.ScanManager( 2406): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setState: State changed from NOT_STARTED to STARTING
,D/BtGatt.GattService( 2406): registerClient() - UUID=b61d70b1-9a5d-4775-bb6f-2217412f005a
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=b61d70b1-9a5d-4775-bb6f-2217412f005a, clientIf=6
,D/BluetoothLeAdvertiser( 3569): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2406): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2406): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.AdvertiseManager( 2406): message : 0
,D/BtGatt.AdvertiseManager( 2406): starting multi advertising
,D/BtGatt.GattService( 2406): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2406): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423863.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423863.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454597423863.3569","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597423863.3569, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3569): createAdvertiseData: From: 1454597423863.3569 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/wpa_supplicant( 1155): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3569): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 3569): 
D/BtGatt.AdvertiseManager( 2406): message : 1
I/io.jxcore.node.ConnectionHelper( 3569): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): shutdown
D/BtGatt.AdvertiseManager( 2406): stop advertise for client 6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): onServerStopped
D/BtGatt.GattService( 2406): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2406): Client app is not null!
,D/BtGatt.GattService( 2406): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2406): registerClient() - UUID=e83ed417-76c8-4f16-9f83-02cbba4cd15c
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=e83ed417-76c8-4f16-9f83-02cbba4cd15c, clientIf=6
D/BluetoothLeAdvertiser( 3569): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2406): message : 0
,D/BtGatt.AdvertiseManager( 2406): starting multi advertising
,D/BtGatt.GattService( 2406): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2406): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): start: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): onStartSuccess
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3569): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: STARTED
I/wpa_supplicant( 1155): P2P-FIND-STOPPED 
,D/BtGatt.AdvertiseManager( 2406): message : 1
D/BtGatt.AdvertiseManager( 2406): stop advertise for client 6
,D/BtGatt.GattService( 2406): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2406): Client app is not null!
,D/BtGatt.GattService( 2406): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from RUNNING to NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [SCANNING]
,D/BtGatt.GattService( 2406): stopScan() - queue size =1
,D/BtGatt.GattService( 2406): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
D/BtGatt.GattService( 2406): unregisterClient() - clientIf=5
D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setState: State changed from STARTING to NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [SCANNING] to [NOT_STARTED]
D/BtGatt.ScanManager( 2406): stop scan
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [NOT_STARTED]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [NOT_STARTED] to [ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): release: No more listeners, de-initializing...
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue=0,
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3569): clear,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3569): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 3569): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Insecure RFCOMM socket port number: -1, ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Scan mode: 1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb92489 added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): setDiscoveryMode: BLE_AND_WIFI -> WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3569): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597424053.3569
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424053.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3569): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Waiting for incoming connections...,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597424053.3569, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424053.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424053.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424053.3569","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597424053.3569, mode: WIFI
I/wpa_supplicant( 1155): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/jxcore-log( 3569): ok 66 Should be able to call startBroadcasting without error,
I/jxcore-log( 3569): 
I/io.jxcore.node.ConnectionHelper( 3569): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3569): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: RUNNING_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery started successfully
I/wpa_supplicant( 1155): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3569): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
I/jxcore-log( 3569): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3569): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1068045 added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3569): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597424146.3569
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424146.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597424146.3569, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): bind: Binding a new listener
W/BluetoothAdapter( 3569): getBluetoothService() called with no BluetoothManagerCallback,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Waiting for incoming connections...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3569): createAdvertiseData: From: 1454597424146.3569 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2406): registerClient() - UUID=5da2201b-2e26-4240-965c-4a539db91014
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=5da2201b-2e26-4240-965c-4a539db91014, clientIf=5
D/BluetoothLeScanner( 3569): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2406): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setState: State changed from NOT_STARTED to STARTING
,D/BtGatt.ScanManager( 2406): handling starting scan
,D/BtGatt.GattService( 2406): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2406): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue=1,
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/BtGatt.GattService( 2406): registerClient() - UUID=2b1da322-5fc7-488c-8952-5648ed733ab4
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=2b1da322-5fc7-488c-8952-5648ed733ab4, clientIf=6
D/BluetoothLeAdvertiser( 3569): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2406): message : 0
,D/BtGatt.AdvertiseManager( 2406): starting multi advertising
,D/BtGatt.GattService( 2406): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2406): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424146.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424146.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424146.3569","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
,I/io.jxcore.node.ConnectionHelper( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597424146.3569, mode: BLE_AND_WIFI
I/wpa_supplicant( 1155): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): start
I/jxcore-log( 3569): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3569): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3569): createAdvertiseData: From: 1454597424146.3569 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/io.jxcore.node.ConnectionHelper( 3569): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: NOT_STARTED
D/BtGatt.AdvertiseManager( 2406): message : 1
D/BtGatt.AdvertiseManager( 2406): stop advertise for client 6
D/BtGatt.GattService( 2406): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2406): Client app is not null!
D/BtGatt.GattService( 2406): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2406): registerClient() - UUID=7c4d3176-3d02-44c3-97a5-116cfbe573f0
D/BtGatt.GattService( 2406): onClientRegistered() - UUID=7c4d3176-3d02-44c3-97a5-116cfbe573f0, clientIf=6
,D/BluetoothLeAdvertiser( 3569): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2406): message : 0
,D/BtGatt.AdvertiseManager( 2406): starting multi advertising
,D/BtGatt.GattService( 2406): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2406): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopForRestart
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3569): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): onStartSuccess
I/wpa_supplicant( 1155): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 2406): message : 1
D/BtGatt.AdvertiseManager( 2406): stop advertise for client 6
,D/BtGatt.GattService( 2406): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2406): Client app is not null!
,D/BtGatt.GattService( 2406): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from RUNNING to NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [SCANNING]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: true
,D/BtGatt.GattService( 2406): stopScan() - queue size =1
,D/BtGatt.GattService( 2406): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setState: State changed from STARTING to NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [SCANNING] to [ADVERTISING_SELF]
D/BtGatt.GattService( 2406): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
D/BtGatt.ScanManager( 2406): stop scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopBlePeerDiscoverer: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3569): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
I/jxcore-log( 3569): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 3569): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@115552a7 added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): setDiscoveryMode: BLE_AND_WIFI -> WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3569): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to WIFI
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597424415.3569
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424415.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3569): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Waiting for incoming connections...,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597424415.3569, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424415.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424415.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424415.3569","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597424415.3569, mode: WIFI
,I/wpa_supplicant( 1155): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local service added successfully
I/jxcore-log( 3569): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 3569): 
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1155): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 3569): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3569): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): stop: Stopping P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3569): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3569): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3569): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 3569): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3569): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fa7243 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3569): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597424534.3569
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): initialize: My bluetooth address is F8:CF:C5:D9:E5:61,
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424534.3569","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): setConnectionTimeout: 15000,
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): start: OK
I/io.jxcore.node.ConnectionHelper( 3569): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3569): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597424534.3569, mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3569): createAdvertiseData: From: 1454597424534.3569 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2406): registerClient() - UUID=836f63a9-2875-4578-a98b-3e628ab91439
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=836f63a9-2875-4578-a98b-3e628ab91439, clientIf=5
,D/BluetoothLeScanner( 3569): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2406): start scan with filters
,D/BtGatt.ScanManager( 2406): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setState: State changed from NOT_STARTED to STARTING
,D/BtGatt.GattService( 2406): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2406): registerClient() - UUID=8c070c64-7c6c-4962-a53d-83cd7e68ce15
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=8c070c64-7c6c-4962-a53d-83cd7e68ce15, clientIf=6
D/BluetoothLeAdvertiser( 3569): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2406): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/BtGatt.AdvertiseManager( 2406): message : 0
,D/BtGatt.AdvertiseManager( 2406): starting multi advertising,
,D/BtGatt.GattService( 2406): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2406): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3569): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424534.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424534.3569","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454597424534.3569","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454597424534.3569, mode: BLE_AND_WIFI,
I/io.jxcore.node.ConnectionHelper( 3569): start: OK
I/jxcore-log( 3569): ok 72 Should be able to call startBroadcasting without error
,I/jxcore-log( 3569): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3569): createAdvertiseData: From: 1454597424534.3569 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/io.jxcore.node.ConnectionHelper( 3569): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3569): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3569): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3569): onServerStopped
,D/BtGatt.AdvertiseManager( 2406): message : 1
D/BtGatt.AdvertiseManager( 2406): stop advertise for client 6
D/BtGatt.GattService( 2406): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2406): Client app is not null!
,D/BtGatt.GattService( 2406): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2406): registerClient() - UUID=ce6923af-f15e-4b9d-b884-ce538088bf98
,D/BtGatt.GattService( 2406): onClientRegistered() - UUID=ce6923af-f15e-4b9d-b884-ce538088bf98, clientIf=6
D/BluetoothLeAdvertiser( 3569): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2406): message : 0
D/BtGatt.AdvertiseManager( 2406): starting multi advertising,
,D/BtGatt.GattService( 2406): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2406): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): start: Already running
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): start: Already running, call stopListening() first to restart,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [NOT_STARTED] to [SCANNING, ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3569): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): stop
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3569): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant( 1155): P2P-FIND-STOPPED ,
D/BtGatt.AdvertiseManager( 2406): message : 1
D/BtGatt.AdvertiseManager( 2406): stop advertise for client 6
,D/BtGatt.GattService( 2406): onAdvertiseInstanceDisabled() - clientIf=6, status=0,
D/BtGatt.GattService( 2406): Client app is not null!
D/BtGatt.GattService( 2406): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from RUNNING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [SCANNING, ADVERTISING_SELF] to [SCANNING]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [SCANNING]
,D/BtGatt.GattService( 2406): stopScan() - queue size =1
D/BtGatt.GattService( 2406): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3569): setState: State changed from STARTING to NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsScannerStartedChanged: false
D/BtGatt.GattService( 2406): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [SCANNING] to [NOT_STARTED]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [NOT_STARTED]
D/BtGatt.ScanManager( 2406): callback done for clientIf - 5 status - 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3569): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3569): setState: State changed from NOT_STARTED to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): onIsAdvertiserStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3569): updateState(): State changed from [NOT_STARTED] to [ADVERTISING_SELF]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsBlePeerDiscovererStateChanged: [ADVERTISING_SELF]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
D/BtGatt.ScanManager( 2406): stop scan
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): stop: Stopping P2P device discovery...
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2406): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3569): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3569): Local services cleared successfully,
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3569): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3569): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3569): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3569): Service requests cleared successfully
I/jxcore-log( 3569): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3569): 
I/jxcore-log( 3569): # setup
I/jxcore-log( 3569): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3569): start: Cannot start, because not initialized
,D/btif_config_util( 2406): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/KeepSync( 3822): Connecting to GoogleApiClient
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1781): Handling authorization failure,
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
,E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
,E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	,at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	,at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): ,	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	,at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340),
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781),: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more,
V/KeepSync( 3822): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3822): IOException
E/KeepSync( 3822): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3822): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3822): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3822): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3822): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3822): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3822): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3822): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3822): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3822): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3822): 	... 10 more
W/KeepSync( 3822): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 328511, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3d1eed26}
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3d1eed26}
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1268): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1268): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1268): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1268): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1268): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1268): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1268): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3042): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3042): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3042): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3042): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3042): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3042): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3042): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3042): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,I/BooksSync( 3865): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3865): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 39569(1966KB) AllocSpace objects, 13(679KB) LOS objects, 31% free, 34MB/50MB, paused 3.231ms total 191.893ms
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3865): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3865): Soft error
E/BooksSync( 3865): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3865): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3865): Sync error
E/BooksSync( 3865): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3865): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3865): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 363735, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3480): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3480): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3480): 	at jdm.a(PG:82)
E/HttpOperation( 3480): 	at jcs.o(PG:406)
E/HttpOperation( 3480): 	at jcn.a(PG:1379)
E/HttpOperation( 3480): 	at jcs.i(PG:143)
E/HttpOperation( 3480): 	at blb.a(PG:3937)
E/HttpOperation( 3480): ,	at czp.a(PG:18188)
E/HttpOperation( 3480): 	at czp.a(PG:9081)
E/HttpOperation( 3480): 	at czq.run(PG:1686)
E/HttpOperation( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3480): 	at java.lang.Thread.run(Thread.java:818)
,E/HttpOperation( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3480): 	at jdj.a(PG:4091)
E/HttpOperation( 3480): 	at jdj.a(PG:1125)
E/HttpOperation( 3480): 	at jdm.a(PG:77)
E/HttpOperation( 3480): 	... 12 more
E/HttpOperation( 3480): Caused by: faj: BadAuthentication
E/HttpOperation( 3480): 	at fal.a(PG:38)
E/HttpOperation( 3480): 	at jdj.a(PG:4089)
E/HttpOperation( 3480): ,	... 14 more
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3480): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3480): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3480): 	at jdm.a(PG:82),
E/HttpOperation( 3480): 	at jcs.o(PG:406)
E/HttpOperation( 3480): 	at jcn.a(PG:1379)
E/HttpOperation( 3480): 	at jcs.i(PG:143)
E/HttpOperation( 3480): 	at hec.a(PG:42)
E/HttpOperation( 3480): 	at hee.a(PG:102)
E/HttpOperation( 3480): 	at czr.a(PG:65)
E/HttpOperation( 3480): 	at kka.a(PG:108)
E/HttpOperation( 3480): 	at czp.a(PG:19176)
E/HttpOperation( 3480): 	at czp.a(PG:9081)
E/HttpOperation( 3480): 	at czq.run(PG:1686),
E/HttpOperation( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3480): 	at java.lang.Thread.run(Thread.java:818),
E/HttpOperation( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3480): 	at jdj.a(PG:4091)
E/HttpOperation( 3480): 	at jdj.a(PG:1125)
E/HttpOperation( 3480): 	at jdm.a(PG:77)
E/HttpOperation( 3480): 	,... 15 more
E/HttpOperation( 3480): Caused by: faj: BadAuthentication
E/HttpOperation( 3480): 	at fal.a(PG:38)
E/HttpOperation( 3480): ,	at jdj.a(PG:4089)
E/HttpOperation( 3480): 	... 17 more
E/ExperimentLoader( 3480): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3480): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3480): 	at jdm.a(PG:82)
E/ExperimentLoader( 3480): 	at jcs.o(PG:406)
E/ExperimentLoader( 3480): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3480): 	at jcs.i(PG:143)
E/ExperimentLoader( 3480): 	at hec.a(PG:42)
E/ExperimentLoader( 3480): 	at hee.a(PG:102)
E/ExperimentLoader( 3480): 	at czr.a(PG:65)
E/ExperimentLoader( 3480): 	at kka.a(PG:108)
E/ExperimentLoader( 3480): 	at czp.a(PG:19176)
E/ExperimentLoader( 3480): 	at czp.a(PG:9081)
E/ExperimentLoader( 3480): 	at czq.run(PG:1686)
E/ExperimentLoader( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/ExperimentLoader( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3480): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3480): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3480): 	at jdm.a(PG:77)
E/ExperimentLoader( 3480): 	... 15 more
E/ExperimentLoader( 3480): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3480): 	at fal.a(PG:38)
E/ExperimentLoader( 3480): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3480): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 365296, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3632): [388] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3632): [388] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3632): [388] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3632): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3632): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3632): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3632): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,V/KeepSync( 3822): Connecting to GoogleApiClient
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3822): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3822): IOException
E/KeepSync( 3822): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3822): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3822): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3822): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3822): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3822): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3822): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3822): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3822): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3822): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3822): 	... 10 more
W/KeepSync( 3822): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 579209, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,I/BooksSync( 3865): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3865): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3865): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3865): Soft error
E/BooksSync( 3865): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3865): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3865): Sync error
E/BooksSync( 3865): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3865): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3865): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 649989, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,I/art     ( 1268): Explicit concurrent mark sweep GC freed 56254(2MB) AllocSpace objects, 15(1653KB) LOS objects, 36% free, 27MB/43MB, paused 2.278ms total 72.681ms
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3480): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3480): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3480): 	at jdm.a(PG:82)
E/HttpOperation( 3480): 	at jcs.o(PG:406)
E/HttpOperation( 3480): 	at jcn.a(PG:1379)
E/HttpOperation( 3480): 	at jcs.i(PG:143)
E/HttpOperation( 3480): 	at blb.a(PG:3937)
E/HttpOperation( 3480): 	at czp.a(PG:18188)
E/HttpOperation( 3480): 	at czp.a(PG:9081)
E/HttpOperation( 3480): 	at czq.run(PG:1686)
E/HttpOperation( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3480): 	at jdj.a(PG:4091)
E/HttpOperation( 3480): 	at jdj.a(PG:1125)
E/HttpOperation( 3480): 	at jdm.a(PG:77)
E/HttpOperation( 3480): 	... 12 more
E/HttpOperation( 3480): Caused by: faj: BadAuthentication
E/HttpOperation( 3480): 	at fal.a(PG:38)
E/HttpOperation( 3480): 	at jdj.a(PG:4089)
E/HttpOperation( 3480): 	... 14 more
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3480): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3480): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3480): 	at jdm.a(PG:82)
E/HttpOperation( 3480): 	at jcs.o(PG:406)
E/HttpOperation( 3480): 	at jcn.a(PG:1379)
E/HttpOperation( 3480): 	at jcs.i(PG:143)
E/HttpOperation( 3480): 	at hec.a(PG:42)
E/HttpOperation( 3480): 	at hee.a(PG:102)
E/HttpOperation( 3480): 	at czr.a(PG:65)
E/HttpOperation( 3480): 	at kka.a(PG:108)
E/HttpOperation( 3480): 	at czp.a(PG:19176)
E/HttpOperation( 3480): 	at czp.a(PG:9081)
E/HttpOperation( 3480): 	at czq.run(PG:1686)
E/HttpOperation( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3480): 	at jdj.a(PG:4091)
E/HttpOperation( 3480): 	at jdj.a(PG:1125)
E/HttpOperation( 3480): 	at jdm.a(PG:77)
E/HttpOperation( 3480): 	... 15 more
E/HttpOperation( 3480): Caused by: faj: BadAuthentication
E/HttpOperation( 3480): 	at fal.a(PG:38)
E/HttpOperation( 3480): 	at jdj.a(PG:4089)
E/HttpOperation( 3480): 	... 17 more
E/ExperimentLoader( 3480): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3480): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3480): 	at jdm.a(PG:82)
E/ExperimentLoader( 3480): 	at jcs.o(PG:406)
E/ExperimentLoader( 3480): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3480): 	at jcs.i(PG:143)
E/ExperimentLoader( 3480): 	at hec.a(PG:42)
E/ExperimentLoader( 3480): 	at hee.a(PG:102)
E/ExperimentLoader( 3480): 	at czr.a(PG:65)
E/ExperimentLoader( 3480): 	at kka.a(PG:108)
E/ExperimentLoader( 3480): 	at czp.a(PG:19176)
E/ExperimentLoader( 3480): 	at czp.a(PG:9081)
E/ExperimentLoader( 3480): 	at czq.run(PG:1686)
E/ExperimentLoader( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3480): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3480): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3480): 	at jdm.a(PG:77)
E/ExperimentLoader( 3480): 	... 15 more
E/ExperimentLoader( 3480): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3480): 	at fal.a(PG:38)
E/ExperimentLoader( 3480): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3480): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 653201, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3632): [389] a.<init>: mAccountName set to: thalitester@gmail.com
,I/EventLogService( 1781): Opted in for usage reporting
I/EventLogService( 1781): Aggregate from 1454596076650 (log), 1454596076650 (data)
,I/art     (  823): Explicit concurrent mark sweep GC freed 45094(2037KB) AllocSpace objects, 10(442KB) LOS objects, 31% free, 34MB/50MB, paused 1.649ms total 92.456ms
,W/EventLogAggregator( 1781): Unknown tag: snet_gcore
W/EventLogAggregator( 1781): Unknown tag: snet_launch_service
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3632): [389] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3632): [389] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3632): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3632): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3632): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3632): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3632): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3632): 	at com.a.a.k.run(SourceFile:110)
,I/ServiceDumpSys( 1781): dumping service [account]
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,I/ActivityManager(  823): Start proc 4145:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4145): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4145):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4145):   adb logcat -s GAv4
,W/GAv4    ( 4145): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4145): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4145): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  823): Killing 2315:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/GCM     ( 1268): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,V/KeepSync( 3822): Connecting to GoogleApiClient
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3822): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3822): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3822): IOException
E/KeepSync( 3822): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3822): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3822): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3822): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3822): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3822): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3822): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3822): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3822): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3822): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3822): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3822): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3822): 	... 10 more
W/KeepSync( 3822): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1079794, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,I/BooksSync( 3865): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3865): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3865): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3865): Soft error
E/BooksSync( 3865): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3865): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3865): Sync error
E/BooksSync( 3865): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3865): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3865): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1172261, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2406): Stopping oneshot timer
,I/UsageStatsService(  823): User[0] Flushing usage stats to disk,
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3480): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3480): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3480): 	at jdm.a(PG:82)
E/HttpOperation( 3480): 	at jcs.o(PG:406)
E/HttpOperation( 3480): 	at jcn.a(PG:1379)
E/HttpOperation( 3480): 	at jcs.i(PG:143)
E/HttpOperation( 3480): 	at blb.a(PG:3937)
E/HttpOperation( 3480): 	at czp.a(PG:18188)
E/HttpOperation( 3480): 	at czp.a(PG:9081)
E/HttpOperation( 3480): 	at czq.run(PG:1686)
E/HttpOperation( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3480): 	at jdj.a(PG:4091)
E/HttpOperation( 3480): 	at jdj.a(PG:1125)
E/HttpOperation( 3480): 	at jdm.a(PG:77)
E/HttpOperation( 3480): 	... 12 more
E/HttpOperation( 3480): Caused by: faj: BadAuthentication
E/HttpOperation( 3480): 	at fal.a(PG:38)
E/HttpOperation( 3480): 	at jdj.a(PG:4089)
E/HttpOperation( 3480): 	... 14 more
,I/GLSUser ( 1268): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1268): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1268): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1268): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1268): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3480): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3480): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3480): 	at jdm.a(PG:82)
E/HttpOperation( 3480): 	at jcs.o(PG:406)
E/HttpOperation( 3480): 	at jcn.a(PG:1379)
E/HttpOperation( 3480): 	at jcs.i(PG:143)
E/HttpOperation( 3480): 	at hec.a(PG:42)
E/HttpOperation( 3480): 	at hee.a(PG:102)
E/HttpOperation( 3480): 	at czr.a(PG:65)
E/HttpOperation( 3480): 	at kka.a(PG:108)
E/HttpOperation( 3480): 	at czp.a(PG:19176)
E/HttpOperation( 3480): 	at czp.a(PG:9081)
E/HttpOperation( 3480): 	at czq.run(PG:1686)
E/HttpOperation( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3480): 	at jdj.a(PG:4091)
E/HttpOperation( 3480): 	at jdj.a(PG:1125)
E/HttpOperation( 3480): 	at jdm.a(PG:77)
E/HttpOperation( 3480): 	... 15 more
E/HttpOperation( 3480): Caused by: faj: BadAuthentication
E/HttpOperation( 3480): 	at fal.a(PG:38)
E/HttpOperation( 3480): 	at jdj.a(PG:4089)
E/HttpOperation( 3480): 	... 17 more
,E/ExperimentLoader( 3480): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3480): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3480): 	at jdm.a(PG:82)
E/ExperimentLoader( 3480): 	at jcs.o(PG:406)
E/ExperimentLoader( 3480): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3480): 	at jcs.i(PG:143)
E/ExperimentLoader( 3480): 	at hec.a(PG:42)
E/ExperimentLoader( 3480): 	,at hee.a(PG:102)
E/ExperimentLoader( 3480): 	at czr.a(PG:65)
E/ExperimentLoader( 3480): 	at kka.a(PG:108)
E/ExperimentLoader( 3480): 	at czp.a(PG:19176)
E/ExperimentLoader( 3480): 	at czp.a(PG:9081)
E/ExperimentLoader( 3480): 	at czq.run(PG:1686)
E/ExperimentLoader( 3480): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3480): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3480): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3480): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3480): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3480): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3480): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3480): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3480): 	at jdm.a(PG:77)
E/ExperimentLoader( 3480): 	... 15 more
E/ExperimentLoader( 3480): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3480): 	at fal.a(PG:38)
E/ExperimentLoader( 3480): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3480): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1208232, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1268): Explicit concurrent mark sweep GC freed 65155(3MB) AllocSpace objects, 13(1434KB) LOS objects, 37% free, 27MB/43MB, paused 1.255ms total 46.764ms
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2406): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4236): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4236): CheckJNI is OFF
D/AndroidRuntime( 4236): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  823): Killing 3569:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  823): Skipping PackageSetting{2609b380 com.example.hello/10273} due to missing metadata
D/WifiService(  823): Client connection lost with reason: 4
I/WindowState(  823): WIN DEATH: Window{3071f710 u0 com.test.thalitest/com.test.thalitest.MainActivity}
E/libprocessgroup(  823): failed to kill 1 processes for processgroup 3569
W/ActivityManager(  823): Force removing ActivityRecord{131e0157 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
V/ActivityManager(  823): Display changed displayId=0
I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
W/ActivityManager(  823): Spurious death for ProcessRecord{cef4bd3 3569:com.test.thalitest/u0a265}, curProc for 3569: null
D/TaskPersister(  823): removeObsoleteFile: deleting file=28_task.xml
I/Keyboard.Facilitator( 1242): resetDictionaries() : en_US
I/InputReader(  823): Reconfiguring input devices.  changes=0x00000010
D/BuaReceiver( 3353): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/art     ( 1075): Explicit concurrent mark sweep GC freed 73003(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 1.369ms total 49.060ms
I/Keyboard.Facilitator.DecoderInitializer( 1242): run()
I/art     ( 1532): Explicit concurrent mark sweep GC freed 3178(305KB) AllocSpace objects, 1(24KB) LOS objects, 22% free, 27MB/35MB, paused 9.790ms total 71.501ms
I/Decoder ( 1242): createOrResetDecoder
I/ActivityManager(  823): Start proc 4252:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
W/InputMethodManagerService(  823): Got RemoteException sending setActive(false) notification to pid 3569 uid 10265
I/Keyboard.Facilitator( 1242): onFinishInput()
I/art     (  823): Explicit concurrent mark sweep GC freed 46720(2MB) AllocSpace objects, 15(522KB) LOS objects, 31% free, 34MB/50MB, paused 2.268ms total 104.325ms
I/ConfigService( 1268): onCreate
I/art     (  823): WaitForGcToComplete blocked for 40.257ms for cause Explicit
I/art     ( 1385): Explicit concurrent mark sweep GC freed 4988(364KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 880us total 22.504ms
W/LocationOracleImpl( 1532): Best location was null
I/Keyboard.Facilitator.MainLanguageModelLoader( 1242): run()
I/HotwordRecognitionRnr( 1532): Starting hotword detection.
I/MicrophoneInputStream( 1532): mic_starting com.google.android.apps.gsa.speech.audio.u@21438857
I/AudioFlinger(  358): AudioFlinger's thread 0xb4cd4000 ready to run
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1532): mic_started com.google.android.apps.gsa.speech.audio.u@21438857
D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
D/JobSchedulerService(  823): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  823): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
I/Keyboard.Facilitator.MainLanguageModelLoader( 1242): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1242): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1242): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1242): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1242): run()
I/StatsUtilsManager( 1242): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1242): shouldRecordStats() = Too Soon
D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@295d4773}
E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=62.00 rxSuccessRate=71.50 targetRoamBSSID=any RSSI=-51
D/VoicemailCleanupService( 4252): Cleaning up data for package: com.test.thalitest
I/art     (  823): Explicit concurrent mark sweep GC freed 8513(401KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 1.842ms total 141.647ms
I/HotwordWorker( 1532): onReady
I/ActivityManager(  823): Start proc 4295:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=87.50 rxSuccessRate=193.25 targetRoamBSSID=any RSSI=-51
I/ContactLocale( 4252): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1701111059
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/DataBuffer( 1808): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1497101f)
I/art     ( 1808): Explicit concurrent mark sweep GC freed 16983(989KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 927us total 25.541ms
I/ActivityManager(  823): Start proc 4313:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
W/ContextImpl( 4313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
I/art     ( 4236): System.exit called, status: 0
I/AndroidRuntime( 4236): VM exiting with result code 0.
E/NetworkScheduler.SchedulerReceiver( 1268): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1268): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/kickstart(  878): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  878): STATUS: Wrote to /sys/power/wake_lock
I/ActivityManager(  823): Killing 3414:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
E/kickstart(  878): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  878): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1781): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1781): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1781): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1781): Module APK com.google.android.play.games already loaded
D/Launcher.Workspace( 1385): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1385): 11683562 - stripEmptyScreens()
I/UpdateIcingCorporaServi( 1532): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/LocationSettingsChecker( 1781): Removing dialog suppression flag for package com.test.thalitest
W/Launcher( 1385): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@ff774cf new=com.google.android.velvet.VelvetApplication@ff774cf
D/GOOGLEHELP_CompatibleDatabase( 1781): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1781): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1781): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1781): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/FileUtils( 1781): Failed to chmod(/data/data/com.google.android.gms/databases/help_responses.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
D/GOOGLEHELP_CompatibleDatabase( 1781): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1781): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
E/SQLiteLog( 1781): (3850) statement aborts at 21: [DELETE FROM help_responses WHERE app_package_name="com.test.thalitest"] disk I/O error
D/GOOGLEHELP_CompatibleDatabase( 1781): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
--------- beginning of crash
E/AndroidRuntime( 1781): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1781): Process: com.google.android.gms, PID: 1781
E/AndroidRuntime( 1781): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1781): 	at com.google.android.gms.googlehelp.c.b.d(SourceFile:535)
E/AndroidRuntime( 1781): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
E/AndroidRuntime( 1781): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1781): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1781): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  823): Start proc 4345:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/SQLiteDatabase( 1781): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1781): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1781): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1781): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1781): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1781): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1781): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1781): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1781): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1781): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1781): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1781): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1781): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1781): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1781): Opened phenotype.db in read-only mode
E/SQLiteLog( 1532): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AppDataSearchHelper( 1532): Exception thrown from onTableChanged
E/AppDataSearchHelper( 1532): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1532): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 1532): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 1532): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 1532): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 1532): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 1532): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 1532): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AppDataSearchHelper( 1532): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 1532): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 1532): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 1532): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 1532): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 1532): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 1532): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 1532): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 1532): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 1532): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 1532): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1532): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 1532): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 1532): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 1532): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 1532): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 1532): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 1532): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 1532): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 1532): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 1532): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 1532): 	... 16 more
W/AppDataSearchHelper( 1532): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 1532): UpdateCorporaTask done [took 84 ms] updated apps [took 84 ms] 
I/ActivityManager(  823): Start proc 4362:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
W/ResourcesManager( 4345): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4345): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager(  823): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  823): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/DropBoxManagerService(  823): Can't write: system_app_crash
E/DropBoxManagerService(  823): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  823): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  823): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  823): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  823): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  823): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  823): 	... 5 more
I/MultiDex( 4345): VM with version 2.1.0 has multidex support
I/MultiDex( 4345): install
I/MultiDex( 4345): VM has multidex support, MultiDex support library is disabled.
D/OpenGLRenderer(  823): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  823): Validating map...
I/ConfigFetchService( 1781): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1781): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
I/ConfigFetchService( 1781): service connected
I/PeopleContactsSync( 1781): CP2 sync disabled
W/BaseAppContext( 1781): Using Auth Proxy for data requests.
I/Icing   ( 1781): doRemovePackageData com.test.thalitest
V/JNIHelp ( 4345): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/BaseAppContext( 1781): Using Auth Proxy for data requests.
E/SQLiteDatabase( 1781): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1781): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1781): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1781): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1781): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1781): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1781): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1781): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1781): Runtime exception while performing operation
E/ClearPendingStateOp( 1781): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1781): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1781): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1781): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1781): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1781): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1781): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1781): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1781): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1781): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1781): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1781): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1781): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1781): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1781): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1781): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  823): Can't write: system_app_wtf
E/DropBoxManagerService(  823): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  823): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  823): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  823): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  823): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  823): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  823): 	... 5 more
I/OpenGLRenderer(  823): Initialized EGL, version 1.4
D/OpenGLRenderer(  823): Enabling debug mode 0
I/ProviderInstaller( 4345): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4345): Failed to open lock file
W/NativeLibraryUtils( 4345): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4345): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4345): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4345): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4345): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4345): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4345): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4345): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4345): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4345): 	... 3 more
I/ActivityManager(  823): Killing 3305:com.google.android.music:main/u0a66 (adj 15): empty #17
I/HotwordDetector( 1532): Closing mic
I/MicrophoneInputStream( 1532): mic_close com.google.android.apps.gsa.speech.audio.u@21438857
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1532): Hotword detection finished
I/HotwordRecognitionRnr( 1532): Stopping hotword detection.
E/Search.SharedPreferencesProto( 1532): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/ActivityManager(  823): Killing 3659:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
I/GAv4    ( 4362): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4362):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4362):   adb logcat -s GAv4
W/GAv4    ( 4362): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4362): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4362): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4362): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4362): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4362): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4362): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4362): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4362): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4362): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4362): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4362): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4362): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4362): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4362): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4362): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4362): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4362): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4362): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4362): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4362): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4362): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4362): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4362): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4362): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4362): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4362): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4362): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4362): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4362): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4362): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4362): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4362): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4362): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4362): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4362): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4362): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4362): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4362): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4362): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4362): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4362): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4362): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4362): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4362): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4362): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4362): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4362): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/native  ( 1242): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1242): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1242): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1242): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/SQLiteDatabase( 4362): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4362): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4362): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4362): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4362): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4362): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4362): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4362): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4362): 	at aej.c(PG:139)
E/SQLiteDatabase( 4362): 	at aej.b(PG:398)
E/SQLiteDatabase( 4362): 	at agf.f(PG:417)
E/SQLiteDatabase( 4362): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4362): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4362): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4362): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4362): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4362): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4362): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4362): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4362): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4362): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4362): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4362): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4362): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4362): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4362): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4362): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4362): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4362): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4362): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4362): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4362): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4362): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4362): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4362): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4362): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4362): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4362): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4362): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4362): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4362): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4362): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4362): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4362): 	at java.lang.Thread.run(Thread.java:818)
E/native  ( 1242): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1242): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1242): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1242): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
W/GAv4    ( 4362): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4362): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4362): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 4362): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4362): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAv4    ( 4362): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4362): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4362): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4362): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4362): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4362): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4362): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4362): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4362): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4362): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4362): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4362): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4362): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4362): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4362): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4362): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4362): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4362): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4362): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4362): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4362): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4362): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4362): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4362): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4362): 	at aen.run(PG:536)
I/ActivityManager(  823): Start proc 4409:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  823): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{16358695 token=Token{29cd864c ActivityRecord{19c1667f u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4362): Sending signal. PID: 4362 SIG: 9
E/lowmemorykiller(  257): Error writing /proc/4362/oom_score_adj; errno=22
E/JavaBinder(  823): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  823): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  823): android.os.TransactionTooLargeException
W/ActivityManager(  823): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  823): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  823): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  823): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  823): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  823): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  823): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  823): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  823): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  823): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  823): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  823): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  823): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  823): 	at android.os.Binder.execTransact(Binder.java:446)
I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 324us total 15.316ms
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 309us total 12.742ms
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 297us total 12.619ms
E/kickstart(  878): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  878): WARNING: function: sahara_start:892 Retrying memory read request
I/ActivityManager(  823): Start proc 4426:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  823): Spurious death for ProcessRecord{376e29c6 4426:com.google.android.apps.docs/u0a46}, curProc for 4362: null
W/OpenGLRenderer( 1385): Incorrectly called buildLayer on View: ew, destroying layer...
E/SQLiteDatabase( 4409): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4409): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4409): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4409): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4409): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4409): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4409): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4409): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4409): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4409): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4409): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4409): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4409): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4409): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4409): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4409): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4409): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4409): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4409): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4409): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4409): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4409): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4409): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4409): Shutting down VM
E/AndroidRuntime( 4409): FATAL EXCEPTION: main
E/AndroidRuntime( 4409): Process: com.android.documentsui, PID: 4409
E/AndroidRuntime( 4409): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4409): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4409): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4409): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4409): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4409): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4409): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4409): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4409): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4409): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4409): 	at android.database.sqlite.SQLiteConnect,ion.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4409): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4409): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4409): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4409): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4409): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4409): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4409): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4409): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4409): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4409): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4409): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4409): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4409): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4409): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4409): 	... 9 more
I/ActivityManager(  823): Killing 3679:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
D/GCM     ( 1268): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  823): Start proc 4447:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
E/DropBoxManagerService(  823): Can't write: system_app_crash
E/DropBoxManagerService(  823): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  823): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  823): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  823): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  823): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  823): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  823): 	... 5 more
I/ActivityManager(  823): Killing 3735:com.android.chrome/u0a40 (adj 15): empty #17
D/AuthorizationBluetoothService( 1268): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 1781): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@295d4773}
D/WearableService( 4345): callingUid 10011, callindPid: 4345
D/LocationInitializer( 1781): Restart initialization of location

```
