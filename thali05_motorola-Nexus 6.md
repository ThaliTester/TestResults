#### Test 5753124374916c2_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
I/CheckinService( 1766): Done disabling old GoogleServicesFramework version
,D/AndroidRuntime( 3576): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3576): CheckJNI is OFF
D/AndroidRuntime( 3576): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{3d841887 token=Token{3fa840c6 ActivityRecord{3064f6a1 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3576): Shutting down VM
V/WindowManager(  822): Adding window Window{36f16720 u0 Starting com.test.thalitest} at 2 of 7 (after Window{153ee541 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1510): Closing mic
I/MicrophoneInputStream( 1510): mic_close com.google.android.apps.gsa.speech.audio.u@1192d9f0
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/ActivityManager(  822): Start proc 3590:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1510): Hotword detection finished
I/HotwordRecognitionRnr( 1510): Stopping hotword detection.
I/ActivityManager(  822): Killing 3186:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660896531
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3590): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3590): Time to load native libraries: 3 ms (timestamps 1221-1224)
I/LibraryLoader( 3590): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3590): Binding Chromium to main looper Looper (main, tid 1) {10c154b}
,I/LibraryLoader( 3590): Expected native library version number "",actual native library version number "",
,I/chromium( 3590): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 3590): Initializing chromium process, singleProcess=true
W/art     ( 3590): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3590): ApplicationContext is null in ApplicationStatus
,W/chromium( 3590): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3590): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3590): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3590): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c6b8502:true
,W/art     ( 3590): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3590): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3590): CordovaWebView is running on device made by: motorola
,W/art     ( 3590): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3590): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3590): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3590): Validating map...
,V/WindowManager(  822): Adding window Window{28d332b2 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{36f16720 u0 Starting com.test.thalitest})
,W/chromium( 3590): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  822): Explicit concurrent mark sweep GC freed 24051(1356KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.154ms total 63.152ms
,I/OpenGLRenderer( 3590): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3590): Enabling debug mode 0
,I/Keyboard.Facilitator( 1282): onFinishInput()
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +757ms
,W/BindingManager( 3590): Cannot call determinedVisibility() - never saw a connection for the pid: 3590
,D/JsMessageQueue( 3590): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3590): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576392320
,I/chromium( 3590): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{182c60c8 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,W/jxcore-log( 3590): Initializing JXcore engine
W/jxcore-log( 3590): JXcore engine is ready
,W/Thread-391( 3645): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11361]" dev="sockfs" ino=11361 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-391( 3645): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-391( 3645): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10855]" dev="sockfs" ino=10855 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-391( 3645): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21779]" dev="sockfs" ino=21779 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3590): Starting JXcore engine
,W/jxcore-log( 3590): Platform android
W/jxcore-log( 3590): 
W/jxcore-log( 3590): Process ARCH arm
W/jxcore-log( 3590): 
,I/jxcore-log( 3590): JXcore Cordova bridge is ready!
I/jxcore-log( 3590): 
W/jxcore-log( 3590): JXcore engine is started
,I/jxcore-log( 3590): Toggling radios to true
I/jxcore-log( 3590): 
,D/BluetoothAdapter( 3590): enable(): BT is already enabled..!
,D/WifiService(  822): New client listening to asynchronous messages
,D/WifiService(  822): setWifiEnabled: true pid=3590, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3590): Radios toggled
I/jxcore-log( 3590): 
,I/jxcore-log( 3590): My device name is: motorola-Nexus 6
I/jxcore-log( 3590): 
,I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1313): Read error: ssl=0xb4888600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1313): SSL shutdown failed: ssl=0xb4888600: I/O error during system call, Broken pipe
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  822): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1057): CM callback handler got msg 524292
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering(  822): MasterInitialState.processMessage what=3
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1510): Network connectivity changed, type is: 6
,D/PhoneInterfaceManager( 1394): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1394): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,V/MusicLeanback( 3323): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  822): No APN found to select.
,D/PhoneInterfaceManager( 1394): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1394): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/WifiConfigStore(  822): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): will read network variables netId=0
,I/ActivityManager(  822): Start proc 3655:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/GpsLocationProvider(  822): No APN found to select.
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,I/ActivityManager(  822): Start proc 3681:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  822): Killing 3225:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,D/SprintDMReceiver( 3681): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3681): simOperator:  IMSI: null
D/SprintDMReceiver( 3681): Not Sprint UICC, don't do anything.
,I/ActivityManager(  822): Killing 3017:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/SystemUpdateService( 1766): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1766): onCreate
,D/SystemUpdateService( 1766): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1766): active receiver: enabled
,I/SystemUpdateService( 1766): showing system update notification
,I/iu.Environment( 1766): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1766): num queued entries: 0
,I/ValidateNoPeople(  822): skipping global notification
I/iu.UploadsManager( 1766): num updated entries: 0
,D/ChimeraCfgMgr( 1766): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.SyncManager( 1766): NEXT; no task
,I/Kids    ( 1766): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
V/SystemUpdateService( 1766): retry (wakeup: false) in 3599955 ms
,D/SystemUpdateService( 1766): onDestroy
,I/ActivityManager(  822): Start proc 3701:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 2937): connection state changed from UNKNOWN to DISCONNECTED
I/art     (  367): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 235us total 10.415ms
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 9.465ms
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 8.781ms
,I/GAv4    ( 3701): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3701):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3701):   adb logcat -s GAv4
,W/GAv4    ( 3701): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3701): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3701): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3701): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3701): Time to load native libraries: 3 ms (timestamps 5066-5069)
I/LibraryLoader( 3701): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3701): Binding Chromium to main looper Looper (main, tid 1) {31e5d1ce}
,I/LibraryLoader( 3701): Expected native library version number "",actual native library version number ""
I/chromium( 3701): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3701): Initializing chromium process, singleProcess=true
,W/art     ( 3701): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3701): ApplicationContext is null in ApplicationStatus
,W/chromium( 3701): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3701): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3701): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3701): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3701): Requires BLUETOOTH permission
,I/NSApplication( 3701): Starting up...
,I/ActivityManager(  822): Start proc 3757:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  822): Start proc 3777:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  822): Killing 3268:com.android.settings/1000 (adj 15): empty #17
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3060): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3060): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3060): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  822): Killing 3289:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/wpa_supplicant( 1178): wlan0: Trying to associate with SSID 'NG7005g',
,I/ActivityManager(  822): Killing 3385:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/wpa_supplicant( 1178): wlan0: Associated with c0:ff:d4:d3:aa:4a
,V/MusicLeanback( 3323): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/wpa_supplicant( 1178): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Setting iface cfg
,E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 194
E/WifiStateMachine(  822):  RSSI mgmt: -52
E/WifiStateMachine(  822):  BE :  rx=183 tx=163 lost=0 retries=2
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=7 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 9256 tx_time=150 rx_time=297 scan_time=0
,D/SprintDMReceiver( 3681): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
D/SprintDMHelper( 3681): simOperator:  IMSI: null
D/SprintDMReceiver( 3681): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1766): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1766): onCreate
,D/SystemUpdateService( 1766): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1766): active receiver: enabled
,I/SystemUpdateService( 1766): showing system update notification
,D/ChimeraCfgMgr( 1766): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1766): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1766): retry (wakeup: false) in 3599983 ms
,D/SystemUpdateService( 1766): onDestroy
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/dhcpcd  ( 3808): version 5.5.6 starting
,I/dhcpcd  ( 3808): wlan0: rebinding lease of 192.168.1.122
,I/art     ( 1313): Explicit concurrent mark sweep GC freed 20695(1012KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.069ms total 45.473ms
,I/dhcpcd  ( 3808): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3808): wlan0: leased 192.168.1.122 for 86400 seconds
,I/ActivityManager(  822): Killing 3453:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/jxcore-log( 3590): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3590): 
,I/ActivityManager(  822): Killing 3405:com.android.musicfx/u0a18 (adj 15): empty #18
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 101
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822):    accepting network in place of null
,D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1057): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3,
,I/NetworkMonitor( 3323): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1394): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1394): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
D/NetworkChangeNotifierAutoDetect( 1510): Network connectivity changed, type is: 2
,V/MusicLeanback( 3323): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMReceiver( 3681): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3681): simOperator:  IMSI: null
D/SprintDMReceiver( 3681): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1766): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1766): onCreate
,D/SystemUpdateService( 1766): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1766): active receiver: enabled
,I/SystemUpdateService( 1766): showing system update notification
,I/iu.Environment( 1766): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1766): num queued entries: 0
,I/ValidateNoPeople(  822): skipping global notification
,I/iu.UploadsManager( 1766): num updated entries: 0
V/SystemUpdateService( 1766): retry (wakeup: false) in 3599980 ms
,I/iu.SyncManager( 1766): NEXT; no task
,D/ChimeraCfgMgr( 1766): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1766): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/SystemUpdateService( 1766): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Feb 2016 14:14:21 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454681661352], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454681661331]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1057): CM callback handler got msg 524290
,V/Herrevad( 1766): NQAS connected
,I/Babel   ( 2937): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1313): Connected
,I/GCM     ( 1766): Message from null null
,E/GCM     ( 1766): Dropping message from null
,I/jxcore-log( 3590): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3590): 
,D/GCM     ( 1313): Message class com.google.f.a.a.p
,I/jxcore-log( 3590): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3590): 
,I/jxcore-log( 3590): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3590): 
,I/jxcore-log( 3590): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3590): 
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=17.66 rxSuccessRate=16.50 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,D/Finsky  ( 3060): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3060): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/art     (  822): Explicit concurrent mark sweep GC freed 50977(2MB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 1.613ms total 104.946ms
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3590): Test app app.js loaded
I/jxcore-log( 3590): 
,W/Finsky  ( 3060): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/chromium( 3590): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3590): load: 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3590): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3590): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3590): 	Bluetooth MAC address: F8:CF:C5:D9:E5:61, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3590): ,	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3590): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3590): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3590): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3590): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3590): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c459cc added. We now have 1 listener(s)
,I/jxcore-log( 3590): BLE advertisement is supported
I/jxcore-log( 3590): 
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=9.33 rxSuccessRate=9.25 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 3060): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3060): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,D/Finsky  ( 3060): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3060): [1] DailyHygiene.reschedule: Scheduling new run in 247 minutes (failures=4)
,D/DeviceConnectionService( 1803): client connected with version: 7571000
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.14 rxSuccessRate=4.26 targetRoamBSSID=any RSSI=-52
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3060): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3060): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3060): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  822): Start proc 3869:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/ActivityManager(  822): Start proc 3886:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,W/GAV2    ( 3869): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3869): Created application version: 3.6.8 (30608)
,I/BooksSync( 3869): Starting books sync for 61035162, extras: ade
,I/art     ( 1313): Explicit concurrent mark sweep GC freed 21441(1162KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 25MB/41MB, paused 1.335ms total 34.180ms
,V/KeepSync( 3886): Connecting to GoogleApiClient
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksConfig( 3869): GmsCore Version = 7.8.99 (2134222-430)
,E/ClientConnectionOperation( 1766): Handling authorization failure
E/ClientConnectionOperation( 1766): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1766): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1766): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1766): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1766): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1766): 	... 7 more
,V/KeepSync( 3886): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3886): IOException
E/KeepSync( 3886): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3886): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3886): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3886): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3886): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3886): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3886): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3886): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3886): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3886): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3886): 	... 10 more
W/KeepSync( 3886): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 78844, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  822): Explicit concurrent mark sweep GC freed 29144(1348KB) AllocSpace objects, 6(96KB) LOS objects, 31% free, 34MB/50MB, paused 1.691ms total 67.683ms
,E/BooksAccountManager( 3869): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3869): Soft error
E/BooksSync( 3869): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3869): Sync error
E/BooksSync( 3869): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3869): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78663, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at blb.a(PG:3937)
E/HttpOperation( 3495): 	at czp.a(PG:18188)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 12 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 14 more
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  822): Killing 1464:android.process.acore/u0a5 (adj 15): empty #17
,E/HttpOperation( 3495): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at hec.a(PG:42)
E/HttpOperation( 3495): 	at hee.a(PG:102)
E/HttpOperation( 3495): 	at czr.a(PG:65)
E/HttpOperation( 3495): 	at kka.a(PG:108)
E/HttpOperation( 3495): 	at czp.a(PG:19176)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 15 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 17 more
,E/ExperimentLoader( 3495): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 3495): ,	at jdm.a(PG:82)
E/ExperimentLoader( 3495): ,	at jcs.o(PG:406)
E/ExperimentLoader( 3495): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3495): 	at jcs.i(PG:143)
E/ExperimentLoader( 3495): 	at hec.a(PG:42)
E/ExperimentLoader( 3495): 	at hee.a(PG:102)
E/ExperimentLoader( 3495): 	at czr.a(PG:65)
E/ExperimentLoader( 3495): 	at kka.a(PG:108)
E/ExperimentLoader( 3495): 	at czp.a(PG:19176)
E/ExperimentLoader( 3495): 	at czp.a(PG:9081)
E/ExperimentLoader( 3495): 	at czq.run(PG:1686)
E/ExperimentLoader( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3495): 	at java.lang.Thread.run(Thread.java:818)
,E/ExperimentLoader( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3495): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3495): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3495): 	at jdm.a(PG:77)
E/ExperimentLoader( 3495): 	... 15 more
E/ExperimentLoader( 3495): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3495): 	at fal.a(PG:38)
E/ExperimentLoader( 3495): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3495): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 80366, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 3119:com.google.android.gm/u0a78 (adj 15): empty #17,
,I/GAV2    ( 3869): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  822): Start proc 3935:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 3935): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3935):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3935):   adb logcat -s GAv4
,W/GAv4    ( 3935): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3935): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.41 rxSuccessRate=1.76 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,W/GAv4    ( 3935): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  822): Killing 2301:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/Finsky  ( 3060): [289] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3060): [289] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/Finsky  ( 3060): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3060): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3060): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1282): run()
I/Keyboard.Facilitator( 1282): flushDynamicLanguageModels()
,I/ConfigService( 1313): onCreate
,I/ConfigService( 1313): onDestroy
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.85 rxSuccessRate=3.55 targetRoamBSSID=any RSSI=-52
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3060): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3060): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3060): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.67 rxSuccessRate=2.86 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (324 us)
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  822): Display changed displayId=0
,D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6482000
,D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
,I/kickstart(  869): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  869): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  869): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  869): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 269ms
,I/DreamManagerService(  822): Entering dreamland.
,I/PowerManagerService(  822): Dozing...
,I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0,
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=on,
,D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 12
,E/native  (  822): do suspend false
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=off
,I/Keyboard.Facilitator( 1282): onFinishInput()
,E/WifiStateMachine(  822): cancelDelayedScan -> 14
,E/native  (  822): do suspend true
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/kickstart(  869): STATUS: Received file 'm9kefs2',
I/kickstart(  869): STATUS: 950272 bytes transferred in 0.994574 seconds
I/kickstart(  869): STATUS: Successfully downloaded files from target 
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  869): STATUS: Sahara protocol completed
,V/CheckinService( 1766): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,I/CheckinService( 1766): Checking schedule, now: 1454681747900 next: 1454681737092
,I/CheckinService( 1766): active receiver: enabled
,I/CheckinService( 1766): Preparing to send checkin request
,I/EventLogService( 1766): Accumulating logs since 1454680830802
,I/EventLogService( 1766): Opted in for usage reporting
,W/EventLogAggregator( 1766): Unknown tag: snet_gcore
W/EventLogAggregator( 1766): Unknown tag: snet_launch_service
,I/CheckinRequestBuilder( 1766): Checkin reason type: 11 attempt count: 1
,E/ActivityThread( 1766): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1313): Explicit concurrent mark sweep GC freed 26871(1554KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.575ms total 56.813ms
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3060): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3060): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3060): [1] 5.onFinished: Scheduling replication attempt 5.,
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 1766): awaiting user notification for token
,I/ActivityManager(  822): Start proc 3976:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,I/art     (  822): Explicit concurrent mark sweep GC freed 44973(2MB) AllocSpace objects, 17(460KB) LOS objects, 31% free, 34MB/50MB, paused 1.387ms total 77.628ms
,W/ResourcesManager( 3976): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3976): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3976): VM with version 2.1.0 has multidex support
I/MultiDex( 3976): install
I/MultiDex( 3976): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3976): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3976): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1313): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1313): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1766): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3425): callingUid 10011, callindPid: 3425
,E/MDM     ( 1803): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1766): Restart initialization of location
,D/WVCdm   (  356): Instantiating CDM.
,I/WVCdm   (  356): CdmEngine::OpenSession
I/WVCdm   (  356): Level3 Library Dec 11 2014 16:13:16
,I/GoogleURLConnFactory( 3976): Using platform SSLCertificateSocketFactory
,W/WVCdm   (  356): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  356): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  356): Service_Initialize: starts!
,D/QSEECOMAPI: (  356): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  356): App is not loaded in QSEE
,D/QSEECOMAPI: (  356): Loaded image: APP id = 3
,D/DrmWidevineDash(  356): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  356): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4418000
E/DrmWidevineDash(  356): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4418000
,D/DrmLibTime(  311): got the req here! ret=0
D/DrmLibTime(  311): command id, time_cmd_id = 770
D/DrmLibTime(  311): time_getutcsec starts!
D/DrmLibTime(  311): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  311): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  311): QSEE Time Listener: seconds: 1454681749
D/DrmLibTime(  311): QSEE Time Listener: nano seconds: 344946046
D/DrmLibTime(  311): time_getutcsec returns 0, sec = 1454681749; nsec = 344946046
D/DrmLibTime(  311): time_getutcsec finished! 
D/DrmLibTime(  311): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  311): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  356): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  356): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  356): hlos api version =  9
D/DrmWidevineDash(  356): tz api version =  9
D/DrmWidevineDash(  356): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  356): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  356): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  356): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  356): OEMCrypto_OpenSession: starts! SID=0xbec8b520
D/DrmWidevineDash(  356): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  356): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  356): OEMCrypto_GetRandom: starts! randomData=0xb58762a0, dataLength=8
D/DrmWidevineDash(  356): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  356): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4016800, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  356): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  356): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  356): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  356): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  356): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  356): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d6e440, idLength=0xb3f01710,
,D/DrmWidevineDash(  356): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  356): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  356): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  356): OEMCrypto_SupportsUsageTable: wv_app_version = 21
,D/DrmWidevineDash(  356): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  356): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  356): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  356): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  356): hlos api version =  9
,D/DrmWidevineDash(  356): tz api version =  9
D/DrmWidevineDash(  356): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  356): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  356): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  356): PrepareKeyRequest: nonce=4127900419
D/DrmWidevineDash(  356): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4cfd600
D/DrmWidevineDash(  356): message_length=1599, signature=0xb4c532c0, signature_length=3018856180
,D/DrmWidevineDash(  356): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  356): CdmEngine::CloseSession
D/DrmWidevineDash(  356): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  356): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  356): L3 Terminate.
D/DrmWidevineDash(  356): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  356): Service_Uninitialize: starts!
D/QSEECOMAPI: (  356): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  356): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  356): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  356): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  356): CdmEngine::OpenSession
I/WVCdm   (  356): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  356): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  356): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  356): Service_Initialize: starts!
D/QSEECOMAPI: (  356): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  356): App is not loaded in QSEE
,D/QSEECOMAPI: (  356): Loaded image: APP id = 3
,D/DrmWidevineDash(  356): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  356): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4418000
E/DrmWidevineDash(  356): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4418000
,D/DrmLibTime(  311): got the req here! ret=0
D/DrmLibTime(  311): command id, time_cmd_id = 770
D/DrmLibTime(  311): time_getutcsec starts!
D/DrmLibTime(  311): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  311): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  311): QSEE Time Listener: seconds: 1454681750
D/DrmLibTime(  311): QSEE Time Listener: nano seconds: 169051722
D/DrmLibTime(  311): time_getutcsec returns 0, sec = 1454681750; nsec = 169051722
D/DrmLibTime(  311): time_getutcsec finished! 
D/DrmLibTime(  311): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  311): before calling ioctl to read the next time_cmd
D/DrmWidevineDash(  356): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  356): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  356): hlos api version =  9
D/DrmWidevineDash(  356): tz api version =  9
D/DrmWidevineDash(  356): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  356): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  356): OEMCrypto_IsKeyboxValid: ends! returns 0,
D/WVCdm   (  356): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  356): OEMCrypto_OpenSession: starts! SID=0xb3e03940
D/DrmWidevineDash(  356): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  356): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  356): OEMCrypto_GetRandom: starts! randomData=0xb58762a0, dataLength=8
D/DrmWidevineDash(  356): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  356): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4015000, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  356): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  356): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  356): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  356): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  356): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  356): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d6e480, idLength=0xb3e03710
,D/DrmWidevineDash(  356): OEMCrypto_GetDeviceID: ends! returns 0,
D/DrmWidevineDash(  356): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  356): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  356): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  356): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  356): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  356): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  356): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  356): hlos api version =  9
D/DrmWidevineDash(  356): tz api version =  9
D/DrmWidevineDash(  356): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  356): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  356): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  356): PrepareKeyRequest: nonce=3437244789
D/DrmWidevineDash(  356): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4cfdd00
D/DrmWidevineDash(  356): message_length=1634, signature=0xb5880100, signature_length=3017815796
,D/DrmWidevineDash(  356): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  356): CdmEngine::CloseSession,
D/DrmWidevineDash(  356): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  356): OEMCrypto_CloseSession: ends! returns 0,
I/WVCdm   (  356): L3 Terminate.
D/DrmWidevineDash(  356): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  356): Service_Uninitialize: starts!
D/QSEECOMAPI: (  356): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  356): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  356): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  356): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 4007): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4007): dex2oat took 50.391ms (threads: 4) arena alloc=70KB java alloc=18KB native alloc=1246KB free=6MB,
,I/Adreno  ( 3976): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,V/KeepSync( 3886): Connecting to GoogleApiClient
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Adreno  ( 3976): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,E/ClientConnectionOperation( 1766): Handling authorization failure
E/ClientConnectionOperation( 1766): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1766): ,	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1766): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1766): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1766): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1766): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1766): 	... 7 more
,E/HttpOperation( 3495): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at blb.a(PG:3937)
E/HttpOperation( 3495): 	at czp.a(PG:18188)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	,at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 12 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 14 more
,V/KeepSync( 3886): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at hec.a(PG:42)
E/HttpOperation( 3495): 	at hee.a(PG:102)
E/HttpOperation( 3495): 	at czr.a(PG:65)
E/HttpOperation( 3495): 	at kka.a(PG:108)
E/HttpOperation( 3495): 	at czp.a(PG:19176)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 15 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 17 more
E/ExperimentLoader( 3495): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): 	at jdm.a(PG:82)
E/ExperimentLoader( 3495): 	at jcs.o(PG:406)
E/ExperimentLoader( 3495): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3495): 	at jcs.i(PG:143)
E/ExperimentLoader( 3495): 	at hec.a(PG:42)
E/ExperimentLoader( 3495): 	at hee.a(PG:102)
E/ExperimentLoader( 3495): 	at czr.a(PG:65)
E/ExperimentLoader( 3495): 	at kka.a(PG:108)
E/ExperimentLoader( 3495): 	at czp.a(PG:19176)
E/ExperimentLoader( 3495): 	at czp.a(PG:9081)
E/ExperimentLoader( 3495): 	at czq.run(PG:1686)
E/ExperimentLoader( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3495): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3495): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3495): 	at jdm.a(PG:77)
E/ExperimentLoader( 3495): 	... 15 more
E/ExperimentLoader( 3495): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3495): 	at fal.a(PG:38)
E/ExperimentLoader( 3495): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3495): 	... 17 more
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3886): IOException
E/KeepSync( 3886): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3886): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3886): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3886): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3886): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3886): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3886): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3886): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3886): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3886): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3886): 	... 10 more
W/KeepSync( 3886): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 139745, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 140860, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3869): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3869): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1766): Opted in for usage reporting
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3869): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3869): Soft error
E/BooksSync( 3869): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3869): Sync error
E/BooksSync( 3869): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3869): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 140952, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/CheckinTask( 1766): Sending checkin request (9734 bytes)
,I/CheckinRequestBuilder( 1766): Checkin reason type: 11 attempt count: 1
,E/ActivityThread( 1766): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 1766): awaiting user notification for token
,I/EventLogService( 1766): Opted in for usage reporting
,I/CheckinTask( 1766): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1766): Checking schedule, now: 1454681753098 next: 1454722896089
,I/CheckinService( 1766): active receiver: disabled
,D/ChimeraCfgMgr( 1766): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1766): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/GCM     ( 1313): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  822): Killing 3323:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  822): Start proc 4031:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,V/GmsNetworkLocationProvi( 1803): DISABLE
,D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  822): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  822): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/GmsNetworkLocationProvi( 1803): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/BackupManagerService(  822): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  822): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@381a9dd1
,V/BackupManagerService(  822): Scheduling immediate backup pass
,V/BackupManagerService(  822): Running a backup pass
,V/GmsNetworkLocationProvi( 1803): ENABLE
,V/BackupManagerService(  822): clearing pending backups
,V/GmsNetworkLocationProvi( 1803): SET-REQUEST
V/PerformBackupTask(  822): Beginning backup of 14 targets
,V/GmsNetworkLocationProvi( 1803): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,D/PerformBackupTask(  822): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  822): doBackup() invoked
I/PMBA    (  822): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  822): Getting widget state for user: 0
,W/GmsBackupTransport( 1803): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1803): starting performBackup for @pm@
,V/GmsBackupTransport( 1803): performBackup done for @pm@
,I/Launcher( 1415): Deferring update until onResume
,I/ContactLocale( 4031): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ],
,I/art     (  822): Explicit concurrent mark sweep GC freed 36503(1789KB) AllocSpace objects, 6(190KB) LOS objects, 31% free, 34MB/50MB, paused 1.730ms total 71.797ms
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageBroadcastService( 1766): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 1510): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageBroadcastService( 1766): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1415): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@581e72 new=com.google.android.velvet.VelvetApplication@581e72
,I/Icing   ( 1766): updateResources: need to parse f{com.google.android.gms}
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UpdateIcingCorporaServi( 1510): UpdateCorporaTask done [took 42 ms] updated apps [took 42 ms] 
,W/GLSActivity( 1313): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1313): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1313): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1313): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1313): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1313): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1313): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1803): Error sending final backup to server: 
W/GmsBackupTransport( 1803): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1803): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1803): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1803): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1803): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1803): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1803): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1803): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1803): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1803): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1803): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1803): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1803): 	... 1 more
,D/BackupManagerService(  822): Now staging backup of com.google.android.talk
,D/BackupManagerService(  822): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  822): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  822): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  822): Now staging backup of com.google.android.gm
,D/BackupManagerService(  822): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  822): Now staging backup of com.android.nfc
,D/BackupManagerService(  822): Now staging backup of com.google.android.apps.genie.geniewidget
D/BackupManagerService(  822): Now staging backup of com.google.android.marvin.talkback
D/BackupManagerService(  822): Now staging backup of com.google.android.inputmethod.latin
D/BackupManagerService(  822): Now staging backup of com.google.android.calendar
D/BackupManagerService(  822): Now staging backup of com.android.vending
,D/BackupManagerService(  822): Now staging backup of android
,D/BackupManagerService(  822): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1803): Next backup will happen in 43199958 millis.
,I/BackupManagerService(  822): Backup pass finished.
,I/art     ( 1313): Explicit concurrent mark sweep GC freed 30628(1762KB) AllocSpace objects, 6(661KB) LOS objects, 36% free, 27MB/43MB, paused 1.266ms total 59.712ms
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3655): [385] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1313): Vacuum at: now=1454681760715 tag=VacuumService
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GoogleURLConnFactory( 1313): Using platform SSLCertificateSocketFactory
,W/ExperimentUpdateService( 3655): [385] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3655): [385] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	,at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
,W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,W/Uploader( 1313): No account for auth token provided
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,W/Uploader( 1313): No account for auth token provided
,W/Uploader( 1313): No account for auth token provided
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1313): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1313): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1313): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
,E/Uploader( 1313): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508),
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1313): 	at com.google.android.gms.gcm.am.run(SourceFile:135),
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1313): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1313): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1313): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1313): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1313): No account for auth token provided
,W/Uploader( 1313): No account for auth token provided
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1313): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1313): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1313): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1313): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1313): No account for auth token provided
,W/Uploader( 1313): No account for auth token provided
,W/Uploader( 1313): No account for auth token provided
,W/Uploader( 1313): No account for auth token provided
,W/Uploader( 1313):  no longer exists, so no auth token.
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1313): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1313): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1313): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1313): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1313): No account for auth token provided
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1313): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1313): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1313): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1313): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1313): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1313): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  822): Killing 3681:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3060): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3060): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3060): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1282): run()
I/Keyboard.Facilitator( 1282): flushDynamicLanguageModels()
,I/ConfigService( 1313): onCreate
,V/GoogleAuthProtoRequest( 3655): [386] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [386] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3655): [386] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,I/ConfigService( 1313): onDestroy
,V/KeepSync( 3886): Connecting to GoogleApiClient
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1766): Handling authorization failure
E/ClientConnectionOperation( 1766): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1766): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1766): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1766): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1766): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1766): 	... 7 more
,V/KeepSync( 3886): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3886): IOException
E/KeepSync( 3886): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3886): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3886): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3886): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3886): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3886): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3886): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3886): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3886): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3886): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3886): 	... 10 more
W/KeepSync( 3886): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 229905, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  822): Explicit concurrent mark sweep GC freed 32331(1446KB) AllocSpace objects, 6(378KB) LOS objects, 31% free, 34MB/50MB, paused 1.417ms total 63.916ms
,I/BooksSync( 3869): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3869): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
,E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82),
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	,at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143),
E/HttpOperation( 3495): 	at blb.a(PG:3937)
E/HttpOperation( 3495): ,	at czp.a(PG:18188)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 12 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 14 more
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,E/BooksAccountManager( 3869): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): Soft error
E/BooksSync( 3869): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3869): Sync error
E/BooksSync( 3869): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
I/BooksSync( 3869): Finished books sync
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 232351, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/HttpOperation( 3495): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at hec.a(PG:42)
E/HttpOperation( 3495): 	at hee.a(PG:102)
E/HttpOperation( 3495): 	at czr.a(PG:65)
E/HttpOperation( 3495): 	at kka.a(PG:108)
E/HttpOperation( 3495): 	at czp.a(PG:19176)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 15 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 17 more
E/ExperimentLoader( 3495): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): 	at jdm.a(PG:82)
E/ExperimentLoader( 3495): 	at jcs.o(PG:406)
E/ExperimentLoader( 3495): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3495): 	at jcs.i(PG:143)
E/ExperimentLoader( 3495): 	at hec.a(PG:42)
E/ExperimentLoader( 3495): 	at hee.a(PG:102)
E/ExperimentLoader( 3495): 	at czr.a(PG:65)
E/ExperimentLoader( 3495): 	at kka.a(PG:108)
E/ExperimentLoader( 3495): 	at czp.a(PG:19176)
E/ExperimentLoader( 3495): 	at czp.a(PG:9081)
E/ExperimentLoader( 3495): 	at czq.run(PG:1686)
E/ExperimentLoader( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3495): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3495): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3495): 	at jdm.a(PG:77)
E/ExperimentLoader( 3495): 	... 15 more
E/ExperimentLoader( 3495): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3495): 	at fal.a(PG:38)
E/ExperimentLoader( 3495): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3495): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 230598, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,I/art     ( 1313): Explicit concurrent mark sweep GC freed 62233(3MB) AllocSpace objects, 16(1506KB) LOS objects, 36% free, 27MB/43MB, paused 1.492ms total 66.515ms
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2c963338}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,V/GoogleAuthProtoRequest( 3655): [387] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [387] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3655): [387] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): ,	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	,at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2c963338}
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/KeepSync( 3886): Connecting to GoogleApiClient
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1766): Handling authorization failure
E/ClientConnectionOperation( 1766): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1766): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1766): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1766): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1766): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1766): 	... 7 more
,V/KeepSync( 3886): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3886): IOException
E/KeepSync( 3886): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3886): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3886): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3886): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3886): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3886): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3886): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3886): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3886): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3886): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3886): 	... 10 more
W/KeepSync( 3886): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 352095, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1313): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1313): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1313): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1313): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1313): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1313): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1313): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3060): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3060): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3060): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3060): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3060): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3060): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3060): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3060): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,I/BooksSync( 3869): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3869): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at blb.a(PG:3937)
E/HttpOperation( 3495): 	at czp.a(PG:18188)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 12 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 14 more
,I/art     (  822): Explicit concurrent mark sweep GC freed 35383(1572KB) AllocSpace objects, 15(899KB) LOS objects, 31% free, 34MB/50MB, paused 1.670ms total 123.010ms
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at hec.a(PG:42)
E/HttpOperation( 3495): 	at hee.a(PG:102)
E/HttpOperation( 3495): 	at czr.a(PG:65)
E/HttpOperation( 3495): 	at kka.a(PG:108)
E/HttpOperation( 3495): 	at czp.a(PG:19176)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 15 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 17 more
,E/ExperimentLoader( 3495): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3495): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): ,	at jdm.a(PG:82)
E/ExperimentLoader( 3495): 	at jcs.o(PG:406)
E/ExperimentLoader( 3495): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3495): 	,at jcs.i(PG:143)
E/ExperimentLoader( 3495): 	at hec.a(PG:42)
E/ExperimentLoader( 3495): 	at hee.a(PG:102)
E/ExperimentLoader( 3495): 	at czr.a(PG:65)
,E/ExperimentLoader( 3495): 	at kka.a(PG:108)
E/ExperimentLoader( 3495): 	at czp.a(PG:19176)
E/ExperimentLoader( 3495): 	at czp.a(PG:9081)
E/ExperimentLoader( 3495): 	at czq.run(PG:1686)
E/ExperimentLoader( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3495): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3495): ,	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3495): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3495): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3495): 	at jdm.a(PG:77)
E/ExperimentLoader( 3495): 	... 15 more
E/ExperimentLoader( 3495): Caused by: faj: BadAuthentication
,E/ExperimentLoader( 3495): 	at fal.a(PG:38)
E/ExperimentLoader( 3495): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3495): 	... 17 more
I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3869): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3869): Soft error
E/BooksSync( 3869): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3869): Sync error
E/BooksSync( 3869): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3869): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 386670, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 383533, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3655): [388] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [388] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3655): [388] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,V/KeepSync( 3886): Connecting to GoogleApiClient
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1766): Handling authorization failure
E/ClientConnectionOperation( 1766): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209),
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1766): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1766): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1766): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1766): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.b(SourceFile:30),
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1766): 	... 7 more
,V/KeepSync( 3886): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3886): IOException
E/KeepSync( 3886): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3886): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3886): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3886): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3886): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3886): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3886): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3886): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3886): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3886): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3886): 	... 10 more
W/KeepSync( 3886): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 595767, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,I/art     ( 1313): Explicit concurrent mark sweep GC freed 54001(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 2.199ms total 63.704ms
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at blb.a(PG:3937)
E/HttpOperation( 3495): 	at czp.a(PG:18188)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 12 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 14 more
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3495): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at hec.a(PG:42)
E/HttpOperation( 3495): 	at hee.a(PG:102)
E/HttpOperation( 3495): 	at czr.a(PG:65)
E/HttpOperation( 3495): 	at kka.a(PG:108)
E/HttpOperation( 3495): 	at czp.a(PG:19176)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
,E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 15 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 17 more
E/ExperimentLoader( 3495): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): 	at jdm.a(PG:82)
E/ExperimentLoader( 3495): 	at jcs.o(PG:406)
E/ExperimentLoader( 3495): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3495): 	at jcs.i(PG:143)
E/ExperimentLoader( 3495): 	at hec.a(PG:42)
E/ExperimentLoader( 3495): 	at hee.a(PG:102)
E/ExperimentLoader( 3495): 	at czr.a(PG:65)
E/ExperimentLoader( 3495): 	at kka.a(PG:108)
E/ExperimentLoader( 3495): 	at czp.a(PG:19176)
E/ExperimentLoader( 3495): 	at czp.a(PG:9081)
E/ExperimentLoader( 3495): 	at czq.run(PG:1686)
E/ExperimentLoader( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/ExperimentLoader( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3495): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3495): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3495): 	at jdm.a(PG:77)
E/ExperimentLoader( 3495): 	... 15 more
E/ExperimentLoader( 3495): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3495): 	at fal.a(PG:38)
E/ExperimentLoader( 3495): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3495): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 658693, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,I/BooksSync( 3869): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3869): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3869): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3869): Soft error
E/BooksSync( 3869): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3869): Sync error
E/BooksSync( 3869): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3869): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 665157, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3655): [389] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [389] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3655): [389] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,I/art     (  822): Explicit concurrent mark sweep GC freed 49692(2MB) AllocSpace objects, 10(442KB) LOS objects, 31% free, 34MB/50MB, paused 2.684ms total 82.504ms
,W/bt-btm  ( 2392): Stopping oneshot timer
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/GCM     ( 1313): Message class com.google.f.a.a.i
,I/EventLogService( 1766): Opted in for usage reporting
,I/EventLogService( 1766): Aggregate from 1454681748022 (log), 1454680830802 (data)
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@c9d614c}
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@c9d614c}
,I/art     ( 1803): Explicit concurrent mark sweep GC freed 17152(1065KB) AllocSpace objects, 13(208KB) LOS objects, 37% free, 26MB/42MB, paused 794us total 27.360ms
,E/DataBuffer( 1803): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@325afe2d)
,I/ServiceDumpSys( 1766): dumping service [account]
,V/KeepSync( 3886): Connecting to GoogleApiClient
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1766): Handling authorization failure
E/ClientConnectionOperation( 1766): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1766): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1766): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1766): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1766): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1766): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1766): 	... 7 more
,V/KeepSync( 3886): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3886): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3886): IOException
E/KeepSync( 3886): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3886): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3886): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3886): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3886): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3886): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3886): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3886): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3886): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3886): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3886): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3886): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3886): 	... 10 more
W/KeepSync( 3886): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1082944, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at blb.a(PG:3937)
E/HttpOperation( 3495): 	at czp.a(PG:18188)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 12 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 14 more
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3495): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3495): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3495): 	at jdm.a(PG:82)
E/HttpOperation( 3495): 	at jcs.o(PG:406)
E/HttpOperation( 3495): 	at jcn.a(PG:1379)
E/HttpOperation( 3495): 	at jcs.i(PG:143)
E/HttpOperation( 3495): 	at hec.a(PG:42)
E/HttpOperation( 3495): 	at hee.a(PG:102)
E/HttpOperation( 3495): 	at czr.a(PG:65)
E/HttpOperation( 3495): 	at kka.a(PG:108)
E/HttpOperation( 3495): 	at czp.a(PG:19176)
E/HttpOperation( 3495): 	at czp.a(PG:9081)
E/HttpOperation( 3495): 	at czq.run(PG:1686)
E/HttpOperation( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3495): 	at jdj.a(PG:4091)
E/HttpOperation( 3495): 	at jdj.a(PG:1125)
E/HttpOperation( 3495): 	at jdm.a(PG:77)
E/HttpOperation( 3495): 	... 15 more
E/HttpOperation( 3495): Caused by: faj: BadAuthentication
E/HttpOperation( 3495): 	at fal.a(PG:38)
E/HttpOperation( 3495): 	at jdj.a(PG:4089)
E/HttpOperation( 3495): 	... 17 more
E/ExperimentLoader( 3495): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3495): 	at jdm.a(PG:82)
E/ExperimentLoader( 3495): 	at jcs.o(PG:406)
E/ExperimentLoader( 3495): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3495): 	at jcs.i(PG:143)
E/ExperimentLoader( 3495): 	at hec.a(PG:42)
E/ExperimentLoader( 3495): 	at hee.a(PG:102)
E/ExperimentLoader( 3495): 	at czr.a(PG:65)
E/ExperimentLoader( 3495): 	at kka.a(PG:108)
E/ExperimentLoader( 3495): 	at czp.a(PG:19176)
E/ExperimentLoader( 3495): 	at czp.a(PG:9081)
E/ExperimentLoader( 3495): 	at czq.run(PG:1686)
E/ExperimentLoader( 3495): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3495): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3495): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3495): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3495): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3495): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3495): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3495): 	at jdm.a(PG:77)
E/ExperimentLoader( 3495): 	... 15 more
E/ExperimentLoader( 3495): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3495): 	at fal.a(PG:38)
E/ExperimentLoader( 3495): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3495): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1151392, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3655): [390] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3655): [390] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3655): [390] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3655): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3655): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3655): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3655): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3655): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,I/BooksSync( 3869): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3869): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1313): Explicit concurrent mark sweep GC freed 64713(3MB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 27MB/43MB, paused 1.591ms total 52.929ms
,I/GLSUser ( 1313): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1313): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1313): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1313): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3869): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3869): Soft error
E/BooksSync( 3869): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3869): Sync error
E/BooksSync( 3869): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3869): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3869): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1194307, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2392): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4319): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4319): CheckJNI is OFF
D/AndroidRuntime( 4319): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 3590:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  822): Skipping PackageSetting{1f3741b7 com.example.hello/10273} due to missing metadata
I/WindowState(  822): WIN DEATH: Window{28d332b2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  822): Client connection lost with reason: 4
E/libprocessgroup(  822): failed to kill 1 processes for processgroup 3590
W/ActivityManager(  822): Force removing ActivityRecord{3064f6a1 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
V/ActivityManager(  822): Display changed displayId=0
I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
W/ActivityManager(  822): Spurious death for ProcessRecord{216ca3b 3590:com.test.thalitest/u0a265}, curProc for 3590: null
D/TaskPersister(  822): removeObsoleteFile: deleting file=28_task.xml
I/Keyboard.Facilitator( 1282): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1282): run()
I/Decoder ( 1282): createOrResetDecoder
I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
D/BuaReceiver( 3368): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/art     ( 1057): Explicit concurrent mark sweep GC freed 73023(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 788us total 58.278ms
D/VoicemailCleanupService( 4031): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  822): Start proc 4336:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/ConfigService( 1313): onCreate
I/art     (  822): Explicit concurrent mark sweep GC freed 40012(2MB) AllocSpace objects, 13(490KB) LOS objects, 31% free, 34MB/50MB, paused 1.246ms total 96.690ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1282): run()
I/art     ( 1510): Explicit concurrent mark sweep GC freed 8772(564KB) AllocSpace objects, 1(24KB) LOS objects, 22% free, 27MB/35MB, paused 397us total 120.026ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1282): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1282): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1282): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1282): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1282): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1282): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1282): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1282): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1282): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1282): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1282): run()
I/StatsUtilsManager( 1282): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1282): shouldRecordStats() = Too Soon
I/ActivityManager(  822): Start proc 4358:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3590 uid 10265
D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/Keyboard.Facilitator( 1282): onFinishInput()
W/ContextImpl( 4358): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
W/LocationOracleImpl( 1510): Best location was null
E/NetworkScheduler.SchedulerReceiver( 1313): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1313): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/art     ( 1415): Explicit concurrent mark sweep GC freed 11642(651KB) AllocSpace objects, 10(1188KB) LOS objects, 31% free, 35MB/51MB, paused 1.695ms total 38.044ms
I/HotwordRecognitionRnr( 1510): Starting hotword detection.
I/MicrophoneInputStream( 1510): mic_starting com.google.android.apps.gsa.speech.audio.u@ae62d67
I/AudioFlinger(  356): AudioFlinger's thread 0xb40a5000 ready to run
D/ChimeraCfgMgr( 1766): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1766): Module APK com.google.android.play.games already loaded
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1510): mic_started com.google.android.apps.gsa.speech.audio.u@ae62d67
D/PackageBroadcastService( 1766): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1766): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1766): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1766): Module APK com.google.android.play.games already loaded
D/audio_hw_primary(  356): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  356): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  356): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  356): enable_snd_device: snd_device(55: voice-rec-mic)
I/LocationSettingsChecker( 1766): Removing dialog suppression flag for package com.test.thalitest
D/audio_hw_primary(  356): enable_audio_route: apply and update mixer path: audio-record
I/UpdateIcingCorporaServi( 1510): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1415): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@581e72 new=com.google.android.velvet.VelvetApplication@581e72
D/GOOGLEHELP_CompatibleDatabase( 1766): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1766): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1766): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1766): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1766): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1766): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1766): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/art     (  822): Explicit concurrent mark sweep GC freed 8397(377KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 3.887ms total 167.806ms
D/GOOGLEHELP_CompatibleDatabase( 1766): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1766): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1766): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
I/ActivityManager(  822): Start proc 4398:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
D/GOOGLEHELP_CompatibleDatabase( 1766): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1766): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1766): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ConfigFetchService( 1766): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1766): service connected
I/PeopleContactsSync( 1766): CP2 sync disabled
I/UpdateIcingCorporaServi( 1510): UpdateCorporaTask done [took 67 ms] updated apps [took 67 ms] 
I/Icing   ( 1766): doRemovePackageData com.test.thalitest
I/HotwordWorker( 1510): onReady
W/BaseAppContext( 1766): Using Auth Proxy for data requests.
W/BaseAppContext( 1766): Using Auth Proxy for data requests.
D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3e6a443e}
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=34.50 rxSuccessRate=46.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=76.75 rxSuccessRate=198.00 targetRoamBSSID=any RSSI=-52
I/art     ( 4319): System.exit called, status: 0
I/AndroidRuntime( 4319): VM exiting with result code 0.
D/Launcher.Workspace( 1415): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1415): 11683562 - stripEmptyScreens()
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660896531
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/kickstart(  869): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  869): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  869): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
I/GAv4    ( 4398): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4398):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4398):   adb logcat -s GAv4
W/GAv4    ( 4398): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4398): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4398): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4398): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4398): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4398): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4398): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4398): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4398): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4398): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4398): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4398): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4398): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4398): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4398): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4398): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4398): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4398): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4398): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4398): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4398): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4398): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4398): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4398): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4398): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4398): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4398): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4398): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4398): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4398): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4398): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4398): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4398): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 4398): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4398): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4398): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4398): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4398): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4398): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4398): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4398): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4398): 	at aen.run(PG:536)
W/GAv4    ( 4398): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4398): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4398): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4398): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4398): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4398): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4398): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4398): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4398): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4398): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4398): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4398): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4398): 	at aej.c(PG:139)
E/SQLiteDatabase( 4398): 	at aej.b(PG:398)
E/SQLiteDatabase( 4398): 	at agf.f(PG:417)
E/SQLiteDatabase( 4398): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4398): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4398): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4398): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4398): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4398): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4398): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4398): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4398): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4398): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4398): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4398): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4398): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4398): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4398): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4398): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4398): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4398): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4398): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4398): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4398): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 4398): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4398): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAv4    ( 4398): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4398): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4398): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4398): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4398): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4398): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4398): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4398): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4398): 	at aen.run(PG:536)
I/ActivityManager(  822): Start proc 4440:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  822): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{356ad1aa token=Token{2ded6c95 ActivityRecord{b7d444c u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4398): Sending signal. PID: 4398 SIG: 9
E/lowmemorykiller(  254): Error writing /proc/4398/oom_score_adj; errno=22
E/JavaBinder(  822): !!! FAILED BINDER TRANSACTION !!!
I/HotwordDetector( 1510): Closing mic
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
I/MicrophoneInputStream( 1510): mic_close com.google.android.apps.gsa.speech.audio.u@ae62d67
I/art     (  367): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 216us total 11.739ms
I/art     (  367): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 781us total 9.763ms
I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 9.609ms
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1510): Hotword detection finished
I/HotwordRecognitionRnr( 1510): Stopping hotword detection.
I/ActivityManager(  822): Start proc 4457:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  822): Spurious death for ProcessRecord{13958387 4457:com.google.android.apps.docs/u0a46}, curProc for 4398: null
E/Search.SharedPreferencesProto( 1510): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
W/OpenGLRenderer( 1415): Incorrectly called buildLayer on View: ew, destroying layer...
I/ActivityManager(  822): Killing 3701:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
E/native  ( 1282): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1282): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/Icing   ( 1766): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
E/native  ( 1282): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1282): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1282): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1282): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1282): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1282): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/SQLiteDatabase( 4440): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4440): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4440): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4440): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4440): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4440): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4440): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4440): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4440): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4440): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4440): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4440): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4440): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4440): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4440): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4440): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4440): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4440): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4440): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4440): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4440): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4440): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4440): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4440): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4440): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4440): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4440): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4440): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4440): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4440): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 4440): FATAL EXCEPTION: main
E/AndroidRuntime( 4440): Process: com.android.documentsui, PID: 4440
E/AndroidRuntime( 4440): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4440): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4440): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4440): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4440): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4440): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4440): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4440): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4440): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4440): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4440): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4440): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4440): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4440): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4440): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4440): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4440): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4440): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4440): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4440): 	... 9 more
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
E/Icing   ( 1766): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1766): Could not init tag ds.tag.deleted
D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  822): Validating map...
I/ActivityManager(  822): Start proc 4481:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
I/ActivityManager(  822): Killing 3757:com.android.chrome/u0a40 (adj 15): empty #17
E/kickstart(  869): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  869): WARNING: function: sahara_start:892 Retrying memory read request
I/ActivityManager(  822): Killing 3777:com.google.android.apps.photos/u0a71 (adj 15): empty #17
D/ExternalStorage( 4481): After updating volumes, found 1 active roots
I/OpenGLRenderer(  822): Initialized EGL, version 1.4
D/OpenGLRenderer(  822): Enabling debug mode 0
I/Icing   ( 1766): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
E/Icing   ( 1766): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1766): Writing status failed
E/Icing   ( 1766): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
I/GAv4    ( 4457): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4457):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4457):   adb logcat -s GAv4
I/ActivityManager(  822): Killing 3248:com.android.providers.calendar/u0a3 (adj 15): empty #17
W/GAv4    ( 4457): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4457): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4457): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4457): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4457): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4457): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4457): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
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
E/SQLiteDatabase( 4457): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4457): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4457): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4457): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4457): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4457): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4457): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4457): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4457): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4457): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4457): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
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
E/SQLiteDatabase( 4457): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4457): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4457): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4457): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4457): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4457): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4457): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4457): 	at gir$c.run(Unknown Source)
W/AnalyticsTrackerProxyImpl( 4457): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/GAv4    ( 4457): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 4457): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4457): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4457): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4457): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4457): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3e6a443e}
D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1e08f480}
E/SQLiteDatabase( 4457): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
E/SQLiteDatabase( 4457): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4457): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4457): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4457): 	at aen.run(PG:536)
E/SQLiteDatabase( 4457): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
E/SQLiteDatabase( 4457): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4457): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4457): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4457): 	at aej.c(PG:139)
E/SQLiteDatabase( 4457): 	at aej.b(PG:398)
E/SQLiteDatabase( 4457): 	at agf.f(PG:417)
E/SQLiteDatabase( 4457): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4457): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4457): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 4457): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4457): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4457): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4457): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4457): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4457): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4457): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4457): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4457): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4457): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4457): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4457): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4457): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 4457): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4457): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4457): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/ErrorNotificationActivity( 4457): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
D/OpenGLRenderer( 4457): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 4457): Validating map...
V/WindowManager(  822): Adding window Window{1efb5429 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 8 (after Window{153ee541 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
V/WindowManager(  822): Adding window Window{d84454f u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 9 (before Window{1efb5429 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
I/ProviderInstaller( 4457): Installed default security provider GmsCore_OpenSSL
W/GAv4    ( 4457): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4457): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4457): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4457): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4457): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4457): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak

```
