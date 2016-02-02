#### Test 5797209499148df_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAV2    ( 3553): Thread[GAThread,5,main]: No campaign data found.
--------- beginning of system
I/ActivityManager(  820): Killing 3155:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3183:com.google.android.apps.photos/u0a71 (adj 15): empty #17
D/AndroidRuntime( 3668): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3668): CheckJNI is OFF
D/AndroidRuntime( 3668): Calling main entry com.android.commands.am.Am
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{3373f8a8 token=Token{1fe2f8cb ActivityRecord{3019279a u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  820): Adding window Window{7e416fd u0 Starting com.test.thalitest} at 2 of 7 (after Window{3158f1fc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3668): Shutting down VM
I/MicrophoneInputStream( 1535): mic_close com.google.android.apps.gsa.speech.audio.u@e0f12e3
I/HotwordDetector( 1535): Closing mic
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
I/ActivityManager(  820): Start proc 3683:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 228us total 16.059ms
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1535): Stopping hotword detection.
I/HotwordRecognitionRnr( 1535): Hotword detection finished
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 331us total 17.894ms
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 382us total 18.689ms
I/ActivityManager(  820): Killing 2930:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660409107
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/WebViewFactory( 3683): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3683): Time to load native libraries: 2 ms (timestamps 643-645)
,I/LibraryLoader( 3683): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3683): Binding Chromium to main looper Looper (main, tid 1) {1b0b04d7}
,I/LibraryLoader( 3683): Expected native library version number "",actual native library version number ""
,I/chromium( 3683): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3683): Initializing chromium process, singleProcess=true
W/art     ( 3683): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3683): ApplicationContext is null in ApplicationStatus
,W/chromium( 3683): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3683): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3683): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3683): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ffc3797:true
,W/art     ( 3683): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3683): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3683): CordovaWebView is running on device made by: motorola
W/art     ( 3683): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3683): Attempt to remove local handle scope entry from IRT, ignoring
I/CheckinService( 1807): Done disabling old GoogleServicesFramework version
,D/OpenGLRenderer( 3683): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3683): Validating map...,
,V/WindowManager(  820): Adding window Window{11c43487 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{7e416fd u0 Starting com.test.thalitest})
,W/chromium( 3683): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,I/OpenGLRenderer( 3683): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3683): Enabling debug mode 0
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +857ms
,I/art     (  820): Explicit concurrent mark sweep GC freed 18088(874KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.069ms total 50.087ms
,I/Keyboard.Facilitator( 1240): onFinishInput()
,W/BindingManager( 3683): Cannot call determinedVisibility() - never saw a connection for the pid: 3683
,D/JsMessageQueue( 3683): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3683): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576328320
,I/chromium( 3683): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3683): Initializing JXcore engine
W/jxcore-log( 3683): JXcore engine is ready
,W/Thread-407( 3737): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9550]" dev="sockfs" ino=9550 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-407( 3737): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-407( 3737): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9694]" dev="sockfs" ino=9694 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-407( 3737): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20396]" dev="sockfs" ino=20396 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3683): Starting JXcore engine
,W/jxcore-log( 3683): Platform android
W/jxcore-log( 3683): 
W/jxcore-log( 3683): Process ARCH arm
W/jxcore-log( 3683): 
,I/jxcore-log( 3683): JXcore Cordova bridge is ready!
I/jxcore-log( 3683): 
W/jxcore-log( 3683): JXcore engine is started
,I/jxcore-log( 3683): Toggling radios to true
I/jxcore-log( 3683): ,
,D/BluetoothAdapter( 3683): enable(): BT is already enabled..!
,D/WifiService(  820): New client listening to asynchronous messages,
D/WifiService(  820): setWifiEnabled: true pid=3683, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3683): Radios toggled
I/jxcore-log( 3683): 
I/jxcore-log( 3683): My device name is: motorola-Nexus 6
I/jxcore-log( 3683): 
,I/wpa_supplicant( 1177): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1,
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state,
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  354): Clearing all IP addresses on wlan0
V/NativeCrypto( 1261): Read error: ssl=0xb4885e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1261): SSL shutdown failed: ssl=0xb4885e00: I/O error during system call, Broken pipe
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  820): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1074): CM callback handler got msg 524292
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  820): MasterInitialState.processMessage what=3
D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  820): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3255): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/WifiConfigStore(  820): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): will read network variables netId=0
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
D/PhoneInterfaceManager( 1340): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1340): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,I/VacuumService( 1261): Vacuum at: now=1454416516025 tag=VacuumService
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/ActivityManager(  820): Start proc 3746:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/GpsLocationProvider(  820): No APN found to select.
,D/PhoneInterfaceManager( 1340): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1340): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,I/ActivityManager(  820): Start proc 3772:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
I/ActivityManager(  820): Killing 3205:com.android.settings/1000 (adj 15): empty #17
,D/SprintDMReceiver( 3772): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3772): simOperator:  IMSI: null
D/SprintDMReceiver( 3772): Not Sprint UICC, don't do anything.
,I/ActivityManager(  820): Killing 3223:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/SystemUpdateService( 1807): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1807): onCreate
,D/SystemUpdateService( 1807): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1807): active receiver: enabled
,I/iu.Environment( 1807): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1807): num queued entries: 0
,I/iu.UploadsManager( 1807): num updated entries: 0
,I/iu.SyncManager( 1807): NEXT; no task
,I/SystemUpdateService( 1807): showing system update notification
,D/ChimeraCfgMgr( 1807): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Babel   ( 2896): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1807): retry (wakeup: false) in 3599950 ms
,I/ActivityManager(  820): Start proc 3792:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1807): onDestroy
,I/GAv4    ( 3792): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3792):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3792):   adb logcat -s GAv4
,W/GAv4    ( 3792): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3792): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3792): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3792): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3792): Time to load native libraries: 1 ms (timestamps 4408-4409)
I/LibraryLoader( 3792): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3792): Binding Chromium to main looper Looper (main, tid 1) {2b0f884a}
,I/LibraryLoader( 3792): Expected native library version number "",actual native library version number ""
I/chromium( 3792): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3792): Initializing chromium process, singleProcess=true
,W/art     ( 3792): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3792): ApplicationContext is null in ApplicationStatus
,W/chromium( 3792): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3792): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3792): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3792): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3792): Requires BLUETOOTH permission
,I/NSApplication( 3792): Starting up...
,I/ActivityManager(  820): Start proc 3848:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
I/ActivityManager(  820): Killing 3314:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 3868:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  820): Killing 3336:com.android.musicfx/u0a18 (adj 15): empty #17
,I/wpa_supplicant( 1177): wlan0: Trying to associate with SSID 'NG7005g'
,I/ActivityManager(  820): Waited long enough for: ServiceRecord{7bd26f7 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/ActivityManager(  820): Killing 3387:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,V/MusicLeanback( 3255): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3772): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3772): simOperator:  IMSI: null
D/SprintDMReceiver( 3772): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1807): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1807): onCreate
,D/SystemUpdateService( 1807): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/wpa_supplicant( 1177): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/SystemUpdateService( 1807): active receiver: enabled
I/SystemUpdateService( 1807): showing system update notification
,D/ChimeraCfgMgr( 1807): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1807): retry (wakeup: false) in 3599983 ms
,D/SystemUpdateService( 1807): onDestroy
,I/wpa_supplicant( 1177): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1177): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  354): Setting iface cfg
E/WifiStateMachine(  820): Start Dhcp Watchdog 2
,E/WifiStateMachine(  820):  WifiLinkLayerStats: ,
E/WifiStateMachine(  820):  my bss beacon rx: 186
E/WifiStateMachine(  820):  RSSI mgmt: -52
E/WifiStateMachine(  820):  BE :  rx=156 tx=132 lost=0 retries=1
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 8957 tx_time=154 rx_time=356 scan_time=0
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60,
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/dhcpcd  ( 3900): version 5.5.6 starting
,I/dhcpcd  ( 3900): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3900): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3900): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 101
,I/jxcore-log( 3683): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3683): 
E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  820): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1074): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3255): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3255): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1340): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1340): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3772): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3772): simOperator:  IMSI: null
D/SprintDMReceiver( 3772): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1807): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1807): onCreate
,E/GpsLocationProvider(  820): No APN found to select.
,D/SystemUpdateService( 1807): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1807): active receiver: enabled
,I/SystemUpdateService( 1807): showing system update notification
,V/GoogleAuthProtoRequest( 3746): [400] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3746): [401] a.<init>: mAccountName set to: thalitester@gmail.com
,I/iu.Environment( 1807): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1807): num queued entries: 0
,I/iu.UploadsManager( 1807): num updated entries: 0
,I/iu.SyncManager( 1807): NEXT; no task
,D/ChimeraCfgMgr( 1807): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1807): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1807): retry (wakeup: false) in 3599956 ms
,D/SystemUpdateService( 1807): onDestroy
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1807): [AccountUtils] Account not ready
W/Kids    ( 1807): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1807): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1807): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1807): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1807): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1807): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1807): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1807): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1807): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1807): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1807): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1807): 	at java.lang.Thread.run(Thread.java:818)
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 12:35:20 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454416520334], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454416520233]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1074): CM callback handler got msg 524290
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 2896): connection state changed from DISCONNECTED to CONNECTED
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3746): [400] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3746): [400] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3746): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3746): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3746): 	at com.a.a.k.run(SourceFile:110)
W/ExperimentUpdateService( 3746): [401] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3746): [401] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3746): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3746): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3746): 	at com.a.a.k.run(SourceFile:110)
,V/Herrevad( 1807): NQAS connected
,I/art     ( 1261): Explicit concurrent mark sweep GC freed 34994(1886KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 835us total 22.809ms
,D/GCM     ( 1261): Connected
,D/GCM     ( 1261): Message class com.google.f.a.a.p
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3683): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3683): ,
,I/jxcore-log( 3683): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3683): 
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/art     (  820): Explicit concurrent mark sweep GC freed 53088(2MB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 1.854ms total 71.624ms
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3427): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3427): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3427): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager(  820): Killing 3576:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/ActivityManager(  820): Killing 1454:android.process.acore/u0a5 (adj 15): empty #17
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.34 rxSuccessRate=8.28 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3683): Test app app.js loaded,
I/jxcore-log( 3683): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): ,	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3529adcf added. We now have 1 listener(s)
,I/jxcore-log( 3683): BLE advertisement is supported
I/jxcore-log( 3683): 
,I/chromium( 3683): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.34 rxSuccessRate=8.28 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 7 -> obsolete
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.73 rxSuccessRate=4.57 targetRoamBSSID=any RSSI=-51
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3427): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3427): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3427): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  820): Start proc 3961:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/KeepSync( 3961): Connecting to GoogleApiClient
,I/art     ( 1261): Explicit concurrent mark sweep GC freed 15802(891KB) AllocSpace objects, 6(661KB) LOS objects, 38% free, 25MB/41MB, paused 944us total 39.137ms
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1807): Handling authorization failure
E/ClientConnectionOperation( 1807): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1807): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1807): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1807): 	... 7 more
,V/KeepSync( 3961): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 79225, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3961): IOException
E/KeepSync( 3961): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3961): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3961): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3961): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3961): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3961): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3961): 	... 10 more
,W/KeepSync( 3961): Sync result 2
,I/ActivityManager(  820): Start proc 3994:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 79760, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/GAV2    ( 3994): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3994): Created application version: 3.6.8 (30608)
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 34340(1566KB) AllocSpace objects, 8(222KB) LOS objects, 32% free, 33MB/49MB, paused 2.208ms total 100.844ms
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3994): Soft error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3994): Sync error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3994): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 80761, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 3553:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3467:com.google.android.gms:car/u0a11 (adj 15): empty #18
,I/GAV2    ( 3994): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.35 rxSuccessRate=1.60 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,D/Finsky  ( 3427): [382] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3427): [382] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3427): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3427): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3427): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1240): run()
I/Keyboard.Facilitator( 1240): flushDynamicLanguageModels()
,I/ConfigService( 1261): onCreate
,I/ConfigService( 1261): onDestroy
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.33 rxSuccessRate=1.96 targetRoamBSSID=any RSSI=-51
,V/GoogleAuthProtoRequest( 3746): [403] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3746): [404] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3746): [404] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3746): [404] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3746): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3746): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3746): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3746): [403] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3746): [403] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3746): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3746): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3746): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GoogleURLConnFactory( 1261): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3427): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3427): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3427): [1] 5.onFinished: Scheduling replication attempt 4.
,E/Uploader( 1261): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1261): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1261): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1261): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1261): No account for auth token provided
,W/Uploader( 1261): No account for auth token provided
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1261): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1261): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1261): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1261): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1261): No account for auth token provided
,W/Uploader( 1261): No account for auth token provided
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1261): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1261): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1261): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1261): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1261): No account for auth token provided
,W/Uploader( 1261): No account for auth token provided
,W/Uploader( 1261): No account for auth token provided
,W/Uploader( 1261): No account for auth token provided,
,W/Uploader( 1261): No account for auth token provided
,W/Uploader( 1261): No account for auth token provided
,W/Uploader( 1261):  no longer exists, so no auth token.
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1261): Explicit concurrent mark sweep GC freed 51964(2MB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 1.808ms total 62.247ms
,E/Uploader( 1261): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1261): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1261): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1261): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1261): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1261): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1261): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1261): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1261): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1261): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.35 rxSuccessRate=5.71 targetRoamBSSID=any RSSI=-51
,E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (241 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  820): Display changed displayId=0
,I/kickstart(  876): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  876): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  876): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  820): Excessive delay in setPowerMode(): 273ms
,I/DreamManagerService(  820): Entering dreamland.,
,I/PowerManagerService(  820): Dozing...
I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 12
,E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1240): onFinishInput()
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): cancelDelayedScan -> 14
,E/native  (  820): do suspend true
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/art     (  820): Explicit concurrent mark sweep GC freed 46730(2MB) AllocSpace objects, 14(318KB) LOS objects, 31% free, 34MB/50MB, paused 2.235ms total 95.393ms
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3427): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3427): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3427): [1] 5.onFinished: Scheduling replication attempt 5.
,I/kickstart(  876): STATUS: Received file 'm9kefs2'
I/kickstart(  876): STATUS: 950272 bytes transferred in 0.993623 seconds
I/kickstart(  876): STATUS: Successfully downloaded files from target 
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  876): STATUS: Sahara protocol completed
,V/KeepSync( 3961): Connecting to GoogleApiClient
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,E/ClientConnectionOperation( 1807): Handling authorization failure
E/ClientConnectionOperation( 1807): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1807): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1807): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1807): 	... 7 more
,V/KeepSync( 3961): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
,E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081),
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3961): IOException
E/KeepSync( 3961): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3961): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3961): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3961): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3961): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3961): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3961): 	... 10 more
W/KeepSync( 3961): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 140523, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 138937, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3994): Soft error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3994): Sync error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3994): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 140853, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3427): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 3427): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3427): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1240): run()
I/Keyboard.Facilitator( 1240): flushDynamicLanguageModels()
,I/ConfigService( 1261): onCreate
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 229463, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1261): onDestroy
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3961): Connecting to GoogleApiClient
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1807): Handling authorization failure
E/ClientConnectionOperation( 1807): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1807): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1807): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1807): 	... 7 more
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 3994): Soft error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3994): Sync error
,E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3994): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 231598, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  820): Explicit concurrent mark sweep GC freed 40958(1762KB) AllocSpace objects, 12(757KB) LOS objects, 31% free, 34MB/50MB, paused 6.817ms total 216.792ms
,V/KeepSync( 3961): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3961): IOException
E/KeepSync( 3961): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3961): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3961): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3961): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3961): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3961): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3961): 	... 10 more
,W/KeepSync( 3961): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 232525, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3683): TAP version 13
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # multiplex can send data
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 1 String should be length:200
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # enqueue and run in order
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
,I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 2 firstPromise setTimeout
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 3 firstPromise result
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 4 firstPromise testValue
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 5 secondPromise setTimeout
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 6 secondPromise result
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 7 secondPromise testValue
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 8 thirdPromise in promise
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 9 thirdPromise result
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 10 thirdPromise testValue
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # basic
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 11 sane
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # another
I/jxcore-log( 3683): ,
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 12 sane
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 13 should be equal,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 14 null
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 15 (unnamed assert)
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 16 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 17 should not throw,
I/jxcore-log( 3683): 
I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # successfully read a previous pkcs12 file and return hash value,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 18 (unnamed assert),
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 19 (unnamed assert),
I/jxcore-log( 3683): 
I/jxcore-log( 3683): ok 20 should not throw
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 21 should be equal,
I/jxcore-log( 3683): 
I/jxcore-log( 3683): ok 22 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # failed to extract public key because of corrupt pkcs12 file,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): ,
,I/jxcore-log( 3683): ok 23 should be equal
,I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # failed to get mobile documents path,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 24 should be equal,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #init should register the peerAvailabilityChanged event,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 25 should be equal,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 26 should be equal,
I/jxcore-log( 3683): 
I/jxcore-log( 3683): ok 27 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #init should register the networkChanged event,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 28 should be equal,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #startBroadcasting should throw on null device name
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): ,
,I/jxcore-log( 3683): ok 29 should throw,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 30 should throw
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 31 should throw
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): ,
,I/jxcore-log( 3683): ok 32 should throw
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #startBroadcasting should throw on negative port
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 33 should throw
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #startBroadcasting should throw on too large port
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 34 should throw
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3683): ,
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 35 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 36 should be equal
I/jxcore-log( 3683): 
I/jxcore-log( 3683): ok 37 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3683): ,
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): ,
,I/jxcore-log( 3683): ok 38 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 39 should be equal
I/jxcore-log( 3683): 
I/jxcore-log( 3683): ok 40 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 41 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 42 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 43 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 44 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 45 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 46 should be equal
I/jxcore-log( 3683): 
I/jxcore-log( 3683): ok 47 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 48 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 49 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3683): ,
,I/jxcore-log( 3683): # teardown
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 50 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 51 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # should call Mobile("Disconnect") and handle an error,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): ok 52 should be equal,
I/jxcore-log( 3683): 
I/jxcore-log( 3683): ok 53 should be equal
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # setup,
I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,I/jxcore-log( 3683): 
,I/jxcore-log( 3683): # teardown
,I/jxcore-log( 3683): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3683): load: ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3683): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3683): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3683): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12ce435c added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): setDiscoveryMode: BLE -> BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): onDiscoveryModeChanged: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3683): setBluetoothMacAddress: F8:CF:C5:D9:E5:61,
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3683): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454416742825.3683
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3683): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3683): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3683): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454416742825.3683","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3683): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3683): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3683): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3683): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3683): start: OK
I/io.jxcore.node.ConnectionHelper( 3683): start: Using peer discovery mode: BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3683): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454416742825.3683, mode: BLE_AND_WIFI,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3683): bind: Binding a new listener,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3683): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3683): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3683): Waiting for incoming connections...,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3683): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3683): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3683): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3683): createAdvertiseData: From: 1454416742825.3683 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3683): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2325): registerClient() - UUID=afd6ae44-9f24-4535-bcaf-9bd6625cf7e3
,D/BtGatt.GattService( 2325): onClientRegistered() - UUID=afd6ae44-9f24-4535-bcaf-9bd6625cf7e3, clientIf=5
,D/BluetoothLeScanner( 3683): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2325): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3683): setState: State changed from NOT_STARTED to STARTING
,D/BtGatt.ScanManager( 2325): handling starting scan
,D/BluetoothAdapterService( 2325): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3474c1c4
,D/BtGatt.GattService( 2325): registerClient() - UUID=aa8132d6-76c1-4b78-9537-0f31f9168c82
,D/BtGatt.GattService( 2325): onClientRegistered() - UUID=aa8132d6-76c1-4b78-9537-0f31f9168c82, clientIf=6
D/BluetoothLeAdvertiser( 3683): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2325): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2325): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2325): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2325): callback done for clientIf - 5 status - 0
D/BtGatt.AdvertiseManager( 2325): message : 0
D/BtGatt.ScanManager( 2325): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2325): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BtGatt.AdvertiseManager( 2325): starting multi advertising
,D/BtGatt.GattService( 2325): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2325): onAdvertiseDataSet() - clientIf=6, status=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3683): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3683): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454416742825.3683","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3683): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1454416742825.3683","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3683): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1454416742825.3683","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3683): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3683): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3683): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): start: OK
I/io.jxcore.node.ConnectionHelper( 3683): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1454416742825.3683, mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3683): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3683): createAdvertiseData: From: 1454416742825.3683 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3683): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BtGatt.AdvertiseManager( 2325): message : 1
D/BtGatt.AdvertiseManager( 2325): stop advertise for client 6
,I/jxcore-log( 3683): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3683): 
,D/BtGatt.GattService( 2325): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2325): Client app is not null!,
I/io.jxcore.node.ConnectionHelper( 3683): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3683): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3683): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3683): stopListeningForIncomingConnections: Stopping...,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3683): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3683): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3683): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3683): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3683): setState: NOT_STARTED
D/BtGatt.GattService( 2325): unregisterClient() - clientIf=6
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3683): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3683): setState: State changed from STARTING to NOT_STARTED
,D/BtGatt.GattService( 2325): registerClient() - UUID=650cba39-b5aa-46c6-a287-d72691c95cd2
D/BtGatt.GattService( 2325): onClientRegistered() - UUID=650cba39-b5aa-46c6-a287-d72691c95cd2, clientIf=6
D/BluetoothLeAdvertiser( 3683): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2325): message : 0
D/BtGatt.AdvertiseManager( 2325): starting multi advertising
D/BtGatt.GattService( 2325): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2325): onAdvertiseDataSet() - clientIf=6, status=0,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3683): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3683): start: Already running,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3683): start: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3683): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): startWifiPeerDiscovery: Wi-Fi Direct OK,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3683): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3683): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3683): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3683): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3683): stop
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3683): onIsAdvertiserStartedChanged: true
,V/GoogleAuthProtoRequest( 3746): [405] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1261): Explicit concurrent mark sweep GC freed 48485(2MB) AllocSpace objects, 14(1458KB) LOS objects, 36% free, 27MB/43MB, paused 1.048ms total 36.266ms
,V/GoogleAuthProtoRequest( 3746): [406] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3746): [405] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3746): [405] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3746): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3746): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3746): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3746): [406] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3746): [406] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3746): 	at com.google.android.gms.gcm.c.run(Unknown Source)
,W/ExperimentUpdateService( 3746): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3746): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@31c1336a}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
,D/btif_config_util( 2325): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@31c1336a}
,I/wpa_supplicant( 1177): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	,at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	,at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77),
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
,E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	,at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	,at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 352412, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1261): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1261): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1261): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1261): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1261): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1261): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1261): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3427): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3427): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3427): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3427): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3427): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3427): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3427): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3427): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3961): Connecting to GoogleApiClient
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1807): Handling authorization failure
E/ClientConnectionOperation( 1807): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1807): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1807): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1807): 	... 7 more
,V/KeepSync( 3961): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3994): Soft error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3994): Sync error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3994): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 385998, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 29939(1326KB) AllocSpace objects, 7(394KB) LOS objects, 31% free, 34MB/50MB, paused 1.617ms total 50.122ms
,E/KeepSync( 3961): IOException
E/KeepSync( 3961): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3961): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3961): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3961): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3961): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3961): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3961): 	... 10 more
W/KeepSync( 3961): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 388792, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 1177): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1177): P2P-DEVICE-LOST p2p_dev_addr=de:4a:3e:0f:89:ad
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@28af3d39}
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@28af3d39}
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82),
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 597907, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/ActivityManager(  820): Start proc 4183:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4    ( 4183): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4183):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4183):   adb logcat -s GAv4
,W/GAv4    ( 4183): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4183): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4183): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1261): Explicit concurrent mark sweep GC freed 55041(2MB) AllocSpace objects, 15(1653KB) LOS objects, 36% free, 27MB/43MB, paused 1.100ms total 51.216ms
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3994): Soft error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3994): Sync error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3994): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 665075, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 3358:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,V/KeepSync( 3961): Connecting to GoogleApiClient
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1807): Handling authorization failure
E/ClientConnectionOperation( 1807): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1807): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1807): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1807): 	... 7 more
,V/KeepSync( 3961): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3961): IOException
E/KeepSync( 3961): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3961): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3961): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3961): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3961): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3961): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3961): 	... 10 more
W/KeepSync( 3961): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 670231, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3746): [407] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3746): [408] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3746): [408] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3746): [408] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3746): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3746): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3746): 	at com.a.a.k.run(SourceFile:110)
,I/art     (  820): Explicit concurrent mark sweep GC freed 38659(1767KB) AllocSpace objects, 12(474KB) LOS objects, 31% free, 34MB/50MB, paused 2.145ms total 70.695ms
,W/ExperimentUpdateService( 3746): [407] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3746): [407] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3746): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3746): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3746): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/GCM     ( 1261): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
,E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
,E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): ,	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1088311, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3994): Soft error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3994): Sync error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3994): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1170051, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btm  ( 2325): Request to stop oneshot timer with non empty queue
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,V/KeepSync( 3961): Connecting to GoogleApiClient
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1807): Handling authorization failure
E/ClientConnectionOperation( 1807): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1807): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1807): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1807): 	... 7 more
,V/KeepSync( 3961): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3961): IOException
E/KeepSync( 3961): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3961): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3961): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3961): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3961): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3961): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3961): 	... 10 more
W/KeepSync( 3961): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1210296, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/UsageStatsService(  820): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/art     ( 1261): Explicit concurrent mark sweep GC freed 69383(3MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 1.135ms total 41.190ms
,V/GoogleAuthProtoRequest( 3746): [409] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3746): [410] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3746): [410] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3746): [410] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3746): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3746): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3746): 	at com.a.a.k.run(SourceFile:110)
W/ExperimentUpdateService( 3746): [409] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3746): [409] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3746): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3746): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3746): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3746): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3746): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/art     (  820): Explicit concurrent mark sweep GC freed 49343(2MB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.414ms total 94.303ms
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/EventLogService( 1807): Opted in for usage reporting
I/EventLogService( 1807): Aggregate from 1454416126835 (log), 1454416126835 (data)
,W/EventLogAggregator( 1807): Unknown tag: snet_gcore
W/EventLogAggregator( 1807): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1807): dumping service [account]
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/Finsky  ( 3427): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3427): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 3427): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3427): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3427): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3427): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3427): [1] DailyHygiene.reschedule: Scheduling new run in 89 minutes (failures=3)
,D/DeviceConnectionService( 1786): client connected with version: 7571000
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3427): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3427): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3427): [1] 5.onFinished: Scheduling replication attempt 1.
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3427): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3427): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3427): [1] 5.onFinished: Scheduling replication attempt 2.
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3427): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3427): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3427): [1] 5.onFinished: Scheduling replication attempt 3.
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  820): Prepared write state in 23ms
,I/ProcessStatsService(  820): Pruning old procstats: /data/system/procstats/state-2016-02-01-14-31-22.bin
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1261): Explicit concurrent mark sweep GC freed 69482(3MB) AllocSpace objects, 8(882KB) LOS objects, 37% free, 26MB/42MB, paused 2.302ms total 55.850ms
,D/Finsky  ( 3427): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3427): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3427): [1] 5.onFinished: Scheduling replication attempt 4.
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 31872(1565KB) AllocSpace objects, 7(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.276ms total 73.192ms
,D/Finsky  ( 3427): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3427): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3427): [1] 5.onFinished: Scheduling replication attempt 5.
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/ActivityManager(  820): Killing 2603:com.google.android.calendar/u0a37 (adj 15): empty for 1802s
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3427): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3427): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3427): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/ActivityManager(  820): Killing 2896:com.google.android.talk/u0a61 (adj 11): empty for 1860s
,I/ActivityManager(  820): Killing 3868:com.google.android.apps.photos/u0a71 (adj 13): empty for 1860s
,I/ActivityManager(  820): Killing 3848:com.android.chrome/u0a40 (adj 13): empty for 1860s
,I/ActivityManager(  820): Killing 3792:com.google.android.apps.magazines/u0a67 (adj 13): empty for 1860s
,I/ActivityManager(  820): Killing 3772:com.android.sdm.plugins.sprintdm/1001 (adj 13): empty for 1861s
,I/ActivityManager(  820): Killing 3255:com.google.android.music:main/u0a66 (adj 15): empty for 1861s
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1261): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/art     ( 1786): Explicit concurrent mark sweep GC freed 16499(992KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 2.173ms total 52.651ms
,E/DataBuffer( 1786): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2f4a0640)
,E/DataBuffer( 1786): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@5ec5979)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): ,	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at blb.a(PG:3937)
E/HttpOperation( 3489): 	at czp.a(PG:18188)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 12 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 14 more
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3489): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3489): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3489): 	at jdm.a(PG:82)
E/HttpOperation( 3489): 	at jcs.o(PG:406)
E/HttpOperation( 3489): 	at jcn.a(PG:1379)
E/HttpOperation( 3489): 	at jcs.i(PG:143)
E/HttpOperation( 3489): 	at hec.a(PG:42)
E/HttpOperation( 3489): 	at hee.a(PG:102)
E/HttpOperation( 3489): 	at czr.a(PG:65)
E/HttpOperation( 3489): 	at kka.a(PG:108)
E/HttpOperation( 3489): 	at czp.a(PG:19176)
E/HttpOperation( 3489): 	at czp.a(PG:9081)
E/HttpOperation( 3489): 	at czq.run(PG:1686)
E/HttpOperation( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3489): 	at jdj.a(PG:4091)
E/HttpOperation( 3489): 	at jdj.a(PG:1125)
E/HttpOperation( 3489): 	at jdm.a(PG:77)
E/HttpOperation( 3489): 	... 15 more
E/HttpOperation( 3489): Caused by: faj: BadAuthentication
E/HttpOperation( 3489): 	at fal.a(PG:38)
E/HttpOperation( 3489): 	at jdj.a(PG:4089)
E/HttpOperation( 3489): 	... 17 more
,E/ExperimentLoader( 3489): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3489): 	at jdm.a(PG:82)
E/ExperimentLoader( 3489): 	at jcs.o(PG:406)
E/ExperimentLoader( 3489): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3489): 	at jcs.i(PG:143)
E/ExperimentLoader( 3489): 	at hec.a(PG:42)
E/ExperimentLoader( 3489): 	at hee.a(PG:102)
E/ExperimentLoader( 3489): 	at czr.a(PG:65)
E/ExperimentLoader( 3489): 	at kka.a(PG:108)
E/ExperimentLoader( 3489): 	at czp.a(PG:19176)
E/ExperimentLoader( 3489): 	at czp.a(PG:9081)
E/ExperimentLoader( 3489): 	at czq.run(PG:1686)
E/ExperimentLoader( 3489): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3489): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3489): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3489): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3489): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3489): 	at jdj.a(PG:4091),
E/ExperimentLoader( 3489): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3489): 	at jdm.a(PG:77)
E/ExperimentLoader( 3489): 	... 15 more
E/ExperimentLoader( 3489): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3489): 	at fal.a(PG:38)
E/ExperimentLoader( 3489): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3489): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 2068783, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btm  ( 2325): Stopping oneshot timer,
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,I/BooksSync( 3994): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3994): GmsCore Version = 7.8.99 (2134222-430),
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3994): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3994): Soft error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3994): Sync error
E/BooksSync( 3994): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3994): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3994): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 2179690, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,V/KeepSync( 3961): Connecting to GoogleApiClient
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1807): Handling authorization failure
E/ClientConnectionOperation( 1807): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1807): 	,at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1807): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1807): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1807): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1807): ,	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1807): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1807): 	... 7 more
V/KeepSync( 3961): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3961): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1261): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1261): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1261): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1261): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1261): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3961): IOException
E/KeepSync( 3961): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3961): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3961): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3961): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3961): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3961): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3961): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3961): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3961): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3961): 	... 10 more
W/KeepSync( 3961): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 2259800, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2325): Disconnected process message: 10, size: 0

```
